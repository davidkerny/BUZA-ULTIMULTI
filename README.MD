# Ultimulti

![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_1.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_2.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_4.png)

**Ultimulti** project is a DIY multi-material solution developped in parallel with a similar project, the Kamil4000, both with the ease of use and reliability being the two key improvement objectives, while still maintaining a reasonable amount of reverse-compatibility with MMU2S and mutual compatibility with Kamil.
  
It is compatible with Prusa MMU2S so that the Prusa MMU2S unit can be upgraded to Ultimulti with just an addition of a few hardware components and printing new plastic parts.  
  
The most notable advantage of this system is the idler lock which enables you to open and close the idler-body with just a one-handed flick. No longer you have to undo two bolts to reach the MMU's internals - and then re-set the idler tension on both sides. Single idler tension spring inside the lock means an easier tension adjustments and allows the MMU unit to home idler axis more reliably.
  
Ultimulti should ideally be used as a **full set of plastic parts** of the most up-to-date revision. In case you opt to use just a part of the Ultimulti plastics on your MMU, please refer to the reverse-compatibility milestones and part descriptions below.  
  
When **printing the plastic parts**, the 0.15mm layer height is advised. PETG material is tested to work reliably. As with the MMU2S, the plastic parts are very sensitive to print defects; especially the first layer adhesion and part warping /lifting up from the heatbed. Verify the filament used is dry, the first layer adhesion is sufficient, the part cooling percentage high enough to maintain the dimensional accuracy and the nozzle temperature high enough to ensure the layer-to-layer bonding.  

## Other hardware required apart from the MMU2S / Kamil components:  

- MMU2S **data cable** can be modified to provide a more refined 5V voltage level to the electronics board's logic. A stable 5V supply is crucial. Optionally, you can use the power addon board for improved performance.  
- **2.5mm ID PTFE tubes** should be used.  5x650mm, 5x19mm, 1x360mm
- 19mm and 360mm PTFE tubes can be clear color for better filament visibility, however the rest should be regular non-clear PTFE tubes (for reduced friction)
- the rear of the unit is designed to be used with 5 **E3D collets** to retain the PTFE tubes in.  
- the selector uses the MK3S fs-lever style **magnet and a magnetic ball  **
- the idler is meant to be attached to the motor shaft using either a flat-faced **metal coupler** or a printed adapter with a modified GT2-16 pulley. Remember, idler concentricity is crucial.  
- **M3 washer** for the Chimney calibration screw.  
- then just sum **bolts n nuts**. The majority can be harvested from MMU2S. Extra M3nS square nuts are required.  
- optionally, 5x8mm magnets for motor visualizers  
- Top-mounted electronics cover is held in by two M3x10 bolts instead of M3x18!
  
  
  
## Important development milestones for reverse-compatibility  

  ### Idler body/ pulley body OS(one-sided) C-series 

![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_3.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_5.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_6.png)

- Single lock; on the left side only. Even more filament path visibility. Hex key storage was moved down into the Pulley body.  
- Still compatible with, but shouldn't be used anymore with the fully-printed idler due to a commonly occuring idler runout / wobble causing filament loading and idler homing issues. Idler with metal 5mm shaft coupler or GT2-16 pulley should be used instead.
- Hex key storage on the left side of the Pulley body (2.5mm, 2mm and 1.5mm ones)
- To be used **only** with the bottom-mounted electronics and the corresponding legs that retain the control board below the pulley body.

- Idler bodies since C5_3 and C6 versions, utilize an idler tilt compensation for more equal idler tension across all the filament positions.

  ###  Idler body /pulley body Bxx; labeled as Classic - doublelock version.

![CLASSIC](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/CLASSIC_1.png)
![CLASSIC](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/CLASSIC_2.png)
![CLASSIC](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/CLASSIC_3.png)

- The last version to be used with locks on both sides; works even with just the left one in place.
- Compatible with open-back as well as closed-back electronics cover on top (as in the picture above) or with the bottom mounted electronics.
- Compatible with Power addon board that should be held in by the Addon retainr part. 
- Pulley body compatible with Kamil4000. There is a hex-key storage on the right side of the Idler body.  


- Selector >B13 not reverse compatible with blade holder <B16 as well as Kamil's blade-holder. Selector >B14 should be only used with blade holder >B17.

  ### Idler body version <B19 (obsolete)

![B20](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/B20_1.png)
![B20](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/B20_2.png)

- The last idler body compatible with MMU2S pulley body M1/R1. If you are too lazy or running out of filament; using this version, you can update your MMU2S to idler locks without having to reprint the pulley body.
- printed locks on both sides instead of the M3x30 idler tension bolts directly attached to idler body. Some older versions of the locks have more clearance to account for fully-printed idler's wobble.
- Incompatible with Kamil's Power Addon board. Old MMU2S data & power cables should be used. There is a zip-tie attachment point for the cables.
- a notch below the connectors for easier MMU2S power/data cable removal using a hex key.  
- to be used mainly with the open-back electronics cover - as seen in the picture above - for easier cable management.
- in case it is used with the old fully-printed idler, might require different locks as the printed idlers usually need to compensate the idler eccentricity with idler tension setting.  
  

  ### Experimental

![OSB](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OSB_SELFSTANDING.png)

- **OSB** version / D-series: freely standing C-series UltiMulti MMU integrated onto the buffer.


