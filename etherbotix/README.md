# Etherbotix

## Notes

Notes from stuffing Rev. A:
 * DC-DC regulator is too close to Dynamixel headers (has to be installed slightly angled away)
 * X2 footprint is missing direction indicator.
 * X2 footprint should be a bit wider for hand-stuffing.
 * C39, C40 are 22pF (might still be too high)
 * Encoder capacitor values may not be right (too aggressive of a filter)

Need to source 7/16" or 11mm length, 4-40 or M3 standoff (possibly 952-1520-ND)

## Revision History

 * Rev. B - (Forthcoming)
   * Increase size of P1 indicator on X2.
   * Moved ethernet parts away from MD-03 mounting hole
   * TODO: move U3 away from AX headers
   * TODO: move J1 (ethernet jack) up a bit to avoid collision with IMU
   * TODO: update values of C39, C40
   * TODO: update values of C4, C13, C17, C18
   * TODO: move R19, R24, R25 out from under IMU
   * Move M1 encoder filter away from MD-03 mounting hole
   * Add testpads for PE0, PE1, PE4, PA8
   * Add testpads to encoders, clocks, and current sense
   * Add jumper to force bootloader
   * TODO: change away from clikmate connector
 * Rev. A - September 7, 2014
   * First release
