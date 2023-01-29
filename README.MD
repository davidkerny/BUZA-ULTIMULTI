# Ultimulti

![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_1.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_2.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_5.png)

**Ultimulti** project is a DIY multi-material solution developped in parallel with a similar project, the Kamil4000, both with the ease of use and reliability being the two key improvement objectives.  
  
It is compatible with Prusa MMU2S so that the Prusa MMU2S unit can be upgraded to Ultimulti with just an addition of a few hardware components and printing new plastic parts.  
  
The most notable advantage of this system are the idler locks which enable you to open and close the idler-body with just a one-handed flick. No longer you have to undo bolts to reach the MMU's internals - and the re-set the idler tension on both sides.  
  
Ultimulti should ideally be used as a **full set of plastic parts** of the most up-to-date revision. In case you opt to use just a part of the Ultimulti plastics on your MMU, please refer to the reverse-compatibility milestones and part descriptions below.  
  
When **printing the plastic parts**, the 0.15mm layer height is advised. PETG material is tested to work reliably. As with the MMU2S, the plastic parts are very sensitive to print defects; especially the first layer adhesion and part warping /lifting up from the heatbed. Verify the filament used is dry, the first layer adhesion is sufficient, the part cooling percentage high enough to maintain the dimensional accuracy and the nozzle temperature high enough to ensure the layer-to-layer bonding.  

## Other hardware required apart from the MMU2S components:  

- MMU2S **data cable** can be modified to provide a more refined 5V voltage level to the electronics board's logic. A stable 5V supply is crucial. Optionally, you can use the power addon board for improved performance.  
- **2.5mm ID clear PTFE tubes** should be used.  5x650mm, 5x19mm, 1x360mm
- the rear of the unit is designed to be used with 5 **E3D collets** to retain the PTFE tubes in.  
- the selector uses the MK3S fs-lever style **magnet and a magnetic ball  **
- the idler is meant to be attached to the motor shaft using either a flat-faced **metal coupler** or a printed adapter with a modified GT2-16 pulley. Remember, idler concentricity is crucial.  
- **M3 washer** for the Chimney calibration screw.  
- then just sum **bolts n nuts**. The majority can be harvested from MMU2S. Extra M3nS square nuts are required.  
- optionally, 5x8mm magnets for motor visualizers  
  
## Important development milestones for reverse-compatibility  

![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_3.png)
![OS](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/OS_4.png)
### Idler body/ pulley body OS(one-sided) C-series 
- Single lock; on the left side only. Even more filament path visibility. Hex key storage was moved down into the Pulley body.  
- Still compatible with, but shouldn't be used anymore with the fully-printed idler due to a commonly occuring idler runout / wobble -> filament loading issues.  
- To be used only with the bottom-mounted electronics and the corresponding legs.

  
![CLASSIC](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/CLASSIC_1.png)
![CLASSIC](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/CLASSIC_2.png)
 ###  Idler body /pulley body Bxx; labeled as Classic - doublelock versions.
- The last version with locks on both sides; 
-  compatible also with closed electronics cover which goes on top. 
-  Compatible with Power addon board that should be held in by the Addon retainr part. 
- Pulley body compatible with Kamil4000. The last version with hex-key storage in the Idler body.  
    

![B20](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/B20_1.png)
![B20](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/B20_2.png)

- **idler body version up to B20.** The last idler body compatible with MMU2S pulley body M1/R1  
- to be used with open back electronics cover. 
- Slot for the hex key in the back for easier removal of the connectors for the old MMU2S power/data cables.  
- in case it is used with the old fully-printed idler, might require different locks as the printed idlers usually need to compensate the idler eccentricity with idler tension setting.  
  

### Experimental
- **OSB** version: freely standing MMU integrated onto the buffer. Yet untested.
- 
![OSB](https://github.com/davidkerny/BUZA-ULTIMULTI/blob/main/OLD-OTHER/IMAGES/AAAA_OSB_SELFSTANDING.png)
