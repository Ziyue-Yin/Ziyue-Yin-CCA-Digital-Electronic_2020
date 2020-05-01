# Ziyue-Yin-CCA-Digital-Electronic_2020

## Week 14: Final Project Presentation - Security Protection Device

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0269.jpeg) 

### Concept:
- This is a security device to drive strangers out of the door after midnight. It installs near the doorway. My roommates and I are living in a house in Ocean Ave. There is a potential safety hazard when we fall asleep, especially during the coronavirus time. This device can help us to scare the strangers coming at midnight. 

### Components :
- Basic Parts: Bread board / Wire / Arduino Uno board
- LDR - turn on the device when the surrounding is dark. 
- Ultrasonic Sensor - recognize if the strangers come close the house
- LED Lights - Red and Green, when someone comes close to the house, the red will turn on and the green will turn off. 
- Serial MP3 Player
- Speaker : yell at the strangers:"Get away from my house!"

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0256.jpeg) 
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0258.jpeg) 

### How it works and Prototype:

#### How it works:
This device turns on only at midnight which will be detected by the LDR. If there is someone close to the door at midnight, the distance sensor will discover. Then the speaker will yell at the stranger: “Get away from my house!”. Meanwhile, the red light will turn on and the green one will turn off. 

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0275.GIF) 

#### Prototype:
- At night, no one come close to the door:
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0269.jpeg) 

- Imitate someone comes close to the door:
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/final%20week%20image/IMG_0270.jpeg) 

### Presentation link:
- https://youtu.be/iVoFrzQOh0c

### Code:
- https://youtu.be/iVoFrzQOh0c

## Week 12: Final Project Part 1

### Project revise: 
- Use the LDR  to achieve the function of switch: The device turn on during the night, turn off at the daytime.
- The MP3 speaker cable is to play the voice of "Get away from my house!"
- Distance sensor to perceive if the stangers come close to the outdoor.
- LED light will turn on fade with the speaker's voice at the same time.

#### Resources of the sensors:
- Ultrasonic sensor with speaker: https://youtu.be/gLDoFxYp-Ek
- LED Fade : https://youtu.be/emPE8WUIFRg
- LDR : https://www.youtube.com/watch?v=qKku-mmwNIA

#### Process part 1:
- Steps to do:
- - Install the LDR 
- - Ultrasonic sensor and Speaker
- - LED Sensor

##### Attempt of part 1:
1\ During this week, I attempt to install the ultrasonic sensor, LDR and the LEDs together. 
At first step, I coded the Ultrasonic sensor and LED together, then coded the LDR seperately. 
I would like to use the red LED and the Green LED first. When the distance is less than 5 cm, the red light will turn on and meanwhile the Speaker will work. When the distance is more than 5 cm, the Green LED will turn on and the red one will turn off. 
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/IMG_0181.jpeg)  
Problems:
When I finish the code, the distance sensor can work, but the LEDs cannot work at the same time. 
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Mechatronics_2020/blob/master/final%20project/IMG_0182.jpeg)  

##### NEXT Step for the work: 
Next week, I am going to fix the LEDs' problem first, and then code the LDR, leds, Ultrasonic Sensor and Speaker togther. 

## Week 11: Final Project Proposal

### Concept: Get away from my house!

- This is a security device to drive strangers out of the door after midnight. It installs near the doorway. Now my roommates and I are living in a house in Ocean Ave. There is a potential safety hazard when we fall asleep, especially during the coronavirus time. This device can help us to scare the strangers coming at midnight. 

- How it works: This device turns on only at midnight. Use the remote control to turn on the device. If there is someone close to the door at midnight, the distance sensor will detect him. Then the speaker will yell at the stranger: “Get away from my house!”. Meanwhile, the led light will turn on. 

-  Concept Sketch
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week%2011/%E6%88%AA%E5%B1%8F2020-04-0921.20.44.png)  

##### Must have
- Basic Parts: Bread board / Wire / Arduino Uno board
- Remote Controller
- Ultrasonic Distance Sensor
- LED Light
- Speaker : https://www.adafruit.com/product/1314 / https://www.adafruit.com/product/1313 / https://www.adafruit.com/product/1313  (Select one of them)

