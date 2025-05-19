Comparison the numerical methond (Euler method, Runge–Kutta method, 
Runge-Kutta-Merson method) with physics-informed neural network on simple example.
Equation: y'+y = 3*exp(2x), where 0<=x<=1
Analytical solution: y(x) = exp(2x)
Modelling results:
Xi   Yан(xi)*     Yi(Euler)*    Yi(Runge-Kutta)*    Yi (R-K-M)*     PINN

 0     1           1               1                 1              0.9999
0.2    1.49183     1.4             1.49186           1.49184        1.4932
0.4    2.22554     2.0151          2.22563           2.22557        2.2247
0.6    3.32012     2.9474          3.32028           3.32017        3.3222
0.8    4.95303     4.34999         4.95329           4.95313        4.9515
 1     7.38906     6.45181         7.38946           7.38921        7.3889

Runge-Kutta-Merson (R-K-M) method
*Results of numerical modelling was taken from:
ЧИСЛЕННЫЕ МЕТОДЫ РЕШЕНИЯ КРАЕВЫХ ЗАДАЧ ДЛЯ ОБЫКНОВЕННЫХ
ДИФФЕРЕНЦИАЛЬНЫХ УРАВНЕНИЙ Крайнов А.Ю., Моисеева К.М.
