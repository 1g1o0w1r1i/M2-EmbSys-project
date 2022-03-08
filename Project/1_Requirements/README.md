# PROJECT
# GARDUINO
# Description
GARDUINO is an ARDUINO based system to supervise the temperature, humidity, soil moisture and light status of our plant and automatically provide its necessary needs like light, water, and pure fresh air and evensome sensors are used to control some actuators. The watering of plants is controlled with a soil moisture sensor which is used to turn on the water pump as and when required. The temperature/humidity sensor is responsible for the turning on and off of a 12V DC cooling fans and light. The Water Motor ,Light and Fan can be controlled remotely using google assistant or Garduino Website. The soil sensor ,Temperature and the humidity value can be monitored live using the garduino website.

# License
This file is part of GARDUINO.GARDUINO is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License,or(at your option) any later version . GARDUINO is distributed in the hope that it will be useful,but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU General Public License for more details.You should have received a copy of the GNU General Public License along with GARDUINO. If not, see http://www.gnu.org/licenses/.

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

# 4W's and 1'H
# Who
This is useful for farmers and workers in agricultural field, terrace gardeners etc.
# What
* it helps to increase the production from 25% to 30%.
# When
* The user provides right amount of water at right time by giving instructions. 
# WHERE
* There is lot of agricultural research and innovation  centre recommonding smart irrigation all over the world.
# HOW
* This issue can solved now by initiating this basic idea of irrigation and in future, we will use well developed equipments with innovative ideas in order to reduce or no man power while doing  agricultural activities.

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


 




