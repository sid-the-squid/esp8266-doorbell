# esp8266 doorbell
 a simple smart wireless doorbell
 
This project is adding a simple esp8266 to a 'dumb' Tecknet self-powered wireless doorbell, 
retail price in the UK is about £14
amazon link https://www.amazon.co.uk/gp/product/B00HYZ635U/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1

The reason I chose this doorbell was for its 433mhz self-powered transmitter, my original intention was simply
to listen for the doorbell wireless signal and react to that, however this proved somewhat more of a challenge than expected
and I soon changed the plan to adapting the receiver unit to accommodate a ESP8266 device and connect to my smart home that way.

Please see pictures for the wiring pictures, the yaml folder for my ESPHome yaml
if you haven’t encountered ESPHome before check it out now, it’s simply amazing.

In my version of this project, I used a Lolin/Wemos mini d1 clone, as these are my usual go to ESP devices, I have also removed the speaker from my doorbell and vandalised some of the inbuild LED’s, this was intentional as I didn’t want the sound or desire the light produced from the receiver.  You may find enough space able to retain the speaker if desired.
Please note the power source is 4.7V that seems perfectly sufficient for the mini d1, the internal doorbell ‘logic’ chip operates at 3.6V or at least that is the output voltage from the pin which I am using to make the doorbell activated event.
On the Wemos ESP device 3 pins are connected, 5V, GND and D0.
Please ignore the soldering on D1 & D2 pins on the ESP those pins are Not used in this project, this ESP device has been repurposed a few times 😉

After these pictures were taken, I wrapped the ESP device in black electrical tape to avoid any shorts, with the speaker removed there is plenty of space available for the ESP device to ‘rest’ above the factory circuit board.  

Hope you find this project useful, as with anything related to mains voltage, be careful, be safe.
 

