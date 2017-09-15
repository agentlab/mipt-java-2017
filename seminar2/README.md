# Семинар 2. Работа в IntelliJ Idea, использование Maven

## Навыки по стадиям ЖЦ программы

* Экосистема Java
  * [Pirates of the JVM — The infographic: Are you ready for an adventure?](https://jaxenter.com/pirates-of-the-jvm-the-infographic-132524.html)
* Базовые навыки наборы в IDE
  * [Creating, Running and Packaging Your First Java Application](https://www.jetbrains.com/help/idea/creating-running-and-packaging-your-first-java-application.html)
  * [Debugging Your First Java Application](https://www.jetbrains.com/help/idea/debugging-your-first-java-application.html)
  * [Keyboard Shortcuts You Cannot Miss](https://www.jetbrains.com/help/idea/keyboard-shortcuts-you-cannot-miss.html)
  * [Introduction to Refactoring](https://www.jetbrains.com/help/idea/introduction-to-refactoring.html)

* Язык Java
  * пакеты, import и private/public class
  * модификаторы доступа полей
* Maven
  * Установка
  * Создание maven-проекта
    * в IDE
    * из командной строки через archetype:generate
	* groupId и artifactId, их связь с maven central
	* Фазы compile, clean, test и package
	* фазы из сторонних плагинов. Добавление манифеста с помощью плагина maven-jar-plugin: configuration->archive->manifest->mainClass
	* Cекция test, что-нибудь в неё добавть. Показать, как ломается assertTrue(false)
