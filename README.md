# BoostConverter

## Description

The solar charge board can only deliver 3V3 so we had to make a board that's convert the 3V3 to 5V. We need to do this because the SDS011 sensor has to work on 5V.

## Shematic of the boost converter

In this shematic you can see one big central component the MCP1640CT-I/MC. This component is a synchronous boost regulator with true output disconnect or input/output bypass option. This boost regulator is a DC-DC converter. There are also pins (SV1) provided to connect this board to the sensor board. On the shematic you can also see a coil we needed to put this in the shematic othewise it was not possible to get the 3V3 to 5 V. There are also other components like resistors and capacitors.

![shematic boost converter](/img/shematicBoostConverter.png)

## Board shematic of the boost converter

![board boost converter](/img/boardBoostConverter.png)

## Pin layout boost regulator

Here you can see the pin layout of the MCP1640CT-I/MC synchronous boost regulator.

![board boost converter](/img/boostRegulatorPins.png)

## Partlist boost converter

* [4.7 µF capacitor](https://be.farnell.com/taiyo-yuden/lmk107bj475ka-t/cap-4-7-f-10v-10-x5r-0603/dp/2112745?ost=2112745&ddkey=https%3Anl-BE%2FElement14_Belgium%2Fsearch)
* [10 µF capacitor](https://be.farnell.com/murata/grm188c81c106ma73d/cap-10-f-16v-20-x6s-0603/dp/2470486?ost=2470486&ddkey=https%3Anl-BE%2FElement14_Belgium%2Fsearch)
* [4.7 µH power inductor](https://be.farnell.com/coilcraft/lps4018-472mrb/inductor-4-7uh-20-1-3a-shld-smd/dp/2408103?st=4.7%20%C2%B5H%20inductor)
* [976 kohm resistor](https://be.farnell.com/multicomp/mcwr06x9763ftl/res-976k-1-0-1w-0603-thick-film/dp/2694973?ost=2694973&ddkey=https%3Anl-BE%2FElement14_Belgium%2Fsearch)
* [309 kohm resistor](https://be.farnell.com/vishay/crcw0603309kfkea/res-309k-1-0-1w-0603-thick-film/dp/2138544?st=2138544)
* [4 male pins](https://be.farnell.com/amp-te-connectivity/826629-4/header-1row-4way/dp/3418303?ost=3418303&ddkey=https%3Anl-BE%2FElement14_Belgium%2Fsearch)
* [Boost regulator](https://www.digikey.be/products/nl?keywords=MCP1640CT-I%2FMCCT-ND)
