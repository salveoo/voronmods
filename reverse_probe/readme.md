# Reverse probe (beta)
**Reverse probe** is a mechanical probe based on Voron's Z endstop.
<p align="center">
  <img width="1050" src="https://user-images.githubusercontent.com/44800440/188014465-065af8de-f46c-436f-bcae-0b9f048c78ec.jpg">
</p>

## BOM

* 1x mouse switch (eg. Omron D2F-5)
* 2x M3x20 SHCS
* 2x M2x10 Self-Tapping Screw
* 1x 20T GT2 pulley
* 5x30mm smooth pin
* 2x 6x3mm magnets (tested working with N45 magnets)

## Assembly
*click to see the video*
[![Assembly Video](https://user-images.githubusercontent.com/44800440/188210821-8fd1178c-1e3d-4187-9ab7-67bd1f57ba7a.png)](https://www.youtube.com/watch?v=pl0y2BOf33Q "YouTube")

## Probe holder

:heavy_exclamation_mark: **Still needs to be tested**

<p align="center">
  <img width="350" src="https://user-images.githubusercontent.com/44800440/188212080-591d0747-9640-4fdb-a3e9-648b4b30eba7.png">
</p>

I modified the removable part of [Klicky](https://github.com/jlas1/Klicky-Probe) probe holder. Press fit the magnet in place.

## Macros
*As you can see in the assembly video I have a particular setup, so I can't provide macros.* \
You can watch [this part of the assembly video](https://youtu.be/pl0y2BOf33Q?t=92) to have an idea of the **docking and undocking sequence.**

### probe offset
**z_offset: 6.5 \
x_offset: 0 \
y_offset: 22**

