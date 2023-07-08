# Awesome WebAssembly Languages ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
WebAssembly, or wasm for short, is a low-level bytecode format that runs in the browser just like JavaScript.
It is designed to be faster to parse than JavaScript, as well as faster to execute which makes it a suitable compilation target for new and existing languages.

This repo contains a list of languages that currently compile to or have their VMs in WebAssembly(wasm)  :octocat:


## Contents

- :hatched_chick: - Stable for production usage.
  - [.Net](#dotnet)
  - [AssemblyScript](#assemblyscript)
  - [Brainfuck](#brainfuck)
  - [C](#c)
  - [C#](#csharp)
  - [C++](#cpp)
  - [Clean](#clean)
  - [Cyber](#cyber)
  - [COBOL](#cobol)
  - [F#](#fsharp)
  - [Forth](#forth)
  - [Go](#go)
  - [Grain](#grain)
  - [Lobster](#lobster)
  - [Lox](#lox)
  - [Lua](#lua)
  - [Nelua](#nelua)
  - [Never](#never)
  - [Rust](#rust)
  - [Rego](#rego)</br>
  - [TypeScript](#typescript)
  - ~[Wah](#wah)~ `Unmaintained`
  - [WebAssembly](#webassembly)
  - [Zig](#zig)</br>
  
- :hatching_chick: - Unstable but usable.
  - [C4wa](#c4wa)
  - [Crystal](#crystal)
  - [D](#d)
  - [Eclair](#eclair)
  - [Eel](#eel)
  - [Elixir](#elixir)
  - ~[Idris](#idris)~ `Unmaintained`
  - [Java](#java)
  - [JavaScript](#javascript)
  - [KCL](#kcl)
  - [Kotlin/Wasm](#kotlin)
  - [Lisp](#lisp)
  - [Lys](#lys)
  - [Pascal](#pascal)
  - [Perl](#perl)
  - [PHP](#php)
  - [Poetry](#poetry)
  - [Python](#python)
  - [Prolog](#prolog)
  - [R](#r)
  - [Ruby](#ruby)</br>
  - [Scheme](#scheme)
  - [Scopes](#scopes)
  - ~[Speedy.js](#speedyjs)~ `Unmaintained`
  - [Swift](#swift)
  - ~[Turboscript](#turboscript)~ `Unmaintained`
  - [V](#v)
  - ~[Walt](#walt)~ `Unmaintained`
  - ~[Wam](#wam)~ `Unmaintained`
  
- :egg: - Work in progress.
  - ~[Astro](#astro)~ `Unmaintained`
  - [Ballerina](#ballerina)
  - [Co](#co)
  - [Dart](#dart)
  - [Faust](#faust)
  - [Forest](#forest)
  - [Haskell](#haskell)
  - [Julia](#julia)
  - [Kou](#kou)
  - [Nim](#nim)
  - [Ocaml](#ocaml)
  - [Plorth](#plorth)
  - [Wa](#wa)
  - [Wase](#wase)
  - ~[Wracket](#wracket)~ `Unmaintained`
  - [xcc](#xcc)</br>

--------------------

### <a name="dotnet"></a>.Net <sup>[top⇈](#contents)</sup>
> .NET Framework is a software framework developed by Microsoft that runs primarily on Microsoft Windows. It includes a large class library named Framework Class Library (FCL) and provides language interoperability (each language can use code written in other languages) across several programming languages.
* [Mono](https://github.com/mono/mono/tree/master/sdks/wasm) - an open source implementation of Microsoft's .NET Framework based on the ECMA standards for C# and the Common Language Runtime. For a real-work example, see this repository which contains the [Windows 10 calculator](https://github.com/nventive/calculator). The application is built using standard C++ 11 and C++/CX, with a calculation engine that dates back from 1995. Made by possible with mono via [Uno Platform](https://platform.uno/a-piece-of-windows-10-is-now-running-on-webassembly-natively-on-ios-and-android/).
* [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor) - a web UI framework using C#/Razor and HTML, running client-side via WebAssembly. Source is maintained on [ASP.Net Core](https://github.com/dotnet/aspnetcore) repo.
* [Bolero](https://fsbolero.io/) - Bolero brings Blazor to F# developers with an easy to use Model-View-Update architecture, HTML combinators, hot reloaded templates, type-safe endpoints, advanced routing and remoting capabilities, and more.
* [NativeAOT-LLVM](https://github.com/dotnet/runtimelab/tree/feature/NativeAOT-LLVM) - an experimental fork of the CoreCLR .NET runtime that compiles .NET applications into single-file executables, with the primary target being WASM

--------------------

### <a name="assemblyscript"></a>AssemblyScript <sup>[top⇈](#contents)</sup>
> AssemblyScript is a new compiler targeting WebAssembly while utilizing TypeScript's syntax and node's vibrant ecosystem. Instead of requiring complex toolchains to set up, you can simply npm install it - or run it in a browser.
* [AssemblyScript](https://github.com/AssemblyScript/assemblyscript) - main repository.

--------------------

### <a name="astro"></a>Astro <sup>[top⇈](#contents)</sup>
> Astro is a fun safe language for rapid prototyping and high performance applications.
* ~[Astro](https://github.com/astrolang/astro) - main repository.~ `Unmaintained`

--------------------

### <a name="ballerina"></a>Ballerina <sup>[top⇈](#contents)</sup>
> Ballerina is an open-source programming language for the cloud that makes it easier to use, combine, and create network services.
> The WebAssembly compiler is implemented for the native Ballerina compiler [nBallerina](https://github.com/ballerina-platform/nballerina).
* [Main repository](https://github.com/ballerina-platform/nballerina/tree/wasm) - Ballerina-to-wasm compiler 

--------------------

### <a name="brainfuck"></a>Brainfuck <sup>[top⇈](#contents)</sup>
> Brainfuck is an esoteric programming language created in 1993 by Urban Müller, and notable for its extreme minimalism.
> The language consists of only eight simple commands and an instruction pointer. While it is fully Turing-complete, it is not intended for practical use, but to challenge and amuse programmers.
* [BrainfuckWebassembly](https://github.com/serprex/brainwebfuckassembly) - a simple Brainfuck-to-wasm compiler in one function.
* [Brainfuck2Wasm](https://github.com/verdie-g/brainfuck2wasm) - a Brainfuck-to-wasm compiler and playground.
* [BrainfuckRsWasm](https://github.com/shritesh/brainfuck-rs-wasm) - a Brainfuck interpreter written in Rust and compiled to WebAssembly.
* [bfwasm](https://github.com/surma/bfwasm) - A non-optimizing Brainf_ck to WebAssembly compiler with WASI support.

--------------------

### <a name="c"></a>C <sup>[top⇈](#contents)</sup>
> C is a general-purpose, imperative computer programming language, supporting structured programming, lexical variable scope and recursion, while a static type system prevents many unintended operations.
> C was originally developed by Dennis Ritchie between 1969 and 1973 at Bell Labs,[6] and used to re-implement the Unix operating system.
* [Emscripten](https://github.com/kripken/emscripten) - an LLVM-to-JavaScript/Webassembly compiler. It takes LLVM bitcode - which can be generated from C/C++, using llvm-gcc (DragonEgg) or clang, or any other language that can be converted into LLVM - and compiles that into JavaScript or wasm.
* [Cheerp](https://github.com/leaningtech/cheerp-meta) - an open-source, commercial C/C++ compiler for Web applications. It can compile virtually any C/C++ code (up to C++14) to WebAssembly, JavaScript, asm.js or a combination thereof.

--------------------

### <a name="csharp"></a>C# <sup>[top⇈](#contents)</sup>
> C# is a multi-paradigm programming language encompassing strong typing, imperative, declarative, functional, generic, object-oriented (class-based), and component-oriented programming disciplines.
> Its development team is led by Anders Hejlsberg.
> WebAssembly support is achieved through [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor).
* See [.Net](#dotnet)

--------------------

### <a name="cpp"></a>C++ <sup>[top⇈](#contents)</sup>
> C++ is a general-purpose programming language. It has imperative, object-oriented and generic programming features, while also providing facilities for low-level memory manipulation.
> It was designed with a bias toward system programming and embedded, resource-constrained and large systems, with performance, efficiency and flexibility of use as its design highlights.
> The development of the language was started in 1979 by Bjarne Stroustrup as a "C with Classes".
* See [C](#c).

--------------------

### <a name="c4wa"></a>c4wa <sup>[top⇈](#contents)</sup>
> C4wa ("C for Web Assembly") is a subset of Standard C specifically targeted for simple and efficient Web Assembly compilation. 
> Generated WASM files include no overhead, out of the box compatible with any Web Assembly runtime, support import of variable-argument
> functions (such as `printf`). There is also an option to create well-formatted and readable WAT files.
* [c4wa](https://github.com/kign/c4wa) - main repository.

--------------------
### <a name="clean"></a>Clean <sup>[top⇈](#contents)</sup>
> Clean is a general purpose, state-of-the-art, pure and lazy functional programming language designed for making real-world applications.
> Some of its most notable language features are uniqueness typing, dynamic typing, and generic functions.
* [ABC interpreter](https://gitlab.com/clean-and-itasks/abc-interpreter) - interpreter for Clean's intermediate language ABC, with a WebAssembly version.
* [iTasks](https://gitlab.com/clean-and-itasks/itasks-sdk) - integration of the above ABC interpreter with browser applications.

--------------------

### <a name="co"></a>Co <sup>[top⇈](#contents)</sup>
> A programming language similar to Go and TypeScript.
* [Co](https://github.com/rsms/co) - main repository

--------------------

### <a name="cobol"></a>COBOL <sup>[top⇈](#contents)</sup>
> COBOL is a compiled English-like programming language designed for business use.
> It is imperative, procedural, and object-oriented. COBOL is primarily used in business, finance, and administrative systems.
* [Cobaul](https://github.com/cloudflare/cobaul) - toolchain used to [support COBOL in CloudFlare workers](https://blog.cloudflare.com/cloudflare-workers-now-support-cobol/)

--------------------

### <a name="crystal"></a>Crystal <sup>[top⇈](#contents)</sup>
> Crystal is a programming language with the following goals:
> 
> - Have a syntax similar to Ruby (but compatibility with it is not a goal)
> - Statically type-checked but without having to specify the type of variables or method arguments.
> - Be able to call C code by writing bindings to it in Crystal.
> - Have compile-time evaluation and generation of code, to avoid boilerplate code.
> - Compile to efficient native code.
    
* [Crystal](https://github.com/crystal-lang/crystal) - main repository
* [POC PR](https://github.com/crystal-lang/crystal/pull/10870) - PR adding initial support for WebAssembly

--------------------

### <a name="cyber"></a>Cyber <sup>[top⇈](#contents)</sup>
> Fast, efficient, and concurrent scripting. Dynamic and gradual types; Concurrency with fibers; Multithreaded; Memory safe; FFI and Embeddable.
* [Cyber](https://github.com/fubark/cyber) - project repository

--------------------

### <a name="d"></a>D <sup>[top⇈](#contents)</sup>
> D is a general-purpose programming language with static typing, systems-level access, and C-like syntax.
* [LDC](https://github.com/ldc-developers/ldc) - LLVM-based D compiler, which can generate WASM since version 1.11.0.

--------------------

### <a name="dart"></a>
<sup>[top⇈](#contents)</sup>
> Dart is a client-optimized language for developing fast apps on any platform. Its goal is to offer the most productive programming language for multi-platform development, paired with a flexible execution runtime platform for app frameworks.
* [sdk](https://github.com/dart-lang/sdk) - The Dart SDK, including the VM, dart2js, core libraries, and more.
* [language](https://github.com/dart-lang/language) - Design of the Dart language

--------------------

### <a name="eclair"></a>Eclair <sup>[top⇈](#contents)</sup>
> Eclair is a minimal, fast Datalog implementation that compiles to LLVM IR and WASM.
* [eclair-lang](https://github.com/luc-tielen/eclair-lang) - The Eclair compiler, which can compile Eclair code to LLVM IR and WASM.

--------------------

### <a name="eel"></a>Eel <sup>[top⇈](#contents)</sup>
> Eel is a small language used for, among other things, writing visualizer "presets" for [Milkdrop](http://www.geisswerks.com/milkdrop/), the music visualization program which came with [Winamp](https://en.wikipedia.org/wiki/Winamp).
* [eel-wasm](https://github.com/captbaritone/eel-wasm) - Compiles Milkdrop flavored Eel to Wasm in the browser. Intended to become a component of [Butterchurn](https://github.com/jberg/butterchurn), a WebGL implementation of the Milkdrop Visualizer.

------------------

### <a name="elixir"></a>Elixir <sup>[top⇈](#contents)</sup>
> Elixir is a dynamic, functional language designed for building scalable and maintainable applications.
> Elixir builds on top of Erlang and shares the same abstractions for building distributed, fault-tolerant applications.
* [Lumen](https://github.com/lumen/lumen) - An alternative BEAM implementation (with AOT compiler) designed for WebAssembly.
* ~[ElixirWasm](https://github.com/jamen/elixir-wasm) - an elixir compiler for wasm. [Unmaintained]~

--------------------

### <a name="fsharp"></a>F# <sup>[top⇈](#contents)</sup>
> F# is a mature, open source, cross-platform, functional-first programming language. It empowers users and organizations to tackle complex computing problems with simple, maintainable and robust code.
> WebAssembly support is achieved through [Bolero](https://fsbolero.io/), a set of free and open-source libraries and tools built on top of [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor).
> F# was mainly conceived by Don Syme of Microsoft Research but it's now maintained by the [F# Foundation](http://foundation.fsharp.org/) and its community.
* See [.Net](#dotnet)

--------------------

### <a name="faust"></a>Faust <sup>[top⇈](#contents)</sup>
> Faust (Functional Audio Stream) is a functional programming language specifically designed for real-time signal processing and synthesis. A distinctive characteristic of Faust is to be fully compiled.
* [Faust](https://github.com/grame-cncm/faust) - main repository.

--------------------

### <a name="forest"></a>Forest <sup>[top⇈](#contents)</sup>
> Forest is a functional programming language that compiles to WebAssembly. The main repo contains the compiler and core syntaxes, currently implemented in Haskell.
* [ForestLang](https://github.com/forest-lang/core) - main repository.

--------------------

### <a name="forth"></a>Forth <sup>[top⇈](#contents)</sup>
> Forth is an interactive, extensible, imperative, untyped, stack-based programming language.
* [WASM Forth](https://github.com/stefano/wasm-forth) - Forth implementation for wasm.
* [WAForth](https://github.com/remko/waforth) - Bootstrapping Dynamic Forth Interpreter/Compiler for & in WebAssembly.

--------------------

### <a name="go"></a>Go <sup>[top⇈](#contents)</sup>
> Go is a statically typed compiled language in the tradition of C, with memory safety, garbage collection, structural typing, and CSP-style concurrent programming features added.
* [Go](https://github.com/golang/go) - main repository.
* [TinyGo](https://github.com/aykevl/tinygo) - a subset of Go targeted to embedded devices and WebAssembly.

--------------------
### <a name="grain"></a>Grain <sup>[top⇈](#contents)</sup>
> Grain is a strongly-typed functional programming language built for the modern web.
* [Grain](https://github.com/grain-lang/grain) - main repository.
* [GrainWeb](https://grain-lang.org/) - Web page.

--------------------

### <a name="haskell"></a>Haskell <sup>[top⇈](#contents)</sup>
> Haskell is a standardized, general-purpose purely functional programming language, with non-strict semantics and strong static typing. It is named after logician Haskell Curry.[1] The latest standard of Haskell is Haskell 2010. As of May 2016, a group is working on the next version, Haskell 2020.
* [Asterius](https://github.com/tweag/asterius) - a Haskell to WebAssembly compiler
* [DHC](https://github.com/dfinity/dhc) - a Haskell compiler that accepts only a tiny subset of the language and produces WebAssembly binaries.
* ~[HaskellWasm](https://github.com/haskell-wasm/wasm) - a Haskell compiler infrastructure for generating WebAssembly. [Unmaintained]~
* [haskell-wasm](https://github.com/SPY/haskell-wasm) - Haskell WebAssembly Toolkit. It includes Language helpers and a fully spec-compatible WASM interpreter.
* [wasm-cross](https://github.com/WebGHC/wasm-cross) - A toolchain for cross compiling C and Haskell to WebAssembly, using the WebGHC and LLVM.

--------------------

### <a name="idris"></a>Idris <sup>[top⇈](#contents)</sup>
> Idris is a general purpose pure functional programming language with dependent types. Dependent types allow types to be predicated on values, meaning that some aspects of a program’s behaviour can be specified precisely in the type. It is compiled, with eager evaluation. Its features are influenced by Haskell and ML.
* ~[Idris-codegen-WASM](https://github.com/SPY/idris-codegen-wasm) - WASM codegen repository.~ `Unmaintained`

--------------------

### <a name="java"></a>Java <sup>[top⇈](#contents)</sup>
> Java is a general-purpose computer programming language that is concurrent, class-based, object-oriented, and specifically designed to have as few implementation dependencies as possible. It is intended to let application developers "write once, run anywhere" (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.
> Java was originally developed by James Gosling at Sun Microsystems and released in 1995 as a core component of Sun Microsystems' Java platform. The language derives much of its syntax from C and C++, but it has fewer low-level facilities than either of them.
* [TeaVM](https://github.com/konsoletyper/teavm) - an ahead-of-time translating compiler (transpiler) of Java bytecode, that's capable of emitting JavaScript and WebAssembly.
* [JWebAssembly](https://github.com/i-net-software/JWebAssembly) - A Java bytecode to WebAssembly compiler. It can generate the WebAssembly binary or text format. It is written in Java itself and can be integrated with other Java build tools.
* [Bytecoder](https://github.com/mirkosertic/Bytecoder) - A Rich Domain Model for Java Bytecode and Framework to interpret and transpile it to other languages such as JavaScript, OpenCL or WebAssembly.
* [CheerpJ](https://github.com/leaningtech/cheerpj-meta) - A Java compiler for the web that converts any Java client application into standard HTML5/WebAssembly/JavaScript.

--------------------

### <a name="javascript"></a>JavaScript <sup>[top⇈](#contents)</sup>
> JavaScript is a high-level, interpreted programming language that conforms to the ECMAScript specification. It is a language that is also characterized as dynamic, weakly typed, prototype-based and multi-paradigm.
* [Duktape](https://github.com/svaarala/duktape) - an embeddable Javascript engine, with a focus on portability and compact footprint that's capable of being run in the browser via WebAssembly.
* [Javy](https://github.com/bytecodealliance/javy) - a JavaScript to WebAssembly toolchain, capable of generating WASI-compatible modules from JS by embedding the QuickJS engine.
* [SpiderMonkey](https://github.com/bytecodealliance/spidermonkey-wasm-rs) - experimental Rust bindings and generic builtins for SpiderMonkey for building WASI-compatible modules from JavaScript.
* [quickjs-emscripten](https://github.com/justjake/quickjs-emscripten) - Safely execute untrusted Javascript in your JS/TS, and execute synchronous code that uses async functions.
* [wasmedge-quickjs](https://github.com/second-state/wasmedge-quickjs) - A high-performance, secure, extensible, and OCI-complaint JavaScript runtime for WasmEdge.  Features TCP/UDP support via WasmEdge Sockets.

--------------------

### <a name="julia"></a>Julia <sup>[top⇈](#contents)</sup>
> Julia was designed from the beginning for high performance. Julia programs compile to efficient native code for multiple platforms via LLVM.
* [julia-wasm](https://github.com/Keno/julia-wasm) - Emscripten & LLVM Julia to WASM compiler.
* ~[Charlotte.jl](https://github.com/MikeInnes/Charlotte.jl) - a Julia to WebAssembly/Javascript compiler~ `Unmaintained`

--------------------

### <a name="kcl"></a>KCL <sup>[top⇈](#contents)</sup>
> KCL is a constraint-based record & functional language mainly used in configuration and policy scenarios.
* [KCLVM](https://github.com/KusionStack/KCLVM) - LLVM-based KCL compiler, which can generate WASM.

--------------------

### <a name="kotlin"></a>Kotlin <sup>[top⇈](#contents)</sup>
> Kotlin is a modern but already mature programming language aimed to make developers happier. It's concise, safe, interoperable with Java and other languages, and provides many ways to reuse code between multiple platforms for productive programming.
> 
> Kotlin/Wasm is the new target and toolchain in the Kotlin family. It has a few special properties:
> - It compiles to Wasm directly without any additional layers, to compile as fast as possible, including incrementally in the future.
> - It uses experimental/fresh proposals like GC, Typed Function References, Exception Handling, and Stringref.
* [Kotlin/Wasm (Kotlin WebAssembly)](https://kotl.in/wasm)
* [Kotlin/Wasm examples](https://github.com/Kotlin/kotlin-wasm-examples)

--------------------

### <a name="kou"></a>Kou <sup>[top⇈](#contents)</sup>
> A minimal language compiled into wasm bytecode.
* [Kou](https://github.com/utatti/kou) - main repository.

--------------------

### <a name="lisp"></a>Lisp <sup>[top⇈](#contents)</sup>
> Lisp (historically LISP) is a family of programming languages with a long history and a distinctive, fully parenthesized prefix notation.
* [Femto Emacs](https://github.com/FemtoEmacs/wasCm) - translates Low Level Lisp into WebAssembly.

--------------------

### <a name="lobster"></a>Lobster <sup>[top⇈](#contents)</sup>
> Lobster is a statically typed language with flow-sensitive type inference and specialization, compile time reference counting (lifetime analysis) that looks a bit like Python. It was originally intended specifically for games.
> Lobster has its own Wasm backend that compiles directly to linkable (with LLD) .wasm files.
* [Lobster home](http://strlen.com/lobster/).
* [Lobster docs](http://aardappel.github.io/lobster/README_FIRST.html)
* [Lobster github](https://github.com/aardappel/lobster)
* [Compile to Wasm](http://aardappel.github.io/lobster/implementation.html) - how to compile.
* [Wasm backend details](http://aardappel.github.io/lobster/implementation_wasm.html) - how it is implemented, useful for other language implementors.

--------------------

### <a name="lox"></a>Lox <sup>[top⇈](#contents)</sup>
> Lox is a language created by Bob Nystrom, used to teach compilers in the book Crafting Interpreters. It is dynamically typed, and supports classes, closures, and first-class functions.
* [loxcraft](https://github.com/ajeetdsouza/loxcraft) uses WebAssembly for its [online playground](https://ajeetdsouza.github.io/loxcraft/).

--------------------

### <a name="lua"></a>Lua <sup>[top⇈](#contents)</sup>
> Lua is a lightweight, multi-paradigm programming language designed primarily for embedded systems and clients.[2] Lua is cross-platform, since the interpreter is written in ANSI C, and has a relatively simple C API.
> Lua was originally designed in 1993 as a language for extending software applications to meet the increasing demand for customization at the time.
* [WasmLua](https://github.com/vvanders/wasm_lua) - a Lua VM running in the browser.
* [Luwa](https://github.com/serprex/luwa) - a wasm-to-Lua JIT compiler.
* [Wasmoon](https://github.com/ceifa/wasmoon) - a high level Lua VM with JS bindings.
* [Wasm2Lua](https://github.com/SwadicalRag/wasm2lua) - can compile WebAssembly modules to pure Lua (or with FFI LuaJIT for extra speed).

--------------------

### <a name="lys"></a>Lys <sup>[top⇈](#contents)</sup>
> Lys is a typed functional language that compiles directly to WebAssembly.

* [Lys](https://github.com/lys-lang/lys) - main repository.

--------------------

### <a name="nelua"></a>Nelua <sup>[top⇈](#contents)</sup>
> Minimal, simple, efficient, statically typed, compiled, metaprogrammable, safe, and extensible systems programming language with a Lua flavor.
* [Nelua](https://github.com/edubart/nelua-lang/) - project repository
* [Nelua on the Web](https://github.com/edubart/nelua-lang/discussions/11) - Nelua-wasm discussion

--------------------

### <a name="never"></a>Never <sup>[top⇈](#contents)</sup>
> Never is a simple functional programming language. Technically it may be classified as syntactically scoped, strongly typed, call by value, functional programming language.
* [Never](https://github.com/never-lang/never) - project repository
* [Never on the Web](https://never-lang.readthedocs.io/en/latest/never-web/) - Never language demo

--------------------

### <a name="nim"></a>Nim <sup>[top⇈](#contents)</sup>
> A fringe language with some beautiful design patterns.
* [nlvm](https://github.com/arnetheduck/nlvm) - LLVM-based compiler for Nim with a WebAssembly target supported out of the box
* [nwasm](https://github.com/stisa/nwasm) - a webassembly backend for nim.
* [Nim wasm helpers](https://github.com/Feneric/nim-wasm-helpers) - a helper to set up a VM configured to build WebAssembly code using Nim.

--------------------

### <a name="ocaml"></a>Ocaml <sup>[top⇈](#contents)</sup>
> OCaml, originally named Objective Caml, is the main implementation of the programming language Caml, created by Xavier Leroy, Jérôme Vouillon, Damien Doligez, Didier Rémy, Ascánder Suárez and others in 1996. A member of the ML language family, OCaml extends the core Caml language with object-oriented programming constructs.
* [Ocaml](https://github.com/SanderSpies/ocaml/tree/wasm/wasmcomp) - a fork of main repo containing work on OCaml to wasm compilation.
* ~[OcamlRun](https://github.com/sebmarkbage/ocamlrun-wasm) - a build script for compiling OCaml bytecode interpreter to wasm using emscripten [Unmaintained]~

--------------------

### <a name="pascal"></a>Pascal <sup>[top⇈](#contents)</sup>
> Pascal is a general purpose imperative, procedural and object-oriented
> static typing programming language. The Free Pascal compiler targets many
> processor architectures, including wasm32; operating systems, including
> WASI; and embedded platforms.
* [Free Pascal](https://wiki.freepascal.org/WebAssembly) - Free Pascal compilation target and Pascal-to-Javascript runtime.

--------------------

### <a name="perl"></a>Perl <sup>[top⇈](#contents)</sup>
> Perl is a general-purpose programming language originally developed for text manipulation and now used for a wide range of tasks including system administration, web development, network programming, GUI development, and more.
* [WebPerl](https://github.com/haukex/webperl) - Perl 5 in the browser.

--------------------


### <a name="php"></a>PHP <sup>[top⇈](#contents)</sup>
> PHP is a general-purpose scripting language that is especially suited to server-side web development, in which case PHP generally runs on a web server. Any PHP code in a requested file is executed by the PHP runtime, usually to create dynamic web page content or dynamic images used on websites or elsewhere.
* [PIB](https://github.com/oraoto/pib) - a PHP runtime in the browser.
* [PHP WASM](https://github.com/soyuka/php-wasm) - maintained fork of PIB with PHP 8 support based on the work of [seanmorris](https://github.com/seanmorris/php-wasm).

--------------------

### <a name="plorth"></a>Plorth <sup>[top⇈](#contents)</sup>
> Plorth is stack based, concatenative, strongly typed functional scripting language which is easy to embed to applications written in C++. It's inspired by Forth and Factor programming languages.
* [Plorth](https://github.com/RauliL/plorth-webassembly) - main repository.

--------------------

### <a name="poetry"></a>Poetry <sup>[top⇈](#contents)</sup>
> Poetry is a poetically dynamic and simple programming language that compiles to WebAssembly. It has a minimalisting syntax akin to CoffeeScript and gives you full control over wasm imports and exports.
* [Poetry](https://github.com/FantasyInternet/poetry) - main repository.

--------------------

### <a name="python"></a>Python <sup>[top⇈](#contents)</sup>
> Python is an open source interpreted high-level programming language for general-purpose programming. Created by Guido van Rossum and first released in 1991, Python has a design philosophy that emphasizes code readability, notably using significant whitespace. It provides constructs that enable clear programming on both small and large scales.
* [Pyodide](https://github.com/iodide-project/pyodide) - a port of Python to WebAssembly that includes the core packages of the scientific Python stack (Numpy, Pandas, matplotlib).  Objects transparently convert and share between Python and Javascript.
* [MicroPython](https://github.com/micropython/micropython/tree/master/ports/webassembly) - a lean and efficient Python implementation for microcontrollers and constrained systems.
* [RustPython](https://github.com/RustPython/RustPython) - A Python 3 interpreter written in Rust. Check the demo [here](https://rustpython.github.io/demo/)
* [RPython](https://github.com/soIu/rpython) - A RPython (PyPy's Restricted Python) to WebAssembly compiler
* [TPython](https://github.com/soIu/tpython) - Pythonic++ (a "dialect" of C++) to WebAssembly compiler

--------------------

### <a name="prolog"></a>Prolog <sup>[top⇈](#contents)</sup>

> Prolog is a general-purpose logic programming language associated with artificial intelligence and computational linguistics. Prolog has its roots in first-order logic, a formal logic, and unlike many other programming languages, Prolog is intended primarily as a declarative programming language: the program logic is expressed in terms of relations, represented as facts and rules. A computation is initiated by running a query over these relations.
* [SWI-Prolog port to WebAssembly](https://github.com/SWI-Prolog/swipl-wasm) - a port of SWI-Prolog to WebAssembly. SWI-Prolog is a free implementation of the programming language Prolog commonly used for teaching and semantic web applications.
* [Ciao Prolog](https://github.com/ciao-lang/ciao) - includes a WebAssembly compilation target based on Emscripten. Ciao Prolog is a modern Prolog implementation designed to be portable, extensible and modular. Check the playground [here](https://ciao-lang.org/playground).

--------------------

### <a name="r"></a>R <sup>[top⇈](#contents)</sup>

> R is a language and environment for statistical computing and graphics.

* [WebR](https://github.com/georgestagg/webR) - R in the Browser. You can try it out [here](https://webr.r-wasm.org/latest/)

--------------------

### <a name="rego"></a>Rego <sup>[top⇈](#contents)</sup>

> Open Policy Agent (OPA) is an open source, general-purpose policy engine that unifies policy enforcement across the stack. Rego is a high-level declarative policy language purpose-built for expressing policies over complex hierarchical data structures.

* [OPA-Wasm](https://github.com/open-policy-agent/opa/tree/main/wasm) - Compilation and evaluation of Rego policies using Wasm.
* [npm-opa-wasm](https://github.com/open-policy-agent/npm-opa-wasm) - NPM module providing an SDK for using Wasm compiled OPA policies.
* [rust-opa-wasm](https://github.com/matrix-org/rust-opa-wasm) - A crate to use OPA policies compiled to Wasm.
* [dotnet-opa-wasm](https://github.com/christophwille/dotnet-opa-wasm) - Call OPA policies in Wasm from C# .NET Core.
* [python-opa-wasm](https://github.com/a2d24/python-opa-wasm) - OPA Wasm SDK for Python.
* [java-opa-wasm](https://github.com/sangkeon/java-opa-wasm) - OPA Wasm SDK for Java.

--------------------

### <a name="ruby"></a>Ruby <sup>[top⇈](#contents)</sup>
> Ruby is an open source interpreted high-level programming language for general-purpose programming. Created by Matz. Ruby has a design philosophy that emphasizes code readability, notably using as few sigils (special chars`:.{}%[]&=>;`) as possible.
* [Wruby](https://github.com/pannous/wruby) Web ruby - a port of minimal ruby (mruby).
* [run.rb](https://github.com/jasoncharnes/run.rb) run.rb - allows you to run Ruby code in the browser
* [Artichoke](https://github.com/artichoke/artichoke/blob/f8e9881403a50c3ba7e2b1ffc16f205c0b5e0255/VISION.md#design-and-goals) - a Ruby implementation written in Rust and Ruby. You can try it out here: https://artichoke.run
* [ruby.wasm](https://github.com/ruby/ruby.wasm/) - a collection of "official" WebAssembly ports of the CRuby. You can
  try it out [here](https://try.ruby-lang.org/playground/#code=puts+RUBY_DESCRIPTION&engine=cruby-3.2.0)
* [rlang](https://github.com/ljulliar/rlang) Rlang - a (subset of) Ruby to WebAssembly compiler

--------------------

### <a name="rust"></a>Rust <sup>[top⇈](#contents)</sup>
> Rust is a systems programming language sponsored by Mozilla Research, which describes it as a "safe, concurrent, practical language,"supporting functional and imperative-procedural paradigms. Rust is syntactically similar to C++, but its designers intend it to provide better memory safety while maintaining performance.
* [Rust `wasm32-unknown-unknown` target](https://www.hellorust.com/setup/wasm-target/) - Rust compiler backend for WebAssembly (without the need for Emscripten).
* [Wargo](https://github.com/lord/wargo) - a simple npm package that makes compiling Rust to WebAssembly easy on macOS or Linux.
* [RustWasmLoader](https://github.com/ianjsikes/rust-wasm-loader) - A simple Webpack loader that shells out to cargo to build a Rust project targeting WebAssembly.
* [CargoWeb](https://github.com/koute/cargo-web) - This cargo subcommand aims to make it easy and convenient to build, develop and deploy client-side Web applications written in Rust.
* [Wasm-Bindgen](https://github.com/rustwasm/wasm-bindgen) - A library and a CLI for Rust that facilitate high-level interactions between wasm modules and JavaScript.
* [Woz](https://github.com/alexkehayias/woz) - Woz is a WebAssembly progressive web app (PWA) toolchain for building and deploying performant mobile apps with Rust. Distributing your app is as simple as sharing a hyperlink.

--------------------

### <a name="scheme"></a>Scheme <sup>[top⇈](#contents)</sup>
> Scheme is a programming language that supports multiple paradigms, including functional programming and imperative programming, and is one of the two main dialects of Lisp. Unlike Common Lisp, the other main dialect, Scheme follows a minimalist design philosophy specifying a small standard core with powerful tools for language extension..
* [Schism](https://github.com/schism-lang/schism) - Schism is an experimental self-hosting compiler from a subset of R6RS Scheme to WebAssembly. Development so far has focused on features necessary for self-hosting. The compiler itself is written in, and compiles, a very small subset of Scheme.

--------------------

### <a name="scopes"></a>Scopes <sup>[top⇈](#contents)</sup>
> Scopes is a general purpose programming language and compiler infrastructure specifically suited for short turnaround prototyping and development of high performance applications in need of multi-stage compilation at runtime.
* [Scopes](https://hg.sr.ht/~duangle/scopes) - main repository

--------------------

### <a name="speedyjs"></a>Speedy.js <sup>[top⇈](#contents)</sup>
> Speedy.js is a compiler for a well considered, performance pitfalls free subset of JavaScript targeting WebAssembly. Because WebAssembly is statically-typed, the project uses TypeScript as type-checker and to resolve the types of the program symbols.
* ~[Speedy.js](https://github.com/MichaReiser/speedy.js) - main repository.~ `Unmaintained`

--------------------

### <a name="swift"></a>Swift <sup>[top⇈](#contents)</sup>
> Swift is a general-purpose, multi-paradigm, compiled programming language developed by Apple Inc. for iOS, macOS, watchOS, tvOS, Linux, and z/OS.
* [SwiftWasm](https://github.com/swiftwasm) - GitHub organization.

--------------------

### <a name="turboscript"></a>TurboScript <sup>[top⇈](#contents)</sup>
> TurboScript is an experimental programming language for parallel programming for web which compiles to JavaScript (asm.js) and WebAssembly (targeting post-MVP). The syntax is similar to TypeScript and the compiler is open source and written in TypeScript. TurboScript has zero dependencies.
* [TurboScript](https://github.com/01alchemist/TurboScript) - main repository.

--------------------

### <a name="typescript"></a>TypeScript <sup>[top⇈](#contents)</sup>
> TypeScript is an open-source programming language developed and maintained by Microsoft. It is a strict syntactical superset of JavaScript, and adds optional static typing to the language.
* See [AssemblyScript](#assemblyscript)

--------------------

### <a name="v"></a>V <sup>[top⇈](#contents)</sup>

> V is a statically typed compiled programming language designed for building maintainable software.

* [V](https://github.com/vlang/v) - main repository. You can try it out [here](https://play.vlang.io/)

--------------------

### <a name="wa"></a>Wa <sup>[top⇈](#contents)</sup>

> Wa is a general-purpose programming language designed for developing robustness and maintainability WebAssembly software. Instead of requiring complex toolchains to set up, you can simply go install it - or run it in a browser.

> 凹语言™（凹读音“Wa”）是 针对 WASM 平台设计的的通用编程语言，支持 Linux、macOS 和 Windows 等主流操作系统和 Chrome 等浏览器环境，同时也支持作为独立Shell脚本和被嵌入脚本模式执行。

* [Wa/凹语言](https://github.com/wa-lang/wa) - main repository.

--------------------

### <a name="wah"></a>Wah <sup>[top⇈](#contents)</sup>
> Wah is a slightly higher level language that is a superset of WebAssembly. It aims to make WebAssembly's text format slightly more friendly to humans, without introducing new syntax or datatypes.
* ~[Wah](https://github.com/tmcw/wah) - main repository.~ `Unmaintained`

--------------------

### <a name="walt"></a>WAlt <sup>[top⇈](#contents)</sup>
> WAlt is an alternative syntax for WebAssembly text format. It's an experiment for using JavaScript syntax to write to as 'close to the metal' as possible. It's JavaScript with rules. .walt files compile directly to WebAssembly binary format.
* ~[Walt](https://github.com/ballercat/walt) - main repository.~ `Unmaintained`

--------------------

### <a name="wam"></a>Wam <sup>[top⇈](#contents)</sup>
> WebAssembly Macro language: Wam syntax is a near superset of wast syntax that is more convenient for human developers to write directly.
* ~[Wam](https://github.com/kanaka/wam) - main repository.~ `Unmaintained`

--------------------

### <a name="wase"></a>Wase <sup>[top⇈](#contents)</sup>
> WASE: WebAssembly made easy. Wase is a language, which tries to make WASM easy to write. The language maps closely to WebAssembly, and compiles directly to Wasm bytecode. Has strong typing with type inference.
* [Wase](https://github.com/area9innovation/wase) - main repository.

--------------------

### <a name="webassembly"></a>WebAssembly <sup>[top⇈](#contents)</sup>
> Yes, WebAssembly. `Wasm3` is the fastest WebAssembly interpreter, that enables WebAssembly self-hosting.
* [Wasm3](https://github.com/wasm3/wasm3) - main repository.
* [Wasm3 on WAPM](https://wapm.io/package/vshymanskyy/wasm3) - WAPM package.

--------------------

### <a name="wracket"></a>Wracket <sup>[top⇈](#contents)</sup>
> A lisp-like language that compiles to WebAssembly, written in racket
* ~[Wracket](https://github.com/sschauss/wracket) - main repository.~ `Unmaintained`

--------------------

### <a name="xcc"></a>xcc <sup>[top⇈](#contents)</sup>
> Toy C compiler for x86-64 and wasm
* [xcc](https://github.com/tyfkda/xcc) - main repository.
* [Online demo](https://tyfkda.github.io/xcc/).

--------------------

### <a name="zig"></a>Zig <sup>[top⇈](#contents)</sup>
> Zig is a general-purpose programming language designed for robustness, optimality, and maintainability.
* [Zig WebAssembly](https://ziglang.org/documentation/master/#WebAssembly) - documentation on WebAssembly

--------------------

Please read the [contribution guidelines](CONTRIBUTING.md) if you want to contribute.

--------------------

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Steve Akinyemi](https://github.com/appcypher) has waived all copyright and related or neighboring rights to this work.
