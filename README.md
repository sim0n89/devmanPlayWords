# Отгадай слово (поле чудес)

## Получить случайное слово
Из файла data/sowpods.txt берется набор букв.

## Вывести слово на экран
Выводятся неверные буквы ранее введенные пользователем. 
Выводится загаданная строка в виде пробелов, но если есть отгаданная буква, то выводится она.
Выводится загаданная строка в виде прочерков, где один прочерк это буква.

![Вывести слово на экран](imgs/Screenshot_1.png)

## Получить букву
Пользователь вводит букву. Нельзя вводить слово или ничего не вводить. Введенная буква должна быть в нижнем регистре ASCII.
Выводится количество ранее введенных попыток.

![Получить букву](imgs/Screenshot_2.png)

## Игра
Дается 6 попыток.
Пользователь вводит букву.
Если пользователь ввел букву из загаданного слова, то выводится загаданная строка с отображением отгаданных букв.
Если в строке больше нечего отгадывать выводится сообщение you win. 
Если попытки закончились и выводится сообщение you lose.