# The Monolith Language
Monolith is very similar to the C programming language, most of the points are taken from Rust (memory management) and Go (interfaces), Monolith does not have OOP in full, but uses interfaces just like in Go. Monolith is broadcasted in C (in the future it will be possible to broadcast it into the native code) which allows you to get a very small file size on the output.

## Futures
* Fast compilation
* Perfomance (within 3-4% of C)
* Safety: no null, no global, no UB (Undefined Behavior)
* Translation from Monolith to C
* Easy cross platform compilation (Linux, Windows, MacOS, BSD)

First version of Monolith plan release for February 2019. Right now Monolith in alpha stage.

## Monolith solves next problems
Monolith is similar to the memory model of Rust. Monolith eliminates the following memory access security issues:
- saving the pointer after freeing memory (use-after-free)
- dereference null pointer
- using of uninitialized memory
- the program attempting to free the same cell twice (double-free)
- buffer overflow

## Compiler
Monolith use Tiny C Compiler (TCC) as backend.<br>
For building Monolith you'll need Clang or GCC or TCC:
* Clang (http://releases.llvm.org/download.html) 
* GCC (https://gcc.gnu.org/install/binaries.html).

## Progress:
You can track progress by project https://github.com/orgs/monolithlang/projects/1<br>

![Kernel](https://cdn.discordapp.com/attachments/274567887623159808/623438386891587584/unknown.png)
![Errors](https://cdn.discordapp.com/attachments/274567887623159808/623448684079742987/unknown.png)
![Token tracing](https://cdn.discordapp.com/attachments/274567887623159808/623449038464876545/unknown.png)

## Contact (Primary community)
Discord  - https://discord.gg/w5W76t6<br>
Telegram - https://t.me/monolithlang (Russian Community)
