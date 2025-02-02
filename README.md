# Password-based-key-lock-for-bike

This project implements a password-based key lock system integrated with an ignition key. It provides an additional layer of security, ensuring that only authorized users can start the system by entering the correct password along with the physical key.

Here I am using Proteus software for simulation 
components required :
1. Microcontroller: AT89C51
2. Battery: 12v
3. Keypad
4. Relay: L293D
5. Motor: Dc motor
6. switch

Step 1: Make the connections as per the simulation.
Step 2: Using Keil micro-vision software create a hex file for the micro-controller.
Step 3: Double-tap on the microcontroller in simulation you'll find option "Program File" select it and upload the hex file you created.

You're simulation is ready to run

Note:
1. The program should be according to the PINs that you connected
2. The program I am uploading is according to the pins that I have used, so it may not work accordingly with you're requirements.
3. I have programed the password as"1234".
4. If you want to change it go to "newlock.c" file go to main function at line 049 there you'll find "char pass[5] = "1234";  change the numbers to which ever you want and then build the file run the simulation again. 
