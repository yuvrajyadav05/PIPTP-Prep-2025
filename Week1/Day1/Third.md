 What will be the output of the following pseudocode for a = 8, b = 8?

1. Integer funn(Integer a, Integer b)
2.     if (a && b && a + b > 0)
3.         return a + funn(a - 2, b - 2) + b
4.     End if
5.     return a ^ b
6. End function funn()

Dry run


funn(8, 8)
= 8 + funn(6, 6) + 8
= 8 + (6 + funn(4, 4) + 6) + 8
= 8 + 6 + (4 + funn(2, 2) + 4) + 6 + 8
= 8 + 6 + 4 + (2 + funn(0, 0) + 2) + 4 + 6 + 8
= 8 + 6 + 4 + 2 + (0 ^ 0) + 2 + 4 + 6 + 8
= 8 + 6 + 4 + 2 + 0 + 2 + 4 + 6 + 8
= 40

