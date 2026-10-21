# PPU-Minecraft-CPU-2021-2022
Pat's Processing Unit - a Minecraft cpu I built a long time ago

<img width="2048" height="1142" alt="image" src="https://github.com/user-attachments/assets/bec47fd9-9e4f-4fe2-ad1b-dd2e90565594" />

# 8-bit Redstone CPU

An 8-bit, Turing-complete CPU I built entirely in Minecraft using Redstone in 2022, when I was 12.

I designed the architecture and instruction set from scratch after spending roughly six months learning digital logic and computer architecture.

[Watch the CPU demonstration](https://www.youtube.com/watch?v=7RHQIuh1gzk)

## Specifications

| Feature | Specification |
|---|---|
| Architecture | 8-bit, Harvard architecture |
| Instruction width | 19 bits |
| Instruction set | 24 instructions |
| Opcode width | 5 bits |
| Register addressing | Two 3-bit register addresses |
| Immediate width | 8 bits |
| Registers | 8 bytes, dual-read |
| Program ROM | 71.5 bytes |
| Clock speed | 7.7 seconds per pulse |
| Implementation | Minecraft Redstone |
| Computational model | Turing-complete |

## Architecture

The CPU uses a custom instruction set and a Harvard architecture, with separate instruction and data memory.

Each instruction is 19 bits wide:

| Field | Bits |
|---|---|
| Opcode | 5 |
| Register address A | 3 |
| Register address B | 3 |
| Immediate | 8 |
| **Total** | **19** |

The processor includes an 8-bit arithmetic and logic unit (ALU), a register system supporting two simultaneous reads, instruction decoders, program memory, and control circuitry.

The program ROM uses barrels to encode instructions through Redstone circuits.

## Development

I built the CPU on the Open Redstone Engineers Minecraft server.

I started by learning Boolean logic and building smaller components such as adders, registers, and memory circuits before integrating them into a complete processor.

I also wrote a program to generate WorldEdit schematics for programs, making it easier to load instructions into the CPU's ROM.

The demonstration video shows the processor executing a program, including the ALU performing arithmetic operations.

## What I Learned

- Digital logic and Boolean algebra
- CPU and instruction set architecture
- ALU and register design
- Instruction decoding and control logic
- Memory systems
- Debugging large Redstone circuits
- Programmatic generation of Minecraft schematics

This was my first major computer engineering project.

## Demo

[Redstone CPU (2022 Build) — YouTube](https://www.youtube.com/watch?v=7RHQIuh1gzk)

**Status:** Completed (2022)

Visitable on the ORE computational redstone Minecraft server 
```mc.openredstone.org```

[https://www.youtube.com/watch?v=7RHQIuh1gzk](https://www.youtube.com/watch?v=7RHQIuh1gzk)
watch the video here!
