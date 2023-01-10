# Mini-Project-Team-7

Smart Street Light Using IoT

-> Hardware devices: Arduino UNO, Regulator, LDR, LEDs, Resistors, IR sensors, Wooden board, Connecting wires, Breadboard.
-> Softwares : Arduino IDE, Proteus 8, Windows 11 Operating system.
-> For the initial stage of our project, we built a virtual circuit which consists of the micro-controller, Arduino UNO, along with five LEDs and an LDR(Light 
Dependent Resistor) with the help of Proteus, which is a software, similar to Tinkercad, where we can build virtual circuits and execute them.
-> Later, we have also added in five IR sensors and a regulator to the circuit in order to fulfil our project requirements. 
-> We then analysed all the devices that are needed with the help of the virtual cicuit and gathered them.
-> After that we built the physical circuit similar to the virtual cicuit making a wooden board as our base and representing it as a road.
-> Then we implemented the model by adding our program to the Arduino IDE and then embedding the same program in our virtual as well as physical model. 
-> In the last stage we were able to calculate the amount of power that is being saved with the help of our project per day using the virtual model.

-> Working:
Our project's working depends on two thing:
1) Light
2) Motion of an object
During the day, or when there is ambient light, all the LEDs stay turned off. But when there isn't enough light, could be considered as a cloudy weather or 
during the night, all the LEDs turn on but main a minimal brightness. When any one  of the IR sensors detects movement of any object, regardless a vehicle, an 
animal, or even a human being, the respective LED glows with higher intensity and as soon as the object moves away, the LED goes back to its prior state. As 
we have introduced two stages of brightness, the system is automatically adjusting the intensity of the LEDs, with this we can save a lot of power as well as 
expenses.
