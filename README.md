

# 8-Bit ALU Design Using Verilog HDL

## 📌 Project Overview

This project implements an 8-bit Arithmetic Logic Unit (ALU) using Verilog Hardware Description Language (HDL). An ALU is a fundamental component of a processor that performs arithmetic and logical operations on binary data.

The design was simulated to observe its behavior for different input combinations.

## 🎯 Objectives

- To design an 8-bit ALU using Verilog HDL.
- To implement arithmetic and logical operations.
- To understand combinational logic design.
- To simulate the design and observe its outputs.
- To develop practical skills in digital system design and verification.

## 🛠️ Tools and Technologies

- **Hardware Description Language:** Verilog HDL
- **Simulation Tool:** [lcarus verilog 12.0]
- **Version Control:** GitHub

## ⚙️ Design Specifications

- **Data Width:** 8 bits
- **Inputs:** Two 8-bit operands and operation-select signals
- **Output:** ALU result
- **Design Type:** Digital logic design

*Note: The exact operations, control signals, and output widths depend on the implemented Verilog code.*

## 🔢 Operations

The ALU can perform the arithmetic and logical operations implemented in the design, such as:

- Addition
- Subtraction
- Bitwise AND
- Bitwise OR
- Bitwise XOR
- Other operations, if implemented

## 📂 Project Structure

```text
8-bit-ALU-Verilog/
│
├── alu.v
├── alu_tb.v
├── README.md
└── simulation/
    └── waveform.png
```

- `alu.v` — Verilog source code for the ALU.
- `alu_tb.v` — Testbench used to apply input combinations.
- `README.md` — Project documentation.
- `simulation/waveform.png` — Simulation waveform screenshot (optional).

*The filenames and folder structure above are examples. Update them to match your actual files.*

## 🧪 Simulation and Testing

The ALU was simulated using a Verilog simulation tool to observe its behavior for different input combinations.

The testbench applies input values and allows the corresponding outputs to be examined using simulation waveforms.

Further verification can include checking each supported operation, testing boundary values, and comparing actual outputs with expected results.

## 📈 Simulation Results
<img width="1184" height="341" alt="image" src="https://github.com/user-attachments/assets/dd206a38-92e2-46d3-a8c3-3b5fe400115b" />
The waveform can be used to demonstrate the relationship between the input operands, operation-select signals, and ALU output.

## 📚 Learning Outcomes

- Understanding the working principle of an ALU.
- Writing digital designs using Verilog HDL.
- Creating and using a Verilog testbench.
- Observing simulation waveforms.
- Learning how to document and maintain engineering projects using GitHub.

## 🚀 Future Improvements

- Expand testbench coverage for all supported operations.
- Add automated checks for expected outputs.
- Test boundary conditions and carry or borrow behavior where applicable.
- Explore FPGA implementation, if suitable hardware is available.

## 👩‍💻 Author

**ECE 3rd-Year Student**

This project was developed as part of my learning journey in digital electronics, Verilog HDL, and hardware design.

---
The waveform can be used to demonstrate the relationship between the input operands, operation-select signals, and ALU output.

## 📚 Learning Outcomes

- Understanding the working principle of an ALU.
- Writing digital designs using Verilog HDL.
- Creating and using a Verilog testbench.
- Observing simulation waveforms.
- Learning how to document and maintain engineering projects using GitHub.

## 🚀 Future Improvements

- Expand testbench coverage for all supported operations.
- Add automated checks for expected outputs.
- Test boundary conditions and carry or borrow behavior where applicable.
- Explore FPGA implementation, if suitable hardware is available.

## 👩‍💻 Author

**ECE 3rd-Year Student**

This project was developed as part of my learning journey in digital electronics, Verilog HDL, and hardware design.

---

⭐ If you find this project useful, feel free to explore the code and simulation results.
