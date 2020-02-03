## Tupai

### *Operating system*

Tupai is a multitasking operating system written in Rust targeting i386, amd64 and armv7 architectures.
It focusses on safety, stability, portability and correctness. It is not designed with a specific application in mind, but rather to act as a base for future experiments in software safety.
Tupai does not conform to an existing operating system API (i.e: POSIX) but instead aims to implement a new and innovative design.
Tupai has been rewritten upwards of 8 times in C, C++ and finally Rust.

You can find more information about Tupai [here](https://www.github.com/tupai-os/).

<p>
<img alt="An old revision of Tupai" width="512" src="https://raw.githubusercontent.com/zesterer/tupai/new-vfs/doc/images/tupai-0-6-0-dev.png">
</p>

## Bread

### *Functional programming language*

Bread is a statically-typed functional programming language with a compiler written in Rust.
It features Hindley-Milner type inference, complex types, currying, a bytecode compiler backend, and beautiful error messages.

```hs
def len of (List Num) -> Num = l ->
	if l = []
	then 0
	else 1 + len(list:tail)
```

[You can find out more about Bread and see more example code here](https://www.github.com/zesterer/bread)

## Forge

### *Dynamically-typed imperative programming language*

Forge is a dynamically-typed programming language inspired by JavaScript, Rust, and Python. It aspires to be 'JavaScript, but less shit'.

```js
var basket = ["apple", "banana", "pineapple", "kiwi"];

var display = |item| {
	print("I have a" + item);
};

for item in basket {
	display(item);
}
```

[You can try Forge online here](https://forge.jsbarretto.com).

[You can find out more about Forge here](https://www.github.com/zesterer/forge).

Forge also has an (incomplete) successor, [Leon](https://www.github.com/zesterer/leon)

## Euc

### *Software rendering library*

Euc is a versatile, simple to use library that allows 3D rendering on the CPU.
It has a portable, compact design that makes it perfect for prototyping ideas, unit testing, or even simple realtime applications.

[You can find out more about Euc here](https://www.github.com/zesterer/euc).

<p>
<img alt="The Utah Teapot, rendered with Euc" width="512" src="https://raw.githubusercontent.com/zesterer/euc/master/misc/example.png">
</p>

## Funki Crab

### *Optimising BrainFuck compiler*

Funki Crab is an optimising Brainfuck compiler written in Rust.
It's capable of a large number of Brainfuck optimisation techniques and produces a significant speedup compared to naive compilation.
The performance of programs emitted by Funki Crab are within the ballpark of the best optimising Brainfuck compilers available.

I created Funki Crab as an exercise in learning about compiler development, Immediate Representation (IR) techniques and optimisation.
Brainfuck struck me as a sensible language for such a project given its simplicity, Turing-completeness and wealth of potential optimisations.

Funki Crab is an anagram of Brainfuck. 'Crab' is a reference to Ferris, the Rust mascot.

[You can find out more about Funki Crab here](https://www.github.com/zesterer/funkicrab).

## Veloren

### *Open-world, open-source voxel RPG and engine*

Veloren is a multiplayer voxel RPG written in Rust that I founded. Veloren takes inspiration from games such as Cube World, Minecraft and Dwarf Fortress.
Veloren's world is procedurally-generated and makes use of advanced teleological generation techniques such as erosion simulation.
The game is currently under heavy development, but is playable. Veloren has since grown into a large FOSS project with about 15 active developers.

[You can find out more about Veloren here](https://www.gitlab.com/veloren/veloren).

<p>
<img alt="Night time in Veloren" width="512" src="https://cdn.discordapp.com/attachments/634860358623821835/670788372645675018/unknown.png">
</p>

## Emul8

### *CHIP-8 emulator*

Emul8 is an emulator for the CHIP-8 game system.
It can run a variety of CHIP-8 ROMs including pong, space invaders, snake and tetris.
Emul8 supports various debugging features such as instruction disassembly and step-through execution.

[You can find out more about Emul8 here](https://www.github.com/zesterer/emul8/).

<p>
<img alt="Emul8or running Pong" width="512" src="https://github.com/zesterer/emul8or/raw/master/doc/pong-chip8.png">
</p>
