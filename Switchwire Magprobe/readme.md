# Magprobe for Voron Switchwire conversion

:heavy_exclamation_mark: **if you have a stock Switchwire go to >** [Magprobe for stock Voron Switchwire](https://github.com/salveoo/voronmods/blob/main/Switchwire%20Magprobe/readme.md#magprobe-for-stock-voron-switchwire-beta)

This mod allows you to use a mechanical switch as a probe on your Switchwire conversion without losing any print volume. \
_This mod was created remixing two mods: \
 • [Klicky](https://github.com/jlas1/Klicky-Probe) \
 • [SideSwipe](https://github.com/oldfar-t/Side-Swipe-Magnetic-Probe)_
 
<p align="center">
  <img width="750" src="https://user-images.githubusercontent.com/44800440/152563247-93c3d950-142e-4bd2-89d5-88d2306ed020.jpg">
</p>

## BOM

#### Motion
* 1x SG90 9g servo

#### Probe
* 1x mouse switch (eg. Omron D2F-5)

#### Fasteners
* 3x M3x8 SHCS
* 2x M3x12 SHCS
* 2x M3 t-nut for 2020 extrusion
* 4x M2x10 Self-Tapping Screw

#### Magnets
* 5x 6mmx3mm magnets (tested working with N45 magnets)

## Assembly

### Servo bracket assembly
*1st update: the probe arm doesn't use a 6mm magnet anymore, it has been replaced with an m3x8mm that threads in to the probe arm.
*2nd update: the probe carrier is now a single model. Use 2x m3x8mm to secure it on the side of the bed.
<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/150649458-32afd2e9-f0d9-4afe-be6c-e4a277974baa.PNG">
</p>

<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/150649486-d7856d79-82ef-49e2-a13d-5f056194709a.PNG">
</p>


:heavy_exclamation_mark: **Align the bed surface with the servo holder**
<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/149656820-6d86d061-13e7-4aa4-93d1-d94646e55f35.jpg">
</p>

### Probe assembly

[![Assembly Video](https://user-images.githubusercontent.com/44800440/149659009-e6c0bcc2-035e-4733-a51d-71897badaee7.PNG)](https://youtu.be/O1bFm4f67_E?t=41 "YouTube")

After assembling the probe, check continuity with a multimeter. Follow this from Sideswipe's Github if you have continuity issues: [Probe troubleshooting](https://github.com/oldfar-t/Side-Swipe-Magnetic-Probe#troubleshooting)

### Carriage mount assembly
The carriage mount is remixed from Klicky mod mount. Use 22-24 awg wires.
<p align="center">
  <img width="450" src="https://user-images.githubusercontent.com/44800440/149658491-2cd745b7-0204-4ea6-b79d-f4a45913c59a.PNG">
</p>

Make sure you have enought copper exposed to make good contact
<p align="center">
  <img width="450" src="https://user-images.githubusercontent.com/44800440/149658600-6b11f98c-69b1-4c8f-90c0-92baa65341c1.PNG">
</p>

Insert magnets, then test continuity with a multimeter. Use 2x m3x12mm to bolt it on the carriage.
<p align="center">
  <img width="450" src="https://user-images.githubusercontent.com/44800440/149658667-55900f83-0ddf-436d-b72d-f05ef15fb426.PNG">
</p>

## Macros
I have an Artillery Genius to Switchwire conversion so the coordinates of the macros could be slightly different for an Ender 3 conversion. If you get the macros working with an Ender 3 conversion text me on Discord Salveo#6988.

## Z endstop holder
To make this mod work you need something to home the Z axis. You can use this switch holder, it triggers with _Z_bearing block_. \
You'll need:
* 1x M5 t-nut for 2020 extrusion
* 1x M5x10 BHCS
* 2x M2x10 Self-Tapping Screw
* 1x endstop switch (eg. Omron D2F-5L)

<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/152511671-61c674d6-5adf-4ad7-9fda-3c36949a8c1e.jpg">
</p>

_installed endstop_
<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/152510978-971cfa0e-32ee-4717-8d34-0600e4328b7e.PNG">
</p>

# Magprobe for stock Voron Switchwire
:heavy_exclamation_mark: **Files and macros for stock Switchwire have not been tested**, _if you test them and want to give a feedback text me on Discord Salveo#6988_

Magprobe for stock Switchwire is easy to mount and bolts under the _left Z carriage stop._. The print volume remains the same with this mod installed.
<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/150682952-b8e3eef1-726f-4422-90f9-c206865fc293.PNG">
</p>
<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/150682891-efb3c00d-427f-4cef-b05e-2e5b0c17154b.PNG">
</p>

## BOM

#### Motion
* 1x SG90 9g servo

#### Probe
* 1x mouse switch (eg. Omron D2F-5)

#### Fasteners
* 1x M3x8 SHCS
* 2x M3x12 SHCS
* 1x M5x10 BHCS
* 1x M5 t-nut for 3030 extrusion
* 4x M2x10 Self-Tapping Screw

#### Magnets
* 5x 6mmx3mm magnets (tested working with N45 magnets)

## Assembly

### Servo bracket assembly
*update: the probe arm doesn't use a 6mm magnet anymore, it has been replaced with an m3x8mm that threads in to the probe arm.
<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/149656454-41992511-92d7-49a3-b462-6b2750da8701.jpg">
</p>

:heavy_exclamation_mark: **Align the bed surface with the servo holder**
<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/149656820-6d86d061-13e7-4aa4-93d1-d94646e55f35.jpg">
</p>

### Probe assembly

[![Assembly Video](https://user-images.githubusercontent.com/44800440/149659009-e6c0bcc2-035e-4733-a51d-71897badaee7.PNG)](https://youtu.be/O1bFm4f67_E?t=41 "YouTube")

After assembling the probe, check continuity with a multimeter. Follow this from Sideswipe's Github if you have continuity issues: [Probe troubleshooting](https://github.com/oldfar-t/Side-Swipe-Magnetic-Probe#troubleshooting)

### Carriage mount assembly
The carriage mount is remixed from Klicky mod mount. Use 22-24 awg wires.
<p align="center">
  <img width="450" src="https://user-images.githubusercontent.com/44800440/149658491-2cd745b7-0204-4ea6-b79d-f4a45913c59a.PNG">
</p>

Make sure you have enought copper exposed to make good contact
<p align="center">
  <img width="450" src="https://user-images.githubusercontent.com/44800440/149658600-6b11f98c-69b1-4c8f-90c0-92baa65341c1.PNG">
</p>

Insert magnets, then test continuity with a multimeter. Use 2x m3x12mm to bolt it on the carriage.
<p align="center">
  <img width="450" src="https://user-images.githubusercontent.com/44800440/149658667-55900f83-0ddf-436d-b72d-f05ef15fb426.PNG">
</p>

## Z endstop holder
To make this mod work you need something to home the Z axis. You can use this switch holder, it triggers with _Z_bearing block_. \
You'll need:
* 1x M5 t-nut for 3030 extrusion
* 1x M5x10 BHCS
* 2x M2x10 Self-Tapping Screw
* 1x endstop switch (eg. Omron D2F-5L) \


<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/152593542-cff656ec-0d70-4874-a098-0d4352e299d8.jpg">
</p>

_installed endstop_
<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/44800440/152593603-c5767be7-884d-44fb-acf5-afcc16806252.PNG">
</p>
