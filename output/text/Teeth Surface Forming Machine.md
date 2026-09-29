# Teeth Surface Forming Machine


## Page 1

JIN 
Teeth Surface Forming Machine 
 
 
Operation Manual 
（Electric Diagram） 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
TOKUSHIN ELECTRIC INDUSTRIES CO., 
LTD. 
17-32 Tomiyoshi Aza Suzaki Aizumi-cho 
Itano-gun Tokushima Japan 771-1231 
Tel: (81) 88 - 692 - 5588 
Fax: (81) 88 - 692 – 5986 
March/ 2024



## Page 2

Contents 
 
1. 
About automatic driving .............................................................................................................. 1 
1-1. Automatic startup procedure ................................................................................................... 1 
1-2. Automatic driving stop method ................................................................................................ 1 
2. About return driving ........................................................................................................................ 2 
2-1. A return startup procedure ...................................................................................................... 2 
2-2. Return driving stop method ..................................................................................................... 3 
3. About manual operation .................................................................................................................. 4 
3-1. The startup procedure of manual operation ........................................................................... 4 
4. Indication light / operation switch explanation ............................................................................. 5 
5. About the touch panel screen .......................................................................................................... 7 
5-1. Main screen ............................................................................................................................... 8 
5-1-1. Main screen comment list .................................................................................................. 9 
5-2. Manual Operation ................................................................................................................... 10 
5-3. PLC Device Monitor ................................................................................................................ 11 
5-4. Common Specifications Setup Screen ................................................................................... 12 
5-5.Fault Description ..................................................................................................................... 13 
5-5-1. Fault Content ................................................................................................................... 13 
5-5-2. Fault Detail ...................................................................................................................... 14 
5-5-3. Fault Occurrence Counts ................................................................................................. 15 
5-5-4. Fault History .................................................................................................................... 16 
5-5-5. ST1 Fault Description screen comment list ................................................................... 17 
5-5-6. ST2 Fault Description screen comment list ................................................................... 20 
5-6. Specifications Setting Menu ................................................................................................... 23 
5-7. Common Specifications Setup Screen ................................................................................... 24 
5-8. Specifications setup screen 1/3 .............................................................................................. 25 
5-9. Specifications setup screen 2/3 .............................................................................................. 27 
5-10. Specifications setup screen 3/3 ............................................................................................ 29 
5-11. Copy of Specifications ........................................................................................................... 31 
5-12. Counter screen ...................................................................................................................... 32 
5-13. Type Name Registration ....................................................................................................... 33 
5-14. Load Torque Calibration Screen .......................................................................................... 34 
5-15. ANDON Screen ..................................................................................................................... 35 
6. Calibration method of strain amplifier ........................................................................................ 36 
 
7. Part List 
 
8. Control Panel & Operation Panel Arrangement Dwg. 
 
9. Electric Circuit Diagram 
 
10. PLC Ladder Diagram



## Page 3

1 
 
1. About automatic driving 
1-1. Automatic startup procedure 
 
Start procedure of automatic driving is as follows. 
 
1) Turn ON this equipment power switch. 
 
2) Reset the "EMERGENCY STOP" button on the operation panel and back side 
of machine (turn the switch clockwise). 
 
3) Push the "MASTER" illuminated push button switch, and confirm lighting of 
the lamp. When driving preparations do not enter, confirm next. 
・Is PLC and Safety PLC in a panel running? 
・Does not the light curtain blocked? 
・Does not abnormality of servo driver occur? 
・Does not abnormality of Rotation Refresh Converter occur? 
 
4) Confirm whether abnormality does not occur. 
When abnormality occurs, a red light of facility signal tower turns on.   
Confirm contents with a " Fault Description " screen of touch panel, and push 
the "RESET" button after cancellation of the cause, and remove abnormality. 
 
5) Make the "CYCLE" select switch "AUTO" side. 
 
6) Please select "TYPE" with TYPE SELECT screen of touch panel. 
Please push a "type number change" switch if different from type number to hope for. A 
type number selection window is displayed. Enter the desired model number and press 
the "Change model number" switch for 2 seconds to change the model number. 
 
7) Set a work, and please insert a lower shaft serration. 
 
8) Confirm comment of " Can start automatic operation." with "MAIN" screen of touch 
panel. When comment except this appears, please obey instructions of the 
comment. 
 
9) Automatic driving is started when knocked on “lever switch”. 
If work is completed, and all actuators return to an original position, it is stopped. 
 
1-2. Automatic driving stop method 
 
Stop method of automatic driving has the following method. 
 
1) Switch off this equipment. 
An arrangement stops instantly at the place. There are some cylinders using a 
solenoid valve of two positions, and warn those actuators because those cannot 
stop in mid career.  Do not use this method as much as possible. 
 
2) Push the " EMERGENCY STOP " button. 
Preparing it is running out of driving, and equipment stops instantly at the 
place. 
There is danger to a worker or a work, and use this method when it is urgent.



## Page 4

2 
 
 
3) Light curtain block. 
Preparing it is running out of driving, and equipment stops instantly at the 
place. 
 
4) Make the "CYCLE" select switch "MANU." side. 
Automatic driving stops immediately. 
 
5) Pushing the “HOME POSITION” push button switch. 
Automatic driving stops immediately. But some cylinders using a solenoid 
valve of two positions cannot stop in mid career. 
 
 
2. About return driving 
 
You can return an actuator to machine original position by carrying out return driving. 
 
2-1. A return startup procedure 
 
The start procedure of return driving is as follows. 
 
1) Turn ON this equipment power switch. 
 
2) Reset the "EMERGENCY STOP " button on the operation panel and back side of 
machine (turn the switch clockwise). 
 
3) Push the "MASTER" illuminated push button switch, and confirm lighting of the 
lamp. When driving preparations do not enter, confirm next. 
・Is PLC in a panel running? 
・Does not the light curtain blocked? 
・Does not abnormality of servo driver occur? 
・Does not abnormality of Rotation Refresh Converter occur? 
・Does not abnormality of L/S torque? 
 
4) Confirm whether abnormality does not occur. 
When abnormality occurs, a red light of facility signal tower turns on.   
Confirm contents with a "Fault Description" screen of touch panel, and push the 
"RESET " button after cancellation of the cause, and remove abnormality. 
 
5) Confirm whether NG does not occur. 
When NG occurs, a red light of facility signal tower turns on.   
Perform NG measures. 
 
6) Make the "CYCLE" select switch "MANUAL" side. 
 
7) Confirm comment expression of "Can start Return operation" in "main screen "of touch 
panel. When comment except this appears, obey instructions of the comment. 
 
8) Push the "HOME POSITION" push button switch, then auto cycle start. 
When the equipment becomes original position, it stops. 
If the equipment does not become original position for 30 seconds, it gives up 
and stops.



## Page 5

3 
 
2-2. Return driving stop method 
 
As for return driving, usually when the equipment becomes original position, it stops 
automatically.   
The method to stop return driving on the way has the following method. 
 
1) Switch off this equipment. 
An arrangement stops instantly at the place. Do not use this method as much as 
possible. 
 
2) Push the "EMERGENCY STOP" button. 
Preparing it is running out of driving, and equipment stops instantly at the 
place. 
There is danger to a worker or a work, and use this method when it is urgent. 
 
3) Light curtain block. 
Preparing it is running out of driving, and equipment stops instantly at the 
place. 
 
4) Make the "CYCLE" select switch "MANU." side. 
Return driving stops immediately.



## Page 6

4 
 
3. About manual operation 
 
3-1. The startup procedure of manual operation 
 
Startup procedure of manual operation is as follows. 
 
1) Turn ON this equipment power switch. 
 
2) Reset the " EMERGENCY STOP" button on the operation panel and back side of 
machine (turn the switch clockwise). 
 
3) Push the "MASTER" illuminated push button switch, and confirm lighting of the 
lamp. 
When driving preparations do not enter, confirm next. 
・Is PLC in a panel running? 
・Does not the light curtain blocked? 
・Does not servo amp abnormality occur? 
・Does not abnormality of Rotation Refresh Converter occur? 
 
4) Make the "CYCLE" select switch "MANU" side. 
 
5) Choose an item (an actuator), which you want to operate with a screen of 
"Manual Operation” and press the "EXECUTE" illuminated button to operate 
the actuator. 
When movement condition of the chosen actuator is concluded, lamps of these 
illuminated buttons flash on and off, and the lamp of corresponding lights it 
when it arrives at a movement edge. 
＊Manual operation does not start it when blocked light curtain. 
In addition, it does not work unless it satisfies movement condition. 
An actuator stops immediately when get off these illuminated push button 
swatches. 
6) An actuator that inching is possible stops immediately when get off these 
illuminated push button swatches. 
 
7) An actuator block with a light curtain during an operation. During automatic driving 
equipment stops immediately when they push this switch.



## Page 7

5 
 
4. Indication light / operation switch explanation 
 
Functions of indicators and operation switches on the control box and the control 
panel are as follows. 
 
1) The “POWER” indication light 
It is with a main circuit breaker, and a control power supply turns on during 
electricity. 
 
2) The "CYCLE" select switch 
It is as follows in a choice state. 
"MANUAL”: manual operation each one operation is enabled. 
"AUTO": automatic driving is enabled. 
 
