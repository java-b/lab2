# lab3
##目标：学习常见的循环方式，然后完成给定题目。

##`for`循环

>```
for(int i = 0;i < 10;i++){
   System.out.println(i);
}
```
>这是最常见的循环方式，首先定义循环变量（可在外部定义）:`int i = 0`,然后设置循环条件:`i < 10`,设置循环结束后所执行的语句`i++`,
>最后编写循环语句。

>`for`循环也有第二个用法.

>```
int[] arr = {1,3,5,6,9};
for(int i:arr){
   System.out.println(i);
}
```
>这个循环的作用就是遍历数组arr。

>注意的是，`for`语句中的每一个表达式都可以不填写.

>```
for(;;)
```

>这里就是一个死循环.

##`while`循环

>```
int num = 0;
while(num<2322){
   num += 4;
   num *= num;
}
```

>这个循环的作用很简单，当不符合循环条件时，就跳出循环。
 
##1.打印三角形

>给定一个数字***n***,打印相应行数的金字塔.

>样例输入 : 3

>样例输出:

>>```
  *
 ***
*****
```

##2.兔子繁殖

>小明家中没有兔子，第一天他带回家一只兔子，之后每天的兔子数量都是前两天的兔子数量之和.

>指定第***n***天，给出直至该天为止的的历史兔子数量.

>样例输入 :  4

>样例输出:

>>```
0,1,1,2,3
```

##3.判断回文数

>所谓回文数就是诸如**838**,  **995599**这样的数字.

>给定一个数字***n***,判断该数字是否为回文数.

>样例输入:9755579

>样例输出：

>>```
true
```



