# Experiment 4

## Implementation of Addressing Modes using Shift and Rotate Operations in Logisim

---

## Objective

The objective of this experiment is to design and implement different addressing modes using shift and rotate operations in Logisim Evolution. The aim is to understand bit manipulation techniques, data movement, and the role of control signals in selecting operations.

---

## Background Study

Addressing modes define how data is accessed and manipulated in digital systems. Bit manipulation operations such as shifting and rotating are fundamental in implementing these modes.

Shift operations move bits either to the left or right. Logical shifts introduce zeros, while arithmetic shifts preserve the sign bit. Rotate operations move bits circularly within the register, and carry-based rotations include an external carry bit.

Registers are used to store data, and multiplexers are used to select the desired operation among multiple available operations.

---

## Experiment Description

In this experiment, an 8-bit register was used to store input data. The stored data was then passed to multiple combinational logic circuits that perform different operations.

The following operations were implemented:

- Arithmetic Shift Left (ASL)  
- Logical Shift Right (LSR)  
- Logical Shift Left (LSL)  
- Arithmetic Shift Right (ASR)  
- Rotate Right (RR)  
- Rotate Left (RL)  
- Rotate Right with Carry (RRC)  
- Rotate Left with Carry (RLC)  

Each operation was designed using logic gates and wiring connections.

All operation outputs were connected to a multiplexer. The multiplexer selects one operation based on control inputs. The selected output was then displayed as the final result.

A clock signal was used to control the register, ensuring proper storage and updating of input data.

---

## Circuit Diagram

(Uploaded along with the file)

---

## Observations

1. The register correctly stored input data on the application of the clock signal.  
2. All shift operations performed accurate left and right bit movements.  
3. Logical shifts introduced zeros, while arithmetic shifts preserved the sign bit.  
4. Rotate operations correctly cycled bits within the register.  
5. Carry-based rotations (RRC and RLC) correctly handled the carry bit during operation.  
6. The multiplexer successfully selected the desired operation based on control inputs.  
7. The output matched the expected results for all tested cases.  

---

## Result

All addressing modes based on shift and rotate operations were successfully implemented using a register, combinational logic, and a multiplexer in Logisim. The circuit produced correct outputs for all selected operations.

---

## Conclusion

This experiment helped in understanding how different addressing modes can be implemented using bit manipulation techniques. It demonstrated the working of shift and rotate operations and highlighted the importance of registers and multiplexers in digital systems. The experiment also showed how multiple operations can be performed in parallel and selected using control signals.
