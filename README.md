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


Final reflection
-------------------------------------------
I think that this project for me honestly was difficult. This was my first time using kicad to create a pcb and schematic, and i did some issues, like forgetting to make a schematic and jumping directly to pcb. I had to do many retries to get to my final result. I did much experimenting with trasferring the ink from paper to pcb. I ended up printing the pcb-layout on the paper 3 times through printer, since i twas a normal paper

I further also did not log the hours that i took me to find the ldo voltage regulator from a motherboard, and the time taken to research the different parts from the robot vacuum, because i dont think this counts.

I finally did enjoy making this project, and it was both entertaining and taught me how pcbs are made. If i had to redo this, I think i would put money in getting glossy paper, because they would have made this a lot easier by transferring the ink from the printer directly to pcb.

This project was overall successful, although I had some errors and mistakes. It hepled me with learning how to make PCBs, how to reuse unknow parts by lookin in their schematics, how to connect the ESP32, and at last it needed a lot of creativity to work.

