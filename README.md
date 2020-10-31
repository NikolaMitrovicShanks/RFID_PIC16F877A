# RFID_PIC16F877A
RFID system is a system that provides identification of the students, employees, and other using RFID tag, in order to monitor their presence, work, working time and many other. 
This article is in sponsor with JLCPCB. I really thank JLCPCB for sponsoring this project.

Step 1: Introduction
This system is designed around PIC microcontroller PIC16F877A and RFID Reader RDM6300, which is 125 kHz reader. It also features LCD 1602 display, a buzzer, servo SG90 and a voltage regulating part. When a tag is detected, display gives information about which tag is detected, buzzer sounds a beep, LED turns on, and a servo is activated.

Step 2: Components Required
PIC16F877A
 
This powerful CMOS FLASH-based 8-bit microcontroller packs Microchip’s powerful PIC architecture into a 40- or 44-pin package. The PIC16F877A features 256 bytes of EEPROM data memory, self-programming, an ICD, 2 Comparators, 8 channels of 10-bit Analog-to-Digital (A/D) converter, 2 capture/compare/PWM functions, the synchronous serial port can be configured as either 3-wire Serial Peripheral Interface (SPI™) or the 2-wire Inter-Integrated Circuit (I²C™) bus and a Universal Asynchronous Receiver Transmitter (USART).
Detailed Features of PIC16F877A:
-	CPU: 8-bit PIC
-	Pin Count: 40
-	Max. CPU Speed (MHz): 20
-	Internal Oscillator: No
-	No. of ADC channels: 14
-	Max ADC Resolution (bits): 10
-	Internal Voltage Reference: Yes
-	No. of UART module: 1
-	No. of SPI Module: 1
-	No. of I2C module: 1
-	Cap. touch Channels: 11
-	Minimum Operating Voltage (V): 2
-	Maximum Operating Voltage (V): 5.5

RDM6300
 
RDM6300 125KHz card reader mini-module is designed for reading code from 125KHz card compatible read-only tags and read/write card. It can be applied in office/home security, personal identification, access control, anti-forgery, interactive toy and production control systems etc.
Key Features:
-	Support external antenna;
-	Maximum effective distance up to 50 mm;
-	Less than 100 ms decoding time;
-	UART interface;
-	Support EM4100 compatible read only or read/write tags;
-	Small outline design.

LCD1602 Display
 
The display is composed of a 16-character x 2-line LCD display with a blue backlight and white characters.  Each of the characters are composed of a 5 x 8 dot matrix for good character representation. The backlight has a potentiometer for adjustment of the contrast of the display for best viewing.
Key features of LCD1602 display:
-	16-character x 2-line Blue LCD;
-	Optional I2C interface;
-	Adjustable backlight intensity and contrast;
-	5 V operation.

Servo SG90
 
Micro Servo Motor SG90 is a tiny and lightweight server motor with high output power. Servo can rotate approximately 180 degrees (90 in each direction). You can use any servo code, hardware or library to control these servos. Good for beginners who want to make stuff move without building a motor controller with feedback & gear box, especially since it will fit in small places. 
Key features:
Weight: 9 g
Dimension: 22.2 x 11.8 x 31 mm approx.
Stall torque: 1.8 kgf·cm
Operating speed: 0.1 s/60 degree
Operating voltage: 4.8 V (~5V)
Dead band width: 10 µs
Temperature range: 0 ºC – 55 ºC

Passive Components
Buzzer
SMD LM7805 voltage regulator
3x 1206 LED (one red, two green)
3x SMD 0805 resistor 330 Ω
1x SMD 0805 resistor 10 KΩ
2.1 mm DC connector
SMD Quartz oscillator 4 MHz 
2x 2pin KF301 connector
1x 3pin KF301 connector
3x SMD 0805 capacitor 100 nF
1x SMD Potentiometer 10 kΩ
1x16 Female Header

Step 3: Schematics

 
RDM6300 is connected to PIC16F877A through UART pins of the PIC. Display is connected in parallel data mode, while servo is connected to the pin RB0. Buzzer is connected to the pin x. Power is supplied through the classic DC connector and through the voltage regulating circuit. 

Step 4: Ordering the PCBs
After the both schematics and layout is done, next step is ordering the PCB. For ordering, best site that I have come to is JLCPCB. To order, just go to their website, register, and go to Quote now button. 
 
JLCPCB is sponsor of this project. JLCPCB (Shenzhen JLC Electronics Co., Ltd.), is the largest PCB prototype enterprise in China and a high-tech manufacturer specializing in quick PCB prototype and small-batch PCB production. You can order a minimum of 5 PCBs for just $2.

Step 5: Add Your Gerber File
To get your designed board, you need to upload the gerber files. Of course, JLCPCB site offers detailed instructions on how to generate gerber files for different softwares. When gerber files are generated, zip them, and upload them as a single file to JLCPCB. 
 
When the zip files are uploaded, you can see them in the gerber viewer. There, you can make sure whether everything is alright with your board, and does it look ok. After that, re-check board size, board color and other properties, and proceed to checkout. You can order 5 PCBs for just $2
 
To place the order, click on “SAVE TO CART” button.
This PCB was manufactured in 3 days, and arrived in two weeks using FedEx. Of course, all 5 PCBs were greatly packed in the box and in the bubble envelope, so there were no chance that boards get damaged. Quality of the PCBs was, and always has been, BRILLIANT! 

        

          
