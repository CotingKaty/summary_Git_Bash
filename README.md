<div>
<h3 align="center">summary_Git_Bash
  <img src="https://drive.google.com/uc?export=download&confirm=no_antivirus&id=1bT8xerzZ_L4P9KnG-pPrs8VNYfLfH_Xk" title="Git" alt="Git" width="40" height="40"/></h3>
  </div>
<h5 align="center">My personal summary Git_Bash</h5>


Git-Bash homework подробно

#1) Посмотреть где я

sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1
$ `pwd`
/c/Users/sss/Documents/Git_Bash/homework/new_1/folder_1

#2) Создать папку
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1
$ `mkdir new`

#3) Зайти в папку
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1
$ `cd new`

#4) Создать 3 папки
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `mkdir 1 2 3`

#5) Зайти в любоую папку
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `cd 1`

#6) Создать 5 файлов (3 txt, 2 json)
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new/1
$ `touch {1.txt,2.txt,3.txt,1.json,2.json}`

#7) Создать 3 папки
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new/1
$ `mkdir 4 5 6`

#8. Вывести список содержимого папки
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new/1
$ `ls -l`
total 0
-rw-r--r-- 1 sss 197121 0 Feb  9 13:05 1.json
-rw-r--r-- 1 sss 197121 0 Feb  9 13:05 1.txt
-rw-r--r-- 1 sss 197121 0 Feb  9 13:05 2.json
-rw-r--r-- 1 sss 197121 0 Feb  9 13:05 2.txt
-rw-r--r-- 1 sss 197121 0 Feb  9 13:05 3.txt
drwxr-xr-x 1 sss 197121 0 Feb  9 13:06 4/
drwxr-xr-x 1 sss 197121 0 Feb  9 13:06 5/
drwxr-xr-x 1 sss 197121 0 Feb  9 13:06 6/


#9) + Открыть любой txt файл
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new/1
$ `cat 1.txt`

#10) + написать туда что-нибудь, любой текст.
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new/1
$ `cat >> 1.txt`
```
{
        "user_name":"Maria",
        "user_age": 34,
        "salary": 1000,
        "family": {
                "person_1":{
                        "name":"Max",
                        "age": 2
                },
                "person_2":{
                        "name":"Murzik",
                        "age": 2
                }
        }
}

{
        "user_name":"Maria",
        "user_age": 34,
        "salary": 1000,
        "family": {
                "person_1":{
                        "name":"Max",
                        "age": 2
                },
                "person_2":{
                        "name":"Murzik",
                        "age": 2
                }
        }
}
```


#11) + сохранить и выйти.
На клавиатуре набрать `Ctrl`+`C`

#12) Выйти из папки на уровень выше
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new/1
$ `cd ..`
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$

#13) переместить любые 2 файла, которые вы создали, в любую другую папку.
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1
$ `mv 1.txt new/1.txt`

sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1
$ `mv 1.json new/1.json`

#14) скопировать любые 2 файла, которые вы создали, в любую другую папку.
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `cp 1.json 1/1.json`

sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `cp 1.txt 1/1.txt`

#15) Найти файл по имени
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `find 1/1.txt`
1/1.txt

#sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `find 1/1.txt`
1/1.txt

#16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает.

sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `tail -f 1.txt`
Hello World

#17) вывести несколько первых строк из текстового файла
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `head -n10 1.txt`
Hello World

{
        "user_name":"Maria",
        "user_age": 34,
        "salary": 1000,
        "family": {
                "person_1":{
                        "name":"Max",
                        "age": 2



#18) вывести несколько последних строк из текстового файла
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `tail -n5 1.txt`
                        "name":"Murzik",
                        "age": 2
                }
        }
}


#19) просмотреть содержимое длинного файла (команда less) изучите как она #работает.
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `less 1.txt`


#20) вывести дату и время
sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `date`
Thu Feb  9 13:42:03 RTZ 2023


#Задание *
#1) Отправить http запрос на сервер.

sss@HOME-PC MINGW64 ~/Documents/Git_Bash/homework/new_1/folder_1/new
$ `curl http://162.55.220.72:5005/terminal-hw-request`
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   232  100   232    0     0   2162      0 --:--:-- --:--:-- --:--:--  2188<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 3.2 Final//EN">
<title>404 Not Found</title>
<h1>Not Found</h1>
<p>The requested URL was not found on the server. If you entered the URL manually please check your spelling and try again.</p>

2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
```
#! /bin/bash
pwd
#3) Зайти в папку
mkdir from_script

#4) Создать 3 папки
mkdir from_skript_1 from_script_2 from_script_3

#5) Зайти в любоую папку
cd from_script_3

#6) Создать 5 файлов (3 txt, 2 json)
touch {7.txt,8.txt,9.txt,6.json,5.json,4.sh}

#7) Создать 3 папки
mkdir from_skript_4 from_script_5 from_script_6

#8. Вывести список содержимого папки
ls -l

pwd
#13) переместить любые 2 файла, которые вы создали, в любую другую папку.
mv 8.txt new_1.1/8.txt
```


