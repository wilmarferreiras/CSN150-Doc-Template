# Cybersecurity : CSN150-Doc-Template

## Name of Project         
ESP32 Final Project- Whatsapp API

## Purpose
We are meant to troubleshoot and figure out the how  to get Whatsapp API working and sending messages  to our phone.   
## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation
![https://randomnerdtutorials.com/esp32-send-messages-whatsapp/](https://randomnerdtutorials.com/esp32-send-messages-whatsapp/)
##### Video 1: 
No videos during this process the documentation link was super helpful. 
##### Other Links: 
Other materials I used was ChatGPT, but it was not as helpful as the Whatsapp API documentation.  

## Steps I followed
Write the steps you followed here.  This way you can keep track of where you might have messed up if the project does not work. 
1. I set up the API key by using the number referred on the documentation
2. I made sure that the APIKey was working by using the refrence link provided in the documentation to send message via php
3. I copied the example code in the documentation for the whatsapp API
4. I changed the SSID and password
5. I changed the phone number and entered the API key
6.I downloaded the UrlEncoder by fowllowing instructions from documentation 
7. Finally I canged the the message and send uploaded the code into the esp32-cam board       
## Problems
Note your problems or errors here.  Google any error you may come across, and not what you tried (even if it does not work), and what was the final answer. Document your errors and solutions that worked for you.  

### Problem 1

FQBN: esp32:esp32:esp32cam
Using board 'esp32cam' from platform in folder: C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0
Using core 'esp32' from platform in folder: C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0

cmd /c if exist "C:\\Users\\ferre\\OneDrive\\Documents\\Arduino\\whatsappAPI\\partitions.csv" COPY /y "C:\\Users\\ferre\\OneDrive\\Documents\\Arduino\\whatsappAPI\\partitions.csv" "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\partitions.csv"
cmd /c if not exist "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\partitions.csv" if exist "C:\\Users\\ferre\\AppData\\Local\\Arduino15\\packages\\esp32\\hardware\\esp32\\3.2.0\\variants\\esp32\\partitions.csv" COPY "C:\\Users\\ferre\\AppData\\Local\\Arduino15\\packages\\esp32\\hardware\\esp32\\3.2.0\\variants\\esp32\\partitions.csv" "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\partitions.csv"
cmd /c if not exist "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\partitions.csv" COPY "C:\\Users\\ferre\\AppData\\Local\\Arduino15\\packages\\esp32\\hardware\\esp32\\3.2.0\\tools\\partitions\\huge_app.csv" "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\partitions.csv"
        1 file(s) copied.
cmd /c IF EXIST "C:\\Users\\ferre\\OneDrive\\Documents\\Arduino\\whatsappAPI\\bootloader.bin" ( COPY /y "C:\\Users\\ferre\\OneDrive\\Documents\\Arduino\\whatsappAPI\\bootloader.bin" "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\whatsappAPI.ino.bootloader.bin" ) ELSE ( IF EXIST "C:\\Users\\ferre\\AppData\\Local\\Arduino15\\packages\\esp32\\hardware\\esp32\\3.2.0\\variants\\esp32\\bootloader.bin" ( COPY "C:\\Users\\ferre\\AppData\\Local\\Arduino15\\packages\\esp32\\hardware\\esp32\\3.2.0\\variants\\esp32\\bootloader.bin" "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\whatsappAPI.ino.bootloader.bin" ) ELSE ( "C:\\Users\\ferre\\AppData\\Local\\Arduino15\\packages\\esp32\\tools\\esptool_py\\4.9.dev3\\esptool.exe" --chip esp32 elf2image --flash_mode dio --flash_freq 80m --flash_size 4MB -o "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\whatsappAPI.ino.bootloader.bin" "C:\\Users\\ferre\\AppData\\Local\\Arduino15\\packages\\esp32\\tools\\esp32-arduino-libs\\idf-release_v5.4-2f7dcd86-v1\\esp32\\bin\\bootloader_qio_80m.elf" ) )
esptool.py v4.8.1
Creating esp32 image...
Merged 2 ELF sections
Successfully created esp32 image.
cmd /c if exist "C:\\Users\\ferre\\OneDrive\\Documents\\Arduino\\whatsappAPI\\build_opt.h" COPY /y "C:\\Users\\ferre\\OneDrive\\Documents\\Arduino\\whatsappAPI\\build_opt.h" "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\build_opt.h"
cmd /c if not exist "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\build_opt.h" type nul > "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\build_opt.h"
cmd /c type nul > "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9/file_opts"
cmd /c COPY /y "C:\\Users\\ferre\\AppData\\Local\\Arduino15\\packages\\esp32\\tools\\esp32-arduino-libs\\idf-release_v5.4-2f7dcd86-v1\\esp32\\sdkconfig" "C:\\Users\\ferre\\AppData\\Local\\arduino\\sketches\\9A47C0B67FD8740BCEA97149660FB9D9\\sdkconfig"
        1 file(s) copied.
Detecting libraries used...
C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp-x32\2411/bin/xtensa-esp32-elf-g++ -c @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/cpp_flags -w -Os -Werror=return-type -w -x c++ -E -CC -DF_CPU=240000000L -DARDUINO=10607 -DARDUINO_ESP32_DEV -DARDUINO_ARCH_ESP32 -DARDUINO_BOARD="ESP32_DEV" -DARDUINO_VARIANT="esp32" -DARDUINO_PARTITION_huge_app -DARDUINO_HOST_OS="windows" -DARDUINO_FQBN="esp32:esp32:esp32cam:CPUFreq=240,FlashFreq=80,FlashMode=qio,PartitionScheme=huge_app,DebugLevel=none,EraseFlash=none" -DESP32=ESP32 -DCORE_DEBUG_LEVEL=0 -DBOARD_HAS_PSRAM -mfix-esp32-psram-cache-issue -mfix-esp32-psram-cache-strategy=memw -DARDUINO_USB_CDC_ON_BOOT=0 @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/defines -IC:\Users\ferre\OneDrive\Documents\Arduino\whatsappAPI -iprefix C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/include/ @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/includes -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/qio_qspi/include -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\cores\esp32 -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\variants\esp32 @C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9/build_opt.h @C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9/file_opts C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9\sketch\whatsappAPI.ino.cpp -o nul
Alternatives for WiFi.h: [WiFi@3.2.0]
ResolveLibrary(WiFi.h)
  -> candidates: [WiFi@3.2.0]
C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp-x32\2411/bin/xtensa-esp32-elf-g++ -c @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/cpp_flags -w -Os -Werror=return-type -w -x c++ -E -CC -DF_CPU=240000000L -DARDUINO=10607 -DARDUINO_ESP32_DEV -DARDUINO_ARCH_ESP32 -DARDUINO_BOARD="ESP32_DEV" -DARDUINO_VARIANT="esp32" -DARDUINO_PARTITION_huge_app -DARDUINO_HOST_OS="windows" -DARDUINO_FQBN="esp32:esp32:esp32cam:CPUFreq=240,FlashFreq=80,FlashMode=qio,PartitionScheme=huge_app,DebugLevel=none,EraseFlash=none" -DESP32=ESP32 -DCORE_DEBUG_LEVEL=0 -DBOARD_HAS_PSRAM -mfix-esp32-psram-cache-issue -mfix-esp32-psram-cache-strategy=memw -DARDUINO_USB_CDC_ON_BOOT=0 @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/defines -IC:\Users\ferre\OneDrive\Documents\Arduino\whatsappAPI -iprefix C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/include/ @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/includes -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/qio_qspi/include -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\cores\esp32 -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\variants\esp32 -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\libraries\WiFi\src @C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9/build_opt.h @C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9/file_opts C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9\sketch\whatsappAPI.ino.cpp -o nul
Alternatives for Network.h: [Networking@3.2.0]
ResolveLibrary(Network.h)
  -> candidates: [Networking@3.2.0]
C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp-x32\2411/bin/xtensa-esp32-elf-g++ -c @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/cpp_flags -w -Os -Werror=return-type -w -x c++ -E -CC -DF_CPU=240000000L -DARDUINO=10607 -DARDUINO_ESP32_DEV -DARDUINO_ARCH_ESP32 -DARDUINO_BOARD="ESP32_DEV" -DARDUINO_VARIANT="esp32" -DARDUINO_PARTITION_huge_app -DARDUINO_HOST_OS="windows" -DARDUINO_FQBN="esp32:esp32:esp32cam:CPUFreq=240,FlashFreq=80,FlashMode=qio,PartitionScheme=huge_app,DebugLevel=none,EraseFlash=none" -DESP32=ESP32 -DCORE_DEBUG_LEVEL=0 -DBOARD_HAS_PSRAM -mfix-esp32-psram-cache-issue -mfix-esp32-psram-cache-strategy=memw -DARDUINO_USB_CDC_ON_BOOT=0 @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/defines -IC:\Users\ferre\OneDrive\Documents\Arduino\whatsappAPI -iprefix C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/include/ @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/includes -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/qio_qspi/include -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\cores\esp32 -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\variants\esp32 -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\libraries\WiFi\src -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\libraries\Network\src @C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9/build_opt.h @C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9/file_opts C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9\sketch\whatsappAPI.ino.cpp -o nul
Alternatives for HTTPClient.h: [HTTPClient@3.2.0]
ResolveLibrary(HTTPClient.h)
  -> candidates: [HTTPClient@3.2.0]
C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp-x32\2411/bin/xtensa-esp32-elf-g++ -c @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/cpp_flags -w -Os -Werror=return-type -w -x c++ -E -CC -DF_CPU=240000000L -DARDUINO=10607 -DARDUINO_ESP32_DEV -DARDUINO_ARCH_ESP32 -DARDUINO_BOARD="ESP32_DEV" -DARDUINO_VARIANT="esp32" -DARDUINO_PARTITION_huge_app -DARDUINO_HOST_OS="windows" -DARDUINO_FQBN="esp32:esp32:esp32cam:CPUFreq=240,FlashFreq=80,FlashMode=qio,PartitionScheme=huge_app,DebugLevel=none,EraseFlash=none" -DESP32=ESP32 -DCORE_DEBUG_LEVEL=0 -DBOARD_HAS_PSRAM -mfix-esp32-psram-cache-issue -mfix-esp32-psram-cache-strategy=memw -DARDUINO_USB_CDC_ON_BOOT=0 @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/defines -IC:\Users\ferre\OneDrive\Documents\Arduino\whatsappAPI -iprefix C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/include/ @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/includes -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/qio_qspi/include -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\cores\esp32 -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\variants\esp32 -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\libraries\WiFi\src -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\libraries\Network\src -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\libraries\HTTPClient\src @C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9/build_opt.h @C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9/file_opts C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9\sketch\whatsappAPI.ino.cpp -o nul
Alternatives for NetworkClientSecure.h: [NetworkClientSecure@3.2.0]
ResolveLibrary(NetworkClientSecure.h)
  -> candidates: [NetworkClientSecure@3.2.0]
C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp-x32\2411/bin/xtensa-esp32-elf-g++ -c @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/cpp_flags -w -Os -Werror=return-type -w -x c++ -E -CC -DF_CPU=240000000L -DARDUINO=10607 -DARDUINO_ESP32_DEV -DARDUINO_ARCH_ESP32 -DARDUINO_BOARD="ESP32_DEV" -DARDUINO_VARIANT="esp32" -DARDUINO_PARTITION_huge_app -DARDUINO_HOST_OS="windows" -DARDUINO_FQBN="esp32:esp32:esp32cam:CPUFreq=240,FlashFreq=80,FlashMode=qio,PartitionScheme=huge_app,DebugLevel=none,EraseFlash=none" -DESP32=ESP32 -DCORE_DEBUG_LEVEL=0 -DBOARD_HAS_PSRAM -mfix-esp32-psram-cache-issue -mfix-esp32-psram-cache-strategy=memw -DARDUINO_USB_CDC_ON_BOOT=0 @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/defines -IC:\Users\ferre\OneDrive\Documents\Arduino\whatsappAPI -iprefix C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/include/ @C:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/flags/includes -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\tools\esp32-arduino-libs\idf-release_v5.4-2f7dcd86-v1\esp32/qio_qspi/include -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\cores\esp32 -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\variants\esp32 -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\libraries\WiFi\src -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\libraries\Network\src -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\libraries\HTTPClient\src -IC:\Users\ferre\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.2.0\libraries\NetworkClientSecure\src @C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9/build_opt.h @C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9/file_opts C:\Users\ferre\AppData\Local\arduino\sketches\9A47C0B67FD8740BCEA97149660FB9D9\sketch\whatsappAPI.ino.cpp -o nul
C:\Users\ferre\OneDrive\Documents\Arduino\whatsappAPI\whatsappAPI.ino:14:10: fatal error: UrlEncode.h: No such file or directory
   14 | #include <UrlEncode.h>
      |          ^~~~~~~~~~~~~
compilation terminated.
Alternatives for UrlEncode.h: []
ResolveLibrary(UrlEncode.h)
  -> candidates: []
exit status 1

Compilation error: UrlEncode.h: No such file or directory

## Atemps solution 
### Problem 1

* Manually restarted the esp32 cam with buttons
* Used Chatgpt- reseaved the idea of downloading UrlEncode, however was not successful due to incorrect information
* Tried installing it externally using github- no success

## Solutions
### problem 1
* The solution I found by going back into teh documentation and recieved information on how to install the library in Arduino ide
### Steps
* go to sketch manue
* select include library
* select manage library
* filter the search UrlEncode
* Finally install the library UrlEncode         


## Final Report

I had fun setting up the Whatsapp API. By usin the documentation it was very straight foward, and walks you through  everything you need to set it up. I only ran into one issue of not having the library, but once i had that resolved everything worked just fine. I will be using this board with this Whatsapp API for transfering videos from my computer to my phone. Therefore, this project was veruy simple and intertaining and comes in handy to me, inspiring me to explore more about the esp32 and what else I can do that can be beneficial for me in the future.
