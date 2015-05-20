# Геповая колонка

В выравнивании могут попадаться колонки, состоящие целиком из
гепов:

```
ACAG---CGAGTA-GTC-GGCAGGA
ACAG---CGAGTT-GTC-GGCAGGA
ACAG---GGAGTT-GTCTGGCAGGA
```

Ваша задача исправить выравнивание, "схлопнув" геповые колонки:

```
ACAGCGAGTAGTC-GGCAGGA
ACAGCGAGTTGTC-GGCAGGA
ACAGGGAGTTGTCTGGCAGGA
```

## Задание

Напишите функцию `f`, которая получает на вход выравнивание в
форме таблицы, состоящей из строк одинаковой длины. Если в
выравнивании есть полностью геповые колонки, их надо исключить.
Функция должна возвращать исправленное выравнивание.

Функция должна порождать ошибку в случае входных данных, не
соответствующих условию задачи.