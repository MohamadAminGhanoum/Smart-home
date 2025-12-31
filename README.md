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


[Uploading BOM - Name:,Part nr:,Price:,Quantity:,Function:,Link:
ESP32,ESP32-Wroom,0,1,To control and connect to wifi,
CeramicCapacitors,1uF,0,Multipe,Stabilize voltage,From laptop motherboard
Electrolytic capacitors,"100uF, 25V",0 USD,2,For power smoothing,From robot vacuum
Curtain motor,(Wheels of vacuum),0 USD,2,Open/close curtain,From robot vacuum
Motor driver,AM4659 ,0 USD,2,to drive the motor,From robot vacuum
Fan,5v Fan,0 USD,1,prevent solder smoke/ventilate,From pc
LED strip,5V old LED strip,0 USD,1,to light the room,Laying around
Thermistor,10 kohm NTC,0 USD,1,Measure temperature,From laptop cpu temp sensor
Mosfet,G961 1A LDO,0 USD,1,To control brightness of LED strip,https://www.alldatasheet.com/datasheet-pdf/view/105493/GMT/G961-18ADJTEU.html
Copper Clad,to have pcb on it,7 dollar,5,To put components on,https://www.aliexpress.com/item/1005006221193001.html?spm=a2g0o.productlist.main.13.460e3a69bUSqmc&algo_pvid=0f968f4b-4dab-44e4-9940-d1a89bb61177&algo_exp_id=0f968f4b-4dab-44e4-9940-d1a89bb61177-12&pdp_ext_f=%7B%22order%22%3A%222%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21DKK%21129.05%2140.11%21%21%21138.24%2142.97%21%4021038df617671818425206967e2690%2112000036339815987%21sea%21DK%213871794027%21X%211%210%21n_tag%3A-29919%3Bd%3Ac5797a79%3Bm03_new_user%3A-29895%3BpisId%3A5000000198273513&curPageLogUid=TUCw4VrV8onk&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006221193001%7C_p_origin_prod%3A
Wires,any type of wire,0 USD,Multiple,to connect the connectors,Any type of wire
"Resistor, pull up",10 kohm,0 USD,1,Voltage divider for thermistor,Had it laying around
Resistor,"0.1 ohm, 1W",0 USD,2,Current sensing for the AM4659,Any resistor under 1 ohm
Input protection,ET9528,0 USD,1,Overvoltage & overcurrent protection,https://etek.com.cn/upload/files/product/20250630/17512731716326659.pdfSmart home - BOM.csv…]()


This project was overall successful, although I had some errors and mistakes. It hepled me with learning how to make PCBs, how to reuse unknow parts by lookin in their schematics, how to connect the ESP32, and at last it needed a lot of creativity to work.

