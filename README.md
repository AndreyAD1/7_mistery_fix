# Решатель квадратных уравнений

Модуль **`quadratic_equation`** вычисляет корни квадратного уравнения.

# Как использовать

Модуль **`quadratic_equation`** требует для своей работы
интерпретатор Python версии 3.5.
Модуль содержит одну функцию - **`get_roots(a,b,c)`**, которая
возвращает корни квадратного уравнения **`ax^2+bx+c=0`**.
В случае отсутствия корня уравнения функция возвращает **`None`**.

Пример использования модуля:
```python
>>> from quadratic_equation import get_roots
>>> get_roots(1,-2,1)
(1.0, None)
```

# Как запустить
Чтобы протестировать работу модуля **`quadratic_equation`** поместите в папку с модулем файл `tests.py` и запустите его.
Скрипт сообщит о том, прошли ли тесты упешно.
Пример запуска tests.py на системе Linux:
```bash
$ tests.py
....
-------------------------------------------------
Ran 4 tests in 0.03s

OK
```
Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
