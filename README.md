# MoteinoMega-1284p
Arduino IDE modifications to LowPowerLab/Moteino/MEGA/Core/ for support of AVR 1284p MCU at 10MHz

Copy the "Moteino" folder and all its contents in your Arduino sketch folder under "hardware" folder.
Others had luck putting this at your Arduino installation folder, I didn't.

After copying the path the the boards.txt file should look like this:
    [Arduino Sketch path]/hardware/Moteino/avr/boards.txt

Then restart the Arduino IDE and under "Tools > Boards" you should have 2 new entries: Moteino, MoteinoMEGA.  

This was tested and is supported on Arduino IDE v1.6.1, please upgrade to this version to use this core.

This was forked from LowPowerLab/Moteino project.
