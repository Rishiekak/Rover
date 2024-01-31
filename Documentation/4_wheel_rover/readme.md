## 4 Wheel Rover
### Parts Needed
   1- ESP32 Dev module (you can use any other module but not NodeMCU)

2- L298 Motor Driver module

3- 4 x DC motors (Yellow motors)

4- Jumper wires

5- 9V Battery (we are using Archon mart 9V powerbank works fine)

6- 3d printed Kit

## Process

4 wheel & DC motors arrangement
![image](https://github.com/Rishiekak/Rover/assets/129143946/71927087-8c0b-4936-bb14-7d12bd1bf2d1)


Now take there wires up into the body & check if they are working by connecting them directly with power source or battery(this is important as if they are not working then you might have to face trouble taking them out again later)

So if they all are working check direction of left and right motors, both left motors should run forward with some wire config, combine those wires so now you have combined 4 wires into 2 each side.

Now take ESP32 & L298n motor driver and connect your motors like this as per this circuit diagram:
"C:\Users\rishi\OneDrive\Pictures\Screenshots\Screenshot 2024-01-31 154702.png"


ESP32 with l298n Motor driver connections

the wiring for this Bluetooth car using esp32 is very easy:  
Let’s look at it in little details.

All you need to do is connect 4 wires from ESP, we have used pins 12, 14, 26, and 27 from ESP in the diagram above. Then connect all 4 motors as described above into the motor driver, 2 on one side, and 2 on the other. (note that if your DC motor is going in the opposite direction just shuffle its wires)

Then connect the positive terminal of the battery to the 12V block of L298n and the negative to Ground, also connect ground and 5V with ESP32 ground and Vin.

After completing the wiring, it’s time to assemble the roof and any other props you need & get started with coding. First of all you should try to manually provide pulses by using a simple code into ESP32 and see if the motors are moving. After testing the motors out, here is code to run Bluetooth-controlled RC Car:
[Code](Documentation/4_wheel_rover/Code.py)

Upload this code to ESP32 and you are ready to go. You can now turn the mobile application ON and connect with the car (you may have to pair your bluetooth first from bluetooth settings)

#### Pin number may be neede to interchange 
