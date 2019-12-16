---
name: Seeeduino XIAO
category: Development Board
bzurl: 
oldwikiname: 
prodimagename:
surveyurl: 
sku: 102010328
tags:
---

![](https://github.com/SeeedDocument/Seeeduino-XIAO/raw/master/.img/Seeeduino-XIAO-wiki.jpg)

The Seeeduino XIAO is the smallest member of the Seeeduino family. It carries the powerful ATSAMD21G18A-MU which is a low-power microcontrollers. On the other hand, this little board has good performance in processing but needs less power. As a matter of fact, it is designed in a tiny size and can be used for wearable devices and small projects.

Seeeduino XIAO has 14 GPIO PINs, which can be used for 11 digital interfaces, 11 mock interfaces, 10 PWM interfaces (d1-d10), 1 DAC output pin D0, 1 SWD pad interface, 1 I2C interface, 1 SPI interface, 1 UART interface, Serial communication indicator (T/R), Blink light (L). The colors of LEDs(Power,L,RX,TX) are green, yellow, blue and blue. Moreover, Seeeduino XIAO has a Type-C interface which can supply power and download code. There are two reset button, you can short connect them to reset the board.

## Features

- Extra Header Pads(Power)
- KB Flash,KB SRAM
- Compatible with Arduino
- Breadboard-friendly
- Small size (17x21mm) as a thumb for wearable devices and small project.
- Protection cover for protecting the circuit

## Specification

|Item|Value|
|---|---|
|CPU|ATSAMD21G18A-MU|
|Maximum CPU frequency|MHz|
|Flash Memory|KB|
|SRAM|KB|
|Digital I/O Pins|11|
|Analog I/O Pins|11|
|I2C interface|1|
|SWD pad interface|1|
|SPI interface|1|
|UART interface|1|
|Power supply and downloading interface| Type-C|
|Power|3.3V/5V DC|

!!!note:
- The MCU of this design is powered by 3.3v, please pay attention not to introduce the IO level of 5V into the IO interface of the system, otherwise the chip may be damaged;
- Please pay attention to use, do not lift the shield cover.

## Hardware Overview


![](https://github.com/SeeedDocument/Seeeduino-XIAO/raw/master/.img/Seeeduino%20XIAO%20Pins.jpg)




## Getting Started


First of all, you need to install the latest version of Arduino IDE.



<p style="text-align:center"><a href="https://www.seeedstudio.com/Seeeduino-Femto-p-4323.html" target="_blank"><img src="https://raw.githubusercontent.com/SeeedDocument/Seeeduino_Stalker_V3_1/master/images/Download_IDE.png" /></a></p>


### Install the board in Arduino IDE


- **Step1**
Open the Arduino IDE, click **File -> New** to create a new sketch.


![](https://github.com/SeeedDocument/Seeeduino-Femto/raw/master/.img/wiki1.png)


- **Step2**
Click **File-> Preferences**, and copy below url to **Additional Boards Manager URLs**.


https://raw.githubusercontent.com/Seeed-Studio/Seeed_Platform/master/package_seeeduino_boards_index.json


![](https://github.com/SeeedDocument/Seeeduino-Femto/raw/master/.img/wiki2.png)


- **Step3**
Click **Tools-> Board-> Boards Manager...**, print "Seeeduino Femto" in the searching blank. Here comes the "Seeed SAMD Boards". Install it.


![](https://github.com/SeeedDocument/Seeeduino-XIAO/raw/master/.img/wiki3.png)


- **Step4**
After installing the board, click **Tools-> Board**, find "Seeeduino Femto M0" and select it. Now you have already set up the board of Seeeduino Femto for Arduino IDE.


![](https://github.com/SeeedDocument/Seeeduino-XIAO/raw/master/.img/wiki4.png)


From now on, you can build your own project with Seeeduino Femto based on Arduino IDE platform.



## Resourses

- **[Zip]** [Seeeduino XIAO Repository](https://github.com/Seeed-Studio/ArduinoCore-samd/archive/master.zip)
- **[PDF]** [SAMD datasheet](https://github.com/SeeedDocument/Seeeduino-XIAO/raw/master/res/310010095_SMD%20IC%20MCU%3BVFQFN-48%20%E8%A3%B8%E9%9C%B2%E7%84%8A%E7%9B%98_%E8%A7%84%E6%A0%BC%E4%B9%A6.pdf)
- **[PDF]** [Hardware manual](https://github.com/SeeedDocument/Seeeduino-XIAO/raw/master/res/seeeduino%20femto_v1.0_SCH_190806.pdf)


## Tech Support
Please do not hesitate to submit the issue into our [forum](https://forum.seeedstudio.com/).
