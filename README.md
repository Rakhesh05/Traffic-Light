The code is written in Embedded C for the 8051 microcontroller using the reg51.h header.

Three LEDs (Red, Yellow, Green) are connected to P1.0, P1.1, and P1.2 respectively.

sbit is used to define symbolic names for the specific port pins controlling the LEDs.

A delay function is implemented using nested for loops to create approximate timing delays.

Inside the main() function, an infinite loop (while(1)) is used to continuously cycle through the traffic light sequence.

First, the Red LED is turned ON while the Yellow and Green LEDs are OFF, simulating the stop signal.

After a delay, the Yellow LED is turned ON alone to indicate a warning or transition.

Then, the Green LED is activated, signaling vehicles to go, while the others remain OFF.

Each state (Red, Yellow, Green) is held for a specific delay to simulate real-world traffic signal timing.

The cycle repeats endlessly, simulating a simple automatic traffic signal system.
