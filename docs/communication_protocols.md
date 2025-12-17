# Communication Protocols

This project integrates multiple industrial communication protocols to
simulate a realistic automation environment.

## TCP/IP
Used for communication between:
- PLC M340 and SCADA (process monitoring and control)
- PLC M340 and the robotic arm (command-based execution)

## Modbus RTU
Used to communicate between:
- PLC M340 and an industrial gateway
- Gateway and Allen-Bradley Micro850 PLC

This allowed distributed control of auxiliary processes.

## CANopen
Used for real-time communication between:
- PLC M340 and a Variable Frequency Drive (VFD)

CANopen was selected for its reliability and deterministic behavior in
drive control applications.
