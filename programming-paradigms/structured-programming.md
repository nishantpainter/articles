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
