## Список

Список: упорядоченная изменяеммая коллекция объектов.
Списки в Python очент похожи на массивы в других языках программирования.
Это индексируеммые коллекции объектов, в которых элементы нумеруются, 
начиная с нуля.

В Python списки являются **динамическими** структурами и количество 
элементов в них можно менять по требованию. Кроме того, списки могут быть
**гетерогенными**, в один и тот же список можно добавлять объекты разных 
типов. Так же в списоке можно изменить в любой момент, добавив, удалив 
или изменив объекты.

Списки всегда заключены в **квадратные скобки**, а объекты в списке 
всегда отделяются друг от друга **запятыми**.

```python
# Пример пустого списка
found = []

# Пример однострочного списка
word = [ "Hello", "world"]

# Приммер многосторочного списка
odds = [ 1, 3, 5, 7, 9, 11, 13, 15, 17, 19,
         21, 23, 25, 27, 29, 31, 33, 35, 37,
         39, 41, 43, 45, 47, 49, 51, 53, 55,
         57, 59 ]
```

**Литеральным** называется список заполненый объектами непосредственно в 
коде.

Другой способ создания и заполнения списка - постеаенное добавление в 
него элементов в процессе выполнения программы.

```python 
# Объекты с плавующей точкой
float = [3.4, 1.0, 55,7]

# Список строковых объектов
words = ['hello', 'world']

# Список различных объектов
another = ['Toys', 76, 2.2]

# Список в списке
everything = [ float, words, another]

ends = [ [ 1, 2, 3], [ 'a', 'b', 'c'], [ 'one', 'two', 'three'] ]
```