3) The " MASTER " illuminated push button switch 
Switch: 
Turn on driving preparations. 
Power is supplied, and / return / automatic driving worked by hand is 
enabled. 
Condition: 
The "EMERGENCY STOP" button of a control panel and back side art not 
pushed into. 
・Is PLC in a panel running? 
・Does not the light curtain blocked? 
・Does not servo amp abnormality occur? 
・Does not abnormality of Rotation Refresh Converter occur? 
Lamp: 
Turn on among driving preparations ON. 
 
4) The "EMERGENCY STOP" lock type push button switch 
It is running out of driving and stops all power supply. Establish it in a control 
panel and the vicinity of a back safety door. 
 
5) The "RESET" push button switch 
When an abnormal cause is removed, abnormality is reset when you push this 
switch. The warning buzzer stops when you push this switch when an abnormal 
cause is not removed. 
 
6) The "HOME POSITION" type push button switch 
When “CYCLE” is selected “MANU”, you push this switch. And return driving 
starts. During automatic driving equipment stops immediately when they push 
this switch.



## Page 8

6 
 
7) The "EXECUTE" illuminated push button switch 
Switch: 
Operate an operation item (an actuator) chosen with a screen of "Manual 
Operation" of touch panel to the original position side. 
Condition: 
Driving preparations are ON, and "MANU." is chosen with the "CYCLE" 
selecting switch. 
There are conditions for each operation item. 
Lamp: 
When the original position side operation condition of a chosen operation 
item is concluded, it flashes on and off. 
It turns on at time of the chosen operation item is the original position end.   
In addition, turn on when you push a "Lamp Check" switch of touch panel 
"Setting Menu Screen". 
8) Buzzer 
When a Lever switch was able to leave ON in the state that in heterology or 
automatic driving cannot carry out, it is sounded. 
In addition, sound when auto driving passed with possible condition more than five 
seconds. 
A buzzer stops when pushes a "reset" switch. 
9) “ACCESS OK” Lamp 
When they do not work, an actuator and a servomotor turn on Midori. I turn on red 
during the movement of facilities. The driving preparations do not fail in a rye toe 
curtain at the time of the green lighting even if they shade the light, but driving 
preparations fail in light car ten at the time of the red lighting when they shade the 
light.



## Page 9

7 
 
5. About the touch panel screen 
 
There is a screen such as follows in touch panel. 
Screens not requiring password 
･ MAIN SCREEN 
･ MANUAL OPEARTION SCREEN 
･ PLC DEVICE MONITOR SCREEN 
･ COUNTER SCREEN 
･ SPECIFICATIONS MONITOR SCREEN 
･ ABNORMAL DESCRIPTION SCREEN 
･ ABNORMAL HISTORY SCREEN 
Screens that cannot be displayed unless password is input 
･ COMMON SPECIFICATIONS SETUP SCREEN 
･ SPECIFICATIONS SETUP SCREEN 
･ COPY OF SPECIFICATIONS SCREEN 
･ TYPE NAME REGISTRATION SCREEN 
･ L/S TORQUE CALIBRATION SCREEN



## Page 10

8 
 
5-1. Main screen 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) It displays the name selected for product currently. 
 
2) It displays cycle time of the machine. 
 
3) It displays the work type number 
 for product currently. 
 
4) Type change switch 
Please press the model number you want to select.  
Press for 2 seconds to change the model number. 
 
5) Display current input shaft torque. 
Display current input shaft torque. 
 
6) Display current load shaft torque. 
Load shaft torque is output at +-10V by AS2603. Become 200N / m at 10V. 
 
7) Display Average L/S Torque 
Revise load torque during forming. Display average load torque between revision. 
 
8) DMC code display. 
 
9) System home position lump 
The station turns on at a home position. 
 
10) Tool change cycle manual select switch and lamp 
This button lights, and when machine home position, the tool change cycle can be 
started. 
 
11) Comment indication 
Here, it displays various comments to help operation of an operator. 
(Refer to 5-1-1."Main" screen comment list) 
 
