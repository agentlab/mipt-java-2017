# mitp-java-2017

# Семинар 1. Работа с инструментами командной строки Java SDK

## Навыки по стадиям ЖЦ программы

* Собрать и запустить через консоль
  * https://www.youtube.com/watch?v=Nvj4gN7PuS4
* Отладить через консоль
  * https://www.youtube.com/watch?v=i2FcaVNXjb0
* Зарелизить jar сборку через консоль
  * https://www.youtube.com/watch?v=WTfjbOIfi10

## Типы приложений

* Утилиты командной строки с аргументами командной строки. Разбор аргументов разного уровня сложности.
  * https://www.youtube.com/watch?v=-CbBayOZrEw
  * https://docs.oracle.com/javase/tutorial/essential/environment/cmdLineArgs.html
  * [Для крутых] https://commons.apache.org/proper/commons-cli/usage.html
* Интерактивные консольных программы с консольным вводом-выводом. Декораторы потоков
  * https://www.youtube.com/watch?v=Kp5CGyLct20
  * https://docs.oracle.com/javase/tutorial/essential/io/cl.html
  * https://alvinalexander.com/java/edu/pj/pj010005
* Консольные программы с файловым вводом-выводом. Обработка исключительных ситуаций. Мышление в разрешенных и запрещенных состояниях и ограничениях
  * [Java vs C++; Работа с исключениям и I/O](https://goo.gl/wps6dA) 
  * https://github.com/DanAnastasyev/mipt-java-2016/tree/master/seminars/src/ru/mipt/java2016/seminars/seminar1
  * https://stackoverflow.com/questions/38012164/xor-operation-on-first-256-bytes-of-an-video-file

## Вредное задание на семинар

Написать шифровальщик -- консольное приложение, которое шифрует (xor с ключом 31337) содержимое всех файлов в текущей папке и ее подпапках. Учесть все исключительные и нежелательные ситуации. Отладить и выпустить в виде распространяемой jar сборки.
