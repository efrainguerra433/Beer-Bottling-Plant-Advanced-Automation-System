# Control Strategy

## Overall Strategy
The M340 PLC acts as the master controller, coordinating the complete
bottling process.

The control logic is organized as a sequence of states representing each
stage of the bottling line.

## Process Sequencing
- Bottle positioning
- Filling
- Conveying
- Robot-assisted handling

Each stage includes interlocks and safety conditions.

## Robot Integration
The robotic arm executes predefined routines. The PLC sends execution
commands via TCP/IP based on the current process state.

## Simulation Considerations
Since the system was simulated:
- Sensors were emulated in SCADA
- Actuator feedback was logically generated
- Timing and state validation were handled in the PLC
