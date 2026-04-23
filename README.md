# Numerical Methods

This repository contains two laboratory works:  
- Solving nonlinear equations  
- Function approximation and interpolation  

---

## English Version

## Lab 1: Solving Nonlinear Equations

### Problem
Find the root of the nonlinear equation:

$$f(x) = 2\ln(x) - \frac{1}{x} = 0$$

### Methods Used
1. **Fixed-Point Iteration Method**
2. **Newton's Method**
3. **Steffensen's Method**

### Key Steps
- Graphical root isolation
- Convergence analysis using contraction mapping theorem
- Iterative solution with precision $\varepsilon = 10^{-7}$
- Comparison of methods by:
  - Number of iterations
  - Residual $f(x^*)$
  - Convergence rate

---

## Lab 2: Approximation & Interpolation

### Problem
Reconstruct function values based on tabulated data:

$$f(x) = \alpha e^x + (1 - \alpha)\cos(x)$$

### Methods Used
1. **Least Squares Approximation (Polynomial degree 5)**
2. **Lagrange Interpolation Polynomial**
3. **Newton Interpolation (Divided Differences)**
4. **Chebyshev Nodes Interpolation**
5. **Newton–Bessel Interpolation (central interpolation)**

### Key Features
- Construction of interpolation polynomials
- Error estimation (theoretical vs practical)
- Comparison of node distributions (uniform vs Chebyshev)

---

## Key Insights

- Quadratic convergence does not guarantee fewer iterations (depends on constants)
- Numerical stability is critical for higher precision
- Choice of interpolation nodes significantly affects accuracy
- Chebyshev nodes minimize interpolation error

---

## Technologies
- Python
- NumPy
- Matplotlib
- Pandas

---

## Русская версия

## Лабораторная работа 1: Решение нелинейных уравнений

### Задача
Найти корень уравнения:

$$f(x) = 2\ln(x) - \frac{1}{x} = 0$$

### Используемые методы
1. **Метод простой итерации**
2. **Метод Ньютона**
3. **Метод Стеффенсена**

### Основные этапы
- Графическое отделение корня
- Проверка условий сходимости
- Итерационное решение с точностью $\varepsilon = 10^{-7}$
- Сравнение методов по:
  - количеству итераций
  - невязке $f(x^*)$
  - скорости сходимости

---

## Лабораторная работа 2: Аппроксимация и интерполяция

### Задача
Восстановить значения функции:

$$f(x) = \alpha e^x + (1 - \alpha)\cos(x)$$

### Используемые методы
1. **Метод наименьших квадратов (5-я степень)**
2. **Многочлен Лагранжа**
3. **Интерполяция Ньютона (разделённые разности)**
4. **Интерполяция на узлах Чебышёва**
5. **Формула Ньютона–Бесселя**

### Особенности
- Построение интерполяционных многочленов
- Теоретическая и практическая оценка погрешности
- Сравнение равномерных и чебышёвских узлов

---

## Технологии
- Python
- NumPy
- Matplotlib
- Pandas