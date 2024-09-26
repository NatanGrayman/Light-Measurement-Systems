# Light Measurement System Project

## Project Overview
The Light Measurement System Project is designed to enhance safety and visibility on a jungle gym located in a park in Johannesburg, South Africa. This system automatically activates additional lighting when natural illumination is insufficient, ensuring the play area remains safely lit during periods of low light. This enhances safety for children using the jungle gym.

## Project Components
- **PIN-Photodiode Sensor**: Measures light levels and controls the lighting system.
- **Transimpedance Amplifier**: Converts photodiode current into a measurable voltage.
- **Low-Pass Filter**: Reduces high-frequency noise for more accurate measurements.
- **ATmega328P Microcontroller**: Handles sensor data processing and system controls.
- **LCD Display**: Offers a real-time display of light levels and system status.

## Part 1: Initial Design and High-Level Solution
### Introduction and Design Requirements
The initial part of the project focuses on the high-level design and specification of the system to address the environmental conditions of Johannesburg. Key aspects such as the visible light spectrum (380-700 nm), system responsiveness, and accuracy were considered.

### Proposed High-Level Solution
The proposed solution in part one includes:
- **Signal Conditioning**: Handled by a transimpedance amplifier for current-to-voltage conversion.
- **Signal Processing**: A low-pass filter ensures the fidelity of the signal by attenuating noise.

Refer to the **High-Level Diagram** and **Design Overview** in Figure 1 of the [`Measurement Systems Project Report 1`](Measurements_Project_Report_1_2344104.pdf).

### Implementation on Jungle Gym
Design modifications to the jungle gym ensure no interference from children and optimal exposure to light. Features like a flat roof for equipment and inclined surfaces for water runoff were implemented.

For visuals, see the **Annotated Diagram** of the jungle gym setup in Figure 1 and **CAD Schematic** in Figure 7 of [`Measurement Systems Project Report 1`](Measurements_Project_Report_1_2344104.pdf).

## Part 2: Detailed Design and Performance Evaluation
### Detailed System Design
Part two delves deeper into the electronic design, featuring detailed circuitry and microcontroller logic to ensure precise measurement and control:
- **Photodiode Characteristics**: Detailed modeling captures the required light intensity.
- **Microcontroller Logic**: Manages complex signal processing and control algorithms.

Check the **Logic Flowchart** and **Complete Annotated Circuit Diagram** in Figure 2 and Figure 4 of the [`Measurement Systems Project Part 2`](2344104_Part_2_Measurements_Project_.pdf).

### Performance Evaluation
The system's performance was rigorously evaluated through simulations and empirical testing:
- **Transfer Function and Bode Plot**: MATLAB simulations validate the dynamic response and ensure adherence to design specifications.

Refer to the **Bode Plot** in Figure 3 of the [`Measurement Systems Project Part 2`](2344104_Part_2_Measurements_Project_.pdf).

## Conclusion
This project effectively demonstrates the application of advanced measurement and control techniques to enhance child safety in public play areas. The sequential design process, from initial conception to detailed implementation, ensures that the system meets the specific needs of its intended environment and operational demands.
