# **2 Wheel Rover**

## **Component required** 

- **3d Printed component** 
    - Frame
    - Battery case
    - Wheels
    - Supporting plates

- **IOT components**
   -   DC Gear Motor
   -   Esp 32 module
   -   L298N module 
   -   Joystick
   -   Power switch
   -   Battery
   -   Jumper wires
   -   Breadboard

- **Other Component**

   -  Nut and bolts
   -  Double sided tape
   -  Solding iron and Solder

## Process of making Rover 
### There are two parts 

- Transmiter
- Receiver

### Transmiter
Firstly we make transmiter to control rover by using joystick
### components required 

-  Esp 32 module
-  Analog joystick
-  Breadboard
-  Doublesided tape
-  Jumper wires
-  5v DC supply

### Step 1

-  Firstly we make connection Between ESP 32 module and Joystick and 5v dc port.
-  Mount Esp 32 on Breadboard.
-  Attach Joystick on breadboard using double sided tape.
-  Connect Esp 32 pins to joystick pin as per image
- Get the MAC address of ESP 32 module
- [How to get the MAC address of ESP 32](Documentation/how_read_mac_address_ESP32)
- Upload the Transmiter code to esp 32 Module using Arduino IDE -[Code](Documentation/2_wheel_rover/transmiter_code.ino)
- 
