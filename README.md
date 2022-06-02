# Smart-Home-automation-system
smart home automation system is done for controlling home electric appliances through a mobile app which requires esp32, relay module, blynk IOT app and code implementation with C++.
you need an arduino IDE to burn ESP32
things you need to do before uploading the code to ESP32
Preferences--> Aditional boards Manager URLs : 
https://dl.espressif.com/dl/package_esp32_index.json, http://arduino.esp8266.com/stable/package_esp8266com_index.json
Download Board ESP32 : https://github.com/espressif/arduino-esp32 //OR BY SEARCHING ESP32 AND DOWNLOAD IT FROM SKETCH->INCLUDE LIBRARY
Download the Libraries:
Blynk Library:  https://github.com/blynkkk/blynk-library OR BY SEARCHING
then select BOARD AS "DOIT ESP32 DEVKIT V1" in tools->Board
setup blynk template
now mov to the code
set blynk template credentials as provided in your app template
#define BLYNK_TEMPLATE_ID ""
#define BLYNK_DEVICE_NAME ""
connect esp32 and relay module according to code
then run the code files we provided
