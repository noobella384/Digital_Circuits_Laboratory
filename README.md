# Digital Circuits Laboratory (EE 214) – IIT Bombay

## Project Overview
This repository showcases my work and learning outcomes from the Digital Circuits Laboratory (EE 214) course at IIT Bombay. The course served as a practical extension to the theoretical knowledge acquired in Digital Systems (EE 224), focusing on the design, simulation, and testing of digital circuits. Through a series of lab tasks, I gained hands-on experience in implementing various digital systems, enhancing my proficiency in digital design and analysis.

## Workflow and Lab Tasks Overview

### Workflow
1. **Understanding and Pen-Paper Design**: Analyze the task requirements and create the initial design using theoretical principles.
2. **Writing Code and Importing Previously Made Modules**: Develop the system using HDL code, reusing previously created modules for efficiency and consistency.
3. **Testing Using Software (ModelSim Altera)**: Simulate the design using ModelSim Altera to verify functionality and ensure it meets the design specifications.
4. **Using ScanChain for Hardware Testing (where applicable)**: Implement ScanChain for fault detection and testing in hardware, ensuring design correctness at the physical level.
5. **Implementation on FPGA XEN 10 Board**: Transfer the design onto the FPGA XEN 10 board for real-world testing and verification, bridging the gap between simulation and actual hardware performance.

### Lab Tasks Overview

| Task No. | Task Name                           | Description                                                                                                                                         |
|----------|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| 1        | Basic Logic Gates                   | Designed and simulated basic logic gates (AND, OR, NOT) and their combinations using VHDL, reinforcing foundational digital design concepts.        |
| 2        | 4-bit Adder Subtractor              | Implemented a 4-bit adder-subtractor using basic logic gates and K-map techniques for efficient design and optimization.                             |
| 3        | Encoders                            | Designed binary and priority encoders using basic logic gates and VHDL, focusing on optimizing the encoding process for various input cases.         |
| 4        | Muxes using Logic Gates            | Constructed multiplexers using logic gates and VHDL, mapped output based on select pins, and ensured proper functionality through simulation tests.  |
| 5        | Majority Circuit using Logic Gates | Designed a majority circuit using logic gates, ensuring correct output for multiple input cases, validated by simulation.                             |
| 6        | Universal Rotator using Mux        | Developed a universal rotator using multiplexers for rotation and shifting operations, analyzing delays and optimizing for performance.               |
| 7        | BCD Adder                           | Designed a BCD adder with VHDL, using modular design and validating carry generation and decimal correction through thorough testbenches.           |
| 8        | Arithmetic Logic Unit (ALU)        | Implemented an ALU using VHDL, integrating arithmetic and logical operations with structural modeling and verifying functionality via test cases.     |
| 9        | Sequence Generator                 | Designed a sequence generator using shift registers and control logic, validating its operation through extensive simulation tests.                  |
| 10       | String Detector Mealy Machine      | Modeled a Mealy machine for string detection in VHDL, using state diagrams for design and validating functionality via testbenches.                   |
| 11       | Clock Divider                      | Implemented a clock divider using flip-flops, achieving frequency division through sequential logic and testing it with simulation.                   |
| 12       | Traffic Signal Controller          | Developed a traffic signal controller using finite state machine principles, testing transitions and timing through exhaustive simulation cases.     |

## Repository Structure

This section contains hyperlinks to the problem statements, code, and reports for each lab task.

| Task No. | Problem Statement | Code | Report |
|----------|-------------------|------|--------|
| 1        | [LAB1 Basic logic gates.pdf](./LAB1%20Basic%20logic%20gates.pdf) | [Code](./Code_files/LAB1%20Basic%20logic%20gates.zip) | [Report](./Lab_Reports/LAB1%20Basic%20logic%20gates.pdf) |
| 2        | [LAB2 4bit Adder Subtractor.pdf](./LAB2%204bit%20Adder%20Subtractor.pdf) | [Code](./Code_files/LAB2%204bit%20Adder%20Subtractor.zip) | [Report](./Lab_Reports/LAB2%204bit%20Adder%20Subtractor.pdf) |
| 3        | [LAB3 Encoders.pdf](./LAB3%20Encoders.pdf) | [Code](./Code_files/LAB3%20Encoders.zip) | [Report](./Lab_Reports/LAB3%20Encoders.pdf) |
| 4        | [LAB4 Muxes using logic gates.pdf](./LAB4%20Muxes%20using%20logic%20gates.pdf) | [Code](./Code_files/LAB4%20Muxes%20using%20logic%20gates.zip) | [Report](./Lab_Reports/LAB4%20Muxes%20using%20logic%20gates.pdf) |
| 5        | [LAB5 Majority Circuit using Logic Gates.pdf](./LAB5%20Majority%20Circuit%20using%20Logic%20Gates.pdf) | [Code](./Code_files/LAB5%20Majority%20Circuit%20using%20Logic%20Gates.zip) | [Report](./Lab_Reports/LAB5%20Majority%20Circuit%20using%20Logic%20Gates.pdf) |
| 6        | [LAB6 Universal Rotator using Mux.pdf](./LAB6%20Universal%20Rotator%20using%20Mux.pdf) | [Code](./Code_files/LAB6%20Universal%20Rotator%20using%20Mux.zip) | [Report](./Lab_Reports/LAB6%20Universal%20Rotator%20using%20Mux.pdf) |
| 7        | [LAB7 BCD Adder.pdf](./LAB7%20BCD%20Adder.pdf) | [Code](./Code_files/LAB7%20BCD%20Adder.zip) | [Report](./Lab_Reports/LAB7%20BCD%20Adder.pdf) |
| 8        | [LAB8 Arithmetic Logic Unit.pdf](./LAB8%20Arithmetic%20Logic%20Unit.pdf) | [Code](./Code_files/LAB8%20Arithmetic%20Logic%20Unit.zip) | [Report](./Lab_Reports/LAB8%20Arithmetic%20Logic%20Unit.pdf) |
| 9        | [LAB9 Sequence Generator.pdf](./LAB9%20Sequence%20Generator.pdf) | [Code](./Code_files/LAB9%20Sequence%20Generator.zip) | [Report](./Lab_Reports/LAB9%20Sequence%20Generator.pdf) |
| 10       | [LAB10 String Detector Mealy Machine.pdf](./LAB10%20String%20Detector%20Mealy%20Machine.pdf) | [Code](./Code_files/LAB10%20String%20Detector%20Mealy%20Machine.zip) | [Report](./Lab_Reports/LAB10%20String%20Detector%20Mealy%20Machine.pdf) |
| 11       | [LAB11 Clock Divider.pdf](./LAB11%20Clock%20Divider.pdf) | [Code](./Code_files/LAB11%20Clock%20Divider.zip) | [Report](./Lab_Reports/LAB11%20Clock%20Divider.pdf) |
| 12       | [LAB12 Traffic Signal Controller.pdf](./LAB12%20Traffic%20Signal%20Controller.pdf) | [Code](./Code_files/LAB12%20Traffic%20Signal%20Controller.zip) | [Report](./Lab_Reports/LAB12%20Traffic%20Signal%20Controller.pdf) |

## Hardware Implementation and Advanced Testing
For several lab tasks, I implemented the designs on hardware, specifically using the **FPGA XEN 10 board**. This provided a practical testbed for validating my designs beyond simulation, ensuring that they work under real-world conditions.

In addition, I applied **ScanChain** techniques for hardware testing, enabling fault detection and simplifying debugging processes. I also utilized **JTAG** for further testing and debugging of hardware implementations, enhancing the overall reliability of the designs.
