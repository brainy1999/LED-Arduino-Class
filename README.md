# LED-Arduino-Class
An Arduino implementation of multi-control LEDs.

This Library is a command tool to make arduino LED control easier.

Colorled - Class control for a RGB LED

    Colorled(int redpun, int bluepin, int grenpin) = Sets the pin number of a Digital LED Pin (Constructor).
    
    setcolorled(int rcolor, int gcolor, int bcolor) = Sets color in R,G,B.
    

    
Normalled - Class control for a Normal 5v LED

    Normalled(int pin) = creates an LED with the pin number (Constructor)
    
    ledsingleblink() = blinks the led once.
    
    ledblink(int amount, int delay) = blinks the led for x amount of times with delay being the time in between blinks.
    
    ledbutton() = turns led on or off depending on what the led's state is. 
    
    dimbutton(int time) = turns led on or off depending on what the led's state is through dimming. //ANALOG PIN ONLY
    

LEDArray = sets up an array of single color LEDs

    LEDArray(array) = creates an array of LEDs (TAKES AN ARRAY TO RUN).


