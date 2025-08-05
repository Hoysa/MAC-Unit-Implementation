# MAC-Unit-Implementation using vedic mathematics 

##  Overview

This project implements a **Multiply-Accumulate (MAC) Unit** using the **Urdhva Tiryagbhyam Sutra** from Vedic Mathematics. The design achieves **faster arithmetic computation**, **lower power consumption**, and **reduced hardware utilization**, making it ideal for **DSP**, **ML**, and **embedded system applications**.

By leveraging parallelism inherent in the Vedic multiplication technique, this design significantly reduces delay, power consumption, and hardware resource utilization when compared to traditional approaches like the Booth multiplier.

---

##  Technologies Used

- **HDL Language**: Verilog
- **Simulation Tools**: ModelSim, Xilinx Vivado, ISE
- **Hardware Platform**: Xilinx Spartan-7 FPGA
- **Mathematical Model**: Urdhva Tiryagbhyam Sutra (Vedic Mathematics)
- **Design Domains**: Digital Design, Arithmetic Circuits, VLSI, DSP

---

## Key Features

- High-speed MAC unit using parallel Vedic multiplication
- Signed number support using 2’s complement
- Zero DSP slices used – fully logic-based
- Reduced propagation delay and power consumption
- Verified via simulation and hardware synthesis

---

## Architecture

### ➤ Working Principle
1. **Multiplication** using Urdhva Tiryagbhyam logic.
2. **Accumulation** of result with prior sum.
3. **Final Output** after N clock cycles.

### ➤ Block Diagram
![Block Diagram](https://github.com/user-attachments/assets/e0b9e0ba-eb6a-459b-bdd5-cb189d8a3d1c)

---

## Performance Comparison

| Metric                  | Booth MAC        | Vedic MAC         | Improvement       |
|-------------------------|------------------|-------------------|-------------------|
| **Delay**               | 20.5 ns          | 6.999 ns          | ~66% faster       |
| **Total Power**         | 30 W             | 21.506 W          | ~28% lower        |
| **LUTs Used**           | 1024             | 32                | ~97% fewer        |
| **DSP Slices Used**     | 16               | 0                 | Fully logic-based |
| **Registers Used**      | ~500             | 0                 | Reduced area      |
| **IOB Utilization**     | ~30%             | 24%               | Slightly lower    |

### ➤ Waveform Snapshot
![Waveform](https://github.com/user-attachments/assets/52d0bbb4-3e70-4720-8238-350df59887d5)

### ➤ FPGA Utilization
![FPGA Utilization](https://github.com/user-attachments/assets/796a3885-7033-4824-a79e-6528dbfe90b0)

---

## Vedic Math: Urdhva Tiryagbhyam

The **Urdhva Tiryagbhyam Sutra** ("Vertically and Crosswise") allows parallel partial product generation and minimized carry propagation, which makes it highly suitable for hardware acceleration of multiplication.

### Benefits:
- Reduced delay due to parallelism
- Simplified logic and fewer gates
- Scalability to higher-bit multipliers

---

## Results

-  **~66% speed improvement** over Booth MAC
-  **~30% power savings**
-  **Zero DSP blocks and minimal LUT usage**
-  **FPGA-ready Verilog implementation**

---

## Applications

- Digital Signal Processing (DSP)
- Image and Audio Processing
- Machine Learning Accelerators
- Edge AI and Embedded Devices
- Low-power IoT Systems

---

## Future Scope

- Floating-point Vedic MAC design
- Pipelined architecture for throughput boost
- Integration with convolution engines
- ASIC-level implementation and benchmarking

---
**Name:** Hoysaleshwari U

**Degree:** B.E. in Electronics & Communication Engineering 

**Institution:** SJBIT

**Email:** hoysaleshwariu@gmail.com

**LinkedIn:** https://linkedin.com/in/hoysaleshwariu


