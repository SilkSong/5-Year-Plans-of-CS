# 2025.3

## 2025.3.24

#### IDEA 操作

* IDEA 快捷键
    * ⌘ + D 复制当前行到下一行
    * Option + Enter: 自动补全提示
    * `hello.name.sout`: 快速打代码
    * `Shft + ⌘ + E`: recent location
    
#### Java 基础

* a++ 与 ++a的区别: `b = a++; c = ++a`: a++ 就是先返回a, 再++, ++a 就是先++, 再返回a
* 2*8 怎么算最快? 2*2*2*2, 2*8 需要调用乘法指令，在硬件层面可能涉及多步计算, 移位运算本质上是调整电路高低电平, 2 << 3, 箭头的方向就是向哪边移动
* 如果不自行初始化, 输出默认值，布尔值默认是 false, 除了基本类型, 默认值是 null
* final 修饰常量, 表示赋值后不可更改


## 2025.3.26

#### 后端开发

* MyBatisPlus 的链式调用: 
    * last() 是 LambdaQueryWrapper 方法，它的作用是直接在 SQL 语句的末尾追加原生 SQL 语法，不进行任何 SQL 关键字的检查或拼接优化, Oracle 查询最新的一条数据: `last("FETCH FIRST 1 ROWS ONLY")`
* 


