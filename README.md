The-LED-heart-_-Arduino

On a 8X8 LED dot matrix,we display a heart with the help of an Arduino Uno.

//the project 

On a 8x8 LED dot matrix we display a heart image (which is created by the matrix's dots/LEDs that are ON).
We wait for 5 seconds and then booom!, the leds that compose the heart turn on and a heart can be seen on
the matrix.
We keep the heart image on the matrix for 15 seconds and then we turn it off.


//List with items needed for the project

-an Arduino board (I used an Uno R3)
-one breadboard
-one 8x8 led dot matrix
-8 220Ω resistors
-jumper wires


//Build the circuit

(check the img_schematic)

The led dot matrix has 16 pins , 8 pins for each row and 8 pins for each column.
We connect the row pins with the Arduino's D0-D7 digital pins (we connect each row pin through a resistor to an Arduino's digital pin). 
We connect the column pins as following:
  the first column->digital pin 8
  the second column->digital pin 9
  the third column->analog pin A0 (we use it as a digital pin here)
  .... 
  the eighth column->analog pin A5

It is really important to find out which physical pin of the matrix corresponds to which column or row pin !!!
  

	

