---
title: "Henoc | Engineering Portfolio"
---

# Henoc L.
### MEng Electrical & Electronic Engineering — University of Southampton

I am an Electrical and Electronic Engineering student with strong interests in embedded systems, power electronics, control, and robotics.  
This portfolio highlights the technical projects I have developed through university work, Formula Student, and personal engineering builds.

📧 **Email:** henocl205@gmail.com  
💻 **GitHub:** [github.com/hsl25](https://github.com/hsl25)

---

# Technical Skills

### Software & Tools
- KiCad, Multisim, LTSpice, Quartus Prime  
- MATLAB, STM32CubeIDE, Arduino IDE, Raspberry Pi  
- Microsoft Office (Excel, PowerPoint, Word)

### Programming
- **C / C++**
- **Python**
- **SystemVerilog**
- Embedded firmware development and debugging

### Electronics & Lab
- Oscilloscopes, multimeters, signal generators  
- Circuit prototyping, debugging, PCB schematic design  
- Serial communication + CAN interfacing

---

# Featured Engineering Projects

---

## High Voltage Battery Management System (BMS)
**Southampton University Formula Student Team**

![High Voltage BMS](assets/images/bms.jpg)

### Overview
Worked on research and development of a High Voltage Battery Management System, focusing on measurement circuitry, safety algorithms, and communication protocols required for Formula Student compliance and real-world reliability.

### Key Contributions
- Designed concepts for voltage, current, and temperature sensing circuits.
- Investigated safety requirements for charge/discharge operation.
- Worked with **Texas Instruments BQ79616** development board.
- Focused heavily on communication protocols and CAN-based interfacing between cell monitoring and system controller.

### Skills Demonstrated
**Battery safety • CAN communication • high-voltage systems • embedded monitoring**

🔗 **Repository:** *(Private / Team project)*

---

## Steering Wheel Dashboard Electronics
**Southampton University Formula Student Team**

![Formula Student Dashboard](assets/images/dashboard.jpg)

### Overview
Developed electronics for an LCD steering wheel dashboard, supporting driver telemetry and control interface.

### Key Contributions
- Integrated an LCD display into steering wheel design.
- Designed buck/boost converter schematic for stable power delivery.
- Designed touch-screen module schematic including:
  - STM32F746 microcontroller
  - RAM module integration
- Applied PCB routing practices including **RAM length matching**.

### Skills Demonstrated
**PCB schematic design • power conversion • STM32 hardware integration**

🔗 **Repository:** *(Private / Team project)*

---

## Robotic Arm (3-DOF + Claw Mechanism)
**Arduino Embedded Control Project**

![Robotic Arm](assets/images/robotic_arm.jpg)

### Overview
Designed and programmed a robotic arm with servo control and a mechanical claw mechanism, enabling manual control using potentiometer input.

### Key Contributions
- Implemented servo motor control for **3 degrees of freedom**.
- Designed a claw with gear mechanism capable of 180° motion.
- Iteratively prototyped the claw design (5 revisions) for performance improvements.
- Implemented control modes ("active/rest") using button input.
- Programmed using Arduino Uno (C/C++).

### Skills Demonstrated
**embedded control • prototyping • servo systems • iterative design**

🔗 **GitHub Repository:** [Robotic Arm Project](https://github.com/hsl25/robotic-arm)

---

## Traffic Light Controller (Digital Logic Hardware)
**Sequential Logic Circuit Design**

![Traffic Light Circuit](assets/images/traffic_light.jpg)

### Overview
Built a hardware-based traffic light controller using fundamental logic ICs and sequential logic design methods.

### Key Contributions
- Designed a complete state machine using:
  - ASM chart
  - state transition table
  - Karnaugh maps
- Implemented the circuit using:
  - 74HC08 AND gates
  - 74HC32 OR gates
  - 74HC74 D-type flip-flops
- Tested the real circuit successfully on hardware.

### Skills Demonstrated
**digital logic design • state machines • Karnaugh optimisation**

🔗 **GitHub Repository:** [Traffic Light Controller](https://github.com/hsl25/traffic-light-controller)

---

## Autonomous Rover (Year 2 Team Project)
**Software Lead — Navigation + Control**

![Autonomous Rover](assets/images/rover.jpg)

### Overview
Leading software development for an autonomous rover system using LiDAR-based navigation and embedded motor control.

### Key Contributions
- Working on LiDAR-based SLAM research and implementation.
- Developing motor control firmware and control logic.
- Creating a Bluetooth debugging app to assist testing.
- Programming with **Raspberry Pi Pico W (C++)**.

### Skills Demonstrated
**robotics • SLAM • embedded C++ • sensor integration**

🔗 **Repository:** *(In progress)*

---

## Sudoku (C++ Game + Solver)
**Command Line Application**

![Sudoku](assets/images/sudoku.jpg)

### Overview
Created a playable Sudoku game with difficulty selection and a built-in solver.

### Key Contributions
- Designed interactive terminal UI.
- Added difficulty levels with progressively harder boards.
- Implemented board validation and input logic.
- Developed a solver algorithm to solve any given Sudoku.

### Skills Demonstrated
**C++ • recursion/backtracking • algorithms • CLI applications**

🔗 **GitHub Repository:** [Sudoku Game](https://github.com/hsl25/sudoku)

---

## Engineering Toolkit (C++ Multi-Tool Application)
**Circuit Simulation + Fourier Analysis + Logic Gate Engine**

![Engineering Toolkit](assets/images/toolkit.jpg)

### Overview
Developed a modular engineering toolkit combining circuit simulation utilities, Fourier series waveform analysis, and scalable logic evaluation.

### Key Contributions
- Integrated a provided circuit simulator framework.
- Built Fourier Series waveform generator supporting:
  - sine, square, triangle, sawtooth, custom waveforms
- Developed scalable logic engine to evaluate boolean functions for n inputs.
- Implemented file-driven logic selection for complex expressions.

### Skills Demonstrated
**software architecture • mathematical modelling • scalable design**

🔗 **GitHub Repository:** [Engineering Toolkit](https://github.com/hsl25/engineering-toolkit)

---

## PWM + ADC + PID Control (ATmega164PA)
**Embedded Control Systems Project**

![PID Control](assets/images/pid.jpg)

### Overview
Designed a low-pass filter system controlled via PWM, with closed-loop PID control implemented on a microcontroller.

### Key Contributions
- Built low-pass filter circuit.
- Used ATmega164PA timer for PWM generation.
- Implemented serial interface through PuTTY for user-defined duty cycle.
- Designed and tuned PID controller to reject external disturbances.

### Skills Demonstrated
**embedded C • PID control • timers/PWM • ADC sampling**

🔗 **GitHub Repository:** [PWM ADC PID](https://github.com/hsl25/pwm-adc-pid)

---

## Wave Generator GUI (Python + Embedded Integration)
**Real-Time Control Visualisation**

![Wave GUI](assets/images/gui.jpg)

### Overview
Built a Python GUI to visualise real-time voltage response and allow tuning of PID constants dynamically.

### Key Contributions
- Designed Tkinter GUI interface.
- Displayed real-time waveform response from LPF circuit.
- Allowed user adjustment of PID constants and set-point voltage.
- Integrated with embedded C firmware to demonstrate closed-loop behaviour.

### Skills Demonstrated
**Python GUI • serial interfacing • control systems**

🔗 **GitHub Repository:** [Wave Generator GUI](https://github.com/hsl25/wave-generator-gui)

---

## Arduino Mini Projects Collection

![Arduino Mini Projects](assets/images/arduino.jpg)

### Overview
A collection of smaller Arduino projects demonstrating sensor integration and motor control.

### Included Projects
- DC motor speed control (button + joystick)
- Servo joystick control
- LCD + DHT11 sensor integration
- Number base calculator (binary/decimal/hex)

### Skills Demonstrated
**embedded programming • motor drivers • sensors • rapid prototyping**

🔗 **GitHub Repository:** [Arduino Mini Projects](https://github.com/hsl25/arduino-mini-projects)

---

# Next Goals
- Develop more STM32 projects with real-time peripherals (CAN, SPI, DMA).
- Build a personal PCB design project (power converter or sensor interface).
- Expand autonomous rover work with full SLAM mapping + path planning.

---
