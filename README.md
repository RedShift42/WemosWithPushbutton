# SonoffWemosWithPushbutton3

This project is an extension of Aruna Tennakoon's Wemos Relay switch.  Doug Strickland added code to allow an external switch in case Alexa, WiFi, etc. wasn't working.  I modified Doug's code work with a Sonoff.  Caution!  Do NOT connect the Sonoff to any AC power until after you have completed and tested up to step 15.  Then you can connect AC power to the input of the Sonoff and test again after you have disconnected the USB to Serial adapter both from your computer and from the Sonoff!

Hardware setup:
1. Add/solder 4 pin headers to the Sonoff (see internet tutorials on modifying the Sonoff for 3rd party code)
2. Connect a PL2303 or similar USB to Serial breakout adapter to the Sonoff
3. Configure Arduino IDE for ESP8266 (there are many tutorials on this - much reading may be required)
4. Copy/Paste code into an empty sketch in Arduino IDE
5. Edit ssid/password to match your WiFi netowrk
6. Edit device_name to match the name you want Alexa to discover
7. Save!
8. Hold the very long stemed button on the Sonoff and connect the USB adapter to the PC.  Release after a couple seconds.
9. Updoad sketch to the Sonoff (there are also many tutorials on this)
10. Wait just a second after the upload completes for the Sonoff to boot and test.
11. If you have the serial monitor open in the Arduino IDE you should see the Sonoff boot and acquire and IP address.
12. Ask Alexa to discover devices.  Hopefully it shows up now.
13. Ask Alexa to turn on/off the device (what ever you named it - mine was Lamp 1)
14. If all is well, you can now reassemble your Sonoff and wire up your AC components.
15. Enjoy!

To toggle the Sonoff relay manually, simply press the pushbutton on the Sonoff.
