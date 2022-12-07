# Задача :

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

# Описание алгоритма решения:

В начале объявляется два массива: изначальный и вторый такой же длины. 

Потом метод, в котором цикл FOR соразмерный длине массива, внутри цикла проверка условия IF( <=3 ), если да элемент первого массива заносится в COUNT  элемент второго массива.

Переменная COUNT чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. 

После присвоения увеличивается переменная COUNT  на 1 и возвращается к циклу FOR в котором i увеличивается на 1. Таким образом  проверяется до конца.

# Методы, которые были использованы:

- NewArray - для ввода массива пользователем.

- PrintArray - создание и вывод запрашиваемого по условию задачи массива.