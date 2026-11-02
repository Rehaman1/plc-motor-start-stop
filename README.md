# plc-motor-start-stop
PLC Ladder Logic motor control, simulation and functional testing
# PLC Motor Start/Stop Control

## Project Overview
This is my first PLC programming project, developed to practise basic motor control using Ladder Logic.

## Objectives
- Start a motor using a START pushbutton.
- Stop the motor using a STOP pushbutton.
- Implement a seal-in (holding) circuit.
- Understand motor control logic and fault conditions.

## Components and Signals
| Tag | Description |
|---|---|
| `Start_PB` | Start pushbutton input |
| `Stop_OK` | Stop circuit healthy signal |
| `Overload_OK` | Overload healthy signal |
| `Motor_Run` | Motor contactor command output |

## Operating Sequence
1. Press START to energise the motor output.
2. Release START; the holding circuit maintains the output.
3. Press STOP to de-energise the output.
4. Simulate an overload trip and verify that the output switches off, if implemented.

## Testing
- [ ] Initial state: motor OFF
- [ ] Press START: motor ON
- [ ] Release START: motor remains ON
- [ ] Press STOP: motor OFF
- [ ] Overload trip: motor OFF, if implemented

## Tools Used
- PLC Ladder Logic simulator: [Add your simulator name]
- Programming language: Ladder Diagram (LD)

## Project Status
Completed beginner learning project / simulation.

## Safety Note
This is an educational project. Real motor installations require suitable electrical protection, correctly designed control circuits and qualified commissioning.

---
**Author:** Rahaman Sheikh  
**Portfolio focus:** PLC Programming | Electrical Commissioning | Industrial Automation
