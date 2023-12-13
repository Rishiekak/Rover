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

## Transmiter
Firstly we make transmiter to control rover by using joystick
### components required 

-  Esp 32 module
-  Analog joystick
-  Breadboard
-  Doublesided tape
-  Jumper wires
-  5v DC supply

### Following steps

 -  Firstly we make connection Between ESP 32 module and Joystick and 5v dc port.
 -  Mount Esp 32 on Breadboard.
 -  Attach Joystick on breadboard using double sided tape.
 -  Connect Esp 32 pins to joystick pin as per image
 - Get the MAC address of ESP 32 module
 - [How to get mac address of ESP 32 module](https://github.com/Rishiekak/Rover/tree/main/Documentation/how_read_mac_address_ESP32)
 - Upload the Transmiter code to esp 32 Module using Arduino IDE -[Code](https://github.com/Rishiekak/Rover/blob/main/Documentation/2_wheel_rover/transmiter_code.ino)
 - Set the mac address in transmiter code.
## Reciever
### Component required
 - Esp 32 module
 - L298N motor driver
 - 7-12v battery
 - Jumper wire
 - Frame
 - 2 main wheel 
 - Supporting wheel
 - Supporting plates 
 - Nut & screws
 - Doublesided tape
 
 ### Follwing steps
 
 
 - Assemble the Rover
 -Solder the wires to gear motor.
 -Mount two gear motors to the frame using nuts and screws.
 -Attache front wheel.
 -Attache wheel to the rover.
 -Fix L298N motor driver on the frame 
 -Make the circuit like the image
![Screenshot 2023-12-13 155307](https://github.com/Rishiekak/Rover/assets/129143946/13ef081a-270e-49a2-a04a-6bcd230d811e)

 -Fix the ESP 32 pin with L298N motor driver using table
 ![Screenshot 2023-12-13 155512](https://github.com/Rishiekak/Rover/assets/129143946/0ae3763a-25d5-4977-999b-4bb9b410abe3)

 - Install ESP32 module using Arduino Board manager-[Arduino Board manager](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbnA0Q1kwQUNDeDJuMUJhbmpDaGJmYUF0endRZ3xBQ3Jtc0trekRUOVpSYXpVZW1ERWUxellycXlTWUFjZDlBc3B2UUluT0hMcnJTY2ljZnEzY2M1OUE4OXNxTmgwYnliSjFYUmhLOVBNRUlwbjJBak51ellEMnRuYkJYYVZ5cV8xekY2NHNrV3Y1VUtmajJOdDEzdw&q=https://dl.espressif.com/dl/package_esp32_index.json&v=uNXP95vOytw)
 -Go to file 
 -Preferences
 -Add additional board link
 -Then go tools
 -Board manager
 -search esp32
 -install it
 - Connect ESP 32 to Laptop.
 - Upload reciever code-[Code](https://github.com/Rishiekak/Rover/blob/main/Documentation/2_wheel_rover/Reciever_code.ino)
 - Select module & Port
 - Upload the code.
 - Connect the Battery to the Rover
 
 Now Give the 5v power supply to the transmiter.
 Done !

For change the mode 
Throttal mode to strearing mode press joystick button......

