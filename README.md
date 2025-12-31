[BOM - Smart home - BOM.csv](https://github.com/user-attachments/files/24395662/BOM.-.Smart.home.-.BOM.csv)
ESP32 - Smart home project:
--------------------------------
Project description:
This project is a custom-built ESP32-based control to automate a curtain motor and manage multiple devices in my room such as a fan, LED strip, temperature sensor, and additional motors. This is buit using a custom PCB designed in KiCad, using only salvaged components from old electronics but also used Arduino uno for the code

Video: https://www.youtube.com/shorts/h7QkvN7-KNk

The project focuses mainly on hardware design, PCB routing and building in Kicad, reusing components, and experimentation, but not so much software work.
"Note, the main code is not fully written by me, and it is not the main focus of this project. It is only here for reference or experimenting."

Why i mainly made this project:
I wanted to make this project to:
- Learn how to design PCB
- Searching schematics for components and reusing the components from devices
- Build something practical that i can use in my everyday life.

Below is the schematic diagram: Note: im missing 2 resistors, since i could not find the exact symbol for the motor driver that was in the robot-vacuum board.
<img width="574" height="469" alt="Screenshot 2025-12-23 at 22 29 42" src="https://github.com/user-attachments/assets/ba5900f4-e3a7-4d67-969e-463a5b390d80" />


Below is the pcb that i etched myself:
![PCB - etched](https://github.com/user-attachments/assets/d60f12ae-535b-467d-b2cd-d1bf1b9a4a3a)

This is the wiring diagram of the pcb:
<img width="794" height="556" alt="Final pcb" src="https://github.com/user-attachments/assets/03d8aa9e-94bc-45c0-a1e8-d62a09732ae8" />


These are all materials that i used in the project, u can also access it in the repo
![Screenshot_31-12-2025_161940_docs google com](https://github.com/user-attachments/assets/e6924fbf-e70e-44c1-8849-92bfb6caae08)




This project was overall successful, although I had some errors and mistakes. It hepled me with learning how to make PCBs, how to reuse unknow parts by lookin in their schematics, how to connect the ESP32, and at last it needed a lot of creativity to work.

