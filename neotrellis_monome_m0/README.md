# neotrellis monome compatible grid

Neotrellis Grid Code for Adafruit M0 and M4 controllers.

Note - To compile this source and have it work properly, this requires some changes to the underlying libraries (replacing the Adafruit_USBD_Device library deep in the adafruit/arduino core libraries).


## Adafruit Kit
[Adafruit 8x8 NeoTrellis Feather M4 Kit Pack](https://www.adafruit.com/product/1929)

If you have this (or have built an 8x8 grid with Feather M4) you can use the enclosed compiled firmware [neotrellis_m4_8x8_featherM4.UF2](neotrellis_m4_8x8_featherM4.UF2) assuming your setup uses the following addresses 
```
{ Adafruit_NeoTrellis(0x2E), Adafruit_NeoTrellis(0x30) },
{ Adafruit_NeoTrellis(0x32), Adafruit_NeoTrellis(0x36) }

```