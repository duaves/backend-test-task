# Backend test task

## PHP

1. Реализовать свою функцию сортировки. Функция принимает массив целых чисел и
булевый параметр направления, возвращает массив.
Принцип работы. Числа во входящем массиве передаются хаотично, например в таком
порядке: 1, 5,6,2,8,10,100,14... В зависимости от второго булевого параметра функция
сортирует входящий массив в порядке убывания или в порядке возрастания и возвращает
его. То есть на выходе получаем массив либо как 1,2,3,4,5..., либо как ...5,4,3,2,1.
2. Написать функцию-парсер новостей с сайта www.opennet.ru. Функция должна вернуть
ассоциативный массив с заголовками и ссылками на статьи с индексной страницы сайта.
3. Расширение функции из задачи 2. Данные хранить в кеше, организованном в памяти.
Если, при повторном вызове функции, в кеше есть запись с заголовком статьи и ссылкой,
то их не записывать, если нет, то записать в кеш.

Все задачи должны выполняться в среде php-cli.

## PostgreSQL
1. Написать функцию из задачи 1 для PHP.

## Установите зависимости, выполнив

```
composer install
```
