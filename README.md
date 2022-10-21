# Nano NeoPixel driver
An all in one board for driving neopixel, or equivalent, led strips using an Arduino Nano

**WARNING: THIS BOARD IS 5V ONLY. APPLYING A HIGHER VOLTAGE WILL RESULT IN A DEAD ARDUINO AND LEDS**

Instructions for the jumpers on the back

Adafruit recommends putting a 470 ohm resistor in series with the WS2812B data line. To acomodate both LED and GPIO signals, the back of the board has a resistor footprint and a solder jumper for each exposed DIO. Populate the resistor for DIO that will drive an LED signal, and solder the jumper for DIO that will be GPIO.

Assembly
1) Populatate the resistors and jumpers on the back as needed
2) Install the arduino
3) Attach wire or headers for Vin and the DIO
4) Install the capacitor

BOM

1x Arduino Nano

1x 1000uF Würth Elektronik 860010274015 (or comparable capacitor with same footprint)

8x 470 ohm 0805 resistors
