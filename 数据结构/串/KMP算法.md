


# KMP算法
例：模式串——t=abcaabbabcab
求next、nextval数组
主串长度：m、模式串长度n
未优化前的KPM算法次数（朴素模式）：m-n+1
next 数组（从0开始）：
t      ——     a b c a a b b a b c a b
     ( t )单位——1 2 3  4 5 6 7 8 9 10 11 12
( next )i—— 0 1 1 1 2 2 3 1 2 3 4 5、（前面对几个就写几个-1）
（nextval）0 1 1 0 2 1 3 0 1 1 0 5（一样的写最初的，不一样的nextval的）
  

<!--stackedit_data:
eyJoaXN0b3J5IjpbNjA4MjIyMzAyLC0xMTA5MjcxOTgzLC0yMD
c5MjA5ODA2LDE3MjMwMDI4OTcsMjA5ODY2NzIxNSwtMzM1NDQ5
NjEwLC0xNjg3OTI2Mzc4XX0=
-->