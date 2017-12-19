# Решатель квадратных уравнений

Предназначен для вычисления корней квадратного уравнения

# Как использовать

Для вычислений предназначена функция get_roots, которая принимает 3 аргумента и возвращает корни квардратного уравнения или None в зависимости от значения дискриминанта

Пример использования функции:

```python
from quadratic_equation import get_roots

print(get_roots(1, 2, -3)) # (-3.0, 1.0)
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
