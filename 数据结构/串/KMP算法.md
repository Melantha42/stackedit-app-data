


# KMP算法
例：模式串——t=abcaabbabcab
求next、nextval数组
主串长度：m、模式串长度n
未优化前的KPM算法次数（朴素模式）：m-n+1
next 数组（从0开始）：
t      ——     a b c a a b b a b c a b
     ( t )单位——1 2 3  4 5 6 7 8 9 10 11 12
( next )i—— 0 1 1 1 2 2 3 1 2 3 4 5、（前面对几个就写几个-1）
（nextval）0 1 1 0 2 1 3 0 1 1 0 5
--关于nextval数组
- 该单位前缀与该单位前缀一致&&该单位与其净元素一致，模式串下标为净元素next数组下标
- 该单位净元素与净元素一致&&该单位与净元素不一致，模式串下标为该元素next数组下标
- 该单位前缀与其净元素不一致，模式串下标为该元素Next数组下标
  

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3NjQ1NTU3MDAsLTExMDkyNzE5ODMsLT
IwNzkyMDk4MDYsMTcyMzAwMjg5NywyMDk4NjY3MjE1LC0zMzU0
NDk2MTAsLTE2ODc5MjYzNzhdfQ==
-->