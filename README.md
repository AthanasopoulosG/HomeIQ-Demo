# HomeIQ-Demo
[![Watch the video](https://img.youtube.com/vi/WI-GMfCQGWU/0.jpg)](https://www.youtube.com/watch?v=WI-GMfCQGWU)


## HomeIQ
 HomeIQ is an IoT product that is to improve the daily living standards of an average user. It is a combination of hardware and software which effectively manages the resources of home . More specifically, as far as the hardware is concerned, it is an Arduino panel on which various other layers of material are embedded, such as humidity measuring sensors, temperature sensors, motion detectors and others. These sensors have to measure and collect data, communicate with each other and finally send their information to the user. As the sensors can be placed anywhere in the space, they support advanced wired and wireless communication protocols such as WiFi, Bluetooth, etc. 
 
 Οn the other hand, the software provides the ability to store, process and visualize the data. It also provides an interface to the user to access and process them in a simple and clear way. In addition, through this interface the user has the option to configure his devices / sensors, by sending commands to change the functionality of them. It is about an interactive communication between user and sensors. 
 
 Important to highlight is the modularity of HomeIQ, that is, a user can add functionality by adding plug and play extra hardware. In this way the potential of the HomeIQ is further expanded. 


 ### HomeIQ mainly consists of:
 - **An adruino based Command Center**: The Arduino Command center is purposed to gather real-time data and interact with 3rd party sensors. Such interaction can be a switch on/off of lights in a room, or a thermostat adjustment. The variety of the interactions is heavily dependent on the specifications of the 3rd party sensors(whether they have the ability to have their state altered or not).
 - **3rd Party Sensors**: The 3rd party sensors can be a variety of different devices that support universal communication protocols. These sensors/devices vary from simple data-transmitting only sensors(e.g. a humidity sensor) to more complex devices such as a “smart thermostat” which not only transmits real-time data to the user but also gives them the ability to change the temperature.
 - **A server**: The server's purpose is to gather the sensor & user information in a database to be processed later on.
 - **A Web application**: The web application’s purpose is the visualization of such data and the interaction with the user in regards to controlling the 3rd party devices & creating custom automations on demand.

### Product Functions
1. HomeIQ offers the opportunity to plug and play a variety of 3rd party devices on the HomeIQ mainframe through a web based setup process. Such process involves searching for devices with supported communication protocols in the area in close proximity to HomeIQ mainframe.
2. All data are collected from the HomeIQ mainframe and forwarded to the server.
3. All data are visualized in the web platform. Such visualization can be customized according to the needs of the user. One significant example of data visualization benefits of the app is the graphical display of the sensor's data for all or a specific room.
4. The user is able to control the devices in the network that offer that capability through the web platforms. Example is shown in the video-demo provided above in which the user has access to lighting system of the house with a simple mouse click.
5.  The user is able to create custom automations that combine different 3rd party devices. Such automations can involve complex device interaction that is coordinated from HomeIQ mainframe. E.g. if the built-in automation is enabled and if livingroom's and Bedroom's lights are on then turn on lights in Kid's room automatically.
