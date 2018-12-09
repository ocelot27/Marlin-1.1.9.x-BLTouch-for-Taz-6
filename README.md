# Marlin-1.1.9.x-BLTouch-for-Taz-6

This is an edit of 1.1.9.28 cloned from the Lulzbot devel of 1.1.9.x - this is developement firmware - use at your own risk. Must be compiled using Arduino IDE 1.8.5.

It is configured for a Taz 6 using the BLTouch and Bilinear leveling. You will need to choose your printer toolhead in Configuration_LulzBot.h - it is currently configured for the e3D V6 "Aerostruder." 

It is also configured to use a K-type thermocouple for the hot end - if you are using a thermistor you will need to edit the temperature sensor type in Conditionals_LulzBot.h find "LULZBOT_TEMP_SENSOR_0" (line #875) and it change to the appropriate number. Lastly you will need to change the pin for the hotend thermistor in pins_RAMBO.h find "TEMP_0_PIN" (line #145).
