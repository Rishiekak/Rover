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
  ![Screenshot 2023-12-13 133933](https://github.com/Rishiekak/Rover/assets/129143946/9087bfd8-4dfe-4700-982b-1710faadb18f)

-  Mount Esp 32 on Breadboard.
-  Attach Joystick on breadboard using double sided tape.
-  Connect Esp 32 pins to joystick pin as per image

![Screenshot 2023-12-13 134525](https://github.com/Rishiekak/Rover/assets/129143946/7f7dcf13-6583-4c10-9b88-5994547d103b)

- Get the MAC address of ESP 32 module
- [How to get mac address of ESP 32 module](https://github.com/Rishiekak/Rover/tree/main/Documentation/how_read_mac_address_ESP32)
- Upload the Transmiter code to esp 32 Module using Arduino IDE -[Code](https://github.com/Rishiekak/Rover/blob/main/Documentation/2_wheel_rover/transmiter_code.ino)
- 
