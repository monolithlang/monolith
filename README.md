# The Monolith Language
Release plan on 2021 or 2022 (plans can change quickly).

Monolith is very similar to the C Programming Language, some princips taked from C and Rust.
I wanna make an ideal and powerful programming language for developing maintainable software. As of right now, I don’t  know any languages suitable for my purposes.

## Futures
- Fast and optimized compilation
- Incredible perfomance
- **Safety**: no null (cannot derefer null pointer), no globals, no UB (Undefined Behavior)
- **Backend**: uses LLVM as backend or native code generation with supporting a lot of most popular architectures.
- **Transpiler**: can be fast transpiled to other languages by progressive AST to C, C++, Go, Python ...
- **Compilation**: simple and easy cross platform compilation for most popular OS and architectures ...
- **Size**: by aggressive optimizing and native code generation can give small sizes at or less than C
- **Syntax**: simple but productive syntax without unnecessary keywords and constructions

At the current moment Monolith written for **25%**.

## Solves next problems
Memory model similar to Rust. Monolith eliminates the following memory access security issues:
- saving the pointer after freeing memory (use-after-free)
- dereference null pointer
- using of uninitialized memory
- the program attempting to free the same cell twice (double-free)
- buffer overflow

## Progress
https://github.com/monolithlang/monolith/projects/1

## Documentation
https://monolithlang.github.io/

## Contact (primary community)
Discord - https://discord.gg/w5W76t6<br>
Telegram - https://t.me/monolithlang (Russian Community)
