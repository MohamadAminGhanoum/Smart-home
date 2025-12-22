
ESP32 - Smart home project:
--------------------------------
Project description:
This project is a custom-built ESP32-based control to automate a curtain motor and manage multiple devices in my room such as a fan, LED strip, temperature sensor, and additional motors. This is buit using a custom PCB designed in KiCad, using only salvaged components from old electronics but also used Arduino uno for the code

The project focuses mainly on hardware design, PCB routing and building in Kicad, reusing components, and experimentation, but not so much software work.
"Note, the main code is not fully written by me, and it is not the main focus of this project. It is only here for reference or experimenting."

Why i mainly made this project:
I wanted to make this project to:
- Learn how to design PCB
- Searching schematics for components and reusing the components from devices
- Build something practical that i can use in my everyday life.

Below is the pcb that i etched myself:
![PCB - etched](https://github.com/user-attachments/assets/d60f12ae-535b-467d-b2cd-d1bf1b9a4a3a)

This is the wiring diagram of the pcb:
<img width="794" height="556" alt="Final pcb" src="https://github.com/user-attachments/assets/03d8aa9e-94bc-45c0-a1e8-d62a09732ae8" />


| Component:    | price         | Nr of them    |
| ------------- | ------------- | ------------- |
| ESP32         |       0       |       1       |
| Capacitors    |       0       |    Multipe    |
| Curtain motor |       0       |       2       |
| AM4659 driver |       0       |       2       |
| Fan           |       0       |       1       |
| LED strip     |       0       |       1       |
| Thermistor    |       0       |       1       |
| Mosfet        |       0       |       1       |
| Copper Clad   |    7 dollar   |       5       |
| Wires         |       0       |   Multiple    |


This project was overall successful, although I had some errors and mistakes. It hepled me with learning how to make PCBs, how to reuse unknow parts by lookin in their schematics, how to connect the ESP32, and at last it needed a lot of creativity to work.

