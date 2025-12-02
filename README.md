# Hex Keypad
A simple keypad for Arduino using Cherrry MX type key switches.<br>

The main idea was so I could test keyboard scan codes using an Arduino as a protocol converter.<br>

It's pretty simple:
- no diodes to prevent ghosting - expects only one key at a time
- no pull-up resistors - activate in Arduino

Needs nine pins on the Arduino - five for rows and four for columns.<br>

- Enter the two digit hex code, 0x00 to 0xFF
- Press ENTER when the number entry is completed
- Press INVERT if you want to invert the entered hex value, i.e. ~0x12 = 0xED
- Press CLEAR if you make a mistake and want to reset the entry
- Press SEND to instruct the Arduino to send the scan code to the host computer

## [KiCad Design & Fabrication Files](/KiCad)
Schematic, PCB and Gerber files.<br>

## [Arduino Sketch]
To be done

![Hex keypad 3D](/Hex_Keypad_3D.png)

