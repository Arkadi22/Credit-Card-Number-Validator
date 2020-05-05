# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

05.05.2020 было проведено тестирование граничный значений приложения Credit Card Number Validator

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Получаю статус "Fail" при вводе валидной 14-значаной кредитной карты](https://github.com/Arkadi22/Credit-Card-Number-Validator/issues/1)
* [Получаю статус "Fail" при вводе валидной 15-значаной кредитной карты](https://github.com/Arkadi22/Credit-Card-Number-Validator/issues/2)
* [Получаю статус "Fail" при вводе валидной 19-значаной кредитной карты](https://github.com/Arkadi22/Credit-Card-Number-Validator/issues/3)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* Checklist 
* Баг-репорт

В качестве тестовых данных использовались данные из сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html#fakeNumbers)

* Visa Card 4716522175821950 (Result is OK)
* Master Card 5189304385160920 (Result is OK)
* Diners Club - International 36164178087617 (Result is OK)
* American Express (AMEX) 378351491260080 (Result is OK)
* Visa Card 4556671782685030000 (Result is OK)

Тестирование производилось в следующем окружении:
* Windows 10 Pro 64-bit
* Java version "11.0.7" 2020-04-14
