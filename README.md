# rcore 2020
OS Tutorial Summer of Code 2020
Day 0~30
* Day 0

下载rustup工具，安装RLS
配置环境
* Day 1 (2020-06-27)

**学习Rust基础知识**

Rust是静态类型语言，任何值都属于一种明确的类型，内建类型分为：标量（scalar） 和 复合（compound）
Rust 有四种基本的标量类型：整型、浮点型、布尔类型、和字符类型
Rust 有两个原生的复合类型：元组（tuple） 和 数组（array）

**控制流**
if表达式和loop、while、for循环

**错误处理**
Rust 将错误组合成两个主要类别：可恢复错误（recoverable）和 不可恢复错误（unrecoverable）

* Day 2 (2020-06-28)

**所有权**
堆和栈、String 类型、Slice 类型、Option 枚举

所有权规则：

1.每一个值都被它的所有者（owner）变量拥有。

2.值在任意时刻只能被一个所有者拥有。

3.当所有者离开作用域，这个值将被丢弃。

Rust中作用域的作用是制造一个边界，这个边界是所有权的边界。
变量走出其所在作用域，所有权会move。
如果不想让所有权 move ，则可以使用 **引用**来“出借”变量，而此时作用域的作用就是保证被**借用**的变量准确归还。

Rust 通过在编译时进行**泛型**代码的 单态化（monomorphization）来保证效率。

* Day 3 (2020-06-29)

使用Rust编写一个LinkList， 要求所有的节点需要分配在堆上，需要实现pop、push方法

使用Rust编写双链双端队列以及对应的方法

* Day 4 (2020-07-04)

写完了小学期java的作业，我回归了
