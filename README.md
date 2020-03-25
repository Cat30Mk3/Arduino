# Neopixel Analog Tutorial
The 8 pixel Neopixel strip has been wired for direct connection to the Arduino Mega 2560, or through the intermediary breadboard. For ease of connection, the required 470 ohm resistor has been soldered inline of the yellow Data In wire. The red wire must be connected to a 5 volt supply, and the black wire to ground. The yellow Data In wire must be connected to a GPIO Pin. For the purpose of our tutorial we will use Pin#7.

The 10k ohm potentiometer, used by one of the previous lesson sketches,  provides a variable analog input.  The potentiometer is wired to make a voltage divider with its 0-5volt output read by the Arduino Mega 2560. For consistency with the previous tutorials we will connect the vltage divider output ti the A5 pin. 

For ease of connections the breadboard is used to distribute the 5volt positive and ground connections.
