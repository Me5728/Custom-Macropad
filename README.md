# Custom-Macropad
A custom designed macropad for personal use! 

* 4 customizbale keys
* 128x32 OLED Display
* EC11 Rotary Encoder
* 7 WS2812B RGB LEDs. Four for backlighting and three for underglow.
* SEEED XIAO Rp2040 MCU
* 3d printed and acrylic layered case. Incoporates built in kickstand to prop up macropad for better ergonomics.

QMK Firmware
* LED pulses under key when pressed
* OLED graphics
* Controls the macros

# CAD Model
The case was designed in Fusion 360. It consists of 3 separate printed pieces and one layer of cut acrylic. For the revolute joints, assembly will require M3 bolts.

# PCB Design
The PCB was completely deisgned in KiCAD.

PCB Schematic

PCB Layout

PCB Model

# Firmware Overview
This macropad utilizes QMK firmware for all functions. Current macros:
* 4 keys - #1 switch between layers
  Layer 1:
  #2 Switch desk to right
  #3 Switch desk to left
  #4 Toggle touchscreen on/off
  Layer 2:
  #2 Pull up To Do list
  #3 Instant MLA formatting
  #4 Switch to international keyboard

* Rotary encoder
  Layer 1:
  Adjusts brightness. Press for full.
  Layer 2:
  Adjusts volume. Press to mute.
