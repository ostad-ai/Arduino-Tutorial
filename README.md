# Arduino Tutorial
1. **LED Blinking:** We use an LED (Light Emitting Diode), which is connected to the Arduino via a resistor. The resistor limits the current that flows through the LED to prevent it from burning by too much current. 
 - The **pinMode()** defines the pin of Arduino that is connected to the LED as **OUTPUT**, **INPUT**, or **INPUT_PULLUP**. 
 - Function **delay()** pauses the program for the amount of time in milliseconds.
 - Function **digitalWrite()** sets the value of the given digital pin as HIGH or LOW.
<p align="center">
<a href="https://wokwi.com/projects/374869964416433153" >LED Blinking: click to see the live demo., and get the code</a></p>
<p align="center">
<img src="./Media/1.jpg" width="500" height="400"/>
</p>

2. **Slide switch to turn ON and OFF an LED:** We use a slide switch to turn an LED ON and OFF. As before, the LED is connected to the Arduino via a resistor. 
 - We define the pin of Arduino that is connencted to the common contact of the switch, as **INPUT_PULLUP**, which means that this pin is an input, and it is HIGH by default, if it is not connected to the GROUND.
<p align="center">
<a href="https://wokwi.com/projects/375711320031687681" >Slide switch to toggle LED: click to see the live demo., and get the code</a></p>
<p align="center">
<img src="./Media/2.jpg" width="500" height="400"/>
</p>

3. **Controlling the brightness of an LED with slide potentiometer:** A slide potentiometer is connected to an analog pin from which the value is taken to change the brightness of an LED connected to a PWM (Pulse Width Modulation) pin. 
 - **analogRead()** is a function that can read analog values from the analog pins A0, A1, A2, A3, A4, and A5. Such pins get the values in integer forms, ranging from 0 to 1023.
 - **analgWrite()** writes an analog value in the pins denoted by ~ on the board. For Arduino uno, these pins are: 3, 5, 6, 9, 10, and 11. The analog value is created by PWM. To be more specific, the duty cycle of a rectangular wave is changed based on the desired analog value.
<p align="center">
<a href="https://wokwi.com/projects/376216892255611905" >LED Brightness change with slide potentiometer: click to see the live demo., and get the code</a></p>
<p align="center">
<img src="./Media/3.jpg" width="500" height="400"/>
</p>