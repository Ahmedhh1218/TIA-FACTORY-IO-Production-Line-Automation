# TIA-FACTORY-IO-Production-Line-Automation

This project implements a fully functioning production line simulation using Factory IO and Siemens TIA Portal. The production line automates tasks such as machining, sorting, and assembly, starting from raw materials to finished products. The system is controlled by a SIMATIC S7-1200 PLC and includes a custom HMI interface for monitoring and supervisory control. Field-related alarms are utilized for fault detection, ensuring smooth and efficient operation.

## Project Overview

### Production Line Design and Simulation

1. **Production Line Simulation**:
   - Design a complete production line on Factory IO, incorporating tasks such as machining, sorting, and assembly.
   - Use Siemens TIA Portal to control the simulated production line, integrating all studied functions for efficient operation.

2. **Components and Operations**:
   - **Feeding Unit**: Generates random raw materials (green or blue) and places them on the output conveyor using a pick & place robot.
   - **Machining Center**: Manufactures lids and bases from raw materials using a CNC machine. Lids take 6 seconds, and bases take 3 seconds to produce.
   - **Assembly Unit**: Assembles lids and bases into finished products, ensuring proper alignment and fit.

3. **Process Flow**:
   - Generate random raw materials in the feeding station.
   - Move materials to the machining center using the pick & place robot.
   - Fabricate products (lids and bases) in the machining center.
   - Assemble products in the assembly unit.
   - Sort finished products by color and move them to designated storage areas.
   - Track the number of finished products of each color and stop the production line when the desired count is reached.

### HMI Development

- Design an HMI module in TIA Portal to monitor and visualize the various states of the production line.
- Provide supervisory control commands through the HMI.
- Indicate the state of each station and display production statistics.

### Fault Detection and Alarms

- Implement field-related alarms for detecting hardware and sequence faults.
- Ensure efficient operation by incorporating robust fault detection mechanisms across the feeding unit, machining center, and assembly unit.

### Deliverables

1. **Software Code**: TIA Portal code for controlling the production line.
2. **HMI Interface**: Custom HMI interface developed in TIA Portal for monitoring and control.
3. **Simulation**: SIL/HIL simulation of the automated production line.
4. **Technical Report**: Detailed report highlighting results, system performance, and contributions of each team member.

### Usage

1. **Open the Project Files**:
   - Use Factory IO to open the `.factoryio` file for the production line simulation.
   - Use Siemens TIA Portal to open the `.ap17` file for PLC programming and HMI development.

2. **Run the Simulation**:
   - Start the simulation in Factory IO.
   - Monitor and control the production line using the HMI interface developed in TIA Portal.

3. **Fault Detection**:
   - Observe field-related alarms and respond to any hardware or sequence faults detected during the simulation.

## Conclusion

This project demonstrates the integration of industrial automation technologies to create a simulated production line. By leveraging Factory IO and Siemens TIA Portal, the project showcases the automation of complex tasks and the implementation of advanced control systems for efficient and reliable production operations.
