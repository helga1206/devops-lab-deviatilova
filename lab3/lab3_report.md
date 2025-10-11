University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://) ADD link
Year: 2025/2026
Group: U4125
Author: Deviatilova Olga
Lab: Lab3
Date of create: 11.10.2025
Date of finished: 13.10.2025

# Настройка мониторинга с Prometheus и Grafana

## 1. Создание конфигурации Prometheus:

Создала папку prometheus и файл prometheus.yml

![](screen1.jpg)

![](screen2.jpg)

## 2. Запуск Node Exporter:

Запустила контейнер Node Exporter для сбора системных метрик и проверила работу

![](screen3.jpg)

![](screen4.jpg)

## 3. Запуск Prometheus:

Создала том для данных Prometheus, запустила контейнер и проверила работу, открыв ссылку в браузере

![](screen5.jpg)

![](screen6.png)

![](screen7.jpg)

## 4. Запуск Grafana:

Создала том для данных Grafana, запустила контейнер и проверила работу в браузере

![](screen8.jpg)

![](screen9.jpg)

![](screen10.jpg)

## 5. Настройка Grafana:

Зашла в Grafana, добавила источник данных Prometheus, но при сохранении и тестировании возникла ошибка.
Поэтому обновила конфигурацию Prometheus с использованием единого IP-адрес хоста: host.docker.internal, перезапустила все контейнеры.
После этого Grafana успешно подключилась к Prometheus.

![](screen11.jpg)

![](screen12.jpg)

![](screen13.jpg)

Создала дашборд с меетрикой node_cpu_seconds_total и сохранила его

![](screen15.jpg)

## 6. Тестирование системы:

Проверила все контейнеры, убедилась, что метрики собираются и графики отражаются с разными метриками

![](screen14.jpg)

![](screen16.jpg)

![](screen17.jpg)

![](screen18.png)
