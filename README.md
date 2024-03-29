# Lab 4
**Total tasks:** 1

**Deadline:** Wednesday April 10, 2024 11:55pm

**Submission instructions**:
Submit all the relevant code files that you think are necessary to recreate the project on LMS. You must also submit a very simple claims list that simply mentions the components used (sensors, actuators, and the communication protocols) and the functionality of the project (doesn't have to be long, just mention in the bullet points what the project does). Please do this via the "submission text" box on the LMS submission tab.
 
## Project details
As announced in the class, for LAB 4, you are supposed to work on a single task: *deployment of a complete IoT system*. Or more specifically, you are supposed to come up with a simple IoT system, that involves all the components we have discussed in the class so far. 

Your project is required to have the following components:

**Sensors**: You are required to have at least two sensors in your project. You can use any sensor you like, but you are required to have at least one sensor. Multiple sensors are definintely encouraged.

You can use any sensor you like, including the ones provided to you, and you can get access to more e.g. Accelerometers, door sensors, flame sensors, microphones etc. either from the TA or from the EE department.

**Actuators**: You are required to have at least one actuator in your project. An actuator can be anything from a physical motor, to a buzzer, or a simple LED to show status. Once again, you can get access to more actuators from the TA or from the EE department.

**Communication**: In order to communicate/interface with the sensors, use the sensor's datasheet to understand how to interface with it. You can use any communication protocol you like, including I2C, SPI, UART, etc. You can also use any communication protocol to communicate between the sensors and the actuators. 

You must however use a Wireless communication protocol to communicate with the cloud/gateway. You are required to have atleast one backend control server for your IoT deployment. The server can either be hosted on the cloud, or can be running locally. This server can be a dashboard software, e.g. ThingsBoard, Azure IoT etc. Or an application
(web app, or mobile app) running locally. You can use any wireless communication protocol you like, including WiFi, Bluetooth, Zigbee, etc. Serial communication between a microcontroller and a computer to simulate communication with a server is not allowed.

There are no requirements for a database, to store the data or for any other purpose, but you can use one if you like.

### Suggestions
A few suggestions:

- Be a little creative with your project. The project is not really a project per se, you are required to build a simple prototype of an IoT system. So you can be creative with the sensors and actuators you use, and the way you use them. The possibilities are quite literally endless. Don't settle for something boring like simply reading from sensors and  displaying it on a dashboard. You obviously won't be penalized for something that's working correct, but is "boring".
- Note that IoT deployments don't necessarily just regurgitate the data they collect. You can choose to run ML models on the data, or use the data to control actuators, or use the data to make decisions, etc. The possibilities are endless.
- The guidelines for the project are intentionally kept vague, so that you can come up with your own ideas. If you are unsure about something, feel free to ask the TA.
- You can use the sensors and actuators provided to you, or you can get access to more from the TA or the EE department. I am sure everyone can find what they need.
- We have a variety of micro-controllers available in the Lab, including Raspberry Pis, Arduinos, STMs, etc. You should be using your esp32, but if you want to use more MCUs, feel free to ask.
- As discussed in the class, security implications are much more worsened in the case of IoT, where there are multiple attack avenues. Try to figure out the possible points of attacks in your system, and try to secure them. You can use any security mechanism you feel like mitigates the vulnerabilities. Who knows, you might get extra credit for that :)