12) Touch panel screen changing switch 
 
 
2
1
4
3
5
6
8
9
11 
12 
7
10



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "1234567890abcdefg",
  "source_file_origin": "production_line_monitoring_system",
  "page_or_sheet_location": "main control panel",
  "component_name": "HMI screen for tooth surface forming machine",
  "keywords": [
    "tooth surface forming",
    "machine interface",
    "fault monitoring"
  ],
  "visual_specifications": {
    "expected_color": "The background is black with blue and white text, and red highlights for faults.",
    "critical_alignment_angles": "The layout is symmetrical, with two main sections labeled 'ST1' and 'ST2', each containing multiple sub-sections.",
    "surface_texture_purity": "The interface appears clean and well-organized."
  },
  "detailed_explanation": "This image shows a high-resolution HMI screen of a tooth surface forming machine. It displays various parameters such as current type, changeable status, cycle time, and torque measurements for both 'ST1' and 'ST2'. The screen is divided into two main sections with labels in Japanese (left) and English (right). Red highlights indicate fault conditions, while yellow boxes highlight the 'CHANGE CYCLE' and 'CHANGE POSITION' options. The bottom section includes a red bar indicating faults on both sides.",
  "common_defects_and_failures": [
    {
      "defect_type": "Fault",
      "visual_signs": "Red highlights around fault indicators, such as 'ST2 FAULT CONTENT', 'ST1 FAULTCONTENT', and 'ANDON' buttons.",
      "criticality_level": "HIGH"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/00fbdd72.jpeg"
}
```


## Page 11

9 
 
 5-1-1. Main screen comment list 
 
Comments on the Main screen are allocated to the PLC internal relays 
ST1 M640 to M671, ST2 M1640 to M1671. When an internal relay turns ON,  
the comment corresponding to the internal relay is displayed. 
If multiple internal relays should turn ON simultaneously, switch comment at an 
interval for three seconds. 
 
Main screen comment list 
ST1 
Device
ST2 
Device
Comment 
M640
M1640
Fault Occurred.
M641
M1641
Please press "MASTER ON" button. 
M642
M1642
Emergency stop button is pressed.
M643
M1643
Manual operation.
M644
M1644
Light curtain is being blocked.
M645
M1645
During safety maintenance 
M646
M1646
Vacuum filter check timing
M647
M1647
L/S Torque NG
M648
M1648
Please check the air dryer power.
M649
M1649
W/S Torque NG
M650
M1650
Automatic off NG
M651
M1651
Please change W/S socket.
M652
M1652
Please change L/S socket.
M653
M1653
Lack of Tonner forecast
M654
M1654
Please set a work-piece.
M655
M1655
Please take out a marker pen.
M656
M1656
Please take out a work-piece.
M657
M1657
Please insert the Serration.
M658
M1658
Please return to home position.
M659
M1659
Can start automatic operation.
M660
M1660
Please start warm-up cycle
M661
M1661
Turn Setting switch off.
M662
M1662
During warm-up cycle
M663
M1663
During safety maintenance 
M664
M1664
During auto run cycle
M665
M1665
During return cycle
M666
M1666
M667
M1667
Read Data Matrix code
M668
M1668
TARCEABILITY-NOT OK TO RUN!
M669
M1669
TYPE MISMATCH WITH SERVER 
M670
M1670
Waiting response from server
M671
M1671
PLC Battery Error



## Page 12

10 
 
5-2. Manual Operation 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) Combined illuminated type selector PB switch + collective indicator lamp 
There are switches to select items to be selected (actuators) and lamps to 
indicate selection of the items. 
When the run preparation is ON and the "MANUAL" mode is selected on the 
"CYCLE" selector switch, push an item to be operated. An operation items is 
selected, and the lamp for the item comes on to indicate the item is selected. 
When an operation items is selected, individual operation becomes available by 
pressing the "EXECUTE" illuminated type pushbutton switch or "RETURN" 
illuminated type pushbutton switch. However, refer to above-mentioned "3-2. 
Manual operation condition lists" because operating conditions are specified per 
operation item. 
In addition, indicator lamps are provided on the operation side and the original 
position side ends of each item, so that the lamp comes on when the applicable 
sensor turns ON. 
 
2) Load Torque Display  
Display current load torque value. 
 
 
 
1
2



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "ST1-1_240224105015",
  "source_file_origin": "Manual ST1-1/2",
  "page_or_sheet_location": "Page 1, Sheet 1",
  "component_name": "HMI Screen for Manufacturing Equipment",
  "keywords": [
    "HMI",
    "Manufacturing",
    "Equipment",
    "Traceability"
  ],
  "visual_specifications": {
    "expected_color": "The background is black with colored text and buttons.",
    "critical_alignment_angles": "The screen has a grid layout with rows and columns, each containing different control options.",
    "surface_texture_purity": "The interface appears to be clean and well-organized."
  },
  "detailed_explanation": "This image shows an HMI (Human-Machine Interface) screen used for controlling manufacturing equipment. The screen is divided into multiple sections with various buttons and labels, each representing different functions such as work clamp control, forming rotation, and torque settings. The top of the screen displays the date and time, while the bottom indicates that it's in Japanese and English languages. The screen also shows traceability information at the top left corner.",
  "common_defects_and_failures": [
    {
      "defect_type": "Incorrect Language Display",
      "visual_signs": "The language display is incorrect (Japanese instead of English).",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/add02362.jpeg"
}
```


## Page 13

11 
 
5-3. PLC Device Monitor 
 
Almost all devices possessed by the PLC can be monitored on this screen. 
Monitoring is performed at the unit of 1 word (16 bits). Two different kinds of 
devices are monitored the ON/OFF status, hexadecimal numbers and decimal 
numbers of respective bits at the same time. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) A lamp displays an ON/OFF state of a bit unit.  (ON = green) 
 
 
 
 
1



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "1234567890abcdefg",
  "source_file_origin": "Device Monitor Image",
  "page_or_sheet_location": "Page 1, Sheet 1",
  "component_name": "HMI Screen for Device Monitoring",
  "keywords": [
    "Industrial HMI",
    "Device Monitor",
    "Traceability",
    "Faults"
  ],
  "visual_specifications": {
    "expected_color": "The screen is predominantly purple with black and red text.",
    "critical_alignment_angles": "The layout is organized in a grid format, with rows labeled from X000 to X070 and columns representing different fault categories.",
    "surface_texture_purity": "The interface appears clean and well-organized."
  },
  "detailed_explanation": "This image shows an industrial HMI screen used for monitoring device faults. The screen is divided into rows labeled from X000 to X070, each representing a different fault category such as 'ST1 FAULT CONTENT', 'ST2 FAULTCONTENT', and 'MAINTENANCE'. Each row contains columns with labels like 'F', 'E', 'D', 'C', 'B', 'A', indicating various fault codes. The screen also displays the date, time, and traceability status at the top.",
  "common_defects_and_failures": [
    {
      "defect_type": "Fault Codes",
      "visual_signs": "The rows with black text indicate faults that have occurred or are currently active.",
      "criticality_level": "HIGH"
    },
    {
      "defect_type": "Traceability Status",
      "visual_signs": "The red 'NOT USED' label at the top indicates a traceability issue, which is critical for maintaining production continuity.",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/a728b71b.jpeg"
}
```


## Page 14

12 
 
5-4. Common Specifications Setup Screen 
 
Can refer to various set value of later description 5-8. Common Specifications Setup 
screen with this screen. But can't change set value in this screen. 
For shifting to the setting screen (Specifications Setup), a password is required, but no 
input of a password is required to this screen. 
For contents of each item, refer to Setup screen.



### Extracted Image Analysis

```json
{
  "error": "Expecting ',' delimiter: line 14 column 160 (char 1639)",
  "local_storage_path": "output/images/Teeth Surface Forming Machine/38ff3699.jpeg"
}
```


### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "1234567890abcdefg",
  "source_file_origin": "HMI Monitor Image",
  "page_or_sheet_location": "Monitor Page",
  "component_name": "HMI Monitor",
  "keywords": [
    "HMI",
    "Monitor",
    "Industrial Equipment"
  ],
  "visual_specifications": {
    "expected_color": "The screen is primarily black with blue and red highlights.",
    "critical_alignment_angles": "The layout is symmetrical, with the left side displaying 'ST2' and the right side displaying 'ST1'.",
    "surface_texture_purity": "The interface appears clean and well-organized."
  },
  "detailed_explanation": "This image shows a HMI (Human-Machine Interface) monitor screen from an industrial machine. The screen is divided into two main sections, each labeled with 'ST2' on the left and 'ST1' on the right. Both sections display various parameters such as current type, L/S position gap permits, angle measurements, vacuum filter check time, tonner number of times, and torque revision value. Each parameter has a corresponding numerical or textual value displayed in red boxes with labels like 'USE', 'NG SHOOT SELECT', and 'NONUSE'. The top section includes tabs for different languages such as Japanese (日语) and English (英語), indicating multilingual support. The bottom of the screen shows navigation options including 'PREVIOUS PAGE', 'NEXT PAGE', and 'MAINTENANCE' buttons.",
  "common_defects_and_failures": [
    {
      "defect_type": "Non-Use",
      "visual_signs": "Red boxes with labels like 'USE', 'NG SHOOT SELECT', and 'NONUSE'.",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/5a8833d4.jpeg"
}
```


### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "ST1_SPEC_MONITOR_13",
  "source_file_origin": "HMI Monitor Screen",
  "page_or_sheet_location": "Monitor Page 1/3",
  "component_name": "HMI Monitor Display",
  "keywords": [
    "traceability",
    "monitoring",
    "fault content"
  ],
  "visual_specifications": {
    "expected_color": "Black background with white and red text, blue and yellow buttons",
    "critical_alignment_angles": "Vertically aligned with a horizontal header",
    "surface_texture_purity": "Clean interface with clear text"
  },
  "detailed_explanation": "The image shows an industrial HMI (Human Machine Interface) screen displaying various monitoring parameters for a machine or system. The top section indicates the current date and time as '24/02/24' at '10:59:33'. Below this, there is a header with options such as 'Setup Type', 'Previous Page', 'Next Page', and 'Page Switching'. The main body of the screen lists several monitoring parameters including 'R/G Tooth Number', 'W/S Number of Thread', 'W/S Socket Insert Rota. Speed', among others. Each parameter has its own column, with some having values such as '0' or 'Orev'. There are also sections for torque measurements and other operational metrics like 'Forming Rotation Speed (L)', 'Change Speed Rotation Number', etc. The bottom section includes buttons labeled 'Manual ST1', 'ST2 Fault Content', and 'Maintenance'.",
  ", ": ", ",
  "local_storage_path": "output/images/Teeth Surface Forming Machine/a6b1aec3.jpeg"
}
```


### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "ST1_SPEC_MONITOR_23",
  "source_file_origin": "HMI Screen",
  "page_or_sheet_location": "Monitor Page 2/3",
  "component_name": "Torque Settings and Measurement",
  "keywords": [
    "Torque",
    "Settings",
    "Measurement"
  ],
  "visual_specifications": {
    "expected_color": "Black background with white text, blue highlighted sections for setup type and page switching buttons",
    "critical_alignment_angles": "The screen is divided into two main columns: one on the left showing torque settings (e.g., Left L/S Torque) and another on the right showing revision turn numbers.",
    "surface_texture_purity": "The interface appears clean with clear text, no visible scratches or smudges."
  },
  "detailed_explanation": "This image shows a HMI screen displaying the torque settings for an industrial machine. The left column lists various torque measurements and limits such as Left L/S Torque, Right L/S Torque, and Max Limit. The right column displays revision turn numbers (L) and (R). The top of the screen indicates it is page 2/3 of a monitor setup, with options to switch pages or go back to previous settings. The bottom bar shows different menu options like 'Main', 'Manual ST1', 'ST2 Fault Content', etc.",
  "common_defects_and_failures": [
    {
      "defect_type": "Scratches",
      "visual_signs": "None visible on the screen surface, but scratches might be present in other parts of the machine if not captured here.",
      "criticality_level": "LOW"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/1309055c.jpeg"
}
```


### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "ST1_SPEC_MONITOR_3_3",
  "source_file_origin": "Industrial Machine Interface Monitor",
  "page_or_sheet_location": "Monitor Page 3/3",
  "component_name": "HMI Screen for Monitoring and Setting Parameters",
  "keywords": [
    "HMI",
    "Monitoring",
    "Parameters",
    "Machine Interface"
  ],
  "visual_specifications": {
    "expected_color": "The screen is predominantly black with white text, some elements are highlighted in green or red.",
    "critical_alignment_angles": "The layout follows a standard HMI design with clear sections for different parameters and settings. The top section shows the current date and time, while the main body lists various monitoring and setting options.",
    "surface_texture_purity": "The screen appears to have a smooth surface texture without any visible scratches or damages."
  },
  "detailed_explanation": "This image is an HMI (Human-Machine Interface) screen displaying detailed parameters for machine operation. It shows the current date, time, and various settings such as power levels, speedup times, cycle times, forming numbers, cooling speeds, and more. The screen also includes options to switch between different pages of settings and a main menu button at the bottom.",
  "common_defects_and_failures": [
    {
      "defect_type": "No visible defects",
      "visual_signs": "The screen is clear with no signs of scratches, cracks, or any other damage. All elements are clearly visible.",
      "criticality_level": "LOW"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/93e81d9b.jpeg"
}
```


## Page 15

13 
 
5-5.Fault Description 
5-5-1. Fault Content 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) Displays the total number of abnormalities that are currently occurring. 
2) The fault contents that are currently occurring are displayed 
 
3) Displays the contents and details of the selected anomaly in the currently occurring 
anomaly. 
 
4) Touch this switch to move to the FAULT NUMBER screen. 
 
5) Touch this switch to move to the FAULT HISTORY screen. 
 
 
 
 
1
2
3
5
4



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "ST1_FAULT_CONTENT_240224_111414",
  "source_file_origin": "HMI screen displaying fault content",
  "page_or_sheet_location": "Fault Content page",
  "component_name": "Fault Content display",
  "keywords": [
    "fault",
    "content",
    "traceability",
    "manual"
  ],
  "visual_specifications": {
    "expected_color": "The background is black with white text, and the header has a red background.",
    "critical_alignment_angles": "The layout is horizontal with 'OCCURRENCES' on the left and 'FAULT CONTENT' in the middle.",
    "surface_texture_purity": "The interface appears to be clean and well-defined."
  },
  "detailed_explanation": "This image shows a fault content display from an industrial HMI screen. The header indicates it is for ST1 faults, with a timestamp of February 24, 2024, at 11:14:14. Below the header, there are two columns labeled 'OCCURRENCES' and 'FAULT CONTENT'. Currently, both columns are empty, indicating no occurrences or fault content has been recorded yet.",
  "common_defects_and_failures": [
    {
      "defect_type": "Blank display",
      "visual_signs": "Both columns are completely filled with white space without any text.",
      "criticality_level": "LOW"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/4d36c744.jpeg"
}
```


## Page 16

14 
 
5-5-2. Fault Detail 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) The abnormal contents that are currently occurring are displayed. 
2) Displays the contents and details of the selected anomaly in the currently occurring 
anomaly. 
3) The PLC internal relay number corresponding to the abnormality displayed in 2). 
 
 
 
