# External_Monitor_Brightness_contro_GUI 

To run this program, open command line.

        python3 brgui

This runs the program. But, to set the brightness using cli just type,
        python3 brgui 50

This sets the brightness to 50%

As the program is extremely slow(because of ddcutil) passing commandline argument seems convenient.

## Xrandr
Another solution is to use xrandr but it didn't work as planned. Most of the time it icreased and decreased the brightness perfectly but it messed up my gamma(mostly 1.6 for my monitor). 

Tried to get the same result from ddcutil but couldn't get it done. The UI was ok. No stuttering but when the brightness was below 60%, it was really tough to see anything. 
