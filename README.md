# Cross Traffic Management for Autonomous Vehicles
This project focuses on developing a traffic management system for autonomous vehicles at intersections. The goal is to improve traffic flow and safety by managing the vehicles' movements efficiently. The system implements a FIFO (First-In-First-Out) scheduling algorithm, ensuring that vehicles are processed in the order they arrive at the intersection.

We chose FIFO because of its simplicity and effectiveness in handling traffic at controlled intersections, especially for autonomous vehicles that require precise scheduling. The system is scheduled with FreeRTOS to ensure real-time task management and smooth operation in a multi-tasking environment.

**Key Features:

FIFO Scheduling: Ensures fair and orderly management of vehicles at the intersection based on arrival time.
Real-Time Control: FreeRTOS handles real-time scheduling for optimal traffic flow and system performance.
Autonomous Vehicle Compatibility: The system is designed to work with autonomous vehicles that can communicate and interact with traffic signals and other vehicles in real-time.
Safety and Efficiency: Prioritizes vehicle and pedestrian safety while optimizing the efficiency of the intersection.
Technologies Used:

C++ for the core logic and system control.
VHDL for hardware-level design and simulation.
FreeRTOS for real-time task management and scheduling.
This system represents a crucial step toward the future of smart cities and autonomous vehicle integration in urban traffic management.
