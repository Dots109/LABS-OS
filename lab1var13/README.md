Родительский процесс создает два дочерних процесса. Перенаправление стандартных потоков
ввода-вывода показано на картинке выше. Child1 и Child2 можно «соединить» между собой
дополнительным каналом. Родительский и дочерний процесс должны быть представлены
разными программами.
Родительский процесс принимает от пользователя строки произвольной длины и пересылает их в
pipe1. Процесс child1 и child2 производят работу над строками. Child2 пересылает результат своей
работы родительскому процессу. Родительский процесс полученный результат выводит в
стандартный поток вывода.

    13 вариант. Child1 переводит строки в нижний регистр. Child2 превращает все пробельные
    символы в символ «_».

![Alt text](image.png)