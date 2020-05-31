# Complex-Calculator
This Calculator Application  Performs All the Complex Mathematical Calculations.

Examples are as shown Below:

// define and use variables
>> var = 42
42
>> 2*var + 2var
168

// complex number arithmetic
>> 5i*(3-i) + (1+i) + i^3
6+15i 
>> 5*e^(90deg)i + 3*e^(45deg)i - 1*e^(135deg)i
2.82843+6.41421i
>> exp
7.01015*e^(66.2043deg)i

// define functions with multiple variables
>> fn f(a,b,c) = a*b + c
>> f(2,4,3)
11

// define lists and do basic calculations on them
>> x = [1, 1.5, 2, 2.5, 3, 3.5, 4, 4.5, 5]
>> x
[1, 1.5, 2, 2.5, 3, 3.5, 4, 4.5, 5]
>> x = [for i=1, 5:0.5 i]
>> x
[1, 1.5, 2, 2.5, 3, 3.5, 4, 4.5, 5]
>> len(x); avg(x); sum(x)
9
3
27
>> sx(x); ux(x)
1.36931
0,456435


FEATURES

Variables
Functions (multiple parameters possible)
Complex Number arithmetic
Minimal list support


BUILT IN CONSTARINTS

pi, e, i, deg (will convert to rad, so you can write sin(90deg))

BUILT IN FUNCTIONS

Trigonometric: sin, cos, tan, asin, acos, atan, sinh, cosh, tanh, asinh, acosh, atanh

Temperature Conversion: CtoF, CtoK, FtoC, FtoK, KtoC, KtoF

Lists: avg, len, sum, sum2 (squared sum), sx (standard deviation), ux (standard uncertainty)

Complex: Re, Im, arg, abs, norm

Misc.: ln, log, sqr, sqrt, cbrt, round, ceil, floor, trunc
