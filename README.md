Spark Core
====

The hardware design for the Spark Core.

## TODO
- Re-do the stencil but mirrored correctly

## NECESSARY TESTING
- Get CC3000 and STM32 talking
- Get memory module and STM32 talking
- Test all of the pins, LEDs, buttons, etc.
- Make the VDDA circuit actually work and not kill the board

## NEXT REVISION
- Replace memory module with a smaller footprint one
- Turn the LEDs around so HIGH = on and LOW = off
- Remove the resistors on WIFI_EN and WIFI_CS
- Connect the power regulator directly to C2, not to the power plane
- See if we can add more decoupling capacitors for the CC3000