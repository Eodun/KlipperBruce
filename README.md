# KlipperBruce
My KP3s printer config files.

*Uses configs and instructions from:

- https://github.com/digitalninja-ro/klipper-neopixel Neopixel led scripts (cleaner than mine)
- https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging Adaptive Mesh creation and line purge for each print
- https://github.com/mainsail-crew/moonraker-timelapse Moonraker integrated timelapse
- https://github.com/mainsail-crew/crowsnest For webcam control
- https://github.com/Frix-x/klippain-shaketune For easier inputshaper (in progress)
- https://github.com/Clon1998/mobileraker Android control app

*Upgrades to my printer relevant to the config:

- External access via WireGuard VPN HomeAssistant Addon
- TMC2209 in UART mode
- BlTouch clone (3DTouch)
- Titan Aero Extruder (direct drive), 0.2 nozzle right now, using also high flow 0.4
- USB camera (laptop webcam)
- Endoscopic camera
- Filament detector
- Neopixel 10-led stripe connected to the printer MCU
- Arduino: I use an Arduino UNO to connect an ADXL when needed for input shaper (soon: USB ADXL)
- IKEA RGB lamp connected through HomeAssistant
- MobileRaker Android app
- Trying to configure Shaketune but got weird errors, any help? :D
