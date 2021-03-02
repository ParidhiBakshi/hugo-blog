---
title: Just in Time Compilation
date: 2021-03-02T10:59:05.710Z
description: Just-in-time compilation is a method for improving the performance
  of interpreted programs. During execution the program may be compiled into
  native code to improve its performance. It is also known as dynamic
  compilation.
tags:
  - JIT
categories:
  - JavaScript
---
<!--StartFragment-->

Dynamic compilation has some advantages over static compilation. When running Java or C# applications, the runtime environment can profile the application while it is being run. This allows for more optimized code to be generated. If the behavior of the application changes while it is running, the runtime environment can recompile the code.

Some of the disadvantages include startup delays and the overhead of compilation during runtime. To limit the overhead, many JIT compilers only compile the code paths that are frequently used.

<!--EndFragment-->