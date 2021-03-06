#### 抽象语法树（AST）

用树状的方式表示编程语言的语法结构。抽象语法树中的每一个节点都表示源代码中的一个元素，每一颗子树都表示一个语法元素。

#### 静态单赋值（Static Single Assignment, SSA）
如果一个中间代码具有静态单赋值的特性，那么每个变量就只会被赋值一次。

#### 指令集
不同的处理器使用了不同的架构和机器语言，所以很多编程语言为了在不同的机器上运行需要将源代码根据架构翻译成不同的机器代码。

复杂指令集计算机（CISC）和精简指令集计算机（RISC）是目前的两种 CPU 区别
```text
· 复杂指令集通过增加指令的数量减少需要执行的指令数；
· 精简指令集能使用更少的指令完成目标的计算任务；
```
#### 编译原理
```text
Go 的编译器在逻辑上可以被分成四个阶段：
词法与语法分析、类型检查和 AST 转换、通用 SSA 生成和最后的机器代码生成
```