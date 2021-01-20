# **Отчёт о тестировании Credit Card Number Validator** #

## **Краткое описание** ##
20.01.2021 было проведено функциональное тестирование Credit Card Number Validator.

На тестирование затрачено:  1 час

В результате тестирования выявлены следующие дефекты:

* [Валидные номера банковских карт с числом цифр отличным от 16, считываются как невалидные](https://github.com/KiraSyromiatnikova/CCNV/issues/1)

## **Описание процесса тестирования** ##

В процессе тестирования использовались следующие артефакты:
* [Установка IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* Баг-репорт

В качестве тестовых использовались данные, полученные из [генератора валидных номеров карт](https://www.freeformatter.com/credit-card-number-generator-validator.html).

Тестирование производилось в следующем окружении:
* Windows 10 x64
* Java 11.0.9

