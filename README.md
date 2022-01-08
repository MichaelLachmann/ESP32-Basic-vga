# ESP32-Basic-vga
This is a modified version of ESP32-Basic-vga found on github https://github.com/fg1998/ESP32-Basic-vga from Fernando Garcia
- Revert back to Arduino IDE

- I've added a new compile time option to activate the german keyboard layout when using a real keyboard
- Added NOSOUND and SOUND <freq>, <duration in ms> [, type] .... type: 0=sine,1=square,2=triangle,3=saw.
  Connect the speaker to GPIO25 (see documentation of FABGL).
- Just for documentation you can directly connect a keyboard with USB-Plug instead of a PS2 one. Keyboards emulate the PS2 mode if they are activated as such.
  To connect the keyboard take a USB female connector and connect PIN 1 to 5V, Pin 4 and the shield to Gnd. Pin 2 goes with a 120Ohm resistor to GPIO32, Pin 3 with a 120Ohm resistor
  to GPIO33. Add to pull-up 2k-Ohm resistors from GPIO32 and GPIO33 to 3.3V of the ESP. 
  Please note that such modifications can destroy components if done wrong! I take no responsibility for damages or if you get hurt!



