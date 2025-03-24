# ProgLang_Notes

Notes for a categorical bundle of concepts which allow human brains help figure out things that are computable.

This repo will be focus on indexing & just dropping useful notes on resources reguarding what they are and existing tools people have made. I will be opinionated.

## Notable Authorship

## Tools

## Misc

## Language Listings

Below are listings of langaugesI feel like mentioning. I'm not interested in being exhaustive.	

### Assembly

Barely a langauge, the preprocessors usually have more depth to it than the actual syntax (not that you should manage assembly codebases that way anymore...).

See: [ASM_Notes](https://github.com/Ed94/ASM_Notes)

### Systems-Based

An oversaturated term to mean any language that can actually use the meat of the machine or sandboxed operating enviornment it has on the machine to its fullest extent (in capable hands...).

* C: I don't have to explain this mess. I so far stick with C11 for libraries, and problably will use whatever latest is for everything else.
  * C++: Cursed, but its too late for me. I can read msvc's C++ std lib.. I would have rather learned haskell than have gained this skill.
* [C3](https://github.com/c3lang/c3-web): Nice upgrade for once. Looking forward to trying it.. I don't like cmake though.
* [CakeLisp](https://macoy.me/code/macoy/cakelisp): It looks cool, haven't tried it yet.
* [Jai](https://www.youtube.com/watch?v=TH9VCN6UkyQ&list=PLmV5I2fxaiCKfxMBrNsU1kgKJXD3PkyxO): I will love and problably learn from this codebase more than from any other source.. When I finally get access to it.
* [Odin](https://github.com/odin-lang/Odin.git): Opinionated in mostly good ways, if you dont like them learn the codebase and change them. You'll problably regret doing so in 5 years though so make sure it counts.
* [Zig](https://github.com/ziglang/zig): Opinions I don't care for; in a bloated toolchain & codebase I don't want to learn.

Notable Mentions:

* [Roc](https://github.com/roc-lang/roc): I'd problably like this if it wasn't written in Rust.
* [Haskell](https://www.haskell.org): There is something special here but I don't like the toolchain UX, and the thing is extremely bloated.
* [Rust](https://github.com/rust-lang): How to worship a typesystem without any benefits from the functional cult.

### VM Sandboxed System

These langauges are designed to run from a virtual machine sandbox that is isolated from the native operating environment sandbox accessible on most machines.

* C#: Better Java. Used by gamedev because of XNA and Unity.
* Java: A highly effective tool to extract contracts from governments and ignornant executives.

### Embeddabe

Languages which can be "embedded" into codebases tend to be "scripting" langauges.  
They should be something a user can digested over a few weekends, the point of them is to be so simple they are easy to maintain, and modify as needed for a project.

* [Lua](https://www.lua.org): The og small brazillian. 5.1 is well adored and is tiny. They kept adding stuff after 5.1 but its still resonably sized in 5.4 (< 30 kloc I think).
  * [Teal](https://github.com/teal-language/tl): Typed dialect. (~ 11 kloc added in a single file)
* [Luau](https://luau.org): Derivative of Lua 5.1. Made by roblox people. Unfortunately written in C++.

* [umka-lang](https://github.com/vtereshkov/umka-lang): Statically typed, small, written in C. Looks nice.

### Scripting

Languages which have been designed to be simple and run in an abstract enviornment that should be more compatible with intellectual minds not tainted by those oh so useful tidbits about how machines work.

* Most of embeddable can be dropped into here...
* Shell languages: The only reason to use these is becuase of CLI, and they all mostly suck. (For some reason I tolerate Powershell the most)
* Javascript: This problably did more damage to humanity than cigarettes.
* Python: This serves a similar purpose to 4chan. If it didn't exist another language would just get tainted.
