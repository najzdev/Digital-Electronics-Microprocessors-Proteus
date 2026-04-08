# Digital Logic Simulation – Proteus Projects

This repository contains a set of **digital logic simulations** created using Proteus for studying and verifying the behavior of basic logic gates and flip-flops used in embedded systems and digital electronics.

## 📁 Repository Structure

```
.
├── 2-Bit Full Adder.pdsprj
├── AND_OR_XOR.pdsprj
├── CLOCK FLIP FLOP.pdsprj
├── D FLIP FLOP.pdsprj
```

### 1️⃣ AND_OR_XOR

Simulation verifying the **truth tables** of the following logic gates:

* AND
* OR
* XOR

The circuit uses:

* LogicState inputs
* LogicProbe outputs

All possible input combinations are tested to confirm correct gate behavior.

---

### 2️⃣ D FLIP FLOP

Simulation demonstrating the operation of a **D Flip-Flop**.

Components used:

* D Flip-Flop
* LogicState input (D)
* DCLOCK (clock generator)
* LogicProbe output

The simulation verifies that the output **Q follows the D input on the rising edge of the clock**.

---

### 3️⃣ CLOCK FLIP FLOP

Simulation showing the behavior of a **clocked flip-flop** driven by a **DCLOCK generator**.

Purpose:

* Observe output state transitions
* Understand synchronization with clock signals

---

### 4️⃣ 2-Bit Full Adder

Design and simulation of a **2-bit Full Adder** using basic logic gates.

Logic used:

* XOR
* AND
* OR

Equations implemented:

```
SUM = A ⊕ B ⊕ Cin
Cout = (A · B) + (Cin · (A ⊕ B))
```

This demonstrates how multi-bit arithmetic circuits are built from fundamental logic gates.

---

## 🧰 Software Used

* Proteus Design Suite (ISIS schematic simulation)
* Digital logic components library

---

## 🎯 Purpose

These simulations were created as part of **Digital Electronics and Embedded Systems coursework**, focusing on:

* Understanding logic gate operations
* Verifying truth tables through simulation
* Learning sequential logic (flip-flops)
* Designing combinational circuits (adders)

---

## 👨‍💻 Author

**Hamza Labbaalli**
Computer Engineering & Embedded Systems
Full Stack Developer | AI | IoT | Cybersecurity

GitHub: https://github.com/najzdev

---

⭐ If you find this repository useful, feel free to star it.
