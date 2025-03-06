![](/image/MTDAA-heading.png)

The content is aimed at people interested in train control, programming, electronics and mechanics for model railway systems.

I would like to encourage everyone who develops Arduino solutions for model trains to publish their work here,
and you can choose whether you want to write your contribution in your native language or English.

Write to MTD2A@jorgen-madsen.dk to become affiliated and join teams.

The library is under construction and Danish documentation and guides need to be translated into English.

## Links

[Danish G model Railway Association](https://danskgmodelforening.dk/)

[Digital Command Control](https://en.wikipedia.org/wiki/Digital_Command_Control)

[NMRA Standards and Recommended Practices](https://www.nmra.org/index-nmra-standards-and-recommended-practices)

[Massoth Train Control Systems](https://www.massoth.de/en/)

[Arduino home](https://www.arduino.cc/)

[Arduino libraries](https://docs.arduino.cc/libraries/)

[Arduino Conrolled Model Railway](https://www.arcomora.com/)

[DCC-EX Model Railroading](https://dcc-ex.com/index.html#)

[The Pows (Parco)](https://usuaris.tinet.cat/fmco/home_en.htm)

[IoTT - The Internet of Toy Trains](https://myiott.org/index.php)

<br/> 

## Arduino C++ source code supporting 12 sensors
https://github.com/MTD2A/Train_Emergency_Stop

<br/> 

## Sensor Comparison

![](/image/Sensor%20Comparison.png)

<br/> 

## Speed 

The speed tells how many milliseconds the sensor needs to detect and process. The distance traveled from where the sensor is located, to where the locomotive has moved on to, depends on how quickly the sensor can process and action taken. Up to about 20 cm when train is running fast and the sensor is "slow".

## Distance 

The distances shown are those supported by the Arduino Nano program. Several sensors can measure longer. However, the measuring angle will typically limit the distances to 50 cm.

## Daylight

Most infrared sensors does not work in daylight. Light interference can be significantly reduced by mounting 1-2 cm aluminum tubes or similar blank tubes. At the same time, the measuring angle is reduced considerably, which provides more precise detection. Sensors should not be mounted with vertical tubes, as dust and dirt can get into the tubes, and thus there is a risk that the sensor will not function correctly. 

## Reliability

### Reflection

If dirt gets on the receiver or transmitter units, there is a risk that the circuit will not function correctly. This is particularly risky when mounted under rails. It is possible to use two sensors simultaneously to achieve greater reliability.
This applies to a lesser extent when mounting the ultrasonic sensors under rails, as the ultrasound is powerful and penetrating, and the sensor diameter is significantly larger Ø16 mm. 

### Break beam

Is the most accurate, reliable and efficient train detecton method.