1
2
3



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "G1234567890",
  "source_file_origin": "HMI screen from a manufacturing equipment",
  "page_or_sheet_location": "Fault detail page",
  "component_name": "PLC fault detection system",
  "keywords": [
    "fault",
    "PLC",
    "error"
  ],
  "visual_specifications": {
    "expected_color": "Red background with white text, black border",
    "critical_alignment_angles": "Vertically aligned from top to bottom",
    "surface_texture_purity": "Clean and clear interface"
  },
  "detailed_explanation": "The image shows a fault detail page on an HMI screen of a manufacturing equipment. The page indicates that there is an abnormal content related to a PLC fault, with probable causes listed as 'PLC error has been detected.' It also provides measures for addressing the issue by confirming the PLC program.",
  "common_defects_and_failures": [
    {
      "defect_type": "Fault",
      "visual_signs": "Red background and white text indicating an abnormal content related to a PLC fault, with probable causes listed as 'PLC error has been detected.'",
      "criticality_level": "HIGH"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/c7d51f07.jpeg"
}
```


## Page 17

15 
 
5-5-3. Fault Occurrence Counts 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
This screen displays the details of the error that occurred, the date and time, and the 
number of occurrences. 
 
1) Displays the details of the error that occurred, the date and time, and the number of 
occurrences. 
2) Cursor movement key 
3) It is a key to delete all the abnormality history. 
 
 
 
 
1
2
3



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "1234567890abcdefg",
  "source_file_origin": "HMI screen displaying fault occurrence counts",
  "page_or_sheet_location": "Fault History page",
  "component_name": "Fault History Display",
  "keywords": [
    "fault history",
    "PLC fault",
    "communication error"
  ],
  "visual_specifications": {
    "expected_color": "The background is black, with white text for clear visibility.",
    "critical_alignment_angles": "The data is aligned horizontally in a tabular format.",
    "surface_texture_purity": "The interface appears to be clean and well-maintained."
  },
  "detailed_explanation": "This image shows the fault history section of an industrial Human-Machine Interface (HMI) screen. It displays two entries for faults that occurred on October 22, 2011, at 14:21. The first entry indicates a single occurrence of a PLC fault. The second entry details a P2 Link No. 2 communication error with the CPU-L1 device. The interface includes navigation buttons for moving through the history and clearing faults.",
  "common_defects_and_failures": [
    {
      "defect_type": "Communication Error",
      "visual_signs": "Text indicating 'P2 LINK No. 2 COMMUNICATION ERROR'",
      "criticality_level": "MEDIUM"
    },
    {
      "defect_type": "PLC Fault",
      "visual_signs": "Text indicating 'PLC FAULT'",
      "criticality_level": "LOW"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/0ab2c7ed.jpeg"
}
```


## Page 18

16 
 
5-5-4. Fault History 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
This screen displays the details of the error that occurred and the date and time. 
 
1) Displays the details of the error that occurred and the date and time. 
2) Cursor movement key 
3) It is a key to delete all the abnormality history. 
4) Touch this switch to move to the FAULT DETAIL screen of the anomaly selected in 
1). 
 
 
 
 
 
