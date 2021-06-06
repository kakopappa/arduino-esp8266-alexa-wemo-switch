Box
=======


### If you have [issues](https://github.com/kakopappa/arduino-esp8266-alexa-wemo-switch/issues/7#issuecomment-355533848) discovering please consider using Sinric Pro Smart Home Skill. 
* [sinric.pro](https://sinric.pro) 

I just wanted to build a cheap switch that can be controlled by Amazon Alexa by emulating a delkin device. 

You can do this using WeMos D1-mini + Relay or use SonOff
 

#### Using WeMos D1-mini + Relay  

1. WeMos D1-mini ($4.00)  http://www.aliexpress.com/store/product/D1-mini-Mini-NodeMcu-4M-bytes-Lua-WIFI-Internet-of-Things-development-board-based-ESP8266/1331105_32529101036.html

2.  WeMos Relay ($1.90) http://www.aliexpress.com/store/product/Relay-Shield-for-WeMos-D1-mini-button/1331105_32596395175.html

3. AC-DC HLK-PM01 module voltage 220V to 5V (Optinal) to convert 220V to 5V for D1-mini

Relay is connected to D1

To controlled this switch via Amazon Alexa.

1. Download the code
2. Change the WI-FI settings. 
3. Flash 
4. Scan for new devices in Alexa
5. Say "turn on" box

#### Do you want to turn on / off your TV, AirCon (AC) using Amazon Alexa? Checkout my latest project https://irdevkit.com/

#### Looking for a Cheap DIY Alexa Light Bulb?
https://github.com/kakopappa/ble-light-bulb

##Using Sonoff##

Sonoff - Thanks @joeman2116 (https://github.com/kakopappa/arduino-esp8266-alexa-wemo-switch/issues/6)

Use a ftdi 3.3v as the programmer.
I tried type as a generic 1meg flash but got reboot problems.
So I used the nodemcu.9 choice.

Change the ssid
Change password
Change device name to (your choice)

Pins
I use d6 for the relay and d7 for the led.(optional)

If you want to control more than 1 switch checkout my other project
https://github.com/kakopappa/arduino-esp8266-alexa-multiple-wemo-switch

#### Articles about the Wemos switch
* [monkeytypewritr](https://medium.com/@monkeytypewritr/amazon-echo-esp8266-iot-a42076daafa5#.oc4od1xa0)

 

#### Credits

- makermusings - [GitHub](https://github.com/makermusings/fauxmo)

#### Developed By

* Aruna Tennakoon
 * [paypal.me/arunat](http://paypal.me/arunat)
 * Bitcon ```1JnmhzTbW9MRb7FK7UReoWdUZ18MDn6aNv```
 * 3 beers from [dougstrickland](https://github.com/dougstrickland) - Thanks
 * 2 beers from Michael Berna
 * 1 beer Keg from Phillip Ryals
 * 5 beers from Steven Boger
 * 5 Kegs from Robert Paradiso
