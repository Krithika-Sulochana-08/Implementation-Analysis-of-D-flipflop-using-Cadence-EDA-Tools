# Ex No: 03 - Implementation & Analysis of CMOS D Latch using Cadence EDA Tools

## Aim
The aim is to design, implement, and analyze a D LATCH using Cadence EDA tools, ensuring accurate sequential logic operation through waveform analysis and performance verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the D Latch design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Design the D Latch circuit with key components such as clock signal input, D input, and Q output.
- Implement feedback connections to enable sequential behavior.
- Connect appropriate voltage sources for logic control and supply.

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe timing behavior and output transitions.
- Set simulation parameters such as clock frequency, voltage levels, and delay conditions.
- Use Spectre simulator to perform transient analysis and functional verification.

### 4. Waveform Analysis
- Observe the output waveform to confirm correct D Latch functionality.
- Ensure that the Q output follows the D input on the rising edge of the clock signal.

## Circuit Diagram

### 1. Schematic of D Flip-Flop
![EXP 3 SCHEMATIC](https://github.com/user-attachments/assets/3701067c-0798-4d5d-9626-ef65e8c3c3c9)


### 2. Transient Response Setup
*
![EXP 3 TRANS ](https://github.com/user-attachments/assets/b725cebb-ab1b-4b7f-9db1-c1a382fa4d44) 
![EXP 3 ANALYSES](https://github.com/user-attachments/assets/b04db80a-4747-4e4f-a90b-b9272b71a037)

## Output

### 1. Transient Analysis Output
![EXP 3 OUTPUT ](https://github.com/user-attachments/assets/eab831c5-4cce-45f9-b0c3-1a1b5418deaf)


## Results
1. Successfully designed the D Latch schematic using Cadence EDA tools.
2. The simulation results verified the correct sequential logic behavior, ensuring that the Q output correctly follows the D input on the rising edge of the clock.
3. The waveform analysis demonstrated the expected timing behavior and performance of the D Latch circuit.
