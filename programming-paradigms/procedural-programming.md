# Procedural Programming

<img src='https://miro.medium.com/max/875/0*f26z1WmFpQYk0A0-' height='400' alt='article-image' />

Procedural Programming is an [Imperative](imperative-and-declarative-programming.md) style of [Programming Paradigm](what-are-programming-paradigms.md). It is a style of writing computer programs using procedures. Procedural Programming solves a problem by implementing and making use of various procedures.

## What is a Procedure ?

Procedure is a sequence of computer instructions for performing a specific task. When we need to perform that same task again somewhere else then instead of writing the same instruction set again, we will call the procedure to perform the task. Procedure are also referred to as Routines, Subroutines and Functions. Procedures enable [Modularity](https://en.wikipedia.org/wiki/Modularity_(programming)) in a computer program. Procedure may have input arguments in order to perform given tasks. For example, the procedure to compute and print the square of given integer list can be expressed as follows :

```
procedure print_squares(list_of_integer){
    for each integer in list_of_integer {
        print integer * integer;
    }
}
```

Note : The above construct doesn’t belong to any programming language and it’s used for explanatory purpose only.

## Block and Scope

