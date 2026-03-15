# Custom-Macropad
A custom designed macropad for personal use! 

* 4 customizable keys
* 128x32 OLED Display
* EC11 Rotary Encoder
* 7x SK6812 Mini E-LEDs. Four for backlighting and three for underglow.
* SEEED XIAO RP2040 MCU
* 3d printed and acrylic layered case. Incoporates built in kickstand to prop up macropad for better ergonomics.

QMK Firmware
* LED pulses under key when pressed
* OLED graphics
* Controls the macros

# CAD Model
The case was designed in Fusion 360. It consists of 3 separate printed pieces and one layer of cut acrylic. For the revolute joints, assembly will require M3 bolts.

# PCB Design
The PCB was completely designed in KiCAD.

PCB Schematic

PCB Layout

PCB Model

# Firmware Overview
This macropad utilizes QMK firmware for all functions. It controls the OLED display, pulses the LEDs, and controls the macros. Current macros:

* Contains 4 keys and 1 rotary encoder
- Key #1 switches between layers (Layer 1/Layer 2)
- Key #2 Switches desk to right/Pulls up To Do list
- Key #3 Switches desk to left/Instant MLA formatting
- Key #4 Toggles touchscreen on and off/Switches to international keyboard

* Rotary encoder - Adjusts brightness (press for full)/Adjusts volume (press to mute)

# Bill of Materials
* 4x Cherry MX Switches
* 4x DSA Keycaps
* 5x N4148 DO-35 Diodes
* 1x 0.91" 128x32 OLED Display
* 1x XIAO RP2040
* 7x SK6812 Mini E-LEDs
* 1x Case (3 printed parts, 1 laser cut part)