##### Nice to have
- LED RGB Light (Coding the fade on)
- Remote Control the device on and off.

#### Steps to use the device :
- Use the remote controller to turn on the device at the midnight.
- When the strange person comes close, the led light will fade. 
- Meanwhile, the speaker will yell at the stranger: " Get away from my house!"
- Turn off the device when you get up.

- Optional : This device can also use during the time that the residents are not at home.

- Storyboard about how to use the device: 

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week%2011/digital%20electric_20200409231120-01.png)  

#### Steps to make the device :
- Set up the remote controller to turn the device on at the midnight and turn off during the daytime.
- Write the coding of remote controller, ultrasonic distance sensor, LED and Speaker.
- Find a way to record the voice which can play on the speaker. 
- Install them on the outdoor. 


## week7 - Midterm Project

Description

- In this mid term project, I am going to create a distance measure device. Within the different distances between the object and the device, there will be the different lights turning on and the specific distance number displayed on the digital screen. 
    
- Drawing of initial concept
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week7/concept%20drawing.jpg)  

- Picture of the first iteration

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week7/IMG_6997.jpeg)  

- In this distance measure device, when the distance is in 0-10 cm range, the led will be red.

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week7/IMG_7394.GIF)  

- When the distance is in 10-20 cm, the led will be blue.

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week7/IMG_7396.GIF)  

- When the distance is in 20-30 cm, the led will be green.

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week7/IMG_7395.GIF)  

List of Components:
- Arduino Board
- Breadboard and Jump Wires
- The LCD Screen 
- Potentiometer  - adjust the brightness of LCD screen
- Ultrasonic Sensor 
- RGB LED - OUTPUT to display the different distance ranges


- Code :
 This project code I have already put in the "week 7" folder.
 https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week7/code%20for%20Distance%20sensor%20and%20lcd%20screen

- Video link: 
https://youtu.be/O0MsUV0EuYU

## week6
At the end of week 5, I made the LCD screen circuit individually on the Arduino board. 

Here is my previous work.

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week%206%20upload/the%20end%20of%20wk5.GIF)  

And in the week, I attempt to connect my LCD screen and Ultrasonic Sensor together. It is to display the distance on the screen. 
However, when I combine the LCD and Ultrasonic Sensor together. There comes out a problem : the screen can only display the phrase "Out of range". I set the code: 

if (distance >= 400 || distance <= 2){
    lcd.print("Out of range");
    delay(500);
  }
  else {
    lcd.print(distance);
    lcd.print(" cm");
    delay(500);
  }

That's means when I move the object close to the sensor, it is possible to show the distance which is in the range of 2-400cm. 
However, it does not work.

![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week%206%20upload/wk6.GIF)  


## week5
This week I attempt to finish the digital screen. My schedule is to make the digital screen display the words and the distance sensor can work individually. However, my digital screen is not able to work. It can light, but can not type in the words. I hope I can solve it in class. 

I have already write the individual code for digital screen and my distance sensor. Next step is to combine them together. 

Process of my work: 
![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/week%205%20assign/digital%20screen%20display.jpg)  

## week4

This is my first mock up sketch for the mid-term project.

Sketch :![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/sketch%20for%20first%20mock%20up.jpg)  

