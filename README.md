# 8-to-3 Encoder – Verilog

This project implements an **8-to-3 Encoder** using **Verilog HDL**.

An encoder is a combinational logic circuit that converts one of several active input lines into a binary code at its output. An 8-to-3 encoder has **8 input lines** and **3 output lines**.

## Overview

The 8-to-3 Encoder consists of:

- 8 Input Lines (`D0`–`D7`)
- 3 Output Lines (`Y2`, `Y1`, `Y0`)
- Combinational Logic
- Verilog HDL implementation
- Verilog testbench for functional verification

## Block Diagram

```text
                         ┌───────────────┐
        D0 ─────────────►│               │
        D1 ─────────────►│               │
        D2 ─────────────►│               │
        D3 ─────────────►│               │
        D4 ─────────────►│    8-to-3     │──────► Y2
        D5 ─────────────►│    ENCODER     │──────► Y1
        D6 ─────────────►│               │──────► Y0
        D7 ─────────────►│               │
                         └───────────────┘
