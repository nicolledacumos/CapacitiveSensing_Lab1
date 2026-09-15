# CapacitiveSensing_Lab1

This file includes the following different sections: 
1. Proximity and touch sensor
2. Sensor callibration
3. Capacitive gesture sensing
Stretch goal: Interactive systems

## Proximity and Touch Sensor
This section involves turning a single LED on and off based off touch and proximity. There are two different files used for this section: one includes code that acts as a switch (touch) and the other uses hand's proximity to the sensor to slowly turn the light on and off using the Map function.

## Sensor Callibration
This section demonstrates how I found the thresholds for each wire needed for my slider. Because I was having some trouble printing all three values in a way that was easy for me to see, I just changed the touch_pin value every time I ran the code and noted it in my journal. 

## Capacitive Gesture Sensing
This section focuses on swipe left and swipe right gestures across all three touch sensors. The swipe functions light up 3 different LEDs that correspond the 3 different touch pins. When the serial monitor reads "Swipe Right!" the pins light up left to right on the breadboard. When the serial monitor reads "Swipe Left!" The pins light up right to left on the breadboard.

I have also included a version that changes the color of an RGB light based off the different swipe directions.
