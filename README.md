# Контрольная работа

## Задача
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

*Примеры:*


* ["hello" , "2" , "world" ":-)"] -> ["2" , ":-)"]

* ["1234", "1567" , "-2" , "computer sciense" ] -> ["-2"]

* [ "Russia" , "Denmark" , "Kazan"] -> []

## Описание решения задачи :
* Для начала мы обьявляем два массива. Задаем длину первому, а за тем указываем, что длина второго массива будет идентична первому. 

* Далее мы создаем метод, в котором мы создаем счетчик и цикл for. Далее мы проверяем условия нашей задачи : длина строк в созданном массиве не должна быть больше 3-х символов.  Указываем, что наш массив мы будем заполнять строками из первого массива. ( У нас проверяется условие, если слово или количество цифр соответсвует, то символы добовляются в наш массив, если нет, то программа возвращается в цикл for, который переходит к следущей строке )

* Ну и далее мы создаем метод, который собственно и собирает наш массив.

* Вконце выводим наш массив в консоль.

