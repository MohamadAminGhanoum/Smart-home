Note, the main code is not fully written by me, and it is not the main focus of this project. It is here for reference.
--------------------------------------------------------------------------------------------------

Routed main parts of curtain to pcb
I started this project by routing the curtain motor, that i extracted fron an old robot vacuum, and got that connected to the pcb, and i did some research, by trying to find schematics on different chips from the vacuum-motherboard and found a motor-controlling chip. I added it to my pcb on kicad, and luckily this chip was a 4-pin chip, which was a AM4959. This chip, I could give command to with two gpio pins from ESp-32, which provides 3.3v to make the motor rotate left or right. This was helpful, because now it is not necessary to use two motors, one to open and one to close the curtain.

It took quite some time to find the chip of the ESP32 controller, because it was not in the kicad library, so had to go through many websites to find the chip.

I added some capacitors for stabilizing the voltage so it does not drop at the ESP32 when the motor draws current.

I used a bit of time to get the motor to stick to the wall, and make it pop a bit to the front, so it does not touch the frame of the window. It also took time to use a string from my mom's sewing things and tighten it to the motor, and test if the motor will open and close the curtain using a 5v power supply(originally a phone cable)
curtain motor
-----------------------

added a fan
This time i added a fan to the pcb to control. This fan, i got from an unused desktop, and it didn not need a controller, so i connected one of the pins directly to the gpio pin and two others to gnd and +5v.

I thought that this fan can be used to take the smoke away, when im using the soldering iron, so i do not inhale the smoke.
------------------------

Added temperature sensor
I now added a temperature sensor, or more coorect, a thermistor, which can be calibrated to measure temperature, im thinking by putting it in ice, and make the code so it tells that it is 0 degrees.

It was at first a struggle to connect the resistor and thermistor, because they needed a 3v3 volt connection and there was a track standing in my way, but then i got "a blessing", and thought, why not but the resistor there, so it jumps over the track. This actually helped and i could continue with this project.
-------------------------

Connected LED strip and one more motor + reroute pcb
Before i began this project, i had an led strip connected to my wall, but i had it connected to 5v, phone charger, so everytime i needed to turn it on, i had to connect the charger.

So i thought i should add it to my project, and it was a great idea. But my issue now is to find a mosfet that can regulate the voltage by using the gpio pin as a gate. The issue here was than when i looked in a motherboard, i only found mosfets that needed 4.5v to open the mosfet, however the esp32 only provides 3.3v, so i did a very deep search into that motherboard. It really drained me.

I finally found a chip after looking in that motherboard across 2 days. it took longer than i expected.Now i can use the esp32 to control the voltage output to the 5v LED strip. It was pretty cool.

I then added another motor, just like the one from the first to control the curtain, but this motor, i did not really know what to use it for, but wanted it included for future ideas.

This took a good amount of time to get the components connected, and i had to reroute the pcb so all the components could fit inside.
---------------------------

Etched pcb, before buying one from pcbway
I did not want to use money to buy a new pcb, where I can have connected something wrong, therefore i wanted to try etching the pcb while trying out something new.

I soldered the components to the etched pcb, and could finally put code to control the esp32.
Though since i do not have so much knowledge about the coding, it was not fully written by me, thought the focus of this project is on the hardware building.

I found an error in my connection, and got lucky that i could fix it with the red wire.

This project in general was sucessful, but i had some errors.
Some of them was that i had a big drill, that made the holes large, and i connected the esp32 from above, could not do it from below because i did not mirror the ESP32 in kicad. Therefore this resulted in difficulties in soldering and the esp32 is unstable sometimes, if the casing falls, the connection breaks at 5v, so i have to solder again.

Therefore im thinking, i will definetly buy a pcb on pcbway later or from something similar, idk yey.


