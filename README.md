# LED-Control-With-Raspberry-Pi
To those outside of Mr.Walker's class, this is a school project for my Computer Science class.

For the Hello World mini project, I decided to follow a tutorial on this link [https://grantwinney.com/hello-world-for-the-raspberry-pi-making-an-led-blink/]

Direction
(Note: Refer to the PNG files if you want to see images of what everything looks like)

## Setting up the breadboad
Before doing anything, make sure to disconnect the Raspberry Pi. You can damage your Raspberry Pi or fry your LEDs if you assemble the parts incorrectly. 

1. Instead of using jumper wires (and because we don't have the female jumper wires anyways), connect a cobbler and ribbon to the   Raspberri Pi and the breadboard 
 
2. On the breadboard, connect the longer(anode) side of the LED to pin number 21 (or other pin you want to use)

3. Connect the shorter(cathode) side of the LED to an empty row (any row that is not connected to the GPIO) 

4.Then, take the resistor, connect one end to the same row as the short (cathode) leg of the LED. Connect the other end to one of the "ground" (GND) pins 

The finished product should look like this: ![](https://github.com/annahothai/LED-Control-With-Raspberry-Pi/blob/master/Setup%20Images/Setup1.jpg)

![](https://github.com/annahothai/LED-Control-With-Raspberry-Pi/blob/master/Setup%20Images/Setup3.jpg)

5. You're done! Let's get to the code
 
 
 
 ## Python
 1. You can now plug in your Raspberri Pi
 2. On your Linux desktop, create a python file (I called mine LED.py, you can name it whatever you want.)
 ![](https://github.com/annahothai/LED-Control-With-Raspberry-Pi/blob/master/Scripting%20Images/1.jpg)
 
 ![](https://github.com/annahothai/LED-Control-With-Raspberry-Pi/blob/master/Scripting%20Images/2.jpg)
 
 3. Copy and paste the code from [LED.py](https://github.com/annahothai/LED-Control-With-Raspberry-Pi/blob/master/LED.py) (credit to Grant Winney who coded this). You  can also use the code provided by [The Pi Hut](https://thepihut.com/blogs/raspberry-pi-tutorials/27968772-turning-on-an-led-with-your-raspberry-pis-gpio-pins)
 ![](https://github.com/annahothai/LED-Control-With-Raspberry-Pi/blob/master/Scripting%20Images/3.jpg)
 
 4. Open the terminal and type in
 ```sudo python LED.py``` 
 Your screen will disply "on" when the LED lights up, and "off" when it's turned off.
 ![](https://github.com/annahothai/LED-Control-With-Raspberry-Pi/blob/master/Scripting%20Images/4.jpg)
 ![](https://github.com/annahothai/LED-Control-With-Raspberry-Pi/blob/master/Scripting%20Images/5.jpg)
 ![](https://github.com/annahothai/LED-Control-With-Raspberry-Pi/blob/master/Scripting%20Images/6.jpg)
 
 
 5. The LED should blink twice a second for 5 seconds


    
   
 
 
 
 



