# ENG - FastCGI in ISPmanager 5 for Drupal 8, Wordpress with SSL

Configuration files for the control panel ISPmanager 5 in CentOS (suitable for all Unix system) for Drupal 8, WordPress with SSL support

## Instructions:

- Tested on CentOS 7 with php 5.6, mySQL 5.7, ISPmanager 5 (front with php 7.1)
- Inside conf.txt file, search and replace:
    - `sitename` - to change the domain name of the website
    - `youripadressserver` - to change the server's ip address
    - if necessary, uncomment the gzip compression, delete `#`

## Where to insert:

After making changes to the configuration file, copy it and paste it in the control panel as the account administrator Domains> www domains -> click to yoursite -> in the top bar, choose Config -> Paste and save

# RUS - FastCGI в ISPmanager 5 для Drupal 8, Wordpress с SSL

Конфигурационные файлы для панели управления ISPmanager 5 для Drupal 8, Wordpress с поддержкой SSL

## Инструкции:

- Настройки тестировались в CentOS 7 с php 5.6, mysql 5.7, ISPmanager 5 (с включенным php 7.1 для пользователей)
- Необходимо внести изменения в конфиг файлы перед их использованием:
    - `sitename` - изменить на доменное имя сайта
    - `youripadressserver` - изменить на ip адрес сервера
    - если необходимо, раскомментировать поля с gzip, удалив `#`

## Как вставить конфиги в ISPmanager:

После внесения изменения в конфигурационный файл, копируем его и вставляем в панели управления, под учетной записью администратора в Домены -> www-домены -> выбрать необходимый сайт -> в верхней панели, выбрать Конфиг -> Вставить и сохранить
