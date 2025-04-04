---
{"dg-publish":true,"permalink":"/sfery/programmirovanie/python/uslovnyj-operator-else/","tags":["Программирование"]}
---

- Его нужно ставить в конце после [[Сферы/Программирование/Python/Условный оператор if\|if]] и [[Сферы/Программирование/Python/Условный оператор elif\|elif]] 
- Срабатывает лишь в том случае, если все предыдущие проверки не сработали
```python
a = int(input("Введите число 1: "))
b = int(input("Введите число 2: "))
summa = a + b
proizvedenie: a * b

print ("Сумма чисел:", summa)
print ("Разность чисел:", a - b)
print ("Произведение чисел:", proizvedenie)
print ("Частное чисел:", a / b)

if summa == 50 and proizvedenie == 625:
    print ("Отлично!!!")
else:
    print ("В другой раз повезёт...")
```
