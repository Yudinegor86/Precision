# Отчёт о тестировании Precision

## Краткое описание

17:00-17:30 12.05.2021 было проведено функциональное тестирование по методу Белый ящик, приложения Precision.

На тестирование затрачено: 30 минут

В результате тестирования выявлены следующие дефекты:
* [Не верный результат при сложении данных переменных типа double](https://github.com/Yudinegor86/Precision/issues/1#issue-890075066)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Код для приложения Precision](https://github.com/Yudinegor86/Precision/blob/master/src/Main.java)



В качестве тестовых данных использовались данные кода для приложения Precision :
* double regularBonus = 0.3;<br>
* double specialBonus = 0.6;<br>
* double totalBonus = regularBonus + specialBonus<br>
* Ожидаемый результат: 0.9

Тестирование производилось в следующем окружении:
* Windows 10 x64
* jdk version "11.0.10"
* IntelliJ IDEA 2021.1.1 
