# Arduino Tutorial
1. **LED Blinking:** We use an LED (Light Emitting Diode), which is connected to the Arduino via a resistor. The resistor limits the current that flows through the LED to prevent it from burning by too much current. 
 - The **pinMode()** defines the pin of Arduino that is connected to the LED as **OUTPUT**, **INPUT**, or **INPUT_PULLUP**. 
 - Function **delay()** pauses the program for the amount of time in milliseconds.
 - Function **digitalWrite()** sets the value of the given digital pin as HIGH or LOW.
<p align="center">
<a href="https://wokwi.com/projects/374869964416433153" >LED Blinking: click to get the code</a></p>
<p align="center">
<img src="./Media/1.jpg" width="500" height="400"/>
</p>

2. **Slide switch to turn ON and OFF an LED:** We use a slide switch to turn an LED ON and OFF. As before, the LED is connected to the Arduino via a resistor. 
 - We define the pin of Arduino that is connencted to the common contact of the switch, as **INPUT_PULLUP**, which means that this pin is an input, and it is HIGH by default, if it is not connected to the GROUND.
<p align="center">
<a href="https://wokwi.com/projects/375711320031687681" >Slide switch to toggle LED: click to get the code</a></p>
<p align="center">
<img src="./Media/2.jpg" width="500" height="400"/>
</p>