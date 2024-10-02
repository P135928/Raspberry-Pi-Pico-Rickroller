/////////////////////////////////////////////////////////////////////////////////
CREDIT WHERE ITS DUE
Thanks to earlpilhower for making the Raspberry Pi Pico core for Arduino IDE
Go check out his repo on it!
https://github.com/earlephilhower/arduino-pico 
////////////////////////////////////////////////////////////////////////////////

This is a rickroller I made in Arduino IDE using an Raspberry Pi Pico and a SSD1306 screen. 

The screen is optional if you do not want it.

PinMode(OUTPUT, GP4 SDA); 
PinMode(OUTPUT, GP5, SCL);

Just upload the code and hit the BOOTSEL button and the payload runs! If you need you can change the timings in the "delay(Int);" to make it run better for you.

Lines that have a delay you can change:
115
124
126
133
139
146
148
154
156
162
169 (nice)

The screen shows what is going on in the payload.

I havent but will eventually test this on an Arduino UNO to see if it works. If you get to that before me let me know!
