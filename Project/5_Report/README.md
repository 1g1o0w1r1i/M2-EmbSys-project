# GARDUINO
# Abstract
* India has a population as much as 17.7% of the world’s population but has only about 4% of the world’s freshwater resources. Biggest problems faced by farmers in India is nearly half of the cropped area are under irrigation. Irrigation is the most important agricultural input in a tropical monsoon country like India where rainfall is uncertain, unreliable and erratic.India cannot achieve sustained progress in agriculture unless and until huge cropped area is brought under assured irrigation. 
* The only recommended solution to this issue is modernizing irrigation system using smart technologies. This project aims at developing the  irrigation system which provide adequate water required by crop by monitoring the moisture of soil and climate condition in order to prevent the wastage of water resource. It will also have many advantages for farmers.
# INTRODUCTION
GARDUINO is an Arduino-based system to supervise the temperature, humidity, soil moisture and light status of our plant and automatically provide its necessary needs like light, water, and pure fresh air and even some sensors are used to control some actuators.
# RESEARCH
* Proposed a microcontroller based controlled remote irrigation system developed for the agricultural plantation, which is placed at the remote location and required water provides for plantation when the humidity of the soil goes below the set-point value.  If the set-point value is high, then the motor is turned ON, otherwise the the motor is turned OFF. 
# FLOW CHART OF GARDUINO
![Flow chart of garduino](https://user-images.githubusercontent.com/98813206/155710916-2e4281a7-510a-4fe0-a452-ff85ed3a1582.jpg)


# BLOCK DIAGRAM OF GARDUINO
![GARDUINO](https://user-images.githubusercontent.com/98813206/155710999-132aa60d-1670-4331-adde-1e6d6183c15e.jpg)



# WORKING
* In this irrigation System, Soil Moisture Sensor checks the moisture level in the soil and if moisture level is low then Arduino switches on a water pump to provide water to the  plant. 
* Water pump gets automatically off when system finds enough moisture in the soil.
* The watering of plants is controlled with a soil moisture sensor which is used to turn on the water pump as and when required.
* The temperature/humidity sensor is responsible for the turning on and off of a 12V DC cooling fans and light.
* The Water motor, light and fan can be controlled remotely using Google assistant.
* With the soil sensor, temperature and humidity value can be monitored live using website.
* This system is very useful in Farms, gardens, home etc. In this system, there is a human need for giving the instructions.

# COMPONENTS REQUIRED
* ARDUINO UNO
* SOIL-MOISTURE SENSOR
* TEMPERATURE-HUMIDITY SENSOR (DHT11)
* LED LIGHT & 12V DC COOLING FAN
* RELAY
* DC 12V WATER PUMP SUBMERSIBLE
## Now let’s explore each component
## ARDUINO UNO:
* It is the micro controller board that is equipped with sets of digital and analog input/output pins and has a USB connection to load programs from personal computers.
* The board has 14 digital I/O pins (six capable of PWM output), 6 analog I/O pins,a 16 MHz crystal oscillator, a USB connection, 
a power jack, an ICSP header, and a reset button.
* It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it 
with a AC-to-DC adapter or battery to get started.
* It is programmable with the Arduino IDE (Integrated Development Environment), via a type B USB cable which can be powered by the USB cable or by an external 9-volt battery, though it accepts voltages between 7 and 20 volts.
![Arduino UNO Pic](https://user-images.githubusercontent.com/98813206/155196006-24f5e5a2-9239-4b8a-bde0-15aeab71308f.jpg)

## SOIL-MOISTURE SENSOR: 
* It Used to measure the volumetric water content by using the dielectric constant, electric resistance properties of soil.
* It uses two probes, when inserted into the soil provides the repeated moisture readings used for the irrigation.
* More water makes the soil to conduct more easily (less resistance) while dry soil conducts poorly (more resistance)
![soil moisture sensor](https://user-images.githubusercontent.com/98813206/155710505-04a5585f-48de-4b22-8819-4dcd19593f06.jpg)

## TEMPERATURE-HUMIDITY SENSOR (DHT11): 
* The DHT11 is a basic, ultra low-cost digital temperature and humidity sensor.
* Temperature and humidity sensors are among the most commonly used environmental sensors. 
* These devices are used to provide the actual humidity condition within the air at any given point or in any given place.

![DHT-11](https://user-images.githubusercontent.com/98813206/155710702-119f6f04-67f1-4133-b22e-e9530012e802.jpg)

## LED LIGHT & 12V DC COOLING FAN:
* To power a DC fan, we feed the fan its rated voltage and this power can come from any DC voltage source, such as a DC power supply or even batteries
{For example, to power a 12VDC fan, we need to feed it 12 volts DC} 
* LED light is an electric light that produces flashes using light-emitting diodes (LEDs). which are significantly more energy-efficient than equivalent incandescent lamps and fluorescent lamps.
* These are triggered together by the DHT11 temperature-humidity sensor when the surrounding temperature drop down below a plant-healthy level.
## RELAY:
* It is an electrically operated switch which is used where it is necessary to control a circuit by a low-power signal or where several circuit must be controlled by one signal. (i.e)use an electromagnet to move the switch from OFF to ON position instead of a person moving the switch. 
* Single pole double throw relay is used.

## DC 12V WATER PUMP SUBMERSIBLE:
* Submersible pumps are the pumping machines that are designed to submerge into liquids. 
* The DC submersible pump refers to the submersible pumps that use the direct current electricity as the power source. 
* The most common power sources for the DC submersible pumps are the solar modules, batteries, or generators.
* This is triggered by the soil-moisture sensor as and when the soil gets dry and watering of the plants is needed.

![12v dc water pump](https://user-images.githubusercontent.com/98813206/155710750-0e5ad2f5-7df8-4859-907a-8eb4763911e7.jpg)


# SWOT ANALYSIS
# STRENGTHS
* Works according to the soil moisture condition. 
* Complete elimination of manpower. 
* Fully automated irrigation system which will turn ON and OFF a water pump as per the level of moisture in soil. 
* Highly sensitive, low cost and reliable circuit.
# WEAKNESS
* it have limited life after installation due to the detoriation of the plastic component in a hot, arid climate when exposed to ultraviolet light. 
# THREATS
* New automatic systems are to be introduced to the market which may have better options. 
* cheap complementary products may enter to the market.
# OPPORTUNITIES 
* There are huge opportunities in the local market since these types of automations are not yet penetrated to the villages and rural markets . 
* Agriculture still uses conventional methods for many cases so that a huge opportunities are still awaiting in rural India.


# REQUIREMENT MODELLING

# Table : High level test plan
|Test ID| 	Description|
|---|----|
|H_01|	The sensor senses the temperature and moisture level of the soil|
|H_02|	based on that temperature and moisture, it will water to all crops|
|H_03|	set point of water is programmed with certain level|
|H_04| based on the comment from arduino, the water pump will provides water to the crops|
|H_05| temperature and humidity value can be monitored live with the help of graph|

# Table : Low level test plan
|Test ID| 	Description|
|---|---|
|L_01 | Works according to the soil moisture condition and temperature changes |
|L_02 |	Water motor, light and fan can be controlled remotely using Google assistant |
|L_03 |	provides right amount of water at right time|

# FEATURES
* This provides right amount of water at right time. 
* The plants get water at the proper time then it helps to increase the production from 25% to 30%.
* This system can used to irrigate very large areas as it only needs to divide the whole land into number of sectors and the single micro- -controller can control the whole process.
* It waters when the humidity of the soil goes below the set-point value.  If the set-point value is high, then the motor is turned ON, otherwise the the motor is turned OFF. 
* It sets the irrigation by continuously monitoring the status of the soil and temperature with the use of sensors, flow of water can be controlled by set point which is programmed

# Advantages of Garduino
* It is very economical and easy to handle by the user.
* farmers or workers don't have any works like watering, monitoring etc.. 
* It is help full to disabled people.
* This system avoid over irrigation, under irrigation, top soil erosion and the system action can be changed according to the situations(crops, weather condition, soil etc.) 
*  Can be used in large or small farms, gardens in public place or at home (terrace garden) etc...
* Save energy and time of the workers
# Disadvantages of Garduino
* It needs human help to give the instructions manually.
* it have limited life after installation due to the detoriation of the plastic component in a hot, arid climate when exposed to ultraviolet light


# SUMMARY
In this project we are going to discuss making a Garduino using Arduino.With this circuit, we will be able to  monitor the crops or plants in th efarms by checking the temperature and soil moisture level.with that we will improve our crops growth by watering properly based on the current climatic changes or condition. this is can be monitored live without any manpower and store those date in graphical form. which can be used for further analysis.It also makes the appropriate use of resources like water and electricity which will reduce the wastage of these resources and will also improve the health and life of plants. it a good alternative to the current approaches since it facilitates the farmers to assist them in daily needs of the monitoring and controlling the field environmental parameters with minimum cost and user friendliness   .  

# FUTURE SCOPE
* A lot of future scope are available that can be used with this work to improve the efficiency and effectiveness of the system, the following recommendations can be put into
consideration. 
* The idea of using IOT for irrigation can be implemented with this system. Other activities in farming such as cattle management, fire detection and climate control can be introduced with this system. 
* This system can be improvised by adding a Webscaper which can predict the weather and water the plants/crops accordingly. If rain is forecasted, less water is let out for
the plants.

# CONCLUSION
* The manual method has lots of drawbacks and is quite unreliable for irrigation of big areas. Irrigation has direct impact on cost and production of final product. This system aims to eradicate the traditional manual method of irrigation which needs to be improved over the time. The system will reduce the human efforts in gardening and also make the gardening automated and tech friendly. 
* It also makes the appropriate use of resources like water and electricity which will reduce the wastage of these resources and will also improve the health and life of plants.
* This prototype has many advantages which make it a good alternative to the current approaches since it facilitates the farmers to assist them in daily needs of the monitoring and controlling the field environmental parameters with minimum cost and user friendliness.
