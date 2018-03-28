# learn-markdown
学习markdown语法

# 目录
- [目录的写法](#目录的写法)
  - [一级目录](#一级目录)
  - [二级目录](#二级目录)
- [区块的引用](#区块的引用)
  - [引用多层嵌套](#引用多层嵌套)
  - [引用其他要素](#引用其他要素)
- [列表](#列表)
  - [有序列表](#有序列表)
  - [无序列表](#无序列表)
  - [包含引用的列表](#包含引用的列表)
  
## 目录的写法
### 一级目录
语法：
```
- [章节1](#章节1)
- [章节2](#章节2)
```
效果：
- [章节1](#章节1)
- [章节2](#章节2)

注意:
- 1.这里符号‘-’后面打空格
- 2.小括号里面的章节名要和后面的标题对应，这样才能显示蓝色字体并且能够锚点跳转
- 3.目录里面不能有大写字母和除-以外的符号

### 二级目录
语法：
```
- [一级](#一级)
  - [二级](#二级)
```
效果：
- [一级](#一级)
  - [二级](#二级)
  
注意：
- 加一级前面空2格
- 目录后面加内容要空一行


## 区块的引用
区块的引用只要在文本前加上 > 号就可以了
语法
```
>我是引用块1

>我是引用块2
>
> 引用块2换行
```
>我是引用块1

>我是引用块2
>
> 引用块2换行

注意：
- 结束引用块只要空一行就行了
- 在本块内主动换行就得再空一行并且在行首加 >

## 引用多层嵌套
区块可以嵌套，只要给不同层次加上不同数量的 >
语法：
```
>第一层
>> 第二层
>>> 第三层
```
效果：
>第一层
>> 第二层
>>> 第三层


## 引用其他要素
引用的区块内也可以使用其他的 Markdown 语法，包括标题、列表、代码区块等
语法：
```
> 普通块
> - 序列
> - 代码块
> ```markdown
>  console.log()
>```
```
效果：
> 普通块
> - 序列
> - 代码块
> ```markdown
>  console.log()
>```

注意：
- 用这种方式就得在每一行前加 >


## 列表
## 无序列表
用* - + 号表示无序列表
语法:
```
- 无序列表1
- 无序列表2
+ 无序列表3
+ 无序列表4
* 无序列表5
* 无序列表6
```
效果：
- 无序列表1
- 无序列表2
+ 无序列表3
+ 无序列表4
* 无序列表5
* 无序列表6

注意：
- 符号后面跟一个空格 

## 有序列表
英文数字 + . + 空格
语法：
```
1. 有序列表1
2. 有序列表2
```
效果：
1. 有序列表1
2. 有序列表2

## 包含引用的列表
语法：
```
* 菩提偈:
  > 菩提本无树，明镜亦非台。
  > 本来无一物，何处惹尘埃！
```
效果：
* 菩提偈:
  > 菩提本无树，明镜亦非台。
  > 本来无一物，何处惹尘埃！
  
注意：
- 这里引用文要紧缩两个


