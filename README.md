# Verilog_Converters

A collection of Verilog HDL implementations of **Encoder**, **Decoder**, and **Comparator** circuits. This repository is designed for beginners learning Digital Electronics and Verilog HDL. Each module includes a well-structured design, testbench, and simulation waveform to verify functionality.

---

# 🔹 Encoder

## Description

An **Encoder** converts one active input line into a binary-coded output. It reduces multiple input lines into fewer output lines, making it useful for digital communication and data encoding.

### Truth Table (4-to-2 Encoder)

| D3 | D2 | D1 | D0 | Y1 | Y0 |
|:--:|:--:|:--:|:--:|:--:|:--:|
| 0 | 0 | 0 | 1 | 0 | 0 |
| 0 | 0 | 1 | 0 | 0 | 1 |
| 0 | 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 0 | 0 | 1 | 1 |

---

## 📊 Encoder Waveform

Simulation output generated from the Verilog testbench.

<img width="873" height="187" alt="Image" src="https://github.com/user-attachments/assets/5dae597e-4f09-4ac1-a2a9-8284387dea0e" />

---

# 🔹 Decoder

## Description

A **Decoder** converts binary input data into one active output line. It performs the opposite operation of an encoder and is widely used in memory addressing, display systems, and digital control circuits.

### Truth Table (2-to-4 Decoder)

| A1 | A0 | Y3 | Y2 | Y1 | Y0 |
|:--:|:--:|:--:|:--:|:--:|:--:|
| 0 | 0 | 0 | 0 | 0 | 1 |
| 0 | 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 0 | 1 | 0 | 0 |
| 1 | 1 | 1 | 0 | 0 | 0 |

---

## 📊 Decoder Waveform

Simulation output generated from the Verilog testbench.

<img width="877" height="177" alt="Image" src="https://github.com/user-attachments/assets/27400fe7-2f6a-4fa0-8346-5b9e6ab14977" />

---

# 🔹 Comparator (1-bit)

## Description

A **Comparator** compares two binary numbers and indicates whether one is **greater than**, **less than**, or **equal to** the other. Comparators are commonly used in processors, arithmetic circuits, and digital decision-making systems.

### Truth Table (1-Bit Comparator)

| A | B | A>B | A=B | A<B |
|:-:|:-:|:---:|:---:|:---:|
| 0 | 0 | 0 | 1 | 0 |
| 0 | 1 | 0 | 0 | 1 |
| 1 | 0 | 1 | 0 | 0 |
| 1 | 1 | 0 | 1 | 0 |

---

## 📊 Comparator Waveform

Simulation output generated from the Verilog testbench.

<img width="878" height="281" alt="Image" src="https://github.com/user-attachments/assets/e539ef28-1d8e-4f64-8c64-5ae8fafbf7bb" />

---

## 🛠️ Tools Used

- Verilog HDL
- EDA Playground / ModelSim / QuestaSim
- GTKWave

---

## 🎯 Learning Objectives

- Understand the working of Encoders.
- Learn binary-to-output decoding using Decoders.
- Implement and verify Comparators in Verilog.
- Write and simulate Verilog testbenches.
- Analyze simulation waveforms.

---

## ⭐ Support

If you found this repository helpful, consider giving it a *Star ⭐* to support the project.
