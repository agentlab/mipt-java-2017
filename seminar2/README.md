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
  * в IDE
  * из командной строки через archetype:generate
* Управление зависимостями
  * репозитории артефактов
  * groupId и artifactId, их связь с maven central
* [Жизненный цикл сборки артефакта](https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html)
  * Фазы ЖЦ compile, clean, test и package
* Сторонние плагины
  * фазы из сторонних плагинов. Добавление манифеста с помощью плагина maven-jar-plugin: configuration->archive->manifest->mainClass
* Модульное тестирования
  * секция test, что-нибудь в неё добавть. Показать, как ломается assertTrue(false)
