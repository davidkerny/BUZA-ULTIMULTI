# Ultimulti

![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_1.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_2.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_4.png)

**Ultimulti** MMU3 project is a DIY multi-material solution developped in parallel with the Original Prusa MMU3, both with the ease of use and reliability being the two key improvement objectives, while still maintaining a reasonable reverse-compatibility with the earlier MMU2S. Ultimulti provides more visibility and access to the filament path as well as other hardware components. This comes in handy in the moment you need to clear out a filament jam or resolve a similar problem at runtime.

- **Prusa MMU2S to MMU3 Ultimulti upgrade**: with just an addition of a few hardware components and printing new plastic parts, you can build the Ultimulti. 
- For **Ultimulti MMU3 build** from scratch; use the Prusa MMU3 hardware components and just print the new plastic parts to get Ultimulti.
  
The most notable advantage of this system is the idler lock which enables you to open and close the idler-body with just a one-handed flick. No longer you have to undo two bolts to reach the MMU's internals - and then re-set the idler tension on both sides. Single idler tension spring inside the lock also mean an easy and precise tension calibration. It allows the MMU unit to home idler axis more reliably due to the single spring having a longer effective deflection range too.
  
Ultimulti should ideally be used as a **full set of plastic parts** of the most up-to-date revision. In case you opt to use just a part of the Ultimulti plastics on your MMU, please refer to the reverse-compatibility milestones and part descriptions below.  
  
When **printing the plastic parts**, the 0.15mm layer height is advised. PETG material is tested to work reliably. As with the MMU2S, the plastic parts are very sensitive to print defects; especially the first layer adhesion and part warping /lifting up from the heatbed. Verify the filament used is dry, the first layer adhesion is sufficient, the part cooling percentage high enough to maintain the dimensional accuracy and the nozzle temperature high enough to ensure a proper layer-to-layer bonding as well as print surface adhesion.

The MK3S+ [Precise Calibration Chimney](
https://www.printables.com/model/209869-mk3s-mmu2s-precise-calibration-chimney) should be used on the MK3S+ extruder. Note, there were several versions of the MK3S+ MMU Extruder Idler parts. Use the latest one.

## Hardware required apart from the MMU2S parts:  

- For upgrading from MMU2S, getting a MMU3 upgrade kit is higly advised as it will get you all the necessary new components.

- MMU2S **data cable** can be modified to provide a more refined 5V voltage level to the electronics board's logic. A stable 5V supply is crucial! Ideally, the MMU3 cable and PD-board addon should be used.
- **2.5mm ID PTFE tubes** should be used. (as on MMU3)  5x650mm, 5x19mm, 1x360mm
- 19mm and 360mm PTFE tubes can be clear color for better filament visibility, however the rest should be regular non-clear PTFE tubes (reduced friction)
- the rear of the unit is designed to be used with 5 **E3D collets** to retain the PTFE tubes in. (as on MMU3)
- the selector uses the MK3S fs-lever style **10x6x2 magnet and a 7mm magnetic ball** (as on MMU3)
- the idler is meant to be attached to the motor shaft using either a flat-faced **metal coupler** (MMU3) or a printed adapter with a modified GT2-16 pulley. Remember, idler concentricity is crucial!
- **M3 washer** for the Chimney calibration screw. (MMU3)
- then just sum **bolts n nuts**. The majority can be harvested from MMU2S. Extra M3nS square nuts are required. (use MK3 spare bag)
- optionally, 5x8mm magnets for motor visualizers
- If you plan to use the top-mounted electronics cover; is might be held in by two M3x10 bolts instead of M3x18!!
  
  
  
## Important development milestones for reverse-compatibility  

  ### Idler body/ pulley body OS(one-sided) C-series 

![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_3.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_5.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_6.png)

- Single lock; on the left side only. Even more filament path visibility. 
- Still compatible with, but shouldn't be used anymore with the fully-printed MMU2S idler due to a commonly occuring idler runout / wobble causing filament loading and idler homing issues. Idler with metal 5mm shaft coupler or GT2-16 pulley should be used instead.
- Allen key storage is now on the left side of the Pulley body (2.5mm, 2mm and 1.5mm long ones) 
- To be used **only** with the bottom-mounted electronics and the corresponding legs that retain the control board below the pulley body.

- Front PTFE holder since B15: grooves between the filaments for easier waste management after cutting function was initiated.
- Selector since B17: openings to superglue the bronze bushings in, in case these do not hold in properly. (Usually, they don't only if the parts were printed incorrectly.)
- Selector since B14: different filament entry after FINDA and large opening for clearing out strings from under the FINDA ball. 
- Idler body since C5_3 and C6: Idler tilt compensation for more equal idler tension across all the filament positions. (improvement for extremely stringy materials)


  ###  Idler body /pulley body Bxx; labeled as Classic - doublelock version.

![CLASSIC](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/CLASSIC_1.png)
![CLASSIC](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/CLASSIC_2.png)
![CLASSIC](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/CLASSIC_3.png)

- The last version to be used with locks on both sides; but found to work even with just the left one in place.
- Compatible with all electronics mounting options: open-back or closed-back cover on top (as in the picture above) or the bottom mounted. (C version)
- Idler body since B20 Compatible with PD-board addon (MMU3) that should be held in by the Addon retainr part. 
- Idler body since B20 incompatible with MMU2S. MMU3 compatible. There is a hex-key storage on the right side of the Idler body.  

- Selector >B13 not reverse compatible with blade holder <B16 as well as MMU3 blade-holder. Selector >B14 should be only used with blade holder >B17.

  ### Idler body version <B19 (obsolete)

![B20](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/B20_1.png)
![B20](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/B20_2.png)

- The last idler body compatible with MMU2S pulley body M1/R1. If you are too lazy or out of filament; using this version, you can update your MMU2S to idler locks without having to reprint the pulley body.
- printed locks on both sides instead of the M3x30 idler tension bolts directly attached to idler body. Some older versions of the locks have more clearance to account for fully-printed idler's wobble.
- Incompatible with MMU3 PD-board Addon and cable. Old MMU2S data & power cables should be used. There is a zip-tie attachment point for the cables.
- a notch below the connectors for easier MMU2S power/data cable removal using a hex key. Insert the hex key from side to undo the safety latches on the connectors, while pulling the connectors out.
- to be used mainly with the open-back electronics cover (up to B14) - as seen in the picture above - for easier cable management.
- in case it is used with the old fully-printed idler, might require different locks as the printed idlers usually need to compensate the idler eccentricity with idler tension setting. Different older versions of the locks vary in dimensions.

- Ele cover TOP_NOLOCK_B8 version with idler tension bolt retainers is compatible only with the MMU2S Idler body M1/R1 without the Idler locks. Electronic board torsion strain relief cutouts and TMC venting openings. Zip-tie attachment points for easier cable management. (the initial version)

  ### Experimental

![OSB](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OSB_SELFSTANDING.png)

- **OSB** version / D-series: freely standing C-series UltiMulti MMU integrated onto the buffer.


