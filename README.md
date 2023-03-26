# ChoosingSpecial
В репозитории представлено решение итоговой проверочной работы.

Задача: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше или равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Приложена блок-схема алгоритма решения.

Описание решения:
Пользователь вводит массив строк с помощью клавиатуры, отделяя элементы массива строк с помощью пробела. Создаем второй массив такой же длины. Напишем метод с циклом, соразмерным длине массива. Внутри цикла находится проверка условия (<=3). Если условие соблюдено, то элемент первого массива заносится в count второго массива, затем переменная count увеличивается на 1 и возвращается к циклу for, в котором i увеличивается на 1, и так проверяем до конца. Если условие не соблюдено, то также возвращаемся к циклу for, в котором i увеличивается на 1, и так проверяем до конца. Затем выводим массив строк, длина которых меньше или равна 3 символам, на экран.

Рушение представлено в Itog/Program.cs
