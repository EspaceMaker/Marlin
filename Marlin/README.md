# Firmware for EspaceMaker Ender 3 Pro 

## How to flash

### Burn bootloader
[Ender 3 Firmware flashing Article from All3dp](https://all3dp.com/2/ender-3-with-marlin-how-to-install-marlin-firmware-on-your-ender-3/)

> What You’ll Need
>
>>    - 5x female to female single Dupont wires  
>>    - 1x female to male Dupont wires  
>>    - An Arduino Uno and cable to connect to a PC  
>>    - A computer with the Arduino IDE pre-installed (MacOS, Windows, or Linux versions are available for download)  
>
>How to Do It
>
>>    1. Set up your computer, Arduino, and all the other materials you need near your Ender 3. (You’ll need everything within reach later.)
>>    2. Open Arduino IDE on your computer.
>>    3. Go to example sketches, select Arduino ISP and open it.
>>    4. Go to “Manage libraries” and add the U8glib Library. (Make sure the library is called U8glib. >You may have to scroll down to find it.)
>>    5. Then go to the board manager and add the Sanguino board.
>>    6. Once done, plug in the Arduino Uno to your computer. Select Arduino Uno as the port and Arduino >Uno as the board, then click “Upload sketch”.
>>    7. Select the Sanguino board (that you just added) from the menu.
>>    8. Make sure your printer is turned off. Open your Ender 3’s control box (with the hex key that came with your printer). Wire it up to the Arduino as follows (you’ll need to look at the schematics as nothing is labeled):  
>>        - MISO — MISO  
>>        - 5V — 5V  
>>        - SCK — SCK  
>>        - MOSI — MOSI  
>>        - RESET — Digital pin 10 (the pin with the ~10 on the Arduino in the row of pins)  
>>        - GND — GND  
>>
>>    9. If a blue light flashes on the Creality board, you’ve wired it correctly.
>>    10. Click on the Tools tab and click “Burn bootloader”. If it says “Output bootloader burned successfully”, you’ve done it!
>>    11. Unplug your Dupont connectors from the Ender 3, put the cover back on the board and screw it on.
>>    12. Now unplug your Arduino from the computer.


### Modify Firmware
Take example from [Marlin Configurations Repository](https://github.com/MarlinFirmware/Configurations/tree/import-2.0.x/config/examples/Creality/Ender-3%20Pro)


### Upload Firmware

