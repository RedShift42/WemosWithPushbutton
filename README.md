# WemosWithPushbutton3

This project is an extension of Aruna Tennakoon's Wemos Relay switch.  Doug Strickland added code to allow an external switch in case Alexa, WiFi, etc. wasn't working.  I created this for to make Doug's code work with a Sonoff.  Caution!  Do NOT connect the Sonoff to any AC power until after you have completed and tested up to step 9.  Then you can connect AC power to the input of the Sonoff and test again after you have disconnected the USB to Serial adapter both from your computer and from the Sonoff!!!

Hardware setup:
1. Add 4 pin headers to the Sonoff
2. Connect a PL2303 or similar USB to Serial breakout adapter
3. Configure Arduino IDE for ESP8266 (there are many tutorials on this)
4. Copy/Paste code into an empty sketch in Arduino IDE
5. Edit ssid/password to match your WiFi netowrk
6. Edit device_name to match the name you want Alexa to discover
7. Updoad sketch to the Sonoff (there are also many tutorials on this)
8. Wait just a second after the upload completes for the Sonoff to boot and test.
9. Enjoy!

To toggle the Sonoff relay, simply press the pushbutton.
