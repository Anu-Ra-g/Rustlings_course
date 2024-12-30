# Rustlings_course

This repository contains the solutions for the [Rustlings course](https://rustlings.cool/) which I solved but the solutions will the ones that comes with the package. I'll be updating this README.md as I go through the lessons while solving the exercises.

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
- supports the *push*, *pop*, *indexing* i.e. `vecsam[2]`
- Weird thing - vector are resizable but have to be declared mutable otherwise error. Why?
- So there's `references`, `mutable references`, `ownership` and not `pass by value` and `pass by reference`

`28/12/2024`

- Rust has 3 types of struct: `tuple structs`, `c-style structs` and `unit structs`. 
- Initialization is basic as golang and c
- Structs in Rust are very similar to that in Golang as it includes method implementation.
- These structs methods have **class** kind of implementation.
- Enums are same and can have many types and 
- Rust has `match` instead of `switch` like Python.

`29/12/2024`

- There are two types of string in Rust: **string slice** and **owned String**
- Owned String is created in heap and string slice is created in the stack
- modules system in Rust is new and they're declared inside source files, creating logical separation.

`30/12/2024`

- Hashmaps or *unordered map* is same as most of the other programming language.
- Option is a type to work around optional entities like arguments, elements etc.