Here is my first distance sensor circuit attempt.
Sensor Circuit:![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/Zoey%20Yin_firstMockUp/IMG_6732.jpeg)  
Sensor Circuit:![image](https://github.com/Ziyue-Yin/Ziyue-Yin-CCA-Digital-Electronic_2020/blob/master/Zoey%20Yin_firstMockUp/IMG_6733.jpeg)  


## week3
Device: 
- A device can detect object’s height and weight

Overall Concept:
- In this device, I am going to create a device which can detect the height and the weight of small object. 

Sketch :![devicesketch](devicesketch.jpg)   


Description: 
- For the height part, there will be a Distance Ranging Sensor to display the height of this object. If the object higher than a specific number, there would be a led turn to a red light. Otherwise, when the object comes close to the sensor, the light would be green. For the weight part, a Square Force-Sensitive Resistor can help detect the object’s weight approximately. When the object put on the Square Force-Sensitive Resistor, the force will be detect. If the force larger than the weight number set in advance, another led would turn to red. Otherwise, this led would be green when the object put on the force sensor. 

Punch List:
  - Sensors and Outputs: Adafruit VL6180X Time of Flight Distance Ranging Sensor (VL6180); 
     Square Force-Sensitive Resistor (FSR)-Interlink 406 ; 
     2 LEDs 
  - step 1 : create a sketch about the distance ranging sensor work circuit 
  - step 2 : write a code and create the circuit with the distance sensor
  - step 3 : test it
  
"nice to have" : 
  - play with a figureprint sensor
  - create a code and the second circuit with the force sensor
  - If it is possible, it would be a speaker to achieve an future goal that the distance sensor can detect the sound.
  - The distance sensor and the force sensor can detect the object simutaneously.
  - Or it is possible to have a reminder which produces by the speaker. 
  - It will be nice if there is an output for the force sensor to show the number of the object weight.

3 sensors research :
  - Adafruit VL6180X Time of Flight Distance Ranging Sensor (VL6180)
    link: https://www.adafruit.com/product/3316
  
     The VL6180X (sometimes called the VL6180) is a Time of Flight distance sensor like no other you've used! The sensor contains a very tiny laser source, and a matching sensor. The VL6180X can detect the "time of flight", or how long the laser light has taken to bounce back to the sensor. Since it uses a very narrow light source, it is good for determining distance of only the surface directly in front of it.

    Unlike sonars that bounce ultrasonic waves, the 'cone' of sensing is very narrow. Unlike IR distance sensors that try to measure the amount of light bounced, the VL6180X is much more precise and doesn't have linearity problems or 'double imaging' where you can't tell if an object is very far or very close.

  - Square Force-Sensitive Resistor (FSR)-Interlink 406
    link:https://www.adafruit.com/product/1075
    
     FSRs are sensors that allow you to detect physical pressure, squeezing and weight. They are simple to use and low cost. This sensor is a Interlink model 406 FSR with a 38mm square sensing region. Note that this sensor can't detect where on the square you pressed (for that, check out our ribbon soft pots or capacitive touch pad ).

    FSRs are basically a resistor that changes its resistive value (in ohms Ω) depending on how much its pressed. These sensors are fairly low cost, and easy to use but they're rarely accurate. They also vary some from sensor to sensor perhaps 10%. So basically when you use FSRs you should only expect to get ranges of response. While FSRs can detect weight, they're a bad choice for detecting exactly how many pounds of weight are on them.

    FSRs are made of plastic and the connection tab is crimped on delicate material. The best way to connect to these is to simply plug them into a breadboard or use a clamp-style connector like alligator clips, female header, or a terminal block. It is possible to solder onto the tabs but you must be very fast because if your iron is not good quality or you dally even a few seconds, you will melt the plastic and ruin the FSR! Don't attempt to solder directly to your FSR unless you are absolutely sure you have the skills to do so.
  
  - Adafruit 9-DOF Absolute Orientation IMU Fusion Breakout - BNO055
  
    link: https://www.adafruit.com/product/2472
  
    The sensor fusion algorithms (the secret sauce that blends accelerometer, magnetometer and gyroscope data into stable three-axis orientation output) can be mind-numbingly difficult to get right and implement on low cost real time systems.

    Bosch is the first company to get this right by taking a MEMS accelerometer, magnetometer and gyroscope and putting them on a single die with a high speed ARM Cortex-M0 based processor to digest all the sensor data, abstract the sensor fusion and real time requirements away, and spit out data you can use in quaternions, Euler angles or vectors.
    
Description of what I learned:  
   There are a variety of sensors that are in different categories. Even some sensors are similar; they might work with different principles. The one sensor I found interested me is the fingerprint sensor, which could be a controller in the Arduino work. If it is possible, I will use it to control my LEDs or other outputs. 
    
   link: https://learn.adafruit.com/adafruit-optical-fingerprint-sensor
   
## week2 
Description: In this video, it is a robot hand that can trace the movement of the user's hand when the user wears the gloves. 
The circuit is connected behind the glove in order to track the wispy movements of each joint of the finger.
link:https://youtu.be/mnurLBNWIdc

## week1
-see week 1 floder

