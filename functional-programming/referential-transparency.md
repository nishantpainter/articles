# Referential Transparency

It is an ability of a function such that its invocation can be replaced with actual result without changing the overall behaviour of the sytem.

For example, the add invocation can be replaced directly with the result without affecting anything else in the system

```
function add(a, b) {
  return a + b;
}

const x = add(2, 2); // 4

const x = 4; // 4

```

Even if we replace the function call with the actual result the program will still behave the same.

The function has to be pure and without side effect for being referentially transparent.
