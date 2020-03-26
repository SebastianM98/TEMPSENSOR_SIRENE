# TEMPSENSOR_SIRENE
My project plan is to make a Temperature sensor with a sirene.
If the temperature goes too high, the sirene goes off. 
I use a tweeter speaker as my sirene and a DHT11 sensor for the temperature and humidity.
I also use BLYNK app to show there how the temperature goes.
The BLYNK app is more for the visual, instead of using OLED or LCD or serial monitor.
The app that I use for making the code is arduino.
My micro controller is a ESP32 from JOY-IT.
It uses WiFi to connect with BLYNK.
For the tweeter speaker i use the LM386 as an OPAMP filter.
The tone can be high or low by using the potentio meter.

So now about the working, i have problem that my serial monitor
shows "Can't read the DHT sensor. I use 3.3V input,
it can be solved by using 5V or rewiring a bit. 
My DHT is connected on VCC (3.3V), PIN 4 or D4 on the ESP and GND.
It can be done with other speaker too.
