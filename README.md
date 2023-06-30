# Итоговое задание
## Задача:
### Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
## Решение:
### В первую очередь создаются два массива, один из которых заполнен исходными данными, а второй пустой, но у которого размер равен размеру первого массива. Суть решения заключается в том что происходит перебор каждого элемента первого массива с целью проверки его размера и если размер меньше либо равен трем то этот элемент массива записывается во второй массив. Чтобы запись шла по порядку создается счетчик который увеличивается каждый раз когда записывается очередной элемент во второй массив. В конце выводим второй массив.
