# CadenceProject
Comparative Study of 16-bit Ripple Carry Adder and Weinberger Adder Architectures in Digital Circuit Design 

https://drive.google.com/file/d/1EBO96JjRyy02wX6FjRVfSitM62dEj8g0/view?usp=sharing

---

# 📘 Comparative Study of 16-bit Ripple Carry Adder and Weinberger Adder Architectures

This repository contains the **design, simulation, and comparative analysis** of 16-bit Ripple Carry Adder (RCA) and 16-bit Weinberger Adder using **Cadence Virtuoso** with **GPDK 180 nm CMOS technology**.  
The project includes schematics, logic diagrams, waveforms, simulation graphs, truth tables, and the complete project report.

---

## 🔍 Project Overview

Addition is one of the most fundamental operations in digital systems.  
This project compares two adder architectures:

- **Ripple Carry Adder (RCA):** simple and area-efficient but slow due to sequential carry propagation  
- **Weinberger Adder:** faster design using generate/propagate signals and parallel carry computation  

Both adders were modeled, simulated, and verified using Cadence tools.

---

## 🎯 Objectives

- Design and implement 16-bit RCA and Weinberger adders  
- Create full custom schematic and symbol designs  
- Simulate waveforms and verify correctness  
- Extract delay and power metrics using transient simulation  
- Compare both architectures for speed, power, and scalability

---

## 🛠️ Tools & Technology

| Component | Details |
|----------|---------|
| **EDA Tool** | Cadence Virtuoso |
| **Technology Node** | GPDK 180 nm |
| **Supply Voltage** | 1.8 V |
| **Analysis Type** | Transient Simulation |
| **Temperature** | 27°C |
| **Simulation Library** | gpdk180 |

---

## 📐 Architecture Summary

### 🔹 Ripple Carry Adder (RCA)
- Built using 16 cascaded full adders  
- Carry propagates sequentially  
- Pros: simple, low area  
- Cons: high delay for large bit-widths  

### 🔹 Weinberger Adder
- Uses generate (G) and propagate (P) signals  
- Parallel carry computation  
- Lower delay and better scalability  
- Suitable for high-speed arithmetic in DSPs and processors  

---

## 📊 Results Summary

| Metric | RCA | Weinberger |
|--------|------|------------|
| **Minimum Delay** | 1.672 ns | 121.6 ps |
| **Maximum Delay** | 25.25 ns | 251.7 ps |
| **Power Consumption** | 13.35 µW | 66.25 µW |

### ✔️ Key Findings
- Weinberger Adder delivers **10–20× lower delay**  
- RCA is area-efficient but slower  
- Weinberger is ideal for **high-speed, low-latency VLSI applications**  

---

## 📷 Included Outputs

- Full custom schematics  
- Output waveforms for all input combinations  
- Delay vs. Time plots  
- Power graphs  
- Truth table verification screenshots  
- Final project documentation  

---

## 📝 Conclusion

The comparative analysis demonstrates:

- **RCA** → simple, low-power, but high delay  
- **Weinberger** → significantly faster due to parallel carry calculation  

Therefore, **Weinberger Adder** is superior for modern high-speed digital systems, DSP applications, and low-latency arithmetic units.

---

## 👩‍💻 Contributors

- **Bojja Divya**
- **Srinithi R.M**  
- **Bhavatarini M**   
- **Geetha Sri P**  
(*SENSE, VIT Chennai*)

---




