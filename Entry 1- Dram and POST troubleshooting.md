# DRAM and POST Troubleshooting

**System: Desktop PC Workstation**

## Problem
The desktop powered on but would not complete POST and no video output came on

## Troubleshooting steps taken:
1. Disconnected the AC power and discharged the system.
2. Removed the RAM stick from slot A2.
3. Powered the system on and checked the motherboard debug LEDs and speaker.
4. Noted the memory error shown by the motherboard.
5. Powered the system back down and checked the RAM and slot for visible damage or dirt.

## Root Cause
The RAM stick was not fully seated in slot A2, preventing successful memory initialization during POST.

## Fix
1. Reinstalled the RAM stick into slot A2.
2. Pressed down evenly until both retention clips locked into place.
3. Powered the system back on and allowed it to retrain the memory.
## Result

The system completed POST and entered the UEFI setup screen with the expected amount of RAM detected.

## Skills Shown
Hardware Troubleshooting DRAM POST Diagnostics UEFI