1
2
3
4



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "1234567890abcdefg",
  "source_file_origin": "HMI fault history screen",
  "page_or_sheet_location": "Fault History page",
  "component_name": "Fault History Display",
  "keywords": [
    "fault history",
    "communication error",
    "PLC fault"
  ],
  "visual_specifications": {
    "expected_color": "The background is black, with text in white and red for important messages.",
    "critical_alignment_angles": "The text is aligned horizontally, with the header at the top and the list of faults below it.",
    "surface_texture_purity": "The interface appears to be clean and clear."
  },
  "detailed_explanation": "This image shows a fault history screen from an industrial HMI or machine interface. It displays a log of occurrences and their corresponding fault content, specifically mentioning 'P2 LINK No. 2 COMMUNICATION ERROR CPU-L1' and 'PLC FAULT'. The time stamps indicate the date and time when these faults occurred on October 11th at 15:20.",
  "common_defects_and_failures": [
    {
      "defect_type": "Communication Error",
      "visual_signs": "The text color is red, indicating an error message. The fault content includes 'P2 LINK No. 2 COMMUNICATION ERROR CPU-L1'.",
      "criticality_level": "HIGH"
    },
    {
      "defect_type": "PLC Fault",
      "visual_signs": "The text color is white for the fault content, indicating a normal message.",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/09dcd61e.jpeg"
}
```


## Page 19

17 
 
5-5-5. ST1 Fault Description screen comment list 
 
Comments on the Fault Description screen are allocated to internal relays M800 to 
M847 of PLC. When an internal relay turns ON, the comment corresponding to the 
internal relay is displayed. 
If multiple internal relays should turn ON, all of them are displayed. In such a case, 
comments are displayed in the order of the relays having turned ON. 
 
Abnormal contents comment table - 1 
Device 
Main comment 
Detailed comment 
M800 
W/S rotation servo amplifier (VAR-1) 
fault. 
Please turn the "Reset" button after 
confirms servo amplifier (VAR-1), and 
having removed a factor becoming abnorm. 
M801 
L/S rotation servo amplifier (VAR-3) 
fault. 
Please turn the "Reset" button after 
confirms servo amplifier (VAR-3), and 
having removed a factor becoming abnorm. 
M802 
L/S servo converter (CONV-1) fault. 
Please turn the "Reset" switch after 
confirms a converter (CONV-1), and having
removed an abnormal factor. 
M803 
Light curtain was blocked. 
Light curtain was blocked during machine  
actuating. Please turn the "RESET" switch. 
M804 
Air pressure fall. 
Please turn a "RESET" switch after  
confirms air pressure and a pressure 
sensor (SP-030), and having confirmed 
a cause. 
M805 
L/S torque alarm 
Please turn the "RESET" button after
confirm work condition and torque 
amplifier power and torque sensor switch.
M806 
Master start relay fault 
Master start relay is abnormal.
Please turn a “RESET” switch after 
confirms cause.
M807 
Power supply relay fault 
Power supply relay is abnormal.
Please turn a “RESET” switch after  
confirms cause. 
M808 
Master start condition fault 
Master start condition relay is abnormal.  
Please turn a “RESET” switch after  
confirms cause. 
M809
 
M810 
W/S socket insertion confirm sensor 
fault. 
Though a unit retrogresses, a confirmation 
sensor (LS-047) does ON. Please turn the 
"RESET" switch after having confirmed a 
cause. 
M811
 
M812 
Lack of Tonner 
A toner lacks. When toners decrease, please 
supply it. When toners do not decrease, 
please confirm a sensor (FLS-031). 
M813 
Auto run cycle time over. 
Automatic driving was not finished.
Please check the mechanical problems.



## Page 20

18 
 
Abnormal contents comment table - 2 
Device 
Main comment 
Detailed comment 
M814 
UNIT-10 CH1 communication time over 
Confirm connection of connector of 
CH1 (UNIT-10) 
M815 
ST1 2D code reader 
data error
1) Check noise. 
2) Check setting of 2D code reader.
M816 
ST1 Traceability server 
 time-out 
1) Confirm traceability server. 
2) Confirm LAN cables and switching hubs. 
M817 
UNIT-10 CH2 communication time over 
Confirm connection of connector of 
CH2 (UNIT-10) 
M818 
QJ71C24N-R2 UNIT-10 Fault 
QJ71C24N-R2 Abnormal signal turned ON 
from U-10 
M819 
 
 
M820 
Work Clamp forward and back time-out. 
Work Clamp is taking too long to move  
forward or back. Please check if there are 
any mechanical problems such as damages 
or stuck on air piping. Check if there are 
any malfunction or position gap on detect 
sensors (LS-043,LS-044). 
M821 
W/S Socket Insert forward and back 
time-out. 
W/S Socket Insert is taking too long to 
move forward or back. Please check if there 
are any mechanical problems such as 
damages or stuck on air piping. Check if 
there are any malfunction or position gap 
on detect sensors (LS-045,LS-046). 
M822 
W/S Rotation return to home position 
time-out. 
Return the home position was not 
completed. Please turn the "RESET" switch 
after confirm servo amplifier (VAR-1) and 
the case. 
 M823 
W/S Rotation positioning time-out. 
W/S rotation positioning was not completed. 
Please turn the "RESET" switch after 
confirm servo amplifier (VAR-1) and the 
case. 
M824 
L/S position gap fault. 
Please turn the "RESET" switch after 
confirm specification setup value and work 
condition. 
M825
M826 
W/S Socket insert miss. 
W/S socket insertion was not completed. 
Please turn the "RESET" switch after 
confirm machine and work. 
M827 
L/S insert miss 
L/S socket insertion was not completed. 
Please turn the "RESET" switch after 
confirm machine and work. 
M828 
Work Clamp down and up time-out. 
Work Clamp is taking too long to move 
down or up. Please check if there are any 
mechanical problems such as damages or 
stuck on air piping. Check if there are any 
malfunction or position gap on detect 
sensors (LS-042).



## Page 21

19 
 
Abnormal contents comment table - 3 
Device 
Main comment 
Detailed comment 
M829 
Unit Change right and left time-out. 
Unit Change is taking too long to move 
right or left. Please check if there are any 
mechanical problems such as damages or 
stuck on air piping. Check if there are any 
malfunction or position gap on detect 
sensors (LS-049). 
M830 
 
 
M831 
 
 
M832 
 
 
M833 
 
 
M834 
 
 
M835 
 
 
M836 
 
 
M837 
 
 
M838 
 
 
M839 
 
 
M840 
 
 
M841 
 
 
M842 
 
 
M843 
 
 
M844 
 
 
M845 
 
 
M846 
 
 
M847 
PLC BATTERY FAULT
Please replace the PLC battery.



## Page 22

20 
 
5-5-6. ST2 Fault Description screen comment list 
 
Comments on the Fault Description screen are allocated to internal relays M1800 
to M1847 of PLC. When an internal relay turns ON, the comment corresponding to 
the internal relay is displayed. 
If multiple internal relays should turn ON, all of them are displayed. In such a case, 
comments are displayed in the order of the relays having turned ON. 
 
Abnormal contents comment table - 1 
Device 
Main comment 
Detailed comment 
M1800 
W/S rotation servo amplifier (VAR-3) 
fault. 
Please turn the "Reset" button after 
confirms servo amplifier (VAR-3), and 
having removed a factor becoming abnorm. 
M1801 
L/S rotation servo amplifier (VAR-4) 
fault. 
Please turn the "Reset" button after 
confirms servo amplifier (VAR-4), and 
having removed a factor becoming abnorm. 
M1802 
L/S servo converter (CONV-2) fault. 
Please turn the "Reset" switch after 
confirms a converter (CONV-2), and having
removed an abnormal factor. 
M1803 
Light curtain was blocked. 
Light curtain was blocked during machine 
actuating. Please turn the "RESET" switch. 
M1804 
Air pressure fall. 
Please turn a "RESET" switch after 
confirms air pressure and a pressure 
sensor (SP-025), and having confirmed a 
cause. 
M1805 
L/S torque alarm 
Please turn the "RESET" button 
after confirm work condition and torque 
amplifier power and torque sensor switch. 
M1806 
Master start relay fault 
Master start relay is abnormal. Please turn 
a “RESET” switch after confirms cause. 
M1807 
Power supply relay fault 
Power supply relay is abnormal. Please 
turn a “RESET” switch after confirms 
cause. 
M1808 
Master start condition fault 
Master start condition relay is abnormal. 
Please turn a “RESET” switch after 
confirms cause. 
M1809 
W/S Unit positioning motor overload 
Thermal relay (FA-2) in control box 
tripped. Remove root cause and reset 
thermal relay and Reset button pushed. 
M1810 
W/S socket insertion confirm sensor fault.
Though a unit retrogresses,  
a confirmation sensor (LS-057) does ON. 
Please turn the "RESET" switch after 
having confirmed a cause. 
M1811 
 
 
M1812 
Lack of Tonner 
A toner lacks. When toners decrease, please 
supply it. When toners do not decrease, 
please confirm a sensor (FLS-031). 
M1813 
Auto run cycle time over. 
Automatic driving was not finished. 
Please check the mechanical problems.



## Page 23

21 
 
Abnormal contents comment table - 2 
Device 
Main comment 
Detailed comment 
M1814 
UNIT-11 CH1 communication time over 
Confirm connection of connector of CH1 
(UNIT-11) 
M1815 
ST2 2D code reader 
data error
1) Check noise. 
2) Check setting of 2D code reader.
M1816 
ST2 Traceability server 
 time-out 
1) Confirm traceability server. 
2) Confirm LAN cables and switching hubs. 
M1817 
UNIT-11 CH2 communication time over 
Confirm connection of connector of 
CH2 (UNIT-11) 
M1818 
QJ71C24N-R2 UNIT-11 Fault 
QJ71C24N-R2 Abnormal signal turned ON 
from U-11 
M1819 
 
 
M1820 
Work Clamp forward and back time-out. 
Work Clamp is taking too long to move 
forward or back. Please check if there are 
any mechanical problems such as damages 
or stuck on air piping. Check if there are 
any malfunction or position gap on detect 
sensors (LS-053,LS-054). 
M1821 
W/S Socket Insert forward and back 
time-out. 
W/S Socket Insert is taking too long to 
move forward or back. Please check if there 
are any mechanical problems such as 
damages or stuck on air piping. Check if 
there are any malfunction or position gap 
on detect sensors (LS-055,LS-056). 
M1822 
W/S Rotation return to home position 
time-out. 
Return the home position was not 
completed. Please turn the "RESET" switch 
after confirm servo amplifier (VAR-3 )and 
the case. 
M1823 
W/S Rotation positionig time-out. 
W/S rotation positioning was not completed. 
Please turn the "RESET" switch after 
confirm servo amplifier (VAR-3) and the 
case. 
M1824 
L/S position gap fault. 
Please turn the "RESET" switch after  
confirm specification setup value and work 
condition. 
M1825 
 
 
M1826 
W/S socket insert miss. 
W/S socket insertion was not completed. 
Please turn the "RESET" switch 
after confirm machine and work. 
M1827 
L/S socket insert miss. 
L/S socket insertion was not completed. 
Please turn the "RESET" switch 
after confirm machine and work. 
M1828 
Work Clamp down and up time-out. 
Work Clamp is taking too long to move  
down or up. Please check if there are any 
mechanical problems such as damages or 
stuck on air piping. Check if there are any 
malfunction or position gap on detect 
sensors (LS-052).



## Page 24

22 
 
Abnormal contents comment table - 3 
Device 
Main comment 
Detailed comment 
M1829 
Unit Change right and left time-out. 
Unit Change is taking too long to move 
right or left. Please check if there are any 
mechanical problems such as damages or 
stuck on air piping. Check if there are any 
malfunction or position gap on detect 
sensors (LS-059). 
M1830 
 
 
M1831 
 
 
M1832 
 
 
M1833 
 
 
M1834 
 
 
M1835 
 
 
M1836 
 
 
M1837 
 
 
M1838 
 
 
M1839 
 
 
M1840 
 
 
M1841 
 
 
M1842 
 
 
M1843 
 
 
M1844 
 
 
M1845
M1846 
 
 
M1847



## Page 25

23 
 
5-6. Specifications Setting Menu 
 
The password is necessary to shift to this standard setting menu screen. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) Common Specifications Set up  
Changing to Later description 5-7 common specifications setting window 
2) Specifications Setup Screen 1/3 
Changing to Later description 5-8 specifications set up screen 1/3 
3) Specifications Setup Screen 2/3 
Changing to Later description 5-9 specifications set up screen 2/3 
4) Specifications Setup Screen 3/3 
Changing to Later description 5-10 specifications set up screen 3/3 
5) Copy of Specifications 
Changing to later description 5-11 copy screen 
 
 
 
 
1
2
3
4
4



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "1234567890abcdefg",
  "source_file_origin": "HMI Screen Image",
  "page_or_sheet_location": "SPECIFICATION SETUP MENU",
  "component_name": "HMI Screen",
  "keywords": [
    "HMI",
    "Setup Menu",
    "Specifications"
  ],
  "visual_specifications": {
    "expected_color": "The background is black, and the text and buttons are in bright colors like yellow, red, blue, and white.",
    "critical_alignment_angles": "The layout is symmetrical with two rows of four buttons each. The top row has 'ST2 SPECIFICATIONS SETUP 1/2', 'ST2 SPECIFICATIONS SETUP 2/2', 'ST2 COPY OF SPECIFICATIONS' on the left side and 'ST1 SPECIFICATIONS SETUP 1/2', 'ST1 SPECIFICATIONS SETUP 2/2', 'ST1 COPY OF SPECIFICATIONS' on the right side.",
    "surface_texture_purity": "The buttons have a glossy finish, reflecting light."
  },
  "detailed_explanation": "This image shows an HMI screen with a menu titled 'SPECIFICATION SETUP'. The screen is divided into two rows of four buttons each. Each row contains options for setting up specifications for different systems (ST1 and ST2). The top left button reads 'TRACABILITY NOT USED', indicating that traceability functionality is not enabled in this setup. The bottom right corner has a label 'MAINTENANCE' suggesting it might be used to access maintenance-related functions.",
  "common_defects_and_failures": [
    {
      "defect_type": "Button Glitch",
      "visual_signs": "The buttons may appear slightly misaligned or have a glitch effect, making them look like they are not fully clickable.",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/155e3ab8.jpeg"
}
```


## Page 26

24 
 
 
5-7. Common Specifications Setup Screen 
 
With this screen, set setting items memorizing in PLC. 
Each setting is registered with every work type. 
Attention) Change of a setting value cannot be performed during automatic operation. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) Expression column of various set points 
 
1)-1. L/S posi.gap permis angle 
Set a permission angle of a position as of a thing of W/S and L/S. 
 
1)-2. L/S servo oil supply time 
Set the oil supply time of a load shaft servomotor. 
Start *100 times input values auto driving. 
It is the oil supply time and gets impossible to start. 
 
