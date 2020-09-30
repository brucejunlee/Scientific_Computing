# Scientific_Computing



## FourierTransform_PDE

+ 给出了Fourier变换的推导以及在PDEs中的应用；

+ 给出了1+1维Heat方程和Wave方程的解推导和动画展示；

+ 给出了三维线图和surface图的示例；

+ 给出了三维动画展示，参考前面Fourier变换在PDE中的应用，可以很容易就推广到2+1维PDEs的动画实现；

+ 为了学习的便利，这里没有给出.py文件，而是直接给出了notebook。



## Computing_Symbolically

+ 列出了handcalc库的一些简单使用，该库主要用于指定输出格式的设定；
+ 概要地探究了sympy符号库的一些特性，包括符号结构树，expand, factor,  collect, cancel, simplify, limit, series, diff, integrate, solve, dsolve等；
+ 除此之外，sympy库还可用于statistics, physics, group theory, matrix/graph theory, number theory等很多学科的学习与研究中。



## Computing_Numerically

+ 包括前向差分，后向差分，中心差分，Euler scheme, leapfrog，Crank-Nicolson scheme等，后面将会继续添加finite element, finite volume, ENO/WENO, spectral method等；
+ 符号/odeint/手写数值算法的误差比较，ODE/PDE(包括heat, wave, convection, Burgers等)的数值求解（ICs/BCs）。