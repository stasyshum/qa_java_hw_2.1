# qa_java_hw_2.1
# Отчёт о тестировании Money Transfer #


30.01.2021 - 30.01.2021 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 1 ч.

 ### В результате тестирования выявлены следующие дефекты: ###

1 [Неверное суммирование денежных средств в текущем счете Money Transfer ](https://github.com/stasyshum/qa_java_hw_2.1/issues/1 )  



### Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

-Тест-кейс домашнего задания №2.1 с данными сумм денежных средвст и описанным типом данных.  


Согласно текст-кейсу был написан программный код, приложенный в папке scr. Согласно заданию и написанному коду, ожидаемый результат должен быть равен 2_500_000_000. Однако данное число больше вместимости целочесленного типа данных int (макс. 2 147 483 647), из-за чего фактический результат отличается от ожидаемого.


### Ожидаемый результат:  
*Текущий счет: 2_500_000_000.*

### Фактический результат:
*Текущий счет:-1794967296.*

*Тестирование производилось в следующем окружении:*

Windows 10 64 bit  
java -version (openjdk version "11.0.10" 2021-01-19)
