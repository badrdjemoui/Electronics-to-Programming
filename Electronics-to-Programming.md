# 🖥️ Electronics to Programming

A complete roadmap to understand how a computer works — from electronics fundamentals to high-level programming.

---

## 1️⃣ Diode (الديود)
- **Definition:** Allows current to flow in one direction.
- **Types:** Silicon, Zener, Schottky, LED
- **Applications:** Rectification, reverse-polarity protection
- **Exercise:** Design a half-wave rectifier

```
(+) ──>|── (Load) ── (-)
```

---

## 2️⃣ Transistors (الترانزستورات)
- **Types:** BJT, MOSFET
- **Function:** Switch or amplifier
- **Exercise:** Drive a DC motor using a transistor

```
 Vcc
  |
 Motor
  |
 Transistor ── GND
```

---

## 3️⃣ Logic Gates (البوابات المنطقية)
- AND, OR, NOT, NAND, NOR, XOR, XNOR
- Truth tables
- **Examples:** Half Adder, Full Adder

```
A ---|&>--- Output
B ---|
```

---

## 4️⃣ Flip-Flops (القلابات)
- SR, JK, D, T
- **Project:** Build a binary counter

```
D ──> [FF] ──> Q
clk ──^
```

---

## 5️⃣ CPU — Central Processing Unit (المعالج)
- ALU, Control Unit, Registers
- **Cycle:** Fetch → Decode → Execute

```
[Registers] → [ALU] → Output
       ↑       ↓    
   Control Unit
```

---

## 6️⃣ RAM Memory (الذاكرة)
- **Types:** SRAM, DRAM, Cache
- Memory hierarchy concept

```
Cache
RAM
Storage
```

---

## 7️⃣ Binary System (النظام الثنائي)
- Number conversions
- Two’s complement
- IEEE-754 floating point

```
13 = 1101₂
```

---

## 8️⃣ Machine Language (لغة الآلة)
- Binary instructions

```
0001 = LOAD
0010 = ADD
0100 = JMP
```

---

## 9️⃣ Assembly Language (الأسمبلي)
- Registers, labels, instructions

```
MOV A, 5
ADD A, 2
JMP start
```

---

## 🔟 C Programming (لغة C)
- Pointers
- Memory management
- Simple project

```c
#include <stdio.h>
int main(){ int x = 5; printf("%d", x); }
```

---

### ✅ Conclusion
This guide takes you from **electronics → logic → CPU → programming**, building a true computer science mindset.

---

### 📌 Next Steps
- Add diagrams & simulation files
- Add Arduino + Assembly practice
- Compiler + Memory projects

---

### 🎯 Goal
Understand computers from **electrons to code**.
