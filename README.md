:exclamation: Try it with PlatformIO http://platformio.org/ :exclamation:




# WiFiManager-OTA

It is a combination between:
  - **WiFiManager** https://github.com/tzapu/WiFiManager
  - **OTA Update**  (more info here https://github.com/esp8266/Arduino/tree/master/doc/ota_updates)
  
  
1. Checks for stored  Wifi and password 
2. If found tries to connect
3. If successful - handles code and OTA
4. If nothing is found or connection fails - creates AP - where you can set using default address 192.168.4.1 connection parameters 






from https://github.com/tzapu/WiFiManager



> ## How It Works
> - when y> > our ESP starts up, it sets it up in Station mode and tries to connect to a previously saved Access Point
> - if this > > is unsuccessful (or no previous network saved) it moves the ESP into Access Point mode and spins up a DNS and WebServer > (default i> p 192.168.4.1)
> - using any wifi enabled device with a browser (computer, phone, tablet) connect to the newly created Access Point
> - because > of the Cap> tive Portal and the DNS server you will either get a 'Join to network' type of popup or get any domain you try to access redirected t> o the configuration portal
> - choose one of the access points scanned, enter password, click save
> - ESP will try to connect. If successful, it relinquishes control back to your app. If not, reconnect to AP and reconfigure.

> ## How It Looks
> ![ESP8266 WiFi Captive Portal Homepage](http://i.imgur.com/YPvW9eql.png) ![ESP8266 WiFi Captive Portal Configuration](http://i.imgur.com/oicWJ4gl.png)
