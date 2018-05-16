# SENZ010 红外光电开关、避障传感器(基础板）

###### 翻译

> `英文` 请参考 [`这里`](https://github.com/njustcjj/SENZ010-Adjustable-Infrared-Sensor-Switch-Baisc/blob/master/README.md)

> `中文` 请参考 [`这里`](https://github.com/njustcjj/SENZ010-Adjustable-Infrared-Sensor-Switch-Baisc/blob/master/README_CN.md)

![](https://github.com/njustcjj/SENZ010-Adjustable-Infrared-Sensor-Switch-Baisc/blob/master/pic/SENZ010.jpg "SENZ010")
 

### 产品介绍

> SENZ009是采用夏普公司的距离传感器，有效测距10cm，开关量输出。合理的安装传感器就可以准确的检测出台阶，从而让机器人考虑是否该绕道而行。还能作近距离避障传感器。

> 
> 用途：机器人防摔、机器人避障、黑白循迹、流水线计数等

### 产品参数

* 信号类型：数字输出
- 工作电压：+3.3～5V
- 工作电流：<10mA
- 工作温度范围 ：0℃～＋70℃
- 探测距离：2～30cm
- 尺寸：32 x 14 mm
- 检测角度：35°


### 使用教程

#### 引脚定义

|Sensor pin|Ardunio Pin|Function Description|
|-|:-:|-|
|VCC|3.3V~5V|Power|
|GND|GND||
|DO|Digital pin|Digital Output|



![](https://github.com/njustcjj/SENZ010-Adjustable-Infrared-Sensor-Switch-Baisc/blob/master/pic/SENZ010_pin.jpg "引脚定义") 


#### 连线图

![](https://github.com/njustcjj/SENZ010-Adjustable-Infrared-Sensor-Switch-Baisc/blob/master/pic/SENZ010_connect.png "连线图") 


### 示例代码

	void setup(){
	 Serial.begin(57600);  
	}

	void loop(){
	  Serial.print("Digital Signal:");
	  Serial.println(digitalRead(3),BIN); 
	  delay(50);
	}



### 购买[*SENZ010 红外光电开关、避障传感器(基础板）*](https://www.ebay.com/).