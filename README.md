# mitp-java-2017

# Семинар 1. Работа с инструментами командной строки Java SDK

## Навыки по стадиям ЖЦ программы

* Собрать и запустить через консоль
  * https://www.youtube.com/watch?v=Nvj4gN7PuS4
* Отладить через консоль
  * https://www.youtube.com/watch?v=i2FcaVNXjb0
* Зарелизить jar сборку через консоль
  * https://www.youtube.com/watch?v=WTfjbOIfi10

И вообще, любите консоль!
  * [JDK Tools and Utilities](http://docs.oracle.com/javase/8/docs/technotes/tools/)

## Типы приложений

* Утилиты командной строки с аргументами командной строки. Разбор аргументов разного уровня сложности.
  * https://www.youtube.com/watch?v=-CbBayOZrEw
  * [Oracle: Command-Line Arguments](https://docs.oracle.com/javase/tutorial/essential/environment/cmdLineArgs.html)
  * [Для крутых] https://commons.apache.org/proper/commons-cli/usage.html
* Интерактивные консольных программы с консольным вводом-выводом. Декораторы потоков
  * https://www.youtube.com/watch?v=Kp5CGyLct20
  * [Oracle I/O from the Command Line](https://docs.oracle.com/javase/tutorial/essential/io/cl.html)
  * https://alvinalexander.com/java/edu/pj/pj010005
* Обработка исключительных ситуаций. Мышление в разрешенных и запрещенных состояниях и ограничениях
  * [Oracle Lesson: Exceptions](https://docs.oracle.com/javase/tutorial/essential/exceptions/index.html)
* Консольные программы с файловым вводом-выводом.
  * [Java vs C++; Работа с исключениям и I/O](https://goo.gl/wps6dA) [примеры кода](https://github.com/DanAnastasyev/mipt-java-2016/tree/master/seminars/src/ru/mipt/java2016/seminars/seminar1)
  * [Oracle Lesson: Basic I/O](https://docs.oracle.com/javase/tutorial/essential/io/)

## Вредное задание на семинар

Написать консольное приложение-шифровальщик (используя только текстовый редактор и консоль, без IDE). Отладить и выпустить в виде распространяемой jar сборки.

* Нефункциональные требования к приложению
  * Консольное приложение в виде jar-сборки
  * Максимально возможная скорость работы
  * Учесть все исключительные и нежелательные ситуации, чтобы приложение работало корректно в любых условиях
* Функции приложения
  * При запуске без параметров шифрует (xor с ключом 31337) содержимое всех файлов в текущей папке и ее подпапках всех файлов в текущей папке и ее подпапках
  * При запуске с одним параметром (ключ) расшифровывает с содержимое всех файлов в текущей папке и ее подпапках всех файлов в текущей папке и ее подпапках
  * При запуске с флагом -h показывает справку программы (с какими параметрами запуска что может делать)
