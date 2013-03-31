Spark Core
====

The hardware design for the Spark Core.

## TODO
- Add a 1K resistor in between the MCU and the USB_DISCONNECT transistor, to limit current in case of failure.
- Replace all resistors/capacitors with 0603.
- Link WP# on SST25VF to 3.3V
- Connect HOLD# on SST25VF to 3.3V
- Re-do the stencil but mirrored correctly
- Re-run ERC and DRC
- Fix labeling for LEDs
- Replace micro USB footprint with a better one (maybe with holes for pins?)
- Make sure part numbers match BOM