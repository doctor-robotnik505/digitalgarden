---
{"dg-publish":true,"permalink":"/sfery/programmirovanie/python/uslovnyj-operator-elif/","tags":["Программирование"]}
---

- Расшифровывается как else if 
- Если [[Сферы/Программирование/Python/Условный оператор if\|if]] не выполнится, проведётся ещё одна проверка 
	- То есть условие **выполняется только при обломе с if**
## Код, записанный с elif
```python
num = int(input("Введите число:"))
if num > 505:
    print("Число больше 505")
elif num == 404:
    print("Число равно 404")
elif num == 606:
	print("Число равно 606")
```