---
{"dg-publish":true,"permalink":"/sfery/programmirovanie/python/magicheskij-metod-add/","tags":["Программирование"]}
---

## Как это выглядит упрощённо 
```python
num = 52
print(num + 5) # 57
```
## Как это выглядит на самом деле 
```python
num = 52
print(num.__add__(5)) # 57
```