# NAME:Kishore s
# REGNO:24900831
# EXPNO 10:SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

# AIM:

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

# SOFTWARE REQUIRED:

Quartus prime

# THEORY

# SISO shift Register

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

# Procedure
Implementing SERIAL-IN-SERIAL-OUT-SHIFTREGISTER functions in Verilog HDL (Hardware Description Language) involves translating the simplified Boolean expressions into Verilog code to describe the behavior of digital circuits. The basic building blocks in Verilog is module. The module represent a combinational circuit. Use logical operators (&, |, ~, ^) to implement Boolean functions directly. Use built-in gate primitives for basic functions. Use University program VWF to verify the functionality of your Verilog modules. Create waveform and check outputs against expected results.
/* write all the steps invloved */

# PROGRAM
![Screenshot 2024-12-09 110512](https://github.com/user-attachments/assets/bfa0dce7-e917-4776-ab4e-d7d978c21410)


# RTL LOGIC FOR SISO Shift Register
![shift1](https://github.com/user-attachments/assets/acc8f655-27c0-43e3-8ce1-42dd9b59b43e)


# TIMING DIGRAMS FOR SISO Shift Register
![shift3](https://github.com/user-attachments/assets/2eb7cbc5-229e-45d2-b452-9af1c73cefe0)


# RESULTS
Successfully Implemented  SISO Shift Register using verilog and validating their functionality using their functional tables
