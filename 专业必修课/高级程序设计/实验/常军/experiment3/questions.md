# 实验3

## 3-7

完成函数，参数为两个unsigned short int型数，返回值为第一个参数除以第二个参数的结果，数据类型为short int；如果第二个参数为0，则返回值为-1。在主程序中实现输入输出。注意观察函数的参数传入传出、返回值。  

## 3-13

递归的方法编写函数求 Fibonacci级数，公式为
$$ F_n =F_{n-1}  +F_{n-2},(n>2),F_1=F_2=1 $$
观察递归调用的过程。

## 3-15

写递归函数 getPower 计算$x^y$,在同一个程序中针对整型和实型实现两个重载的
函数：

```c++  
int getPower(int x, int y); //整型版本，当y<0时，返回0  
double getPower(double x,int y);  //实型版本  
```

在主程序中实现输入输出，分别输入一个整数a 和一个实数b作为底数，再输入一个
整数m作为指数，输出$a^m$和$b^m$。另外请读者思考，如果在调用getPower 函数计算
$a^m$时希望得到一个实型结果(实型结果表示范围更大，而且可以准确表示m<0时
的结果)，该如何调用?注意观察递归调用的过程。

## 3-10

编写函数求两个整数的最大公约数和最小公倍数。要求两个整数以及结果在主函数中输入输出。

## 3-9

编写函数判别一个整数是否是质数？要求在主函数中输入输出。
