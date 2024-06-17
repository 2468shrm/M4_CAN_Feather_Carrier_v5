# M4_CAN_Feather_Carrier_v5

## Board Layout
![alt text]()

## Changes from Previous M4 Carrier Boards

This board has undergone multiple changes from previous versions of thie board, including, but not limite to:
- The level shifter for the DIOs was changed to the TXS0104B from the TXB version
  - The TXS version includes built-in pull ups and works considerably more reliably
- LEDs were added to indicate the logical state of the DIOs
  - An LED was added to each DIO as well as the level shifter enable
- The unity gain opamp was chaged to the LMV324AIDR which is a rail-to-rail version of the prior opamp
- One Qwiic/STEMMA port is removed (leaving 3)
- A MicroSD socket is added and extended to the SPI network (which now comprises of the Ethernet FeatherWing and the MicroS socket)
- A DC-DC converter is adde to the PCB replacing the Weewoodday module (woohoo)
- Cost reduced
  - Replaced many components with JLCPCB "Basic Parts" to reduce the Extended Parts costs
  - Many are 0603 devices for use with JLCPCB's PCBA service
- Updated the silkscreen to congratulate Unni Peri's graduation (the team will miss her contributions in the future, we're sure)

A PDF copy of the schematic [here](https://github.com/2468shrm/M4_CAN_Feather_Carrier_v3/blob/main/Images/Schematic.pdf).

## Checkout Status

This board has bot been fabbed yet.

Not yet tested:
- Everything :)