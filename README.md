# Cybersecurity : CSN150-Doc-Template

## Name of Project
ESP32 Introduction

## Purpose
Set up ESP32 and Arduino enviornment. Execute sketch " Wifiscanner". 

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation

##### Video 1: 

##### Other Links: 


## Steps I followed
Write the steps you followed here.  This way you can keep track of where you might have messed up if the project does not work. 
1. 
## Problems
Note your problems or errors here.  Google any error you may come across, and not what you tried (even if it does not work), and what was the final answer. Document your errors and solutions that worked for you.  

### Problem 1
[PYI-19228:WARNING] Failed to remove temporary directory: C:\Users\atswf\AppData\Local\Temp\_MEI192282
Sketch uses 294394 bytes (9%) of program storage space. Maximum is 3145728 bytes.
Global variables use 20576 bytes (6%) of dynamic memory, leaving 307104 bytes for local variables. Maximum is 327680 bytes.
esptool.py v4.8.1
Serial port COM3
Connecting......................................

A fatal error occurred: Failed to connect to ESP32: No serial data received.
For troubleshooting steps visit: https://docs.espressif.com/projects/esptool/en/latest/troubleshooting.html
Failed uploading: uploading error: exit status 2

## Atemps solution 
### Problem 1

* Manually restarted the esp32 cam with buttons

* Chat GPT Powershell restart cmd:
   [System.IO.Ports.SerialPort]::getportnames()  # List available ports

   $port = new-Object System.IO.Ports.SerialPort COM3,115200,None,8,one
   $port.Open()
   $port.WriteLine("import machine; machine.reset()")
   $port.Close()

* Changed USB to Micro cable

* Tried on two different computers 

## Solutions
### problem 1



## Final Report


## Arduino idle installment IMG:
![This is an image of Arduino idle installed locally on my computer](C:\Users\ferre\OneDrive\Pictures\Screenshots\Screenshot 2025-05-04 143254.png)


