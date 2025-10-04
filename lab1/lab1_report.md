University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://) ADD link
Year: 2025/2026
Group: U4125
Author: Deviatilova Olga
Lab: Lab1
Date of create: 03.10.2025
Date of finished: 06.10.2025

# Изучение основ Doker:

## 1.Установка Docker:

Установила Doker, проверила установку, запустила тестовый контейнер и изучила базовые команды.

![](screen1.jpg)

![](screen2.jpg)

![](screen3.jpg)

![](screen4.jpg)

## 2.Работа с готовыми образами:

Скачала образ Ubuntu, запустила интерактивный контейнер, внутри контейнера установила пакет curl, проверила установку и вышла из контейнера.

![](screen5.jpg)

![](screen6.jpg)

![](screen7.jpg)

![](screen9.jpg)

## 3.Запуск веб-сервера:

Запустила контейнер с nginx, проверила работу в браузере, посмотрела логи контейнера, подключилась к нему и вышла.

![](screen10.jpg)

![](screen11.jpg)

![](screen12.jpg)

![](screen13.jpg)

## 4.Управление контейнерами:

Провела базовые операции с контейнерами, удалила контейнер, удалила образ.

![](screen13.jpg)

![](screen14.jpg)

![](screen15.jpg)

![](screen16.jpg)

![](screen17.jpg)

![](screen18.png)

## 5.Работа с томами(volumes):

Создала том и запустила контейнер с параметрами:
-it — интерактивный режим
--name volume-test — имя контейнера
-d — запуск в detached-режиме
-v my-volume:/data — монтирование тома
ubuntu — образ для запуска
bash — команда для выполнения

Подключилась к контейнеру, создала файл и удалила контейнер.

![](screen19.jpg)

![](screen20.jpg)

![](screen21.jpg)

Создала новый контейнер с тем же томом, проверила, что он созранился.

![](screen25.png)

![](screen22.jpg)

![](screen23.jpg)

![](screen24.jpg)


