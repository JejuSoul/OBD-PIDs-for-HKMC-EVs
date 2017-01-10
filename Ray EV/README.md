# OBD PIDs for the Kia Ray EV

## How to use:

These codes are primarily for use with Torque Pro which runs on Android phones and tablets. The preferred method of inputting them to the phone is via the plugin, HKMC-EV-Torque-Plugin.
Or this can be done manually. [Setting up Torque to show OBD data](https://jejusoul.github.io/OBD-PIDs-for-HKMC-EVs/)
For some info on using Torque Pro. [Tips for using Torque Pro](https://jejusoul.github.io/OBD-PIDs-for-HKMC-EVs/tips.html)

- Korean: Setting up Torque (registration required)
  - [Setting up Torque Pro](http://cafe.naver.com/evpoweruser/463)
  - [Adding custom PIDs](http://cafe.naver.com/evpoweruser/465)
  - [Configuring dashboard](http://cafe.naver.com/evpoweruser/466) 
## List of files: 

OBD PIDs in the extendedpids folder 

- `Kia_Ray_EV_BMS_data.csv` :- Data from the High Voltage battery.
- `Kia_Ray_EV_BMS_cell_data.csv` :- The 96 cell voltages of the High Voltage battery.
- `Kia_Ray_EV_OBC_data.csv` :- Data from high voltage battery charger (on-board charger, OBC).
- `Kia_Ray_EV_LDC_data.csv` :- Low-Voltage DC-DC Converter (LDC) data.

## TODO:

- VMCU PIDs
- Unknown bytes in BMS and OBC (see `Spreadsheet_Kia_Ray_EV_OBC_2101_2102.xls`)  

## Glossary:

For an explanation of the acronyms see the [Glossary](https://jejusoul.github.io/OBD-PIDs-for-HKMC-EVs/glossary.html)
