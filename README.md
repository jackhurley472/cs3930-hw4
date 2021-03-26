Name & UNI: Jack Hurley (jth2165)

For the hardware setup, first start with connecting the motors to the esp32.
The stepper motor connects to the ULN2003 Stepper Motor Driver.
You then connect the driver to ground and to 5V.
You also need to connect inputs 1-4 to the esp32.
For my arduino script, I connected IN1, IN2, IN3, IN4 to pins 27, 26, 25, 33 respectively.
The DC motor I connected to the L293D chip.
I connected the red wire from the motor to pin 3 and the red wire to pin 6.
Then connect pins 1, 2 and 7 to the esp32 (I connected them to pins 13, 12, 14 respectively).
Connect pin 8 on the chip to 5V, pin 16 to 3.3V and pin 5 to ground.
Now all the wiring that is required is finished.

For the robot's structure, I started with a tin can robot kit.
From this I used the foundation provided and connected the axel and wheels it came with.
I also used the DC motor from the kit but it was the same as the motor that came with the esp32 kit.
The last thing from the kit I used was the plastic rings that was meant to hold a in can.
I instead placed half a cup upside-down on the top ring and set the stepper motor on top of it.
I cut a whole in to the cup and attached the marker to it.
Then just plug a 9V battery into the esp32 and connect the esp32 to a laptop.
Run the script and go to the webpage "http://165.227.76.232:3000/jth2165/".
Make sure that your robot is on paper and click "run sculpture for 30 seconds" and enjoy.

youtube link: https://youtu.be/t48CsnXUa_s
