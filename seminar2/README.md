# Семинар 2. Работа в IntelliJ Idea, использование Maven

## Базовые навыки наборы в IDE IntelliJ Idea
* [Creating, Running and Packaging Your First Java Application](https://www.jetbrains.com/help/idea/creating-running-and-packaging-your-first-java-application.html)
* [Debugging Your First Java Application](https://www.jetbrains.com/help/idea/debugging-your-first-java-application.html)
* [Keyboard Shortcuts You Cannot Miss](https://www.jetbrains.com/help/idea/keyboard-shortcuts-you-cannot-miss.html)
* [Introduction to Refactoring](https://www.jetbrains.com/help/idea/introduction-to-refactoring.html)

## Язык Java
* Экосистема Java
  * [Pirates of the JVM — The infographic: Are you ready for an adventure?](https://jaxenter.com/pirates-of-the-jvm-the-infographic-132524.html)
* пакеты, import и private/public class
* модификаторы доступа полей

## [Maven](https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html)
* [Установка Maven](https://maven.apache.org/install.html)
* Создание maven-проекта [Maven Getting Started Guide](https://maven.apache.org/guides/getting-started/index.html)
  * [Создание maven-проекта в IntelliJ Idea](https://www.jetbrains.com/help/idea/maven.html)
  * [Из командной строки через archetype:generate](http://maven.apache.org/archetypes/maven-archetype-quickstart/)
* Управление зависимостями
  * [репозитории артефактов](https://maven.apache.org/guides/introduction/introduction-to-repositories.html)
  * Идентификаторы артефакта: groupId, artifactId, version. Их связь с maven central, поисковик [mvnrepository](https://mvnrepository.com)
* [Жизненный цикл сборки артефакта](https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html)
  * Фазы ЖЦ сборки: compile, clean, test и package
* Сторонние плагины
  * Добавление манифеста с помощью плагина [maven-jar-plugin](https://maven.apache.org/plugins/maven-jar-plugin/): configuration->archive->manifest->mainClass См. [пример](https://stackoverflow.com/questions/574594/how-can-i-create-an-executable-jar-with-dependencies-using-maven)
  * Цели из сторонних плагинов
* Биндинг целей плагинов к фазам ЖЦ сборки
  * Задание packaging -- Типовые "упаповки" как биндинги целей к фазам
  * Настройка фазы в плагине
* Модульное тестирование
  * [Unit Testing w/ JUnit Using Maven and IntelliJ - Pt.1](https://dzone.com/articles/unit-testing-w-junit-using-maven-and-intellij-pt1)
  * Секция test, что-нибудь в неё добавть. Показать, как ломается assertTrue(false)

## Источники
* [Туториал и справочник по Maven](https://www.tutorialspoint.com/maven/index.htm)
* [Шпаргалки по Maven] (http://www.cheat-sheets.org/#Maven)
* [Apache Maven Documentation](http://maven.apache.org/guides/)
* [Книги по Maven](https://www.amazon.com/s/ref=sr_ex_n_1?rh=n%3A283155%2Cn%3A5%2Ck%3Amaven&bbn=5&keywords=maven&ie=UTF8&qid=1491648054)
