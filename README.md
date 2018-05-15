# Awesome WebAssembly Languages ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
WebAssembly, or wasm for short, is a low-level bytecode format that runs in the browser just like JavaScript.
It is designed to be faster to parse than JavaScript, as well as faster to execute which makes it a suitable compilation target for new and existing languages.

This repo contains a list of languages that currently compile to or have their VMs in WebAssembly(wasm)  :octocat:

## Contents
- [.Net](#dotnet) :hatching_chick:
- [AssemblyScript](#assemblyscript) :hatching_chick:
- [Astro](#astro) :egg:
- [Brainfuck](#brainfuck) :hatched_chick:
- [C](#c) :hatched_chick:
- [C#](#csharp) :hatching_chick:
- [C++](#cpp) :hatched_chick:
- [Elixir](#elixir) :egg:
- [Faust](#faust) :egg:
- [Forest](#forest) :egg:
- [Forth](#forth) :hatched_chick:
- [Haskell](#haskell) :egg:
- [Java](#java) :hatching_chick:
- [Kotlin/Native](#kotlin) :hatching_chick:
- [Kou](#kou) :egg:
- [Lua](#lua) :hatched_chick:
- [Ocaml](#ocaml) :egg:
- [Plorth](#plorth) :egg:
- [Rust](#rust) :hatched_chick:
- [Speedy.js](#speedyjs) :hatching_chick:
- [Turboscript](#turboscript) :hatching_chick:
- [Wah](#wah) :hatched_chick:
- [Walt](#walt) :hatching_chick:
- [Wracket](#wracket) :egg:
- [Xlang](#xlang) :egg:

--------------------

### <a name="dotnet"></a>.Net <sup>[top⇈](#contents)</sup>
> .NET Framework is a software framework developed by Microsoft that runs primarily on Microsoft Windows. It includes a large class library named Framework Class Library (FCL) and provides language interoperability (each language can use code written in other languages) across several programming languages.
* [Blazor](https://github.com/aspnet/blazor) - an experimental web UI framework using C#/Razor and HTML, running client-side via WebAssembly

--------------------

### <a name="assemblyscript"></a>AssemblyScript <sup>[top⇈](#contents)</sup>
> AssemblyScript is a new compiler targeting WebAssembly while utilizing TypeScript's syntax and node's vibrant ecosystem. Instead of requiring complex toolchains to set up, you can simply npm install it - or run it in a browser.
* [AssemblyScript](https://github.com/AssemblyScript/assemblyscript) - main repository

--------------------

### <a name="astro"></a>Astro <sup>[top⇈](#contents)</sup>
> Astro is a high-performance statically-typed programming language for the web (it compiles to WebAssembly), with Python-like syntax and technical-computing orientation similar to Julia.
> It aims to be the first production-ready language to come out of Africa.
* [Astro](https://github.com/AppCypher/Astro) - main repository

--------------------

### <a name="brainfuck"></a>Brainfuck <sup>[top⇈](#contents)</sup>
> Brainfuck is an esoteric programming language created in 1993 by Urban Müller, and notable for its extreme minimalism.
> The language consists of only eight simple commands and an instruction pointer. While it is fully Turing-complete, it is not intended for practical use, but to challenge and amuse programmers.
* [BrainfuckWebassembly](https://github.com/serprex/brainwebfuckassembly) - a simple Brainfuck-to-wasm compiler in one function
* [Brainfuck2Wasm](https://github.com/verdie-g/brainfuck2wasm) - a Brainfuck-to-wasm compiler and playground
* [BrainfuckRsWasm](https://github.com/shritesh/brainfuck-rs-wasm) - a Brainfuck interpreter written in Rust and compiled to WebAssembly

--------------------

### <a name="c"></a>C <sup>[top⇈](#contents)</sup>
> C is a general-purpose, imperative computer programming language, supporting structured programming, lexical variable scope and recursion, while a static type system prevents many unintended operations.
> C was originally developed by Dennis Ritchie between 1969 and 1973 at Bell Labs,[6] and used to re-implement the Unix operating system.
* [Emscripten](https://github.com/kripken/emscripten) - an LLVM-to-JavaScript/Webassembly compiler. It takes LLVM bitcode - which can be generated from C/C++, using llvm-gcc (DragonEgg) or clang, or any other language that can be converted into LLVM - and compiles that into JavaScript or wasm.
* [Cheerp](https://github.com/leaningtech/cheerp-meta) - an open-source, commercial C/C++ compiler for Web applications. It can compile virtually any C/C++ code (up to C++14) to WebAssembly, JavaScript, asm.js or a combination thereof.

--------------------

### <a name="csharp"></a>C# <sup>[top⇈](#contents)</sup>
> C# is a multi-paradigm programming language encompassing strong typing, imperative, declarative, functional, generic, object-oriented (class-based), and component-oriented programming disciplines.
> Its development team is led by Anders Hejlsberg
* See [.Net](#dotnet)

--------------------

### <a name="cpp"></a>C++ <sup>[top⇈](#contents)</sup>
> C++ is a general-purpose programming language. It has imperative, object-oriented and generic programming features, while also providing facilities for low-level memory manipulation.
> It was designed with a bias toward system programming and embedded, resource-constrained and large systems, with performance, efficiency and flexibility of use as its design highlights.
> The developement of the language was sterated in 1979 by Bjarne Stroustrup as a "C with Classes".
* See [C](#c)

--------------------

### <a name="elixir"></a>Elixir <sup>[top⇈](#contents)</sup>
> Elixir is a dynamic, functional language designed for building scalable and maintainable applications.
> Elixir builds on top of Erlang and shares the same abstractions for building distributed, fault-tolerant applications.
* [ElixirWasm](https://github.com/jamen/elixir-wasm) - an elixir compiler for wasm

--------------------

### <a name="faust"></a>Faust <sup>[top⇈](#contents)</sup>
> Faust (Functional Audio Stream) is a functional programming language specifically designed for real-time signal processing and synthesis. A distinctive characteristic of Faust is to be fully compiled.
* [Faust](https://github.com/grame-cncm/faust) - main repository

--------------------

### <a name="forest"></a>Forest <sup>[top⇈](#contents)</sup>
> Forest is a functional programming language that compiles to WebAssembly. The main repo contains the compiler and core syntaxes, currently implemented in Haskell.
* [ForestLang](https://github.com/forest-lang/core) - main repository

--------------------

### <a name="forth"></a>Forth <sup>[top⇈](#contents)</sup>
> Forth is an interactive, extensible, imperative, untyped, stack-based programming language.
* [WASM Forth](https://github.com/stefano/wasm-forth) - Forth implementation for wasm

--------------------

### <a name="haskell"></a>Haskell <sup>[top⇈](#contents)</sup>
> Haskell is a standardized, general-purpose purely functional programming language, with non-strict semantics and strong static typing. It is named after logician Haskell Curry.[1] The latest standard of Haskell is Haskell 2010. As of May 2016, a group is working on the next version, Haskell 2020.
* [DHC](https://github.com/dfinity/dhc) - a Haskell compiler that accepts only a tiny subset of the language and produces WebAssembly binaries
* [HaskellWasm](https://github.com/haskell-wasm/wasm) - a Haskell compiler infrastructure for generating WebAssembly

--------------------

### <a name="java"></a>Java <sup>[top⇈](#contents)</sup>
> Java is a general-purpose computer programming language that is concurrent, class-based, object-oriented, and specifically designed to have as few implementation dependencies as possible. It is intended to let application developers "write once, run anywhere" (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.
> Java was originally developed by James Gosling at Sun Microsystems and released in 1995 as a core component of Sun Microsystems' Java platform. The language derives much of its syntax from C and C++, but it has fewer low-level facilities than either of them.
* [TeaVM](https://github.com/konsoletyper/teavm) - an ahead-of-time translating compiler (transpiler) of Java bytecode, that's capable of emitting JavaScript and WebAssembly
* [JWebAssembly](https://github.com/i-net-software/JWebAssembly) - A Java bytecode to WebAssembly compiler. It can generate the WebAssembly binary or text format. It is written in Java itself and can be integrated with other Java build tools.

--------------------

### <a name="kotlin"></a>Kotlin <sup>[top⇈](#contents)</sup>
> Kotlin is a statically-typed programming language that runs on the Java virtual machine and also can be compiled to JavaScript source code or use the LLVM compiler infrastructure. Its primary development is from a team of JetBrains programmers based in Saint Petersburg, Russia. While the syntax is not compatible with Java, Kotlin is designed to interoperate with Java code and is reliant on Java code from the existing Java Class Library, such as the collections framework.
* [Kotlin/Native](https://github.com/JetBrains/kotlin-native/) - main repository

--------------------

### <a name="kou"></a>Kou <sup>[top⇈](#contents)</sup>
> A minimal language compiled into wasm bytecode
* [Kou](https://github.com/utatti/kou) - main repository

--------------------

### <a name="lua"></a>Lua <sup>[top⇈](#contents)</sup>
> Lua is a lightweight, multi-paradigm programming language designed primarily for embedded systems and clients.[2] Lua is cross-platform, since the interpreter is written in ANSI C, and has a relatively simple C API.
> Lua was originally designed in 1993 as a language for extending software applications to meet the increasing demand for customization at the time.
* [WasmLua](https://github.com/vvanders/wasm_lua) - a Lua VM running in the browser
* [Luwa](https://github.com/serprex/luwa) - a wasm-to-Lua JIT compiler

--------------------

### <a name="ocaml"></a>Ocaml <sup>[top⇈](#contents)</sup>
> OCaml, originally named Objective Caml, is the main implementation of the programming language Caml, created by Xavier Leroy, Jérôme Vouillon, Damien Doligez, Didier Rémy, Ascánder Suárez and others in 1996. A member of the ML language family, OCaml extends the core Caml language with object-oriented programming constructs.
* [Ocaml](https://github.com/SanderSpies/ocaml/tree/wasm/wasmcomp) - a fork of main repo contianing work on OCaml to wasm compilation
* [OcamlRun](https://github.com/sebmarkbage/ocamlrun-wasm) - a build script for compiling OCaml bytecode interpreter to wasm using emscripten

--------------------

### <a name="plorth"></a>Plorth <sup>[top⇈](#contents)</sup>
> Plorth is stack based, concatenative, strongly typed functional scripting language which is easy to embed to applications written in C++. It's inspired by Forth and Factor programming languages.
* [Plorth](https://github.com/RauliL/plorth-webassembly) - main repository

--------------------

### <a name="rust"></a>Rust <sup>[top⇈](#contents)</sup>
> Rust is a systems programming language sponsored by Mozilla Research, which describes it as a "safe, concurrent, practical language,"supporting functional and imperative-procedural paradigms. Rust is syntactically similar to C++, but its designers intend it to provide better memory safety while maintaining performance.
* [Rust `wasm32-unknown-unknown` target](https://www.hellorust.com/setup/wasm-target/) - Rust compiler backend for WebAssembly (without the need for Emscripten)
* [Wargo](https://github.com/lord/wargo) - a simple npm package that makes compiling Rust to WebAssembly easy on macOS or Linux.
* [RustWasmLoader](https://github.com/ianjsikes/rust-wasm-loader) - A simple Webpack loader that shells out to cargo to build a Rust project targeting WebAssembly.
* [CargoWeb](https://github.com/koute/cargo-web) - This cargo subcommand aims to make it easy and convenient to build, develop and deploy client-side Web applications written in Rust.

--------------------

### <a name="speedyjs"></a>Speedy.js <sup>[top⇈](#contents)</sup>
> Speedy.js is a compiler for a well considered, performance pitfalls free subset of JavaScript targeting WebAssembly. Because WebAssembly is statically-typed, the project uses TypeScript as type-checker and to resolve the types of the program symbols.
* [Speedy.js](https://github.com/MichaReiser/speedy.js) - main repository

--------------------

### <a name="turboscript"></a>TurboScript <sup>[top⇈](#contents)</sup>
> TurboScript is an experimental programming language for parallel programming for web which compiles to JavaScript (asm.js) and WebAssembly (targeting post-MVP). The syntax is similar to TypeScript and the compiler is open source and written in TypeScript. TurboScript has zero dependencies.
* [TurboScript](https://github.com/01alchemist/TurboScript) - main repository

--------------------

### <a name="wah"></a>Wah <sup>[top⇈](#contents)</sup>
> Wah is a slightly higher level language that is a superset of WebAssembly. It aims to make WebAssembly's text format slightly more friendly to humans, without introducing new syntax or datatypes.
* [Wah](https://github.com/tmcw/wah) - main repository

--------------------

### <a name="walt"></a>WAlt <sup>[top⇈](#contents)</sup>
> WAlt is an alternative syntax for WebAssembly text format. It's an experiment for using JavaScript syntax to write to as 'close to the metal' as possible. It's JavaScript with rules. .walt files compile directly to WebAssembly binary format.
* [Walt](https://github.com/ballercat/walt) - main repository

--------------------

### <a name="wracket"></a>Wracket <sup>[top⇈](#contents)</sup>
> A lisp-like language that compiles to WebAssembly, written in racket
* [Wracket](https://github.com/sschauss/wracket) - main repository

--------------------

### <a name="xlang"></a>Xlang <sup>[top⇈](#contents)</sup>
> A programming language similar to Go and TypeScript.
* [Xlang](https://github.com/rsms/xlang) - main repository

--------------------

Please read the [contribution guidelines](CONTRIBUTING.md) if you want to contribute.
