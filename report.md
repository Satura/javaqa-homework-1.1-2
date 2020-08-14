# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

13.08.2020 было проведено позитивное и негативное функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 45 минут

В результате тестирования выявлены следующие дефекты:
* [описание дефекта](https://github.com/Satura/javaqa-homework-1.1-2/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Набор тест-кейсов](https://docs.google.com/spreadsheets/d/1_3pHX70nfMOuITghuxrfbaSxt6ApZ-Kw-_HUTd7V6dk/edit?usp=sharing)


В качестве тестовых данных использовались данные генераторов номеров кредитных карт:
* https://fakepersongenerator.com/Random1/credit_card_generator  
* https://www.randomaddressgenerator.com/visa13-credit-card-generator/ 
* https://wtools.io/ru/credit-card-generator

Номера сгенерированных карт перепроверялись на ресурсах: 
* https://planetcalc.ru/2465/
* https://cardgenerator.io/credit-card-validator/

Тестирование производилось в следующем окружении:
* Windows 10 x64
* openjdk version "11.0.8" 2020-07-14
* IntelliJ IDEA 2020.02
