# 4bit-array-multiplier-tanner-eda
vlsi cmos tanner-eda t-spice s-edit transistor-level digital-ic-design array-multiplier full-adder cmos-design
# Transistor-Level CMOS Design and Optimization of a 4-Bit Array Multiplier

## Overview

This project presents the transistor-level design and optimization of a
4-bit CMOS array multiplier using Tanner EDA.

The design was developed hierarchically, starting from basic CMOS logic
gates and building full-adder cells, a 4-bit ripple-carry adder, and
finally a 4-bit array multiplier.

The primary objective was to optimize the XOR implementation to reduce
transistor count and improve the overall area-delay-power trade-off.

## Tools Used

- Tanner EDA S-Edit
- Tanner T-Spice
- CMOS transistor-level design
- SPICE transient simulation

## Design Hierarchy

```text
CMOS Logic Gates
       ↓
Optimized XOR Gate
       ↓
Full Adder
       ↓
4-Bit Ripple Carry Adder
       ↓
4-Bit Array Multiplier
