# My ESPHome Examples
This repo just contains my ESPHome related project files.

## Home Sensors
My first ESPHome projects are centered around a board that I am using to various ESPHome based sensors.

This board is available on PCBWay from this page: https://www.pcbway.com/project/shareproject/Home_Sensor_Board.html. You can order boards for yourself from PCBWay directly. The PCB project page has most of the components listed (the ones I purchased from Aliexpress).

You can also watch this video is you need more info on how it is designed:

[![PCB board](https://img.youtube.com/vi/WzjfJQtedCA/0.jpg)](https://www.youtube.com/watch?v=WzjfJQtedCA)

## ESPHome standalone in Windows
If you want to use EPSHome without Home Assistant, I have covered that setup in a separate video:

[![ESPHome without HA](https://img.youtube.com/vi/a3iay-g1AsI/0.jpg)](https://www.youtube.com/watch?v=a3iay-g1AsI)

My initial set of project will be used with Node-Red and ESPHome set up to communicate with MQTT. For Home Assistant you can just remove the MQTT related lines and you can use the sensor for Home Assistant.

## Living Room Sensor
This sensor will be mainly an environment sensor for the living room of my holiday home. It will be moniting temperature, humidity and pressure, and also include a radar motion sensor. The sensor is mains powered.
This board users a BME 680 sensor that measures temperautre, humidity, pressure and VOC and a radar or microwave motion sensor. The motion sensor has a simple digital output, therefore it you prefer to use a more regulare PIR sensor, you can just replace that. The header for the motion sensor contains 5V and GND and the OUT pin is the digital out from the sensor. Links to the sensors can be found in the PCB project page (link above).
This video explains more details on this project and how the livingroom.yaml file works:

[![Living Room](https://img.youtube.com/vi/a3iay-g1AsI/0.jpg)](https://www.youtube.com/watch?v=a3iay-g1AsI)

## Fan Controller
This sensor will be controlling a Aerauliqa Quantum HR-150 extractor fan which has 3 different speed setting with a built in heat exchanger and bypass function. The 4 relay board will be controlling this 3 function and the current clamp to monitor the current draw of the fan to later provide some control feedback.
Links to the sensors can be found in the PCB project page (link above).
This video explains more details on this project and how the livingroom.yaml file works:

[![Fan Controller](https://img.youtube.com/vi/UlQvo3mngLM/0.jpg)](https://www.youtube.com/watch?v=UlQvo3mngLM)
