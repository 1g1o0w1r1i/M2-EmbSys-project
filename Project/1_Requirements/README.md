# REQUIREMENTS
# TEMPERATURE CONTROL FAN
# INTRODUCTION
Temperature controlling is required in many places such as server rooms, houses, industries, etc. So this project is very useful to control the temperature at your home. This can be used in anywhere as we want. Here the Temperature controlled fan will act to environment and helps to change the temperature.
# RESEARCH
* We are going to do this with a LM35 temperature sensor. It can be done in various other ways as well. With a thermistor or other sensors like a contactless temperature sensor. But thermistor usually needs contact of the surface and contactless sensors can be costly. While LM35 is a cost-effective sensor.
# WORKING
This project works in three parts -
* In the first step, the sensor senses the temperature by temperature sensor namely LM35.
* In the second step, the sensor's output is taken and conversion of temperature value into a suitable number in Celsius scale is done. The fan speed is controlled by using PWM signals. And last part of the system shows temperature on LCD and Fan runs.
* Then, we have programmed our Arduino according to the requirements. Working on this is very simple. We have generated PWM from Arduino and put it at the base terminal of the transistor. Then transistor generates voltage with respect to the PWM input.
# COMPONENTS REQUIRED
* Arduino UNO
* LM35 sensor
* DC Fan
* 16x2 LCD
* Power supply 
## Now let’s explore each component
## LCD Display
*	This 16*2 LCD display to  displays the status of the fan. (ie).it shows the temperature value by controlling the fan speed. 
## Arduino UNO Board 
*	The Arduino Uno is an open-source microcontroller board based on the Microchip ATmega328P microcontroller.
*	It is a prototyping platform and its simplicity makes it ideal for hobbyists to use as well as professionals.
* The board has 14 digital I/O pins (six capable of PWM output), 6 analog I/O pins,a 16 MHz crystal oscillator, a USB connection, 
a power jack, an ICSP header, and a reset button.
* It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it 
with a AC-to-DC adapter or battery to get started.
* It is programmable with the Arduino IDE (Integrated Development Environment), via a type B USB cable which can be powered by the USB cable or by an external 9-volt battery, though it accepts voltages between 7 and 20 volts.
* We use an arduino board to control the speed of the fan. 
![arduino_uno](https://user-images.githubusercontent.com/98837668/155003074-f5221b39-b07a-462e-8def-85b0489a5005.jpg

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
#  BLOCK DIAGRAM

 ![Blockdiagram of temperature control fan](https://user-images.githubusercontent.com/98813206/154816211-dad6323e-e61f-48bd-af66-c442916236b2.png)

# SUMMARY
In this project we are going to discuss making a temperature-controlled fan using Arduino. With this circuit, we will be able to change the fan speed in our home or any place according to the room temperature and also display the temperature and fan speed changes on a 16x2 LCD display. To do this we will be using an Arduino UNO Board, LCD, DHT11 sensor Module, and DC fan.The sensor senses the temperature which is taken and converted it  into a suitable number in Celsius scale is done. The fan speed is controlled by using PWM signals and the system shows temperature on LCD and Fan runs.

# SWOT ANALYSIS


# FEATURES
* This comfort maintains and controls the room temperature automatically.  
* It gauges the heat index and measures the temperature between the ceiling and floor. 
* Finally, it calculates each fan's ideal fan speed and direction.
* Can be used in industries, homes or any places for reducing the temperature by controlling using environment.

# Advantages of Temperature Controlled Fan
* It is very economical and easy to handle by the user.
* Speed varies automatically, so that it controls the speed without using it manually.
* It is help full to disabled people.
* It is very easy to install in offices, houses etc.
* Save energy by slowing down its speed in low temperature.
# Disadvantages of Temperature Controlled Fan
* Micro controller is the heart of the circuit, if controller is damaged the whole system will be interrupted.
* Speed control is independent of individual preference.

# REQUIREMENT MODELLING

# Table : High level test plan
|Test ID| 	Description|
|---|----|
|H_01|	The sensor senses the temperature|
|H_02|	The value of temperature is converted into celcius and displays in LCD Display|
|H_03|	based on the comment from arduino, Fan rotates|

# Table : Low level test plan
|Test ID| 	Description|
|---|---|
|L_01 |	Temperature value is converted into celcius and displays in LCD display|
|L_02 |	Celcius is used for tracking the temperature between the ground and the ceiling|
|L_03 |	There is no changes in temperature means the fan doesn't rotates|


