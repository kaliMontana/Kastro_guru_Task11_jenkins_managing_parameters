# ru.guru.task 11
1. Доработать свой код:

1.1 Передать из дженкинса адрес selenoid c System.properties

1.2 Спрятать логин/пароль к selenoid в .properties файл, считывать его нужно в коде с owner




2. Групповое дз (выполнить после разделения на группы, будет объявление в чате):

2.1 Сделать сборку в дженкинсе на код коллеги (тест должен успешно пройти)

2.2 Подготовить код, чтобы на ваши тесты коллега сделал сборку с дженкинс.

Комманд для запуска тестов из консоли в selenoid:

gradle clean withListener -DselenoidUrl='selenoid.autotests.cloud/wd/hub' allureServe

gradle clean test -DselenoidUrl='selenoid.autotests.cloud/wd/hub' allureServe
