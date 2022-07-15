<img src="https://img.shields.io/badge/-ATtiny%20Project-blue.svg?&amp;style=flat-square&amp" style="max-width: 100%;"> <img src="https://img.shields.io/badge/-PlattformIO-orange.svg?&amp;style=flat-square&amp" style="max-width: 100%;">


# General info
[![](https://yt-embed.live/embed?v=kuYiHbWjCQM)](http://www.youtube.com/watch?v=kuYiHbWjCQM "electronic pocket dice")

## Code
- first we declare all the LED pins, some variables for a "blink without delay" and an array for all the LEDs.
- the letsGetStarted function shows us at the beginning that all the LEDs are working properly. In this case we work with delays. 
- in the function diceToLed we combine the correct LEDs with the value of the dice so that we get the usual appearance. 
- the function rollTheDice shows us a small frequency of flickering through the dice values until the rolled value is displayed
- for a true random value we work with randomSeed, which is connected to an unused pin. 
- in the loop we debounce the button and roll the dice with blink without delay.

## Hardware
- The hardware for this project is very simple. It runs on an ATtiny24.
- We added 100 Ω resistors for the 3mm LEDs and a 10k Ω resistor for the push button. 

![Verdrahtung](https://github.com/pixelEDI/attiny_pocketdice/blob/main/pocketDice_wiring.jpg)


## 3D Case
Get the Case:  [Thingiverse](https://www.thingiverse.com/thing:5431985)

You like it? Then I would be very happy if you treat me to a coffee on [ko-fi.com/pixeledi](https://www.ko-fi.com/pixeledi)
