---
title: "Ultrasonic Parking Sensor"
excerpt: "Hardware implementation of Ultrasonic Sensor"
collection: portfolio
---
<img src='/images/proj1_1.jpg'>
My partner and I designed this parking sensor using a simple non-inverting amplifier circuit and an ultrasonic sensor. 
There are two LEDs (red and blue) that indicates how close an object is to the sensor. Anything beyond 20cm won't light up the LEDs. The blue LED turns on when an object is detected about 10cm away from the sensor, and both the blue and red LEDs turn on when an object is within 5cm. 

## Key Takeaways 
- Supplying different voltages to different components within a single circuit using only one voltage supply.
- Signal amplification using Schmitt trigger
- Converting PWM signal to DC signal
