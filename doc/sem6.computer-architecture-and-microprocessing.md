# Computer Architecture and Microprocessing

- [Overview](#overview)
  - [Computer](#computer)
  - [Classification of Computers](#classification-of-computers)
  - [Computer Architecture](#computer-architecture)
  - [Components of Computer](#components-of-computer)
- [Computer System](#computer-system)
  - [CPU](#cpu)
  - [Memory](#memory)
  - [Input/Output Devices](#inputoutput-devices)
  - [System Bus](#system-bus)

## Overview

### Computer

**Computer** is an electronic device that manupulates information, or data. It has the ability to **store**, **retrieve**, and **process** data.

Computer works:
- Get input
- Process input with commands which is saved into computer.
- Give output

A computer program is a collection of instructions that performs a specific task when executed by a computer. 

A computer requires programs to function.

![Image 1]

### Classification of Computers

- Microcomputers
- Minicomputers
- Mainframe Computers
- Supercomputers

Modern computers:
- Personal Mobile Device: Smartphone, Tablet, ...
- Desktop Computers
- Server Computers
- Clusters/Warehouse Scale Computers
- Embedded Computers

### Computer Architecture

Computer Architecture is a specification describing how hardware and software technologies interact to create a computer platform or system.

Computer Architecture consists of three main categories:
- Instruction Set Architecture: The inclides the CPU's functions and capabilities, the CPU's programming language, data formats, ...
- Micorarchitecture: This defines the data processing and storage element or data paths and how they should be implemented.
- System design: Tihs includes all the hardware parts, such as CPU, data processors, ...

### Components of Computer

<p align="center">
    <img src="../img/ca.structure.png" width="50%" />
</p>

Central Processing Unit: The CPU sends signals to control the other parts of the computer, almost like how brain controls a body.

Main Memory: Store operating system software, software applications and other information.
- RAM is a temporary memory. Stores data and program instructions while the computer is running. The data stored in RAM is lost forever when power is turn off.
- ROM is a permanent memory. Stores start up instructions when the computer is turn on. The instructions are set by manufacturer and can not be changed by user. The last instruction in ROM directs computer to load the OS.

Input/Output: Interact information between computer and another devices.

System Bus: Connects the major components of a computer system, combining the functions of a **data bus** to carry information, an **address bus** to determine where it should be sent, and a **control bus** to determine its operation.

## Computer System

### CPU

<p align="center">
    <img src="../img/ca.cpu.internal.png" width="70%" />
</p>

- **CU**, controls actions of computer by program.

- **Arithmetic and Logic Unit**, perform arithmetic and logic operations.

- **Register File**, an array of processor registers in a CPU

### Memory

Functions: Stores programs and data.

Action: Write and Read

Components: Internal Memory, External Memory

#### Internal Memory

Contains information that CPU can access directly, quickly, but capacity is not large, use ROM and RAM.

- ROM - Read Only Memory
  - Programmable ROM (PROM)
  - Erasable PROM (EPROM)
  - Electrically EPROM (EEPROM)
  - Flash Memory

- RAM - Random Access Memory
  - Static RAM (SRAM)
  - Dynamic RAM (DRAM)
  - ...

#### External Memory

Functions: Stores resources of computers, connect with computer system like input/ouput devices, large capacity, slowly access.

Types: Hard drive, soft drive, CD, DVD, Flash storage, memory card.

### Input/Output Devices

Functions: information exchange between computer and the world.

Action: Write and Read

Components: Peripheral Devices, IO Modules.

### System Bus

Connects the major components of a computer system, combining the functions of a **data bus** to carry information, an **address bus** to determine where it should be sent, and a **control bus** to determine its operation.

[Image 1]: ../img/ca.computer.png
[Image 2]: ../img/ca.structure.png
[Image 3]: ../img/ca.cpu.internal.png
