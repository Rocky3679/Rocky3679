# Janaki Raman K

**Power Electronics Systems & Embedded Hardware Validation Engineer**  
📍 Chennai, India · [LinkedIn](https://www.linkedin.com/in/janaki-ramank) · [Electro Maestro Hub](https://electromaestrohub.blogspot.com/)

---

### ⚡ Engineering Summary
Electrical & Electronics Engineer specializing in **Power Electronics Stage Design, Embedded Firmware (C/C++), and Hardware Verification & Validation (V&V)**. 

Currently working at **ESAB India Limited**, diagnosing 400V 3-phase industrial power sources, IGBT bridge switching dynamics, motor control panels, and electromagnetic interference (EMI) root causes. My focus centers on designing high-reliability power stages and low-level firmware compliant with automotive standards (**ISO 16750-2, CISPR 25 Class 5, and IEC 61000-4-2**).

---

### 🛠️ Core Technical Competencies

- **Power Electronics & Magnetics:** 
  - 12V / 24V / 48V Automotive Buck, Boost, and SEPIC Topologies.
  - Hard-switched half-bridge inverter stages, parasitic ringing extraction, and RC/RCD snubber damping.
  - Worst-Case Circuit Analysis (WCCA), component derating, and thermal impedance analysis ($Z_{\theta\text{JA}}$).
- **Embedded Systems & Motor Control:** 
  - ANSI C (C99), Q15 Fixed-Point Arithmetic, State Machines, Hardware Abstraction Layers (HAL).
  - Space Vector PWM (SVPWM) generation, Field-Oriented Control (FOC) coordinate transformations (Clarke/Park).
  - STM32, ESP32, Bare-metal microcontroller interfacing, CAN-FD, SPI, I2C.
- **Hardware Validation & EMC Standards:** 
  - CISPR 25 Class 5 (Conducted & Radiated Emissions), ISO 7637-2 / ISO 16750-2 (Transients/Cold-Crank).
  - 4-Layer PCB return path modeling, RF chassis decoupling, and IEC 61000-4-2 ESD protection.
- **EDA & Simulation Tools:** 
  - KiCad 8.0, LTspice, MATLAB / Simulink, Oscilloscope Ground-Spring Probing, Logic Analyzers.

---

### 🚀 Flagship Engineering Repositories

#### 1. [Automotive Power Hardware Validation Suite](https://github.com/Rocky3679/automotive-power-hardware-validation)
*An open-source, multi-module hardware validation architecture for automotive sub-systems (12V / 24V / 48V).*
- **01 · System Grounding & EMC:** 4-layer stackup design rules, high-frequency return path modeling, and chassis decoupling ($1\,\text{M}\Omega \parallel 10\,\text{nF} / 2\,\text{kV}$).
- **02 · Power Semiconductors & Snubbers:** Analytical RC snubber solvers and diode reverse recovery ($t_{rr}$) damping testbenches in LTspice.
- **03 · Gate Drivers:** Isolated bridge drivers, Active Miller Clamping (AMC), and $-4\text{V}$ turn-off bias networks.
- **04 · DC-DC Converters:** Cold-crank ride-through ($3.2\text{V}$), load dump protection, and closed-loop Type-III compensation.
- **05 · Motor Inverters:** ANSI C Q15 Space Vector PWM (SVPWM) firmware engine and dead-time volt-second compensation.

#### 2. [5kW Photovoltaic-to-EV DC-DC Charging Stage](https://github.com/Rocky3679)
*High-power DC-DC converter modeling with strict component stress derating.*
- Complete LTspice time-domain transient simulation with component stress derating ($<70\%$ thermal/voltage margin).
- Inductor volt-microsecond saturation analysis and high-frequency switching hot-loop minimization.

#### 3. [UnitySync: Dual-Core Edge Computing Framework](https://github.com/Rocky3679)
*Real-time power factor correction (PFC) and adaptive load demand management.*
- Dual-core edge processing separating high-speed sensor acquisition from communication stacks.
- Research submitted to *IEEE Access* for peer review.

---

### 📑 Technical Publications & Engineering Standards
I author technical masterclasses and document control standards via **Electro Maestro Hub**:
- **Doc ID: EMH-HW-CKL-001 · Rev 1.0:** *PCB Grounding, Return Paths & EMC Mitigation Checklist (CISPR 25 / ISO 16750-2)*
- **Doc ID: EMH-PE-CAL-002 · Rev 1.0:** *Power Diode Reverse Recovery & Snubber Damping Solver*

---

📫 **Get in Touch:** [janakiraman3679@gmail.com](mailto:janakiraman3679@gmail.com) · [LinkedIn Profile](https://www.linkedin.com/in/janaki-ramank)
