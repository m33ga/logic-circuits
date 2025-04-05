# Logic Circuits

## Overview

This repository contains a comprehensive collection of digital logic circuits designed in Logisim for **Computer Architecture** course at **TUM**. These circuits demonstrate fundamental concepts in digital design, from basic logic gates to more complex computational structures.

## Contents

### Basic Logic Gates

- **e1_NOT**: Simple NOT gate implementation
- **e2_AND**: AND gate implementation
- **e3_OR**: OR gate implementation
- **e4_NAND**: NAND gate implementation
- **e5_NOR**: NOR gate implementation
- **e6_XOR**: XOR (exclusive OR) gate implementation
- **e7_XNOR**: XNOR (exclusive NOR) gate implementation

### Multi-Input Logic Gates

- **e10_4AND**: 4-input AND gate
- **e11_5OR**: 5-input OR gate
- **e12_4XOR**: 4-input XOR gate

### Flip-Flops

- **m1_SR_FF**: SR (Set-Reset) Flip-Flop
- **m2_D_FF**: D (Data) Flip-Flop
- **m3_JK_MS_FF**: JK Master-Slave Flip-Flop
- **m4_T_FF**: T (Toggle) Flip-Flop

### Storage Elements

- **m5_REG**: Basic register implementation
- **h1_CLK_REG**: Clocked register

### Counter and Timing Circuits

- **m6_BIN_CNTR**: Binary counter
- **h3_DELAY**: Delay circuit

### Multiplexers and Demultiplexers

- **m9_2MUX**: 2-to-1 Multiplexer
- **m10_4MUX**: 4-to-1 Multiplexer
- **m11_2DEMUX**: 1-to-2 Demultiplexer
- **m12_4DEMUX**: 1-to-4 Demultiplexer

### Arithmetic Circuits

- **custom_FULL_ADDER**: Full adder circuit
- **custom_4BIT_ADDER**: 4-bit adder
- **h8_8_FULL_ADDER**: 8-bit full adder
- **custom_COMPARATIVE_ADDER**: Adder with comparator functionality

### Comparison Circuits

- **h5_4CMPRTR**: 4-bit comparator
- **custom_4BIT_COMPARATOR**: 4-bit comparator implementation

### Bitwise Operations

- **h16_BTWS_NOT**: Bitwise NOT operation

### Display and I/O

- **e8_LED**: Simple LED circuit
- **e9_LEDs**: Multiple LED setup
- **h18_BIN_DEC**: Binary to decimal converter

## How to Use

1. **Open the File**:

   - Download and install [Logisim](http://www.cburch.com/logisim/)
   - Open logic_circuits.circ with Logisim

2. **Exploring Circuits**:

   - Navigate between different circuits using the left sidebar in Logisim
   - Each circuit is labeled with a descriptive name
   - Circuits with "e" prefix are elementary components
   - Circuits with "m" prefix are moderate complexity components
   - Circuits with "h" prefix are higher complexity components
   - Custom circuits are labeled with descriptive names

3. **Testing Circuits**:
   - Use Logisim's built-in tools to test circuit behavior
   - Provide inputs using switches, buttons, or clock sources
   - Observe outputs on LEDs or Logisim's output components

## Learning Outcomes

This collection demonstrates understanding of:

- Basic digital logic principles
- Sequential circuit design
- Memory elements and flip-flops
- Arithmetic and comparison operations
- Digital circuit optimization
- Hierarchical circuit design

## Notes

- The master-slave JK flip-flop implementation addresses the racing condition problem in standard SR flip-flops
- Several complex circuits like the 4-bit comparator and 8-bit adder are built hierarchically from simpler components
- The custom comparative adder merges addition and comparison functionality
