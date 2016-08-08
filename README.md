# WiFiManager-OTA

It is a combination between:
  - **WiFiManager** https://github.com/erkobg/WiFiManager
  - **OTA Update**  (more info here https://github.com/esp8266/Arduino/tree/master/doc/ota_updates)
  
  
1. Checks for stored  Wifi and password 
2. If found tries to connect
3. If successful - handles code and OTA
4. If nothing is found or connection fails - creates AP - where you can set using default address 192.168.4.1 connection parameters 



