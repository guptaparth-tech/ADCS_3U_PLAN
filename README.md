# Basic ADCS States

The basic ADCS states can be divided as follows:

## 1. Detumbling

- **Entry:** In the beginning only.
- **What all stuff is used:** MT and RnX wheels.

Basically, using the B-dot algorithm to detumble the satellite.

## 2. Sun Pointing

- **Entry:** CSS (coarse sun sensor), SoC (charge).
- **What all stuff is used:** RnX wheels.

## 3. Imaging

- **Entry:** GPS data, triggers, target locations (can be uplinked later as well).
- **What all stuff is used:**

Exactly how it will be done will be figured out after understanding how the camera works (using datasheets).

## 4. Downlink

- **Entry:** GPS data, triggers, target locations (can be uplinked later as well).
- **What all stuff is used:**

Downlink will be done in the required cone.

## 5. P_Dumping

It will be a synchronised state with Sun Pointing.

# Open Questions

1. Should B-dot run on the ADCS or EPS board?
2. If we deploy solar panels, will ADCS support them?
3. Is it required to turn on the OBC (specifically Omega, ...) after detumbling is done?
4. Mission statement (Shashank: required to determine whether we will do imaging at night).
5. Read what GPS exactly gives.
6. Can the camera image at non-nadir points?
7. Run the orbit simulation on the ADCS/OBC board.
8. Status of the RnX wheels (CUBESPACE website).