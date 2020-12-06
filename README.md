# moes-HY368

This device requires batteries with a nominal voltage of 1.5 volts

There is a low battery alert which is triggered by voltage drops below this.

For those wanting to use rechargable batteries this is a problem as NiMH batteries with a nominal voltage of 1.2v typically have an actual voltage of 1.5v after a full recharge. This quickly drops to close to 1.2v causing low battery alerts. Quite often this is shown by receiving multiple low battery alerts - the cause is a voltage drop during operation of the motor.

This is my solution - using a cheap buck voltage converter. Works well on the HY368 from Moes due to a space beneath the battery compartment capable of hiding a small converter.

![thermostat mod](https://user-images.githubusercontent.com/68975498/99322123-33290180-2867-11eb-927f-4bdc6bd4647a.jpg)

converters bought here: https://www.aliexpress.com/i/33050378063.html

solder in the ground and Vin (over length) wires to the converter before fitting  

desolder the positive wire from the battery terminal on the right and solder that to the converter Vo. 

Then trim the ground lead and Vin from the converter to suit and connect to the ground junction and battery +ve terminal (which can be removed from the case to make it easier - they slide out).

A fine solder tip is highly recommended....

be careful reassembling the cover to ensure the buttons do not catch on it.

A greener solution than using dry cell batteries, and less low battery alerts when using NiCad or NiMH batteries!

*note: converters pull some current continually...maybe there are more efficient converters available with a slim form factor?

**Also alternative chemistry rechargable batteries could be used that have the AA form. Ni-Zn batteries have been mentioned which have a nominal voltage of 1.5v and shouldn't trigger low battery alerts. I have not used these so no idea if they have any limitations over Ni-MH chemistry. Worth checking if you need more cells... 
