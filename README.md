# Servo-tester-PCB
𝐒𝐞𝐫𝐯𝐨 𝐌𝐨𝐭𝐨𝐫 𝐓𝐞𝐬𝐭𝐞𝐫 𝐛𝐮𝐢𝐥𝐭 𝐮𝐬𝐢𝐧𝐠 𝐚 555 𝐭𝐢𝐦𝐞𝐫 𝐈𝐂
Servo Motor Tester PCB

A compact, code-free servo motor testing tool built using a 555 Timer IC. This board allows anyone—from students to makers—to quickly test servo motors using PWM signals without the need for microcontrollers.

---

 Overview

This project is a **Servo Motor Tester** designed to output PWM signals to standard hobby servo motors. It uses a 555 Timer IC and passive components to generate pulse signals, with a potentiometer to vary the servo angle. This makes it ideal for:

- IoT students learning actuator control
- Robotics hobbyists testing servo motion
- Hardware developers debugging servo-based systems

---

Features

- PWM generation using **NE555 Timer**
- Manual control via **RV1 Potentiometer (100Ω)**
- 3-pin header for servo motor (GND, VCC, Signal)
- Power input header for external 5V supply
- Easy-to-read silkscreen and user-friendly layout
- LED for visual status/power indication

---

Schematic Annotation

| Symbol | Value     | Footprint                                                  |
|--------|-----------|------------------------------------------------------------|
| C1     | 22nF      | Capacitor_THT:C_Disc_D4.3mm_w1.9mm_P5.00mm                 |
| D1     | 1N4148    | Diode_THT:D_DO-35_s0D27_P7.62mm_Horizontal                 |
| D2     | LED       | LED_THT:LED_D3.0mm                                         |
| J1     | Power In  | PinHeader_1x02_P2.54mm_Horizontal                          |
| J2     | Servo Out | PinHeader_1x03_P2.54mm_Horizontal                          |
| R1     | 3.3MΩ     | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal |
| R2     | 56KΩ      | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal |
| R3     | 1Ω        | Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal |
| RV1    | 100Ω Pot  | Potentiometer_THT:Potentiometer_Alps_RR163_single_Horizontal |
| U1     | NE555P    | Package_DIP:DIP-8_W7.62mm                                  |

---

Applications

- Servo motor testing during early hardware prototyping
- Demonstrating PWM behavior in embedded systems
- Educational tool for IoT and robotics training
- Replacing microcontroller-based test setups for quick checks

--l
