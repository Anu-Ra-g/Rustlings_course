# Rustlings_course

This repository contains the solutions for the [Rustlings course](https://rustlings.cool/) which I solved but the solutions will the ones that comes with the package.

`25/12/2024`

- completed exercises 0 and 1
- variables are to be initialized with let, 
  annotation is optional because of inference, immutable by default
- Shadowing, `consts` are to be annotated

`26/12/2024`

- completed exercises 2, 3 and 4
- functions have implicit returns and must be annotated
- `let number = if condition { 5 } else { 6 };` this is a thing
- slices are backed by arrays and are referenced by pointers
- array indexing is this `arr[index]` and slices index are `arr.index`

`27/12/2024`

- learned about **vector** today - re-sizable arrays
- supports the *push*, *pop*, *indexing* i.e. vecsam[2]
- Weird thing - vector are resizable but have to be declared mutable otherwise error. Why?
- So there's `references`, `mutable references`, `ownership` and not `pass by value` and `pass by reference`