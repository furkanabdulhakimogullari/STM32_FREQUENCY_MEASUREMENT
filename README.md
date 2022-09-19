In this repository, I shared two different frequency measurement methods using STM32L5.

1-)
In "Using_Capture_Input" file, frequency can be measured calculating the difference of two rising edges. TIMER 2 is used to determine edges of pulses. In order to measure frequency, signal is necessary. Here, using external signals coming from PA0 pin, frequency is measured. Also, PA2 pin is related to TIMER 2. 

2-)
In "Counting_Pulses" file, frequency can be measured counting pulses per a second, microsecond or millisecond. After finding iterated pulses, frequency can be measured thanks to different iterations. Also this method gives us more precise results. In order to measure frequency, signal is necessary. TIMER 2 is used to count. Here, using external signals coming from PA0 pin, frequency is measured. Also, PA2 pin is related to TIMER 2. 
