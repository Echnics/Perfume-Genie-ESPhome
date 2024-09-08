![Alt text](images/perfumegenie.jpg)

# This is my guide to get Perfume Genie 2.0 to work in ESPhome.

My Perfume Genie is know connected through ESPhome,
and i control fan speed.<br>
The LED light up blue when connected,red if disconnects.<br>
LED lights up green when fan is running.<br>
The rear button toggels the fan.<br>
I've set up timers in Nodered for runtimes,that can easily be done with HA automations to.<br>


Here is som info on the perfume genie board.<br>
The pins on the header in the top left corner i soldered on my self to make flashing easier.
![Alt text](images/Perfumegenieboard.jpg)
![Alt text](images/perfumegenieespmodule.jpeg) 

Pins:
- IO4 is for PWM to fan(Blue wire).
- IO15 is for LED (WS2812).
- IO16 is for the Connect button.
- IO3 is for the button at the rear.

There is a NFC NXP RC522 for the scent name of the tank.<br>
I haven't figured out how it's connected to the ESP yet.<br>
But i also guess it's not so easy to figure out the data for the tank tag to get it working.<br>
If someone is good at that, let my know.


Flashing:

Used these two pages for some info:
https://tasmota.github.io/docs/Getting-Started/#prerequisites
https://esphome.io/guides/physical_device_connection.html#unpopulated-programming-header


![Alt text](images/flashing.png)
