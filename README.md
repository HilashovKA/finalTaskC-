//ЗАДАЧА
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

//Решение
Обьявляем два массива, одиновокого количества символов. Далее метод, в котором цикл идентичен длине массимва, внутри цикла проверяем условия (<=3), если ДА, элемент первого массива записывается в COUNT элемент второго массива. Далее увеличивается переменная COUNT на 1 и повторяется цикл FOR в котором i увеличивается на 1.