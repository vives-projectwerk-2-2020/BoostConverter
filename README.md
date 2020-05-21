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
