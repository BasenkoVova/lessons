патчи к лекции - https://drive.google.com/drive/folders/1RUW1UjRFSBJVX7DgwB7KykzHKdm_LcEv?usp=sharing


# Шестое занятие
## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) [Разбор домашнего задания](https://drive.google.com/file/d/1qpXqQXmqOD3Idx_DlKehcsY9eeUvpstS/view?usp=sharing)
**Коммиты:**
- [`lesson06 HW05`]

**Ресурсы:**
- [Автоупаковка и распаковка в Java](https://habrahabr.ru/post/329498/)
- [Преобразования Integer и int](https://habrahabr.ru/post/104231/)
- [Класс-обертка](https://www.youtube.com/watch?v=T99Dpp29jrU) (youtube)
- **Дополнительно:**
  - [Autoboxing and Unboxing](https://docs.oracle.com/javase/tutorial/java/data/autoboxing.html)
  - [Why do we use autoboxing and unboxing in Java?](https://stackoverflow.com/questions/27647407/why-do-we-use-autoboxing-and-unboxing-in-java)

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) [1. Iterator / Iterable. Вложенные, внутренние, локальные и анонимные классы](https://drive.google.com/file/d/1QfDmfkIqvOGR92w342fmT74tNXihAiHc/view?usp=sharing)
**Коммиты:**
- [`Lesson06 Iterator, Comparator and Inner Classes`]

**Ресурсы:**
- [Паттерн проектирования Итератор](https://refactoring.guru/ru/design-patterns/iterator/java/example)
- [Iterator / Iterable](http://www.javenue.info/post/101)
- **Дополнительно:**
  - [Iterator in Java](https://www.journaldev.com/13460/java-iterator)
- [Вложенные классы в Java](https://habrahabr.ru/post/342090/) 
- [Вложенные, внутренние, локальные и анонимные классы](http://pr0java.blogspot.ru/2015/08/1.html)
- [Локальные и анонимные классы](http://easy-code.ru/lesson/local-anonymous-nested-classes-java). 
- [Интерфейсы Comparable и Comparator](https://metanit.com/java/tutorial/5.6.php)
- [Анонимные классы в Java](https://www.youtube.com/watch?v=P3uicghNPLg) (youtube)
- [Nested (static) классы в Java](https://www.youtube.com/watch?v=svOwVvSWeus) (youtube)
- [Inner (non-static) классы в Java](https://www.youtube.com/watch?v=LflAy_LOwwQ) (youtube)
- **Дополнительно**
  - [Вложенные, внутренние, локальные и анонимные классы [eng]](https://docs.oracle.com/javase/tutorial/java/javaOO/nested.html)

## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) [2. Новое в Java 8](https://drive.google.com/file/d/12K49FwCieQRorJUtZEveNehMlmhz0j1d/view?usp=sharing)
**Коммиты:**
- [`Lesson06 Lambda`]

**Ресурсы:**
- [Нововведения в java 8](https://habrahabr.ru/post/216431/)
- [Лямбда-выражения в Java 8](https://www.youtube.com/watch?v=DNC6Lknn2AE) (youtube)
- [Функциональный интерфейс](https://geekbrains.ru/posts/java_interfaces)
- [Лямбды в Java 8](https://habrahabr.ru/post/224593/)
- **Дополнительно:**
  - [Java 8 Functional Interfaces](https://www.journaldev.com/2763/java-8-functional-interfaces)
  - [Lambda expressions](https://docs.oracle.com/javase/tutorial/java/javaOO/lambdaexpressions.html)


## ![video](https://cloud.githubusercontent.com/assets/13649199/13672715/06dbc6ce-e6e7-11e5-81a9-04fbddb9e488.png) [Домашнее задание HW6](https://drive.google.com/file/d/1LULdnS0wgz4yQCNPXkG-LQCTdv_ZGrV4/view?usp=sharing)
**Коммиты:**
- [`Lesson06_prepare_to_HW06`]
- Рефакторинг:
  - метод `saveOverflow()` должен исполняться только для массивов
  - в конструктор `Resume` добавьте второй параметр — `fullName`
  - во всех реализациях `Storage` замените метод `Resume[] getAll()` на `List<Resume> getAllSorted()`
- Подумайте, что еще, может выступать в качестве `search key` в реализации на основе `Map`. Выразите свои идеи в коде (в итоге у вас в проекте должны быть два класса, реализованных на основе мапы)
- Переделайте компаратор, учтя тот случай, что `fullName` разных людей может совпадать
- Из-за того, что количество тестовых классов растет, воспользуйтесь [аннотациями](http://javastudy.ru/junit/junit-suite-tests/) JUnit, которые помогут упростить их запуск. Форматируйте класс-запуска тестов в соответствии с [этой](https://drive.google.com/file/d/1XHFbxNLekyAWCPJROPJcxmJydjg0K3eH/view?usp=sharing) картинкой
