### Major Project 

## Title : Using LDR datas is collected on the cloud and analysing it the output is given to LED,it is nothing but designing a Automatically glowing light when its dark.

## Components Reqiured:
+ ESP8266 12E NodeMCU (Lolin)
+ 1 LDR (Photoresistance)
+ 2 Resistors of 1.5K
+ 1 Resistors of 10K
+ 1 Diode led
+ Bread board

## Procedure:
+ Circuit is connected in such a way that Vcc is connected in voltage divider with 1.5k and 1.5k and 10 k resistor is connected in series with LDR and A0 pin of NodeMCU.Output is taken from a output pin of NodeMCU and make sure every node is grounded.Vcc that is supply range is 3.3V to 5V
+ Datas are collected,saved and can be monitored anytime,anywhere using cloud and it provides us a advantage of controlling or commanding using it.And the cloud platform we use is Adafruit IO.
+ Adafruit IO:  It is a solution for the construction of applications IoT created by Adafruit Industries, the well-known open-source hardware marketer, have created this platform for the internet of things based on platforms known as Arduino, Raspberry pi, ESP8266, Intel Galileo, Serial devices And Wifi among others. The Communication API is based on MQTT client with Adafruit servers. In a few minutes you can create a high quality dashboard.
+ Created a account on Adafruit and added downloaded libraries in the code and add the SSID and password in Adurino IDE and then enter username and key in the code and include header file of ESP8266
+As the authentication details for wifi and adafruit is given.This Arduino code, generates the Feed “photocell” associated with the LDR that performs the reading to the ADC0 and coded such a way that ON or OFF command is given to LED and meanwhile system transmits the intensity values to the cloud.
+ The program keeps on running and datas are stored on the cloud with time and automation of light is done.And the code is explained clearly in the code file attached using instruction command.

## Purpose of this project :
+ As an IOT architect,we save electrical energy,time,money by designing a IOT based Light.
+ This saves less man power and developing an idea of fully automated industries.
+ This project helped us understand the basic idea behind connecting microcontroller and hardware with the cloud,and we got to know how efficient a cloud can help us in this modern world and by utilising the cloud so many natural resources can saved,in security domain it brings an revolution and in many other domains it provides advantage.
