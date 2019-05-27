# FusionAdoptabot
  
This is an adaptation of Printrbot's Adoptabot original design (https://www.brookdrumm.com/3dprinters1).  
  
This Adaptation, removes Printerbot proprietary parts.  
* Hotend is replaced with E3D V6 All metal hotend  
* Extruder is an E3D Titan  
* The bed sensor is a BLtouch  
* Electronics are Arduino Mega + Ramps 1.4-1.6  
  
PLA Parts all printed with 3 or 4 Permitars and 33% infill.  
Suports are not included as these will vary with your own printerbot.  
  
The only custom component is the Print bed.  
  
All credit goes to Brook for releasing this design into the community. Without his work this would not have been possible.  
  
**This design is licensed cc sharealike non comercial.**  
  
### 3D Models:  
The 3D design is included  as a Fusion F3Z. Download this Fusion Archive. Launch Fusion 360. Create a new Project and in the data pane click upload. Select the F3Z.
Fusion will unpack the archive and upload all the necissary parts and assemblies into the new project.  
  
The model is also provided as STEP203 and can be imported into most any 3D CAD tool.
  
### STL Files:  
Over the comming weeks I will extract and post the STL files. You can get these yourself from the above 3D models.    
Posting of the STL files is only a convience for those looking to simply print and assemly the printer.  
  
### Firmware:
A work in progress firmware is available here: https://github.com/schneik80/Marlin-FusionAdoptabot  
The firmware currenly support kinimatic setings only. Hotend configuration is TBD.  

### Images:

![](/_PROD-Adoptabot_Ramps_000010_2019-May-25_09-30-13PM-000_CustomizedView15403030646_png.png?raw=true)  
  
![](/_PROD-Adoptabot_Ramps_000010_2019-May-25_09-30-13PM-000_CustomizedView56993606097_png.png?raw=true)  
  
![](/_PROD-Adoptabot_Ramps_000010_2019-May-25_09-30-13PM-000_CustomizedView6313149427_png.png?raw=true)  
  
### Bill of Materials PROD-Adoptabot Ramps 000010 v26:     

| **Display Name**                         | **Material**      | **Count** |
|--------------------------------------|---------------|-------|
| RAMPS1_4 + Arduino Mega Electronics  |               | 1     |
| Limit Switch - 10T85                 |               | 2     |
| DC Jack 5.5 X 2.1mm                  |               | 1     |
| Rocker Switch 10A                    |               | 1     |
| E3D Titan Areo Extruder              |               | 1     |
| E3D v6 HotEnd                        |               | 1     |
| Fan 30 X 30 X 10 - 12v               |               | 1     |
| Fan 40 X 40 X 10mm                   |               | 1     |
| BL-touch                             |               | 1     |
| .125 Print Plate                     | Aluminum 6061 | 1     |
| GT2 20 Tooth Pully                   | Aluminum      | 2     |
| GT2 Belt 305mm                       | Rubber, Black | 2     |
| 8 x 175mm Rod                        | Chrome Steel  | 2     |
| 8 x 190mm Rod                        | Chrome Steel  | 2     |
| 8 x 195mm Rod                        | Chrome Steel  | 2     |
| LM8UU                                |               | 12    |
| 608 2Z Bearing                       |               | 1     |
| 624 2Z - 13 x 4 x 5mm Bearing        |               | 4     |
| NEMA 17  Stepper Motor length - 23mm |               | 1     |
| NEMA 17 - Stepper Motor - 34mm       |               | 2     |
| NEMA-17-TR8-8 X 350 Leadscrew        |               | 1     |
| ISO 4032 - M3                        | Steel, Alloy  | 25    |
| ISO 7089 - 3 - 140 HV(1)             | Steel, Alloy  | 4     |
| ISO10511 - M3                        | Steel, Alloy  | 2     |
| ISO 4026 - M3 x 4I                   | Steel, Alloy  | 4     |
| ISO 10642 - M3 x 8                   | Steel, Alloy  | 4     |
| ISO 4762 - M3 X 8                    | Steel, Alloy  | 13    |
| ISO 4762 - M3 X 10                   | Steel, Alloy  | 5     |
| ISO 4762 - M3 X 12                   | Steel, Alloy  | 13    |
| ISO 4762 - M3 X 16                   | Steel, Alloy  | 6     |
| ISO 4762 - M3 X 20                   | Steel, Alloy  | 15    |
| ISO 4762 - M3 X 35                   | Steel, Alloy  | 3     |
| Case Panel                           | PLA           | 1     |
| X Bar End Clamp Left                 | PLA           | 1     |
| X Build Plate Clamp Left             | PLA           | 1     |
| X Bar End Clamp Right                | PLA           | 1     |
| X Build Plate Clamp Right v1         | PLA           | 1     |
| Belt Tensioner                       | PLA           | 1     |
| X Bearing Block                      | PLA           | 1     |
| Ramps Cover                          | PLA           | 1     |
| Main Housing                         | PLA           | 1     |
| Case Rear                            | PLA           | 1     |
| Z Motor Shim                         | PLA           | 1     |
| Extruder Mount                       | PLA           | 1     |
| Cooling Fan Shroud                   | PLA           | 1     |
| Cooling Fan Shroud Mount             | PLA           | 1     |
| BLTouch Bracket                      | PLA           | 1     |
| Y Bar End Clamp                      | PLA           | 1     |
| Belt Tensioner                       | PLA           | 1     |
| Y Bearing Block                      | PLA           | 1     |
| Z Bar Clamp                          | PLA           | 1     |
| Z Bearing Block                      | PLA           | 1     |
| TR8 Nut                              | PLA           | 1     |
  
