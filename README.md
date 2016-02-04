# GuitarPedal
the purpose of this project is to create a DIY digital guitar pedal using an Arduino UNO. C/C++
the guitar signal, depedning on the potentiomenter/volume knob, will spit out an audio signal from -1V -> +1V
we will use op amp setups to boost the signal by 2.5X, and then adjust it by +2.5V so taht it runs from 0V-5V. 
the arduino's input range is 0 -> 5V. 
the arduino has a built in ADC that will take the impedence matched input signal and convert it to digital. 
within the arduino there will be multiple programmed digital effects.
the output will need to use a resistor set up to convert the signal back to digital and and op amp setup to modify it back to the original -1 -> +1V
