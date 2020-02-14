# Ziyue-Yin-CCA-Digital-Electronic_2020

## week1
-see week 1 floder

## week2 
Description: In this video, it is a robot hand that can trace the movement of the user's hand when the user wears the gloves. 
The circuit is connected behind the glove in order to track the wispy movements of each joint of the finger.
link:https://youtu.be/mnurLBNWIdc

## week3
- Device: 
  A device can detect object’s height and weight

- Overall Concept:
  In this device, I am going to create a device which can detect the height and the weight of small object. 

- Sketch :

- Description: 
  For the height part, there will be a Distance Ranging Sensor to display the height of this object. If the object higher than a specific number, there would be a led turn to a red light. Otherwise, when the object comes close to the sensor, the light would be green. For the weight part, a Square Force-Sensitive Resistor can help detect the object’s weight approximately. When the object put on the Square Force-Sensitive Resistor, the force will be detect. If the force larger than the weight number set in advance, another led would turn to red. Otherwise, this led would be green when the object put on the force sensor. 

- Punch List:
  1\ Sensors and Outputs: Adafruit VL6180X Time of Flight Distance Ranging Sensor (VL6180); 
     Square Force-Sensitive Resistor (FSR)-Interlink 406 ; 
     2 LEDs 
  2\ step 1 : create a code and the first circuit with the distance sensor
     step 2 : create a code and the second circuit with the force sensor
  
"nice to have" : 
  1\ If it is possible, it would be a speaker to achieve an future goal that the distance sensor can detect the sound.
  2\ The distance sensor and the force sensor can detect the object simutaneously.
  3\ Or it is possible to have a reminder which produces by the speaker. 
  4\ It will be nice if there is an output for the force sensor to show the number of the object weight.


- 3 sensors research :
  1\ Adafruit VL6180X Time of Flight Distance Ranging Sensor (VL6180)
    link: https://www.adafruit.com/product/3316
  
     The VL6180X (sometimes called the VL6180) is a Time of Flight distance sensor like no other you've used! The sensor contains a very tiny laser source, and a matching sensor. The VL6180X can detect the "time of flight", or how long the laser light has taken to bounce back to the sensor. Since it uses a very narrow light source, it is good for determining distance of only the surface directly in front of it.

    Unlike sonars that bounce ultrasonic waves, the 'cone' of sensing is very narrow. Unlike IR distance sensors that try to measure the amount of light bounced, the VL6180X is much more precise and doesn't have linearity problems or 'double imaging' where you can't tell if an object is very far or very close.

  2\ Square Force-Sensitive Resistor (FSR)-Interlink 406
    link:https://www.adafruit.com/product/1075
    
     FSRs are sensors that allow you to detect physical pressure, squeezing and weight. They are simple to use and low cost. This sensor is a Interlink model 406 FSR with a 38mm square sensing region. Note that this sensor can't detect where on the square you pressed (for that, check out our ribbon soft pots or capacitive touch pad ).

    FSRs are basically a resistor that changes its resistive value (in ohms Ω) depending on how much its pressed. These sensors are fairly low cost, and easy to use but they're rarely accurate. They also vary some from sensor to sensor perhaps 10%. So basically when you use FSRs you should only expect to get ranges of response. While FSRs can detect weight, they're a bad choice for detecting exactly how many pounds of weight are on them.

    FSRs are made of plastic and the connection tab is crimped on delicate material. The best way to connect to these is to simply plug them into a breadboard or use a clamp-style connector like alligator clips, female header, or a terminal block. It is possible to solder onto the tabs but you must be very fast because if your iron is not good quality or you dally even a few seconds, you will melt the plastic and ruin the FSR! Don't attempt to solder directly to your FSR unless you are absolutely sure you have the skills to do so.
  
  3\ Adafruit 9-DOF Absolute Orientation IMU Fusion Breakout - BNO055
    link: https://www.adafruit.com/product/2472
  
    The sensor fusion algorithms (the secret sauce that blends accelerometer, magnetometer and gyroscope data into stable three-axis orientation output) can be mind-numbingly difficult to get right and implement on low cost real time systems.

    Bosch is the first company to get this right by taking a MEMS accelerometer, magnetometer and gyroscope and putting them on a single die with a high speed ARM Cortex-M0 based processor to digest all the sensor data, abstract the sensor fusion and real time requirements away, and spit out data you can use in quaternions, Euler angles or vectors.
    
    Description of what I learned: 
    
    There are a variety of sensors that are in different categories. Even some sensors are similar; they might work with different principles. The one sensor I found interested me is the fingerprint sensor, which could be a controller in the Arduino work. If it is possible, I will use it to control my LEDs or other outputs. 
    
    link: https://learn.adafruit.com/adafruit-optical-fingerprint-sensor
