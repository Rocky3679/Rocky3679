# Janaki Raman K · Hardware & Embedded Systems Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://linkedin.com)
[![Electro Maestro Hub](https://img.shields.io/badge/Publication-Electro%20Maestro%20Hub-FACC15?style=flat-square)](https://electromaestrohub.blogspot.com/)
[![Standards](https://img.shields.io/badge/Standards-ISO%2016750--2%20%7C%20CISPR%2025%20%7C%20IEC%2061000--4--2-red?style=flat-square)](#)

Electrical & Electronics Engineer specializing in **Automotive Power Electronics (12V / 24V / 48V)**, **Embedded Firmware (ANSI C / Q15 Fixed-Point)**, and **Hardware Test & Validation Architecture**. 

Professional background includes industrial power electronics root-cause failure analysis (RCA), IGBT/MOSFET switching dynamics, and design for electromagnetic compatibility (EMC/EMI). Founder & Technical Editor at **Electro Maestro Hub**.

---

### ⚡ Core Technical Domain

| Engineering Silo | Tools, Standards & Methodologies |
| :--- | :--- |
| **Power Hardware & Validation** | WCCA (<70% Stress Derating), LTspice Simulation, 4-Layer PCB Stackup Design (KiCad 8.0), Snubber Damping (RC/RCD), Gate Drivers |
| **Embedded Firmware & Control** | ANSI C (C99), Fixed-Point Q15 Arithmetic, Space Vector PWM (SVPWM), FOC Math Engines, FreeRTOS, STM32 / ESP32 |
| **Industrial & Automotive Standards**| **CISPR 25 Class 5** (Conducted/Radiated EMI), **ISO 16750-2 / ISO 7637-2** (Transients/Cold Crank), **IEC 61000-4-2** (ESD) |
| **Bench Verification & Testing** | High-Voltage LISN Benches, Thermal Validation, Switch-Node Ringing Damping, 4-Terminal Earth Testing, DSO Loop Probing |

---

### 🚀 Featured Engineering Repositories

#### 🚗 [Automotive Power Hardware Validation Suite](https://github.com/Rocky3679/automotive-power-hardware-validation)
*Master open-source hardware validation suite covering 5 critical power electronics modules:*
* **01 System Grounding & EMC:** 4-Layer controlled-impedance stackup rules, high-frequency return path physics ($f_c \approx 100\,\text{kHz}$), and chassis decoupling ($1\,\text{M}\Omega \parallel 10\,\text{nF} / 2\,\text{kV}$).
* **02 Power Semiconductors & Snubbers:** Switching transient damping, reverse recovery charge ($Q_{rr}$) extraction, and analytical RC snubber solvers.
* **03 Gate Drivers:** Parasitic $dV/dt$ false turn-on suppression, Active Miller Clamping (AMC), and isolated bootstrap networks.
* **04 DC-DC Converters:** Cold-crank ride-through ($3.2\,\text{V}$) synchronous buck and SEPIC architectures.
* **05 Motor Inverters & SVPWM:** Production-grade ANSI C fixed-point Space Vector PWM sector generation engine.

#### 🔋 [5kW Photovoltaic-to-EV Fast Charging Power Stage](https://github.com/Rocky3679)
* Comprehensive LTspice electrical modeling and worst-case circuit derating (WCCA) for high-efficiency DC-DC conversion.
* Component thermal stress modeling and inductor volt-second balancing across extreme automotive ambient profiles ($-40^\circ\text{C}$ to $+105^\circ\text{C}$).

#### 🧠 [UnitySync: Dual-Core Edge Framework for Power Factor & Grid Demand](https://github.com/Rocky3679)
* Dual-core embedded architecture executing concurrent real-time sampling and power factor correction control loops.
* Deterministic inter-core communications with zero cycle-slipping under peak inductive load transients.

---

### 📑 Technical Publications & Engineering Standards
I publish rigorous engineering reference matrices, mathematical derivations, and pre-tapeout checklists at **[Electro Maestro Hub](https://electromaestrohub.blogspot.com/)**:
* **Doc ID: EMH-HW-CKL-001** · *PCB Grounding & EMC Mitigation Checklist (CISPR 25 / ISO 16750-2)*
* **Doc ID: EMH-PE-CAL-002** · *Diode Reverse Recovery ($t_{rr}$) & Snubber Damping Solver*
* **Master Register:** Verified tracking across all deliverables via our formal *Engineering Document Release Register (EDRR)*.

---

### 📬 Direct Engineering Contact
* **Email:** janakiraman3679@gmail.com
* **GitHub Issues:** Open a discussion on the [Validation Suite](https://github.com/Rocky3679/automotive-power-hardware-validation/issues) for errata or design reviews.
