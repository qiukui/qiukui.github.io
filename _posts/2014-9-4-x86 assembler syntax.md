---
layout: post
title: x86汇编语法：AT&T 和 Intel
category: "汇编"
tag: "汇编"
---


>    汇编语言源代码主要采用两种语法：AT&T 和 Intel语法，它们都属于第二代语言，但这二者的语法在变量、常量、寄存器访问、段和指令大小写重写、间接寻址和偏移量等方面都存在巨大的差异。   

1. AT&T汇编语法以%作为所有寄存器名称的前缀，以$作为文字常量（立即数）的前缀，它这样对操作数排序：源操作数委员左边，目的操作数位于右边，使用AT&T语法，EAX寄存器加4的指令为：add $0x4,%eax，GNU汇编器和许多其他GNU工具(如gcc和gdb)都使用AT&T语法。
2. Intel语法与AT&T语法不通，它不需要寄存器和文字前缀，它的操作数排序方式与Intel语法操作数排序恰恰相反：源操作数位于右边，目的操作数位于左边，使用Intel语法，上述加法的指令为：add eax,0x4.使用Intel语法的汇编器包括微软汇编器(MASM)、Borland的Turbo汇编器(TASM)和Netwide汇编器(NASM)。