1)-3. Vacuum filter check time 
Set the time checking an air blow filter. 
Start *100 times input values auto driving. 
It is the filter check time and gets impossible to start. 
 
1)-4. Lack of tonner number of times 
Apply this setting times after a quantity of oil confirmation sensor did OFF. 
Become lack of toner abnormality, and get impossible to start auto driving. 
 
1)-5. W/S torque revision value 
Set revision value of W/S torque. 
 
2) Marker check Use/No use switch 
 
3) NG shoot Use/No use switch 
 
4) Traceability Use/No use switch 
 
 
            
 
 
1
2
3
4



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "1234567890abcdefg",
  "source_file_origin": "image captured from a machine interface display",
  "page_or_sheet_location": "Common Spec Setup page",
  "component_name": "HMI screen displaying common setup parameters for two stations (ST1 and ST2)",
  "keywords": [
    "HMI",
    "common spec setup",
    "traceability"
  ],
  "visual_specifications": {
    "expected_color": "The background is black, with text in white and some elements highlighted in red, blue, green, and yellow.",
    "critical_alignment_angles": "The layout is symmetrical around the center of the screen. The left side contains parameters for ST1, while the right side contains parameters for ST2.",
    "surface_texture_purity": "The interface appears to be clean with no visible scratches or dirt."
  },
  "detailed_explanation": "This image shows a HMI (Human-Machine Interface) screen from an industrial machine setup page. It displays two stations, labeled as ST1 and ST2, each with their respective parameters for traceability, current type, angle settings, vacuum filter check time, toner number of times, and torque revision value. The left side is dedicated to ST1's parameters, while the right side is for ST2. Each parameter has a corresponding label in Japanese (ST1) or English (ST2), with some elements highlighted in red, blue, green, and yellow for emphasis.",
  "common_defects_and_failures": [
    {
      "defect_type": "No visible defects",
      "visual_signs": "Clean screen without any scratches or dirt. All text is clearly legible.",
      "criticality_level": "LOW"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/5efb8c19.jpeg"
}
```


## Page 27

25 
 
5-8. Specifications setup screen 1/3 
 
With this screen, set setting items memorizing in PLC. 
Each setting is registered with every work type. 
As for the setting of ST2, content becomes similar. 
Attention) Change of a setting value cannot be performed during automatic operation. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) The work type number and the name selected for monitor 
currently is displayed. 
 
2) Expression column of various set points 
 
2)-1. R/G tooth number 
Set the number of the teeth of a reduction gear. 
Decide rotation speed of a W/S shaft. Please set it with care. 
 
2)-2. W/S number of start 
Set the number of the screws of a W/S shaft. 
Decide rotation speed of a W/S shaft. Please set it with care. 
 
2)-3. W/S socket insert rota. speed 
Set rotation speed at the time of the W/S serration socket insertion. 
 
2)-4. Forming rotation speed (L) 
Set rotation speed of the left forming. This speed becomes the speed that R/G 
turns. 
2)-5. Forming rotation speed (R) 
Set rotation speed of the right forming. This speed becomes the speed that R/G 
turns. 
 
2)-6. Forming rotation number (L) 
Set the number of the rotations of the left forming. This speed becomes the 
number of the rotations of R/G. 
 
2)-7. Forming rotation number (R) 
Set the number of the rotations of the right forming. This speed becomes the 
number of the rotations of R/G. 
 
2)-8. Speedup & slowdown time (L) 
Set rotation picking up speed and slowing down time of a W/S shaft. 
 
 
 
1
2



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "ST1_SPEC_SETUP_13",
  "source_file_origin": "traceability_not_used",
  "page_or_sheet_location": "SPECIFICATION SETUP PAGE 1/3",
  "component_name": "HMI Screen for Machine Setup",
  "keywords": [
    "HMI",
    "Machine Interface",
    "Setup Page"
  ],
  "visual_specifications": {
    "expected_color": "The screen is black with white text and some red highlights.",
    "critical_alignment_angles": "The layout is horizontal, with the top section containing tabs like 'HOME', 'PREVIOUS PAGE', etc., and the main content area below displaying various setup parameters.",
    "surface_texture_purity": "The surface texture appears to be smooth with no visible scratches or marks."
  },
  "detailed_explanation": "This image shows a HMI (Human-Machine Interface) screen from an industrial machine, specifically page 1/3 of the 'SPECIFICATION SETUP'. The screen displays various setup parameters such as R/G tooth number, W/S number of thread, and forming rotation speed. There are tabs for different pages like 'PREVIOUS PAGE', 'NEXT PAGE', and 'PAGE SWITCHING' at the top. The bottom section has buttons labeled 'MAIN', 'MANUAL ST1', 'ST2 FAULT CONTENT', and 'MAINTENANCE'. The screen also shows traceability information, with a date and time stamp in the top right corner.",
  "common_defects_and_failures": [
    {
      "defect_type": "Text Overlap",
      "visual_signs": "Some text overlaps slightly on adjacent tabs or parameters.",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/0425a219.jpeg"
}
```


## Page 28

26 
 
2)-9. Speedup & slowdown time (R) 
Set rotation picking up speed and slowing down time of a W/S shaft. 
 
2)-10. Torque meas. start time(L) 
Set start time to judge the left forming torque to be it. This setting passes in 
picking up speed and slowing down time after W/S began to turn around and 
empties. 
 
2)-11. Torque meas. start time(R) 
Set start time to judge the right forming torque to be it. This setting passes in 
picking up speed and slowing down time after W/S began to turn around and 
empties. 
 
2)-12. W/S Revision turn number(L) 
Set a torque revision rotation number during the left forming. Revise torque 
every this setting. 
 
2)-13. W/S Revision turn number(R) 
Set a torque revision rotation number during the right forming. Revise torque 
every this setting. 
 
2)-14. Change speed rotation number 
Set the number of the turns to play by speed changing during forming. This 
setting becomes the number of the turns of L/S 
 
2)-15. Change speed during Forming 
Set speed to make speed changing during forming. This setting becomes turn 
speed of L/S. 
 
2)-16. Left L/S load torque(0V) 
Set 0V torque at the time of the left rotation. it every automatic driving auto 
measure, and change setting. 
 
2)-17. Right L/S load torque(0V) 
Set 0V torque at the time of the right rotation. it every automatic driving auto 
measure, and change setting.



## Page 29

27 
 
5-9. Specifications setup screen 2/3 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) The work type number and the name selected for monitor currently is displayed. 
2) Expression column of various set points 
2)-1. Left L/S torque 
    Set target torque value at the time of the left forming. 
2)-2. Right L/S torque 
    Set target torque value at the time of the right forming. 
2)-3. L/S load torque max limit 
    Set the upper limit of load torque. 
    Become abnormal when beyond this set point. 
2)-4. Left L/S torque upper limit 
    Set the load torque upper limit during the left forming. 
    When load torque is beyond this set point after torque judgment start time,  
    become load torque NG. 
2)-5. Left L/S torque lower limit 
Set the load torque lower limit during the left forming. When load torque is less 
than this set point after torque judgment start time, become load torque NG. 
 
2)-6. Right L/S torque upper limit 
Set the load torque upper limit during the right forming. When load torque is 
beyond this set point after torque judgment start time, become load torque NG. 
 
2)-7. Right L/S torque lower limit 
Set the load torque lower limit during the right forming. When load torque is 
less than this set point after torque judgment start time, become load torque 
NG. 
 
2)-8. Left L/S average torque upper limit 
Set the load average torque upper limit during the left forming. When load 
torque is beyond this set point after torque judgment start time, become load 
torque NG. 
 
 
 
