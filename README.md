1. Для доступа и запуска скриптов в любой из любой директории:
Добавить в .bashrc путь к поиску скриптов dir/dir/scripts

    PATH=$PATH:/home/kovtun/Projects/Scripts
    export $PATH

2. Создать скрипт в директории dir/dir/scripts при подключении нашей
директории в PATH bash будет видеть все наши скрипты которые мы добавим:

    1. nano scriptname
    2. добавить в наш файл !#/bin/bash
    3. поменять права нашему скрипту: chmod +x scriptname

Теперь мы можем вызвать наш скрип с любой директории при помощи scriptname