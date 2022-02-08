You will need:

+ A Raspberry Pi Pico
+ An RGB LED
+ 3 x resistors
+ 8 x socket-socket jumper wires

**Note:** You will need to attach resistors to the three shorter legs of the RGB LED. The longer leg is for **Ground** and doesn't require a resistor.

## Look at your RGB LED

Your RGB LED has four legs. Turn your RGB LED so that the longer **GND** leg is second from the left. Notice how the legs go **R** for **red**, then **GND**, then **G** for **green** and finally **B** for **blue**. This will help you remember what each leg is doing. 

![An illustration of an RGB LED.](images/rgb-led-legs.png)

To wire the RGB LED:

+ Attach the **R** leg to **GP1**
+ Attach the **GND** to the **GND** pin
+ Attach the **G** leg to the **GP2** pin
+ Attach the **B** leg to the **GP3** pin

![A diagram of a Raspberry Pi Pico attached to an RGB LED.](images/rgb-led-diagram.png)
