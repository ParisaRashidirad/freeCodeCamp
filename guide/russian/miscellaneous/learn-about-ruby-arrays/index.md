---
title: Learn About Ruby Arrays
localeTitle: Узнайте о массивах Ruby
---
### Основы:

*   Массивы - это список индексированных элементов, хранящихся в скобках `<a href='http://ruby-doc.org/core-2.2.0/Array.html' target='_blank' rel='nofollow'>]` .
*   Ruby использует нулевую индексацию. Это означает, что первый элемент массива хранится в индексном номере `0` , а второй - в индексе номер `1` и т. Д., Увеличиваясь на значения 1 для каждого дополнительного элемента, хранящегося в массиве.
*   Массивы могут быть созданы с использованием синтаксиса `[]` или `Array.new` .
*   Ruby имеет множество методов построения операций для массивов, таких как реверсирование или поиск элемента, хранящегося в массиве.

## Примеры:
```
arr = [1,2,3] 
 # is equivalent to: 
 arr = Array.new(3) 
 arr[0] = 1 
 arr[1] = 2 
 arr[2] = 3 
 # is also equivalent to: 
 arr = Array(1..3) 
 # All three of these examples return: 
 [1,2,3] 
```

## Рекомендации:

*   [Официальная документация Ruby для массивов](https://docs.ruby-lang.org/en/2.0.0/Array.html) .