# 第一部分 程序结构和执行
## 第2章 信息的表示和处理
二值信号能够很容易地被表示、存储和传输。

三种重要表示：
- 无符号编码：基于传统的二进制表示法，表示大于或等于零的数字。
- 补码编码：表示有符号整数的最常见的方式。
- 浮点数编码：表示实数的科学计数法的以2为基数的版本。

计算机的表示法是用有限数量的位来对一个数字编码，因此，当结果太大以至不能表示时，某些运算就会溢出(overflow)。

由于表示的精度有限，浮点运算是不可结合的。

整数运算和浮点运算处理数字表示有限性的方式不同：整数的表示虽然只能编码一个相对较小的数值范围，但是这种表示是精确度；
而浮点数虽然可以编码一个较大的数值范围，但是这种表示只是近似的。

编译器会试图优化算术表达式求值的性能。

### 2.1 信息存储
大多数计算机使用8位的块，或者字节(byte)，作为最小的可寻址的内存单位，而不是访问内存中单独的位。

机器级程序将内存视为一个非常大的字节数组，称为虚拟内存(virtual memory)。

内存的每个字节都由一个唯一的数字来标识，称为它的地址(address)，所有可能地址的集合就称为虚拟地址空间(virtual address space)。

在C语言中，以0x或0X开头的数字常量被认为是十六进制的值。