1
2



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "ST1_SPEC_SETUP_23",
  "source_file_origin": "HMI Screen Capture",
  "page_or_sheet_location": "Setup Page 2/3",
  "component_name": "Torque Setup",
  "keywords": [
    "Torque",
    "Setup",
    "Machine Interface"
  ],
  "visual_specifications": {
    "expected_color": "The screen is predominantly black with white text and some colored elements like blue, yellow, and red.",
    "critical_alignment_angles": "The layout is organized in a tabular format for torque settings on the left side and revision numbers on the right. The top of the screen has tabs for different pages and switching options.",
    "surface_texture_purity": "The interface appears clean with clear text and well-defined sections."
  },
  "detailed_explanation": "This image shows a setup page from an industrial HMI (Human-Machine Interface) system, specifically for setting up torque parameters. The screen is divided into two main sections: one on the left displaying various torque settings such as 'Left L/S Torque', 'Right L/S Torque', and their respective limits, all in Newton-meters (N·m). The right side shows revision numbers with timestamps. At the bottom, there are tabs for different pages like 'Main', 'Manual ST2', 'ST1 Fault Content', and 'Maintenance'. The top of the screen has navigation options including 'Previous Page', 'Next Page', and 'Page Switching' in yellow.",
  "common_defects_and_failures": [
    {
      "defect_type": "No visible defects",
      "visual_signs": "None",
      "criticality_level": "LOW"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/05634b10.jpeg"
}
```


## Page 30

28 
 
2)-9. Left L/S average torque lower limit 
Set the load average torque lower limit during the left forming. When load 
torque is less than this set point after torque judgment start time, become load 
torque NG. 
 
2)-10. Right L/S average torque upper limit 
Set the load average torque upper limit during the right forming. When load 
torque is beyond this set point after torque judgment start time, become load 
torque NG. 
 
2)-11. Right L/S average torque lower limit 
Set the load average torque lower limit during the right forming. When load 
torque is less than this set point after torque judgment start time, become load 
torque NG. 
 
2)-12. W/S torque lower limit 
Set the input shaft torque lower limit during forming. When input shaft torque 
is less than this setting after torque judgment start time, become input shaft 
torque NG. 
 
2)-13. W/S torque upper limit 
Set the input shaft torque upper limit during forming. When input shaft torque 
is beyond this setting after torque judgment start time, become input shaft 
torque NG. 
 
2)-14. L/S climate cycle interval 
Set distance to perform genial climate driving of L/S rotation sorvo. When does 
not start auto driving in current setting time, get impossible to machine a work 
unless starts genial climate driving. 
 
2)-15. L/S climate cycle time 
Set rotation time at the time of genial climate driving.



## Page 31

29 
 
5-10. Specifications setup screen 3/3 
With this screen, set setting items memorizing in PLC. 
Each setting is registered with every work type. 
As for the setting of ST2, content becomes similar. 
Attention) Change of a setting value cannot be performed during automatic operation. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) The work type number and the name selected for monitor 
currently is displayed. 
 
2) Expression column of various set points 
 
2)-1. L/S breaks power 
Set power to brake so that L/S does not do attendants at the time of the W/S 
socket insertion. 
 
2)-2. W/S speedup time assist power 
Set power to assist for at the time of W/S rotation acceleration so that load 
torque does not become high. 
 
2)-3. 0V torque meas. delay time 
Measure 0V torque after W/S rotation acceleration completion, but set the 
measurement start delay line. 
 
2)-4. Cycle time over time 
Set a cycle time over of auto driving. If cycle time becomes longer than this 
setting, become abnormal. 
 
2)-5. Forming number 
Set forming coming and going times. Be one coming and going by right and left 
forming rotation completion. 
 
2)-6. Cooling number after forming 
Set a cooling rotation number after forming. This sets the number of the 
rotations of L/S. 
 
2)-7. Cooling rotation speed 
Set cooling rotation speed after forming. This becomes the speed that L/S turns. 
 
 
 
 
1
2
3
5
4
6
7



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "ST1_SPEC_SETUP_3_3",
  "source_file_origin": "Industrial Machine Interface",
  "page_or_sheet_location": "Setup Page 3/3",
  "component_name": "HMI Screen for Spec Setup",
  "keywords": [
    "HMI",
    "Machine Interface",
    "Spec Setup"
  ],
  "visual_specifications": {
    "expected_color": "The screen has a black background with white text and some elements in green, red, and yellow.",
    "critical_alignment_angles": "The layout is organized into sections for different parameters such as 'Setup Type', 'L/S Breaks Power', 'W/S Speedup Time Assist Power', etc., with labels like 'Previous Page', 'Next Page', and 'Page Switching' at the top.",
    "surface_texture_purity": "The interface appears clean, with clear text and well-defined sections."
  },
  "detailed_explanation": "This image shows a section of an HMI screen used for specifying setup parameters in industrial machinery. It displays various settings such as 'Setup Type', 'L/S Breaks Power', 'W/S Speedup Time Assist Power', etc., with corresponding values and labels like 'Previous Page', 'Next Page', and 'Page Switching'. The layout is organized into sections, each containing different parameters and their respective values.",
  "common_defects_and_failures": [
    {
      "defect_type": "Display Issues",
      "visual_signs": "The screen may have issues with readability or display artifacts if the text is too small or if there are any graphical errors.",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/c730a9ed.jpeg"
}
```


## Page 32

30 
 
2)-8. 1st Forming oil appli. number (L) 
Set the number of the turns to apply a tonner in the left forming first half. 
 
2)-9. 2nd Forming oil appli. number (L) 
Set the number of the turns to apply a toner in the left familiarity latter half. 
 
2)-10. 1st Forming oil appli. number (R) 
Set the number of the turns to apply a tonner in the right forming first half. 
 
2)-11. 2nd Forming oil appli. number (R) 
Set the number of the turns to apply a toner in the Right familiarity latter half. 
 
2)-12. W/S socket kind 
Set a kind of a W/S socket with a number. Memorize W/S use times every set 
kind here. 
 
2)-13. L/S serration kind 
Set a kind of L/S Serration. Memorize use times of L/S Serration every set kind 
here. 
 
2)-14. W/S socket change timing 
Set the exchange time of a W/S socket. It is the exchange time when starts this 
*100 times setting auto driving. 
 
2)-15. L/S serration change timing 
Set the exchange time of a L/S serration. It is the exchange time when starts 
this *100 times setting auto driving. 
 
3) The selection that is given priority to right and left at forming start time 
Set forming rotatory direction. 
 
4) L/S position gap detection selection 
Perform gap detection of a position with a W/S shaft and a L/S shaft when chooses 
ON. Do not detect a position gap when turns it off. 
 
5) L/S load torque rotatory direction selection 
Choose rotatory direction of load torque. Assist when changes rotatory direction. 
 
6) W/S position selection 
Seeing from the system front, set a position of W/S. 
 
7) During Forming Vaccum selection



## Page 33

31 
 
 
5-11. Copy of Specifications 
 
Changing to this screen is possible only from 5-8.Specifications Setup Screen. 
With this screen, copying settings of arbitrary work type into another arbitrary work type 
is possible. But the name of the work type is not copied. 
For adding a new work type, it is efficient to change only diversity entries with 
5-8.Specifications Setup Screen after having used this function. If it is a masterwork, it is 
efficient all the more. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) “COPY SOURCE SELECT” 
The type name of selected source of copy is displayed. 
 
2) “DESTINATION OF COPY” 
The type name of selected destination of copy is displayed. 
 
3) Conduct a copy. 
Copy is conducted by selecting the source of copy and destination of copy, then press 
“COPY” button for 2 seconds. 
Be careful not to accidentally copy to a different type number. 
 
  
 
