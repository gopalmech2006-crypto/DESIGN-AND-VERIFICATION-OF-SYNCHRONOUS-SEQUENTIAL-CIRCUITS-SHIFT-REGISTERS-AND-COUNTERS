# README – Design and Verification of Synchronous Sequential Circuits: Shift Registers and Counters

## Aim

To design, simulate, and verify synchronous sequential circuits such as Shift Registers and Counters using HDL and observe their functional behavior through simulation waveforms.

---

## Theory

Synchronous sequential circuits change their state only at the active edge of a clock signal. Shift registers are used for data storage and transfer, while counters are used for counting clock pulses in a predefined sequence.

### Shift Registers

A shift register consists of a series of flip-flops connected in cascade. Data is shifted from one flip-flop to another on each clock pulse.

**Types:**

* Serial-In Serial-Out (SISO)
* Serial-In Parallel-Out (SIPO)
* Parallel-In Serial-Out (PISO)
* Parallel-In Parallel-Out (PIPO)

### Counters

Counters are sequential circuits that count clock pulses.

**Types:**

* Up Counter
* Down Counter
* Up/Down Counter
* Ring Counter
* Johnson Counter

---

## Software/Hardware Requirements

* HDL Simulator (ModelSim/EDA Playground/Xilinx Vivado)
* Verilog/VHDL
* Computer System

---

## Procedure

1. Write the HDL code for the required shift register or counter.
2. Create a testbench to provide clock and input signals.
3. Compile the design and testbench.
4. Run the simulation.
5. Observe the waveform and verify the output sequence.
6. Compare the obtained results with the expected results.

---

## Observation

### Shift Register Observation

| Clock Pulse | Input Data | Output |
| ----------- | ---------- | ------ |
| 1           | 1          | 0001   |
| 2           | 0          | 0010   |
| 3           | 1          | 0101   |
| 4           | 1          | 1011   |

**Observation:**

* Data shifts one position for every clock pulse.
* Output changes only at the active clock edge.
* The shift operation matches the expected sequence.

### Counter Observation

| Clock Pulse | Counter Output |
| ----------- | -------------- |
| 0           | 0000           |
| 1           | 0001           |
| 2           | 0010           |
| 3           | 0011           |
| 4           | 0100           |
| 5           | 0101           |

**Observation:**

* Counter increments by one for every clock pulse.
* State transitions occur synchronously with the clock.
* The counting sequence follows the designed logic.

---

## Result

The synchronous sequential circuits (Shift Registers and Counters) were successfully designed, simulated, and verified. The observed outputs matched the expected behavior, confirming the correct operation of the circuits.

---



