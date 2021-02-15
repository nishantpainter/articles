# Structured Programming

<img src='https://miro.medium.com/max/875/0*dZknFE3nDPrO7QzO' height='400' alt='article-image' />

## Bit History

In a computer program, control flow is the order in which set instructions are executed. A control flow statement changes program flow, to achieve specific results, by choosing a path from available paths. These statements can be based on some condition; executing instructions only when some condition is met; or can be unconditional; arbitrarily transferring the flow to some different instruction set. The goto statement was the most basic form of unconditional transfer. It transfers the control to the labelled instructions set.

`GOTO LABEL;`

Goto performs one-way transfer of control which means the control is not expected to return after executing the labelled instructions set. On the contrary, calling a [Function](functional-programming.md) usually returns the control after execution. In earlier programming, goto statements were used extensively. However, with increasing complexity it becomes harder to maintain computer programs because goto resulted in non-linear change of control flow which was harder to understand compared to linear transfer.

[Dijkstra](https://en.wikipedia.org/wiki/Edsger_W._Dijkstra) was one of the first persons to criticise the use of goto, arguing about errors and poor structure imposed by using it. He proposed the use of linear control flow transfer under high discipline, thereby eliminating the use of goto in programming and [Spaghetti Code](https://en.wikipedia.org/wiki/Spaghetti_code) caused by goto. This is considered to be an important movement in the history of computer programming and accepted as the beginning of a new Programming paradigm, Structured Programming. It is a paradigm focusing on improving the clarity, control, quality and maintainability of a computer program by making use of disciplined structures.

## Elements of Structured Programming

Structured programming divides a program into simple elements which in-turn can also contain other such elements. These are the building blocks of a structured program.

### Blocks

It is a style of grouping multiple instructions that looks like a single instruction statement. Block also helps in defining the scope of variables to avoid conflicts with other similarly named variables in the instruction set. They have an enclosing structure usually defined by keywords such as begin...end, if...fi etc. Some language supports the use of curly braces {...} to define a block.

### Subroutines and Functions

It allows breaking the program into small modular sets of instructions that perform specific tasks. These modules are called subroutines or functions. They invoke each other internally in specific order to get expected results. They provide re-usability of logic.

### Control Structures 

It enables the control of program flow to determine the execution of instruction in a certain manner. The three main category of control structure are as follows :

Sequence : Providing a sequence of instructions to allow the computer execute them in the provided order for achieving results.

Selection : Allowing the selection of a flow from the list of available flow. This is usually done based on some condition that is evaluated to decide the next executing flow of a program. Keywords such as if...else expresses selection.