1
3
2



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "ST1_SPECIFICATIONS_COPY_240224_131809",
  "source_file_origin": "SOURCE_IMAGE_FILE_PATH",
  "page_or_sheet_location": "SPECIFICATIONS COPY PAGE",
  "component_name": "HMI Screen for Copy Functionality",
  "keywords": [
    "HMI",
    "Copy Function",
    "Fault Content"
  ],
  "visual_specifications": {
    "expected_color": "The screen is black with yellow and white text.",
    "critical_alignment_angles": "The layout is horizontal, with the top section containing status information and the bottom section displaying instructions for copying content.",
    "surface_texture_purity": "The interface appears to be clean and clear."
  },
  "detailed_explanation": "This image shows a HMI screen used in an industrial setting. It displays the current state of a copy function, indicating that no source or destination has been selected yet. The screen prompts the user to push 'COPY' after two seconds if they have already chosen both the source and destination for copying content. The top section includes status information such as 'Shasability Not Used', 'Home Position Black Out', and 'Total Fault'. The bottom section contains buttons labeled 'ST1 Fault Content' and 'ST2 Fault Content', suggesting that this screen is part of a larger system with different fault handling mechanisms.",
  "common_defects_and_failures": [
    {
      "defect_type": "Fault in Copy Function",
      "visual_signs": "The screen displays the message '<PUSH 2 SECONDS TO COPY>', indicating that the user needs to interact with the interface within two seconds after selecting a source and destination.",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/68cf95e5.jpeg"
}
```


## Page 34

32 
 
5-12. Counter screen 
 
Display various counters with this screen. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) Total Counter 
Display times to Total of operations completion. 
 
2) OK Counter 
Display times to OK of operations completion. 
 
3) NG Counter 
Display times to NG of operations completion. 
 
4) W/S Socket Counter 
Display use times of a W/S socket. 
 
5) Serration Counter 
Display use times of a Serration. 
 
6) Toner application Counter 
OFF is condition that did, and quantity of toner confirmation sensor(FLS220) 
displays the times that applied. 
 
7) Vacuum Filter Counter 
Display use times of a Vacuum. 
8) Counter Reset PB 
After selecting the number to reset, press the reset button for 2 seconds to reset it to 
0. 
 
  
 
1
3
2
4
5
6
7
8



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "1234567890abcdefg",
  "source_file_origin": "HMI Display Image",
  "page_or_sheet_location": "Counter Display Page",
  "component_name": "Counter Display Screen",
  "keywords": [
    "Counter",
    "Display",
    "Machine Interface"
  ],
  "visual_specifications": {
    "expected_color": "The screen is divided into two sections with a yellow header, black background for text and blue headers for the counter names.",
    "critical_alignment_angles": "The layout is symmetrical with each section containing four rows of counters. The top row has labels like 'Total Counter', 'OK Counter', etc., while the bottom row contains specific counter types.",
    "surface_texture_purity": "The screen appears to have a smooth surface, typical for industrial HMI displays."
  },
  "detailed_explanation": "This image shows an industrial Human-Machine Interface (HMI) display page titled 'Counter Display'. It is divided into two sections: ST2 and ST1. Each section contains four rows of counters with labels such as 'Total Counter', 'OK Counter', etc., followed by specific counter types like 'W/S Socket Counter' or 'P/S Serration Counter'. The top row has a yellow header, while the bottom row is blue, indicating different sections or statuses.",
  "common_defects_and_failures": [
    {
      "defect_type": "Display Brightness",
      "visual_signs": "The display appears to be too bright, making it difficult to read details clearly.",
      "criticality_level": "MEDIUM"
    },
    {
      "defect_type": "Text Overlap",
      "visual_signs": "Some counter labels overlap with each other, making them hard to distinguish.",
      "criticality_level": "LOW"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/e5c24e67.jpeg"
}
```


## Page 35

33 
 
5-13. Type Name Registration 
 
Register a name of each work type (0 to 99) with this screen. 
Arbitrary characters in a keypad window are used to register a name of each work type. 
(Maximum 16 characters) 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) Each work type name indication column 
Touch the each work type name indication column, and below registered names and 
a cursor are displayed. 
 
 
1



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "1234567890abcdefg",
  "source_file_origin": "HMI screen from a manufacturing equipment",
  "page_or_sheet_location": "Main page of the HMI screen",
  "component_name": "HMI screen displaying registration and fault information",
  "keywords": [
    "HMI",
    "registration",
    "faults"
  ],
  "visual_specifications": {
    "expected_color": "The background is black, with white text for clarity.",
    "critical_alignment_angles": "The layout is organized in a grid format with rows and columns.",
    "surface_texture_purity": "The screen appears to have a smooth surface without visible scratches or damages."
  },
  "detailed_explanation": "This image shows the main page of an HMI (Human Machine Interface) screen, specifically designed for industrial use. The screen is divided into two sections: one on the left displaying registration information and another on the right showing fault details. Each section contains rows with numbers ranging from 001 to 019, indicating different types or statuses. The top of the screen has a header that includes various labels such as 'Type Name', 'Registration 1', 'Traceability Not Used', and other technical terms relevant to industrial equipment monitoring.",
  "common_defects_and_failures": [
    {
      "defect_type": "Scratches",
      "visual_signs": "Visible scratches on the screen surface, affecting readability.",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/c9837a50.jpeg"
}
```


### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "keyboard_1234567890_QWERTYUIOP_CAPS_LSHIFT_CTRL_DEL_BS_MS_MR_Space_Cancel_Enter_left_right_arrow",
  "source_file_origin": "image_source",
  "page_or_sheet_location": "HMI screen or machine interface display",
  "component_name": "Keyboard",
  "keywords": [
    "Industrial HMI",
    "Machine Interface",
    "Keyboard"
  ],
  "visual_specifications": {
    "expected_color": "White keys with black lettering on a grey background.",
    "critical_alignment_angles": "The keyboard is laid out in a standard QWERTY layout, with the top row labeled from left to right as '1', '2', '3', etc., and the second row starting with 'Q' followed by 'W', 'E', etc. The third row starts with 'A', 'S', 'D', etc.",
    "surface_texture_purity": "The keys appear smooth and clean, without any visible scratches or dirt."
  },
  "detailed_explanation": "This image shows a standard QWERTY keyboard layout displayed on an industrial HMI screen. The keys are clearly labeled with numbers from 1 to 9, letters of the alphabet (Q through Z), function keys like 'CAPS', 'LSHIFT', and 'CTRL', as well as special characters such as '$' and symbols like '*', '-', and '/'. The layout is typical for industrial applications where ease of use and clarity are paramount.",
  "common_defects_and_failures": [
    {
      "defect_type": "Scratches",
      "visual_signs": "Visible scratches on the surface of some keys, possibly indicating wear or damage over time.",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/99dd3a65.jpeg"
}
```


## Page 36

34 
 
5-14. Load Torque Calibration Screen 
 
Display a measurement result of load torque with this screen. 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) W/S Rotation order Torque 
I set torque value to operate a W/S rotation at a percentage. 
 
2) W/S Torque 
It display torque value depending on a servomotor 
 
3) W/S Rotation Manual Operation Selection Switch 
Can choose a selection select switch at the time of manual operation for a cycle. Can 
work with a "manual operation" illuminated push button switch  and a "Manual 
Operation Home Position side" illuminated push button switch after selection with 
this switch. 
 
4) L/S Rotation order Torque 
I set torque value to operate a L/S rotation at a percentage. 
 
5) L/S Torque 
It display torque value depending on a torque meter. 
 
6) L/S Rotation Manual Operation Selection Switch 
Can choose a selection select switch at the time of manual operation for a cycle. Can 
work with a "manual operation" illuminated push button switch  and a "Manual 
Operation Home Position side" illuminated push button switch after selection with 
this switch. 
 
 
 
 
 
1
2
3
4
5
6



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "ST1 Calibration Screen",
  "source_file_origin": "Industrial Machine Interface",
  "page_or_sheet_location": "Calibration Page",
  "component_name": "HMI Screen Displaying Calibration Parameters",
  "keywords": [
    "calibration",
    "order torque",
    "w/s rotation",
    "cw",
    "ccw"
  ],
  "visual_specifications": {
    "expected_color": "The screen has a black background with colored text and buttons, primarily in blue, yellow, and green.",
    "critical_alignment_angles": "The layout is organized vertically with sections for 'W/S Rotation' and 'L/S Rotation', each containing two options: CW (clockwise) and CCW (counterclockwise).",
    "surface_texture_purity": "The interface appears clean and well-defined, ensuring easy readability of the text and buttons."
  },
  "detailed_explanation": "This image shows a calibration screen from an industrial machine or equipment. It displays two sets of parameters: 'Order Torque' and 'W/S Torque', both set to zero percent and no torque respectively. The screen is divided into sections for clockwise (CW) and counterclockwise (CCW) rotation, with options highlighted in yellow and green. The top right corner shows the date and time as 24/02/24 at 13:26:13.",
  "common_defects_and_failures": [
    {
      "defect_type": "Wrong Calibration Values",
      "visual_signs": "The values for 'Order Torque' and 'W/S Torque' are both set to zero, indicating no torque applied or detected. This could be a defect if the expected values were different.",
      "criticality_level": "MEDIUM"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/a78dbcee.jpeg"
}
```


## Page 37

35 
 
5-15. ANDON Screen 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
1) Various call buttons 
This is a call button for material shortages, quality, and maintenance. 
2) ANDON call reset button 
Resets the call button that was turned on in step 1). 
  
 
1
2



### Extracted Image Analysis

```json
{
  "asset_type": "embedded_document_image",
  "unique_image_id": "image_20240224_132921",
  "source_file_origin": "HMI screen from an industrial machine",
  "page_or_sheet_location": "Main page with callout buttons and status indicators",
  "component_name": "Andon Callout Buttons",
  "keywords": [
    "Andon",
    "Callouts",
    "Maintenance",
    "Quality"
  ],
  "visual_specifications": {
    "expected_color": "The background is black, text colors are green, blue, red, and white.",
    "critical_alignment_angles": "Buttons are aligned horizontally in a row with the callout message centered below them.",
    "surface_texture_purity": "The interface appears clean and clear."
  },
  "detailed_explanation": "This image is an Andon Callout screen from an industrial machine. It displays four callout buttons for different types of calls: 'Out of Parts', 'Quality Problem', 'Maintenance Needed', and a reset button labeled 'Andon Call'. The top right corner shows the date and time as 24/02/24 at 13:29:21. Below the main callout buttons, there are two additional buttons for manual fault content under categories ST1 and ST2.",
  "common_defects_and_failures": [
    {
      "defect_type": "No visible defects",
      "visual_signs": "All elements are clearly visible with no signs of wear or damage.",
      "criticality_level": "LOW"
    }
  ],
  "local_storage_path": "output/images/Teeth Surface Forming Machine/dcf4acd8.jpeg"
}
```


## Page 38

36 
 
6. Calibration method of strain amplifier 
 
Calibration method of strain amplifier as follows. 
 
1) Turn on the power switch of the machine. 
 
2) Put power switch of strain amplifier. Torque sensor turns sensor body switch into the 
on side. 
 
3) Load (force) is not added to torque sensor and load cell sensor. 
 
4) Filter regulating apparatus selects 〔 10Hz 〕. 
 
5) Push a button of Bal once. 
 
6) Confirm rated value mentioned in test record of result of sensor and value of rated 
output. Please set rated output (mV/V) value with sum rotary switch setting 
calibration (CAL) value. 
 
7) Turn screen of touch panel into SENSOR MONITOR. Do control of afterward while 
looking at input data of each sensor with screen of SENSOR MONITOR. 
 
8) Turn toggle switch of CAL polarity into 〔 OFF 〕 (the center). Adjust it with BAL 
button so that indicated value of touch panel becomes zero. 
 
9) Turn toggle switch of CAL polarity into 〔 + 〕 side. Adjust gain with volume of 
FINE GAIN so that indicated value of touch panel becomes one-half of rated capacity 
(unit, N･m). 
 
10) Several times repetition identifies 8) as 9). 
 
11) If calibration was over, turn toggle switch of CAL polarity into 〔 OFF 〕 (the 
center). 
 
Torque sensor 
 
 
ST1 
ST2 
Rated capacity (N) 
150 N･m 
150 N･m 
Rated output (mV/V) 
1.502 mV/V 
1.504 mV/V 
Calibration set point 
1502 
1504 
 
Display of touch panel 
 
 
ST1 
ST2 
CAL polarity  [＋] 
 100.0 N･m 
100.0 N･m 
CAL polarity [OFF] 
0.0 N･m 
0.0 N･m 
CAL polarity  [－] 
100.0 N･m 
100.0 N･m

