# CaseStudy 1:Temperature Control Fan
#The below block diagram has the major parts for the controlling the temperature using fan
 ![Blockdiagram of temperature control fan](https://user-images.githubusercontent.com/98813206/154816211-dad6323e-e61f-48bd-af66-c442916236b2.png)

## Now let’s explore each component
## LCD Display
*	This 16*2 LCD display to  displays the status of the fan. (ie).it shows the temperature value by controlling the fan speed. 
## Arduino UNO Board 
*	The Arduino Uno is an open-source microcontroller board based on the Microchip ATmega328P microcontroller.
* The board has 14 digital I/O pins (six capable of PWM output), 6 analog I/O pins, and is programmable with the Arduino IDE (Integrated Development Environment), via a type B USB cable.
*  It can be powered by the USB cable or by an external 9-volt battery, though it accepts voltages between 7 and 20 volts.
*   We use an arduino board to control the speed of the fan. 
##  LM35 Temperature Sensor 
*	A thermometer is a device measures the temperature. A Thermometer consists a temperature sensing element that senses environment temperature and provides the result to the suitable devices. During this, a digital thermometer using LM35 temperature sensor which is employed to measure the temperature. 
*	It has three terminal Vcc, Output, Ground as shown in the below image 
![lm35 image](https://user-images.githubusercontent.com/98813206/154816306-4608da6c-8dad-41c5-81b2-2978c49286cb.png)

* The range of the LM35 temperature sensor is from -55 'C to +155 'C. The output range varies by 10mV to each fall and rise in temperature.
* here, Vcc and Vout is given to LCD Display.
*	Vin is given to Arduino uno board.

## DC Fan
* The direct current fans, or DC fans, are powered with a potential of fixed value such as the voltage of a battery. ... In contrast, the alternating current fans, or AC fans, are powered with a changing voltage of positive and of equal negative value.
## Power Supply
*	A 9-V lithium battery rated at approximately 500mAh delivering 25ma has a life expectancy of a little more than 24 hours. When delivering 1A, it would last less than 8 hours.
## 1N4007 diode
* The 1N4007 diode is a standard recovery rectifier with a molded plastic case which is a used as general-purpose diode.
* It is normally constructed to be used as a rectifier in the power supply section of electronic devices to convert AC voltage to DC voltage with other filter capacitors.
* The maximum current carrying capacity is 1A and it withstands peak up to 30A. 
* The reverse current is 5uA which is negligible but it can withstand reverse voltage peak up to 1000V.
## Resistor 1*1k
*	 A 1k Ω resistor has a value of 1,000 ohms and the number we will code is 1,000.

