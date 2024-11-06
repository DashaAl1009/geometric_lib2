
# How to use calculator:
1. Run `python calculate.py`
2. Enter the figure name. Available are Circle, Square.
3. Enter the function: Area or Perimeter.
4. Enter figure sizes. Radius for circle, one side for square.
5. Get the answer!

# Math formulas
## Area
- Circle: `S = πR²`
- Rectangle: `S = ab`
- Square: `S = a²`
- Triangle: `S = sqrt(p * (p-a) * (p-b) * (p-c))` where p is semiperimeter

## Perimeter
- Circle: `P = 2πR`
- Rectangle: `P = 2a + 2b`
- Square: `P = 4a`
- Triangle: `P = a + b + c`

# Library Description
### Geometric_lib allows you to calculate some data connected with geometrical shapes

## Circle
- Area(r)
### Принимает длины сторон a, b, c треугольника и вычисляет площадь 

- Perimeter(r)
### Принимает радиус окружности и вычисляет её длину

## Triangle
- Area(a, b, c)
### Принимает длины сторон a, b, c треугольника и вычисляет площадь

- Perimeter(a, b, c)
### Принимает длины сторон a, b, c треугольника и вычисляет периметр

## Square
- Area(a)
### Вычисляет площадь квадрата по стороне а 

- Perimeter(a)
### Вычисляет периметр квадрата по стороне а

## Calculate
- Calc(fig, func, size)
### Пользователь вводит название фигуры, затем имя функции.
### В зависимости от этого программа вычисляет либо площадь, либо периметр выбранной фигуры

# Commit history
* commit d76db2ac7f69cc920ae2e6f669fb0671a7fa7d71
| Author: Daniil.K <dlkay@yandex.ru>
| Date:   Tue Mar 30 17:57:42 2021 +0300
|
|     L-04: Add calculate.py
|
* commit 51c40ebfd0e0b65f52fe5e54740cbb038e492db3
| Author: smartiqa <info@smartiqa.ru>
| Date:   Fri Mar 26 14:52:26 2021 +0300
|
|     L-04: Doc updated for triangle
|
* commit d080c7888b81955bad2ed78d58ad910526b5132a
| Author: smartiqa <info@smartiqa.ru>
| Date:   Fri Mar 26 14:48:39 2021 +0300
|
|     L-04: Triangle added
|
* commit d078c8d9ee6155f3cb0e577d28d337b791de28e2 (origin/main, origin/HEAD)
| Author: smartiqa <info@smartiqa.ru>
| Date:   Thu Mar 4 14:55:29 2021 +0300
|
|     L-03: Docs added
|
* commit 8ba9aeb3cea847b63a91ac378a2a6db758682460
  Author: smartiqa <info@smartiqa.ru>
  Date:   Thu Mar 4 14:54:08 2021 +0300

      L-03: Circle and square added
