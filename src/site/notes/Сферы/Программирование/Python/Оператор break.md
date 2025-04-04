---
{"dg-publish":true,"permalink":"/sfery/programmirovanie/python/operator-break/","tags":["Программирование"]}
---

- Останавливает [[Сферы/Программирование/Python/Циклы Python\|цикл]]
```python
for stroka in "Hello World": # Перебор строки посимвольно
    if stroka == "o":
        print("Буква o была найдена")
        break # Заканчивает цикл после первой найденной буквы o
```