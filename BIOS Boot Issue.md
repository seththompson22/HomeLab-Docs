# BIOS Boot Issue

## Problem
Server not booting into BIOS; SATA controller in unknown mode (UCHI); all SATA ports disabled.

## Environment
- Model: Dell PowerEdge R410
- BIOS: (record version after fix)
- Drives: (list)
- Keyboard: (type)

## Steps Taken
1. Power off and remove CMOS battery for 5 minutes.
2. Reset CMOS via jumper.
3. Boot and enter BIOS (F2).
4. Set SATA controller to AHCI.
5. Enable SATA Port A.
6. Save & reboot.

## Results
- BIOS accessible
- SATA ports enabled
- Boot device detected

## Notes
- (add anything you learned)
