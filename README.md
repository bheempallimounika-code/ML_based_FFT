# Implementation of ML-Based FFT Architecture (FNO) targeting FPGA

## Project Overview
This project presents a simulation-based hardware architecture accelerator for Fast Fourier Transform (FFT) blocks within Fourier Neural Operators (FNO) for machine learning workflows.

## Design Methodology
1. **Algorithmic Modeling:** Implemented the baseline FNO math in PyTorch to extract fixed-point test vectors.
2. **High-Level Synthesis:** Translated the quantized algorithms into synthesizable hardware architectures using AMD Vitis HLS.
3. **Verification:** Validated the generated Verilog RTL via behavioral simulations and C/RTL co-simulations in AMD Vivado.

## Toolchain & Skillset
* **Languages:** Python, PyTorch, C++, Verilog HDL, SystemVerilog
* **EDA Tools:** AMD Vitis HLS, AMD Vivado Design Suite, PyCharm
