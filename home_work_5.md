# Часть 1: Повторение последнего урока
1) Установить redis
```
sudo apt update
sudo apt install redis -y
```
2) Проверить статус сервиса redis
3) Остановить сервис redis
4) Запустить сервис redis

# Часть 2: Повторение темы "Пользователи и права доступа"
1) Создать группы developers, managers и designers
2) Вывести из файла /etc/group только названия добавленных групп
3) Создать пользователей employer1, employer2, employer3, employer4
4) Задать им пароли и проверить что у всех оболочка /bin/bash и дяя всех создана домашняя директория
5) Вывести из файла /etc/passwd только имена созданных пользователей
6) Добавить пользователей employer2 и employer4 в группу developers
7) Добавить пользователей employer1 и employer3 в группу designers
8) Вывести на экран состав групп developers и designers
9) Создать пользователей employer5, employer6 и chief
10) Задать им пароли и проверить что у всех оболочка /bin/bash и для всех создана домашняя директория
11) Вывести из файла /etc/passwd только имена созданных в п10 пользователей
12) Добавить пользователей employer5 и chief в группу managers
13) Добвить пользователя employer6 в группу developers
14) Вывести состав групп developers, managers и designers
15) В /tmp создать директорию project
16) В /tmp/project создать директории code и media
17) В директории code создать файлы index.html и style.css с произвольным содержимым
18) Дать права на чтение и запись в директорию code группе developers
19) Дать права на чтение и запись в директорию media группе designers
20) В директории /tmp/project создать файл report.csv с произвольным содержимым
21) Дать все права на него группе managers
22) В директории /tmp/project создать директорию dev1
23) Дать права на чтение и запись в dev1 только для пользователя employer1
24) В директории /tmp/project создать директорию main
25) В директории main создать файл map с произвольным содержимымы
26) Дать полные права на файл map пользователю chief

# Часть 3: Повторение темы "Работа с файлами и директориями"
1) Создать в домашней директории папку home_work5
2) В home_work5 создать директорию seaport
3) В директории seaport создать директории departments, areas, journal_lists
4) В директории departments создать файл dep_list с содержимым
```
1. Pilotage service
2. Traffic management service
3. Tugboat service
4. Hydrographic service
5. Emergency rescue service
6. Security service
```
5) В директории areas создать файл area_list с содержимым
```
1. An external raid
2. Internal raid
3. Gateways
4. Mooring lines
5. Warehouses
6. Administrative and industrial buildings
7. Ship repair area
```
6) В директории journal_lists создать файл с именем <date>_list (вместо date подставить результат выполнения ```date +"%Y-%m-%dT%H:%M:%S"```)
7) Вывести полученную структуру командой tree
8) В home_work5 создать директорию seaport_backup
9) Скопировать содержимое seaport в seaport_backup
10) В home_work5 создать директорию backups
11) Переместить seaport_backup в backups
12) Переименовать seaport_backup в <date>_seaport (вместо date подставить результат выполнения ```date +"%Y-%m-%dT%H:%M:%S"```)
13) Создать файл list_of_bk в директории home_work5 и записать в него вывод команды ```ls -1 backups```
14) Скопировать файл list_of_bk в директорию journal_lists
