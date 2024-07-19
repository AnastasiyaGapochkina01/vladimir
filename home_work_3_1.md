1) Настроить возможноcть копирования с хоста в ВМ
2) Созздать в домашений директории папку text_processing
3) Скачать на машину файл metadata.csv, разместить его в text_processing
4) Вывести первые двенадцать строчки файла metadata.csv
```
wget https://raw.githubusercontent.com/AnastasiyaGapochkina01/vladimir/main/files/metasata.csv
```
5) Вывести последние две строки файла metadata.csv
6) С помощью grep найти все строки, содержащие слово mutex в файле metadata.csv
7) С помощью grep найти все строки НЕ содержащие слово gauge в файле metadata.csv
8) Вывести первые 5 строк файла, а затем с помощью cut получить только первый столбец этих 5 строк
9) Вывести поле unit_name из metadata.csv (весь столбец)
11) Скачать файл test.ns, разместить его в text_processing
```
wget https://raw.githubusercontent.com/AnastasiyaGapochkina01/vladimir/main/files/test.ns
```
12) Вывести все имена в A-записях из файла test.ns
13) Скачать файл coins, разместить его в text_processing
```
wget https://raw.githubusercontent.com/AnastasiyaGapochkina01/vladimir/main/files/coins
```
14) Вывести монеты, которые чеканили из золота (gold)
15) Вывести только названия стран, которые чеканили из золота (gold)
16) Вывести монеты, которые чеканили в USA
17) Найти все вхождения www-data во всех файлах в директории /etc
18) Получить все строки, не содержащие nodev из файла /proc/filesystem
