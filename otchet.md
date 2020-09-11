# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

11.09.2020 - 11.09.2020 было проведено функциональное тестирование Credit Card Number Validator

На тестирование затрачено: 40 минут (с учетом написания баг-репортов)

В результате тестирования выявлены следующие дефекты:
* https://github.com/OllyHard/java_2/issues/1
* https://github.com/OllyHard/java_2/issues/2

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Баг-репорт
* Отчет о тестировании

В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
* Карта VISA 4532454442786487 - Result is ОК
* Карта VISA 4716970208694555 - Result is ОК
* Карта MasterCard 5275904212007231 - Result is ОК
* Карта MasterCard 2720996545804670 - Result is ОК
* Карта American Express (AMEX) 343403370237416 - Result is ОК
* Карта Diners Club - Carte Blanche 30497181168107  - Result is ОК

Тестирование производилось в следующем окружении:
* Windows 10/64-разрядная
* Java 11.0.8
* IntelliJ IDEA Community 2020.2.1
