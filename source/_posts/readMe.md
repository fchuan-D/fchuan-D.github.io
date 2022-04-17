# 目录

[TOC]



## 汇编中常见的寄存器

- %rax 一般用作累加器(Accumulator)
- %rbx 一般用作基址寄存器( Base )
- %rxc 一般用来计数( Count )
- %rdx 一般用来存放数据( Data )
- %rsi一般用作源变址( Source Index )
- %rdi 一般用作目标变址( DestinatinIndex )
- %rbp 一般用作基址指针( Base Pointer )
- %rsp 一般用作堆栈指针( Stack Pointer )
- %rip 是指令指针，也称为 PC
- CF、ZF、SF 和 OF 条件码

```
// ji'ben
0x8(%rdx) = 0xf000 + 0x8 = 0xf008
(%rdx, %rcx) = 0xf000 + 0x100 = 0xf100
(%rdx, %rcx, 4) = 0xf000 + 4*0x100 = 0xf400
0x80(, %rdx, 2) = 2*0xf000 + 0x80 = 0x1e080
```

## 汇编常见指令

- jmp无条件跳转
- jle条件转移指令：比如 `cmp a ,b` ，后面再接JLE，如果a<=b的话，就跳转到别的命令上
- lea加载有效地址（load effective address）指令就是lea,他的指令形式就是从内存读取数据到寄存器
