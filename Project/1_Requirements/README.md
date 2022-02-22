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
# SENSOR
* LDR sensor sense the light and sends flag to microcontroller.
Light Dependent Resistors (LDRs) which are placed on a common plate with solar panel. Light from a source strikes on them by different amounts. Due to their inherent property 
of decreasing resistance with increasing incident light intensity, i.e. photoconductivity, the value of resistances of all the LDRs is not always same.
LDR sends equivalent signal of  resistance value to the Microcontroller which is configured by required programming logic. The values are compared with each 
other by keeping a particular LDR value as reference.
# MICRO CONTROLLER
* Based on the input signals received from the LDRs the microcontroller sends  signals to the servo motors . One servo motor is used for tracking along x-axis and the other is for y-axis tracking.
# ADRUINO UNO
![arduino_uno](https://user-images.githubusercontent.com/98837668/155003074-f5221b39-b07a-462e-8def-85b0489a5005.jpg)
* The Arduino Uno is a microcontroller board based on the ATmega328. Arduino is an open-source, prototyping platform and its simplicity makes it ideal for hobbyists to use as 
well as professionals. The Arduino Uno has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a 16 MHz crystal oscillator, a USB connection, 
a power jack, an ICSP header, and a reset button. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it 
with a AC-to-DC adapter or battery to get started.

# ACTUATORS(MOTORS)
* One of the two dc servo motors is mechanically attached with the driving axle of the other one so that the former will move with rotation of the axle of latter one. The axle 
* of the former servo motor is used to drive a solar panel. These two-servo motors are arranged in such a way that the solar panel can move along X-axis as well as Y-axis.
# MOTOR DRIVER
 * Motor driver is used to drive motors(Actuators)
# SOLAR CHARGE FLOW CONTROLLER
* Monitors the battery voltage
* Opens the circuit 
* when the battery voltage ascends to a certain Level it stops charging
* Prevent the DC power streams back to sun based board - during the evening, when sun based boards are not producing power, power can really stream in reverse from the batteries 
through the sunlight based boards, depleting the batteries.
More seasoned sun based charge controllers utilized a mechanical hand-off to open or close the circuit, ceasing or beginning force heading off to the batteries
# BLOCK DIADRAM
![Block diagram for Solar tracker](https://user-images.githubusercontent.com/98837668/154851858-09042167-69b2-47ac-b3c8-86707f2ae9cb.png)
# SUMMARY
In this project we are going to discuss making a temperature-controlled fan using Arduino. With this circuit, we will be able to change the fan speed in our home or any place according to the room temperature and also display the temperature and fan speed changes on a 16x2 LCD display. To do this we will be using an Arduino UNO Board, LCD, DHT11 sensor Module, and DC fan.The sensor senses the temperature which is taken and converted it  into a suitable number in Celsius scale is done. The fan speed is controlled by using PWM signals and the system shows temperature on LCD and Fan runs.

# SWOT ANALYSIS


# FEATURES
* Can be used to power the traffic lights and streetlights
* Can be used in home to power the appliances using solar power
* These can be used in industries as more energy can be saved by rotating the panel
# Limitations of Sun Tracking Solar Panel Circuit
* Though this system is more useful it has low efficiency in rainy season
* As they are expensive they required to change from time to time

# REQUIREMENT MODELLING

# Table : High level test plan
|Test ID| 	Description|
|---|----|
|H_01|	The sensor senses the intensity of light|
|H_02|	The panel moves towards the region where the intensity of light is more|
|H_03|	The panel stops moving when there is no light|

# Table : Low level test plan
|Test ID| 	Description|
|---|---|
|L_01 |	LDR sensor is used to sense the light  |
|L_02 |	One servo motor is used for tracking along x-axis and the other is for y-axis tracking|
|L_03 |	There is no light falls on LDR during night the motors stops rotating |


