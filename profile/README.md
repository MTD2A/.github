# Welcome to <ins>M</ins>odel <ins>T</ins>rain <ins>D</ins>etection <ins>A</ins>nd <ins>A</ins>ction - MTD2A

The content is aimed at people interested in train control, programming, electronics and mechanics for model railway systems.

I would like to encourage everyone who develops Arduino solutions for model trains to publish their work here,
and you can choose whether you want to write your contribution in your native language or English.

Write to MTD2A@jorgen-madsen.dk to become affiliated and join team.
<br/>

## MTD2A main repository
[MTD2A/MTD2A](https://github.com/MTD2A/MTD2A) is part of the official [Arduino library](https://docs.arduino.cc/libraries/), and can be downloaded directly from 
the **Arduino IDE** (Integrated Development Environment) via the [Library Manager](https://github.com/MTD2A/MTD2A/blob/main/image/Arduino-IDE-MTD2A-library-examples.png). 12 use case [examples](https://github.com/MTD2A/MTD2A/tree/main/examples#readme) have been prepared.
<br/>

### links to interesting websites about Arduino, trains and electronics
[Interesting links](https://github.com/MTD2A/.github/blob/main/links.md)
 
### Train emergencey stop system
[Arduino C++ source code supporting 12 sensors](https://github.com/MTD2A/Train_Emergency_Stop)

## Sensor Comparison

![](/image/Sensor%20Comparison.png)

<br/> 

### Speed 

The speed tells how many milliseconds the sensor needs to detect and process. The distance traveled from where the sensor is located, to where the locomotive has moved on to, depends on how quickly the sensor can process and action taken. Up to about 20 cm when train is running fast and the sensor is "slow".

### Distance 

The distances shown are those supported by the Arduino Nano program. Several sensors can measure longer. However, the measuring angle will typically limit the distances to 50 cm.

### Daylight

Most infrared sensors does not work in daylight. Light interference can be significantly reduced by mounting 1-2 cm aluminum tubes or similar blank tubes. At the same time, the measuring angle is reduced considerably, which provides more precise detection. Sensors should not be mounted with vertical tubes, as dust and dirt can get into the tubes, and thus there is a risk that the sensor will not function correctly. 

### Reliability

**Reflection** If dirt gets on the receiver or transmitter units, there is a risk that the circuit will not function correctly. This is particularly risky when mounted under rails. It is possible to use two sensors simultaneously to achieve greater reliability.
This applies to a lesser extent when mounting the ultrasonic sensors under rails, as the ultrasound is powerful and penetrating, and the sensor diameter is significantly larger Ø16 mm. 

<br/>

**Break beam** Is the most accurate, reliable and efficient train detecton method.
