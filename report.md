# Отчёт о тестировании <Денежных переводов>

## Краткое описание

13.09 было проведено функциональное тестирование приложения <Денежные переводы>.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
https://github.com/Lyuda-Ostroumova/Money-Transfer/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
Тест-кейс https://docs.google.com/spreadsheets/d/1M6iPGck9gtouN62UUGYLUGon64H1Vi7G5G6yy_Kj9LI/edit?usp=sharing


В качестве тестовых данных использовались данные, указанные в условии, а также эквивалентные значения больше и меньше указанного в условии:
* сумма перевода 500 000 000 - ожидаемый результат: итоговая сумма 2 500 000 000
* сумма перевода 100 000 000 - ожидаемый результат: итоговая сумма 2 100 000 000
* сумма перевода 600 000 000 - ожидаемый результат: итоговая сумма 2 600 000 000


Тестирование производилось в следующем окружении:
Windows 10 Pro 64
Java 11.0.12
