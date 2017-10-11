# Решатель квадратных уравнений

Проект предназначен для решения простых квадратных уравнений вида *ax^2 + bx + c = 0*.

Состоит из модуля решения (*quadratic_equation*) и модуля с его тестированием (*tests*).

# Как использовать

В модуле *quadratic_equation* содержится функция:
```python
get_roots(a, b, c)
```
Она принимает на вход коэффициенты квадратного уравнения вида *ax^2 + bx + c = 0*.

Формат ответа:
```python
(root1, root2)
```

Импорт функции из модуля:
```python
from quadratic_equation import get_roots
```
Примеры использования функции:

+ пример 1
 ```python
 print(get_roots(1, -2, 1))
 ```
 результат:
 ```python
 (1.0, None)
 ```
 
+ пример 2
 ```python
 print(get_roots(1, 2, -3))
 ```
 результат:
 ```python
 (-3.0, 1.0)
 ```
  
+ пример 3
 ```python
 print(get_roots(1, 2, 3))
 ```
 результат:
 ```python
 (None, None)
 ```
# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
