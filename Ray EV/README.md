# OBD PIDs for the Kia Ray EV

## How to use:

These codes are primarily for use with Torque Pro which runs on Android phones and tablets. The preferred method of inputting them to the phone is via the plugin, HKMC-EV-Torque-Plugin
Or this can be done manually. (Using the Kia Soul EV as an example.)

- English: [Setting up Torque to show BMS data](http://www.mykiasoulev.com/forum/viewtopic.php?f=6&t=471)
- Korean: Setting up Torque (registration required)
  - [Setting up Torque Pro](http://cafe.naver.com/evpoweruser/463)
  - [Adding custom PIDs](http://cafe.naver.com/evpoweruser/465)
  - [Configuring dashboard](http://cafe.naver.com/evpoweruser/466) 
## List of files: 

OBD PIDs 

- `Kia_Ray_EV_BMS_data.csv` :- Data from the High Voltage battery.
- `Kia_Ray_EV_BMS_cell_data.csv` :- The 96 cell voltages of the High Voltage battery.
- `Kia_Ray_EV_OBC_data.csv` :- Data from high voltage battery charger (on-board charger, OBC).
- `Kia_Ray_EV_LDC_data.csv` :- Low-Voltage DC-DC Converter (LDC) data.

## Tips for the Torque Pro user:
To see temperatures in Fahrenheit change the unit settings in Torque, don't change the file.

## TODO:

- VMCU PIDs
- Unknown bytes in BMS and OBC (see `Spreadsheet_Kia_Ray_EV_OBC_2101_2102.xls`)  

## Glossary:
The BMS is the Battery Management System for the High Voltage battery.
