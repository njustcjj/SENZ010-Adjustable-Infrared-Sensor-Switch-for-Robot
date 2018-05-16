# SENZ010-Adjustable-Infrared-Sensor-Switch-for-Robot

###### Translation

> For `English`, please click [`here.`](https://github.com/njustcjj/SENZ010-Adjustable-Infrared-Sensor-Switch-for-Robot/blob/master/README.md)

> For `Chinese`, please click [`here.`](https://github.com/njustcjj/SENZ010-Adjustable-Infrared-Sensor-Switch-for-Robot/blob/master/README_CN.md)

![](https://github.com/njustcjj/SENZ010-Adjustable-Infrared-Sensor-Switch-for-Robot/blob/master/pic/SENZ010.jpg "SENZ010")


### Introduction

>  This is an edge detection sensor from DFRobot. It will help your robot detect the edge of a precipice, preventing it from falling off a table or down the stairs to it's certain demise! This IR distance sensor is connected to an arduino digital pin.
>
> Usage : robot to avoid obstacles and falling off the stairs, industrial flow line to account num.



### Specification

- Power supply: 3.3 ~ 5V
- Working Current: <10mA
- Adjustable detection range: 2cm - 30cm
- Digital output:
	- "0" - found barrier (~0V)
	- "1" - no barrier (~4V)
- Size: 32 x 14 mm

### Tutorial

#### Wire Definition

|Sensor pin|Ardunio Pin|Function Description|
|-|:-:|-|
|VCC|3.3V~5V|Power|
|GND|GND||
|DO|Digital pin|Digital Output|

![](https://github.com/njustcjj/SENZ010-Adjustable-Infrared-Sensor-Switch-for-Robot/blob/master/pic/SENZ010_pin.jpg "Pin Definition") 

#### Connecting Diagram

![](https://github.com/njustcjj/SENZ010-Adjustable-Infrared-Sensor-Switch-for-Robot/blob/master/pic/SENZ010_connect.png "Connecting Diagram") 

#### Sample Code


	void setup(){
	 Serial.begin(57600);  
	}

	void loop(){
	  Serial.print("Digital Signal:");
	  Serial.println(digitalRead(3),BIN); 
	  delay(50);
	}



### Purchasing [*SENZ010 Adjustable Infrared Sensor Switch for Robot*](https://www.ebay.com/).
