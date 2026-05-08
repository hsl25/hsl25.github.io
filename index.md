---
title: "Henoc — Engineering Portfolio"
---

# Hi, I’m Henoc

I’m an MEng Electrical and Electronic Engineering student at the University of Southampton.
This portfolio showcases the engineering projects I’ve worked on so far.

---

# About Me

Interested in internships in:  
- Embedded systems
- Power systems
- Control Systems
- Robotics and Automation
- Analogue/Digital Circuit Design

**Contact:** henocl205@gmail.com  
**GitHub:** https://github.com/hsl25

---

# Skills

- Programming and Software: C, C++, SystemVerilog, Python, MATLAB.
- Embedded Systems: Arduino, Raspberry Pi.
- Electronics and PCB Design: KiCad, Multisim, LTspice.
- Hardware and Engineering Tools: Oscilloscope, multimeter, bench power supply, signal generator, soldering iron.
- Communication Protocols: I2C, UART, USB. 

---

# Featured Projects

## High-Voltage Battery Management System - Southampton University Formula Student Team

- Carried out research and development for the car’s High Voltage Battery Management System, including voltage, current and temperature measurement circuits, algorithms for ensuring safety and charging and discharging of the battery.
- Worked with the BQ79616 Development Board.
- Specialised in communication protocols between the battery, management system and sensor cells, including CAN interfacing.

---

## Dashboard Development - Southampton University Formula Student Team

- Integrating an LCD screen into the steering wheel of the car.
- Designed the schematic for the buck/boost converter.
- Finished schematic design for touch-screen module, STM32F746 microcontroller and RAM module.
- Practised key routing techniques such as length-matching for RAM connections.

---

## Robotic Arm Project

- Programmed and controlled servo motors using potentiometer input, allowing for 3 degrees of freedom.
- Developed a servo-operated mechanical claw with a gear mechanism, capable of 180 degrees of motion and the ability to pick up loads of various shapes and sizes.
- Iteratively designed the claw mechanism, creating five prototypes to optimise performance and efficiency.
- Integrated user control via operational modes — a "rest" and "active" state via button input.
- Programmed with an Arduino Uno R3.

**Repository:** [Robotic Arm Project](https://github.com/hsl25/robotic-arm)

---

## Autonomous Rover (Year 2 Project)

- Developed an autonomous rover capable of navigating through obstacles, as software lead and electronics and mechanical team member.
- Carried out calculations for choosing optimal motor torque by generating motor curves for a selection of sample motors.
- Programmed the Raspberry Pi Pico WH in C++, implementing PWM motor control for brushed DC motors and integrating motor drivers.
- Organised circuitry by connecting battery, buck converter, over-current protection module, fuse circuitry, Pico WH and motor drivers.
- Designed algorithms for efficient forwards and backwards movement, and skid steering.
- Implemented a reactive navigation algorithm using LiDAR and IMU sensor fusion, enabling the rover to autonomously navigate past obstacles.

**Indoor Trials Repository:** [Autonomous Rover](https://github.com/hsl25/indoor_trials) 
**Outdoor Trials Repository:** [Autonomous Rover](https://github.com/hsl25/outdoor_trials) 

---

## Sudoku

- Developed a command line based Sudoku game in C++.
- Added various levels with increasing difficulty.
- Allowed for the user to choose and fill in a given square, updating the board each time.
- Implemented a solver algorithm to automatically solve any given board.

**Repository:** [Sudoku Game](https://github.com/hsl25/Sudoku)

---

## Engineering Toolkit

- Developed a robust command line application in C++ which integrates a circuit simulator, Fourier series graph plotter and a logic gate array.
- The skeleton code for the circuit simulator was provided.
- Fourier Series graph plotter: the user chooses a waveform to plot out of sine, square, triangle, sawtooth and custom waveform. Fourier Series coefficients, amplitudes, frequencies and phase shifts are also selected by the user where applicable. Then the corresponding graph is plotted in the command line.
- logic gate array: I created files, each with different logic functions of increasing complexity. The user chooses from a range of files before choosing values (0 or 1) for each symbol. The logic gate array determines the output (TRUE or FALSE) for any given number of symbols. I designed the gate array to be scalable so that it could calculate the output for logic functions with n different symbols.

**Repository:** [Engineering Toolkit](https://github.com/hsl25/Simulator)

--- 

## PWM, ADC and PID on a Microcontroller

- Built a low-pass filter circuit.
- Used a 10-bit timer on the ATmega164PA microcontroller (programmed in C) to vary PWM duty cycle and therefore the potential difference across the capacitor.
- Used serial communication via PuTTY to take the desired duty cycle from the user.
- Implemented PID control and tuned constants to allow the desired voltage to be maintained when external noise was applied.

**Repository:** [PWM ADC PID](https://github.com/hsl25/pwm-adc-pid)

---

## Wave Generator GUI

- Designed a GUI in Python using Tkinter to display the voltage measured in the LPF circuit.
- Implemented a real-time waveform with the user able to tune PID constants and set a desired set-point voltage in the GUI.
- Integrated this Python GUI with previous C code to allow PID functionality to be visible in the waveform.

**Repository:** [Wave Generator GUI](https://github.com/hsl25/wave-generator-gui)

---

## Arduino mini-projects

- DC motor control with adjustable speed via button input, using the L293D Motor Driver. 
- DC motor control with adjustable speed via joystick, using the L293D Motor Driver.
- Servo motor control with joystick.
- Integration of LCD display with DHT11 Temperature and Humidity sensor.
- Calculator for operations in binary, decimal and hexadecimal.


---
