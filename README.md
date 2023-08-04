# External_Monitor_Brightness_contro_GUI 
## Using `ddcutil`
To run this program, open terminal and run the following command
        python3 brgui

To set the brightness using cli, just type
        python3 brgui 50

This sets the brightness to 50%

As the program is extremely slow(because of `ddcutil`) passing commandline argument seems convenient.

## Xrandr
Another solution is to use `xrandr` but it didn't work as planned. Most of the time it icreased and decreased the brightness perfectly plus the UI was really responsive but it messed up my gamma(mostly 1.6 for my monitor). No stuttering in UI + responsive. But when the brightness was below 60%, it was really tough to see anything. 
