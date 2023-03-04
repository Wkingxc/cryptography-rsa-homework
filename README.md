 # 2022现代密码学实验报告

这里的exp只写了能够用正规的rsa攻击方法解出的明文（而不是去猜随机数算法）

包括

+ fermat 分解法
+ pollard p-1分解
+ william p+1分解(虽然没有一个满足条件)
+ 模不互素
+ 共模攻击
+ 低指数广播攻击
+ coppersmith partical m

exp在src中，分为两个文件

+ sol1.py实现了前六种攻击方法
+ sol2.sage实现了最后一种攻击方法

