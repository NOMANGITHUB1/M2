# introduction
The heat control system is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated. After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a microcontroller called Atmega328.
### Chair photo
![seatcover](https://user-images.githubusercontent.com/91784095/144079615-21ea751b-964d-4d54-a503-055055bfb497.jpg)
# Features
The system will detect person existance.
Driver can modify th etemperature.
Mostly used in Europen Countries.
Low cost.
# SWOT Analysis
## Strengths
User friendly.
Easy to set the temperature .
Low cost
## Weakness
It is used only in the European countries.
## Opportunities
It can be implementaed along with AC.
## Threats
Not used in average and high temperatures.
# 4 W's and 1 H
What: Heat Monitoring System.
Where: Used in automotive industry.
When: At low temperature.
Why: For being warm.
How: Operates by varyibg the temperature.
# High level requirements
1-	When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.	
2-	Next the analog input from the temperature sensor is received and digitized.
3-	The hard disk must be 4 GB .
4-	The web browser must be Microsoft Internet Explorer with a resolution of at least 800 * 600.

# Low level requirements
1-	The digitized temperature input is visualized using Pulse Width Modulation.
2-	The system runs effectively on Windows 2000 server but it will also run equally well on compatible operating systems.	
3-	The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.

