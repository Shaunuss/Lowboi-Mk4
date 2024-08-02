# **Lowboi Mk4 15:1**

## Badass lightweight worm drive extruder.

![Lowboi Mk4 - 003](https://github.com/user-attachments/assets/0906c99f-fc61-479a-980b-68e5d8cabade)

## PARTS DESCRIPTION  
The drivetrain on Lowboi Mk4 uses a single piece gear hob and bearing idler configuration, resulting in a very smooth and high extrusion quality, practically eliminating the common woodgrain artifacting seen in numerous other extruders. This is down to the gear hob being one piece and fully concentric, and no gear meshing issues sometimes seen in dual drive gear extruders. *Bill of materials is at the bottom*

## GEAR  
**K1 steel drive gear hob with DLC coating** is sourced from **AliExpress**, originally intended as an upgrade part for the Creality K1 extruder. I used gears from Mellow and am very happy with the quality. Gear and bearing quality may vary depending on vendor, so I recommend the use of high quality **NSK bearings** including replacing the stock bearing that comes with the gear.
![photo_2024-07-20_02-45-49](https://github.com/user-attachments/assets/f5bb4f71-ad46-460d-bfc0-242190b081e5)

## WORM  
Worm is a high quality steel worm from **KHK** which can come in one or two start configuration, ***cut down to 12mm long***. You are looking at the two start version of the Lowboi Mk4 with a **15:1 drive ratio**. I have also made an extruder body for the one start version for 30:1 drive ratio.
![photo_2024-07-20_02-46-51](https://github.com/user-attachments/assets/f204c4e8-0b08-40db-b61d-cd5fefadcae7)

## GREASE  
It is recommended to use grease containing **molybdenum disulphide** for lubricating the worm and gear, for it's increased anti wear properties.
![photo_2024-07-20_02-51-08](https://github.com/user-attachments/assets/a1d3f296-e734-4f2c-b5b6-442e98179388)

## IDLER BEARING  
Idler is a small bearing mounted in the latch on a **GCR15 bearing steel shaft**. It is technically a fixed unfixed idler without spring, with only a tiny amount of flex in the tensioning latch itself. This provides very strong grip on the filament by the hob.
![photo_2024-07-20_02-53-26](https://github.com/user-attachments/assets/85094aa6-ff2d-40ed-b08f-34381864d50d)

## MOTOR  
Lowboi Mk4 uses a **NEMA14 36mm** pancake motor with 5mm D shaft configuration.

The **LDO-36STH20-1004AH-RevA-1** motor has 0.1Nm of torque, and can be sourced from Mellow on Aliexpress as a replacement motor for their Cannon extruder. This motor will work perfectly fine for most printing applications.

The BOM specifies a MOONs **CSE14HRA2L4100** motor which has 0.19Nm of torque for considerably more extrusion force, and can be sourced from Formbot's website.

## FLOW TESTS
I carry out open air extrusions tests to see flow capability. I tend to use grey or black ASA at 260°C because this filament is a mainstay of my prints. The following tests were all conducted using the same spool of filament, at 260°, unless stated otherwise. 
With the LDO motor, Lowboi Mk4 has been tested to flow up to **31mm^3/s** through a Trianglelab Dragon Ace hotend with the stock 0.4mm nozzle.
With the MOONs motor, the Dragon Ace hotend was able to flow **~35mm^3/s** max on the stock 0.4mm nozzle.
With the addition of the CHT Melt Zone Extender, max flow increased to **45.7mm^3/s**.
Swapping to a 0.5 Bozzle Nozzle increased max flow to **60.1mm^3/s**.
Increasing hotend temp to 300°C increase max flow to **70mm^3/s**.


# 60.1mm^3/s run
https://github.com/user-attachments/assets/7bbf58c4-ef9b-4407-a020-078142051459


# Slow-motion printing vid showing worm drive in action.
https://github.com/user-attachments/assets/c63346ed-cf1d-420c-8268-6457a2b93abd


## BUILD TIPS  
I have printed this in **Polycarbonate**, and **ASA**. Both have worked well.

Print orientation is standing in the normal upright position, on the foot flange, 0.2 layer height with 100% infill, and using automatic supports.

After printing and removing supports, run a 2mm drill bit down through the filament tunnel all the way through the extruder to clear any burrs and prep the tunnel.

Carefully wind a 4mm drill bit by hand through the drive shaft bores, taking care to keep the bit aligned with the holes to avoid removing excess material.

Do the same with a 3mm drill bit through the pivot point bore on the latch. You shouldn't need to do it for the bearing bores unless the shaft is a stubborn fit.

Assemble as per the exploded view, you may need to use polygrip pliers to fit the 4mm driveshaft through the body and bearings.

*Don't forget to cut the worm down to 12mm*.


## CONFIG SETTINGS  

Try these settings to start off with - you may need to tweak rotation distance but this is a great starting point.
```
gear_ratio: 15:1

rotation_distance: 42.3
```

## *Please enjoy Lowboi Mk4 and I would be grateful for your feedback!*

![Lowboi Mk4 - 002](https://github.com/user-attachments/assets/69d5ad3e-afb7-499a-874e-8cfdec06d82f)

## Exploded view with Bill of Materials:
![Exploded](https://github.com/user-attachments/assets/595bb068-20b8-4177-9b76-fb7f80bf6584)


## BOM table, for easy copy paste:

| ITEM NO. | PART NUMBER                | DESCRIPTION                                       | QTY. |
|----------|----------------------------|---------------------------------------------------|------|
| 1        | BODY                       | LOWBOI MK4 BODY - 2 START                         | 1    |
| 2        | MR84-ZZ                    | 4 X 8 X 3 DEEP GROOVE BALL BEARING                | 1    |
| 3        | Bearing Spacer             | 8 X 6 X 2.5 BEARING SPACER (PRINTED)              | 1    |
| 4        | K1 Hob Gear                | K1 steel hob GEAR - DLC COATED                    | 1    |
| 5        | 684-ZZ                     | 4 X 9 X 4 DEEP GROOVE BALL BEARING                | 1    |
| 6        | 4MM GCR15                  | DRIVE SHAFT - Ø4MM X 20MM GCR15 BEARING STEEL PIN | 1    |
| 7        | CSE14HRA2L4100             | MOONS Ø36 X 20.2 NEMA14 PANCAKE STEPPER           | 1    |
| 8        | KHK SW0.5-R2               | KHK 0.5 MODULE TWO START WORM                     | 1    |
| 9        | M3                         | M3 FLAT WASHER                                    | 3    |
| 10       | M03 X 12                   | M3 X 12MM CAPSCREW                                | 2    |
| 11       | M3 4 x 3 brass melt Insert | BRASS MELT INSERT M3 - Ø4MM x 3MM                 | 1    |
| 12       | Latch                      | LOWBOI MK4 IDLER TENSION LATCH                    | 1    |
| 13       | Pivot Shaft                | PIVOT SHAFT Ø3MM x 20MM GCR15 BEARING STEEL PIN   | 1    |
| 14       | MR83-ZZ                    | 3 X 8 X 3 DEEP GROOVE BALL BEARING                | 1    |
| 15       | Idler Shaft                | IDLER SHAFT - Ø3MM x 10MM GCR15 BEARING STEEL PIN | 1    |
| 16       | M03 X 010                  | M3 X 10MM BUTTON HEAD SCREW                       | 1    |
| 17       | Collar                     | REVERSE BOWDEN RETAINING COLLAR                   | 1    |
| 18       | COLLAR Clip                | CLIP FOR RETAINING COLLAR                         | 1    |


