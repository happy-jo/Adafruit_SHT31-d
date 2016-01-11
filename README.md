# Adafruit_SHT31-d
Description: Python script for pulling the Adafruit SHT31-d Temperature and Humidity sensor connect to the I@C bus of a Raspberry Pi.

Thanks to jaques @ (https://github.com/jaques) for the starting point for this code.

In this library you will find "jaques" original code. The files listed within the mod folder have been modified by me.
Feel free to us these at will

Change Log:
Imported code from https://github.com/jaques.
Modified "sht31.py" to change values from (XX.XXXXXXXXXX) to (XX.XX) using "round(var, 2)
Added formula to change "temperature" from Celsius to fahrenheit (temperature * 9/5.0 + 32)
Renamed file to "sht31_mod.py"

Future Goal:
Remove un-needed code to port only the temperature and humidity into a python script as a variable.
