# OBD PIDs for the Kia Niro HEV

## How to use:

These codes are primarily for use with Torque Pro which runs on Android phones and tablets. The preferred method of inputting them to the phone is via the plugin, HKMC-EV-Torque-Plugin.
Or this can be done manually. [Setting up Torque to show OBD data](https://jejusoul.github.io/OBD-PIDs-for-HKMC-EVs/)
For some info on using Torque Pro. [Tips for using Torque Pro](https://jejusoul.github.io/OBD-PIDs-for-HKMC-EVs/tips.html)

## List of files: 

OBD PIDs in the extendedpids folder 

- `0_Niro_PIDs_final.csv`:- Tested working PIDs included BMS data, cell data and extra gauges.
- `000_Niro_HEV_BMS_data.csv` :- Data from the High Voltage battery.
- `001_Niro_HEV_BMS_cell_data` :- The 64 cell voltages of the High Voltage battery.
- `002_Niro_HEV_Extra_gauges` :- Adittional BMS calculated info.

To obtain working PIDs it's only necesary install 0_Niro_PIDs_final.csv. For developing and testing purpouses you can use all the files.

## TODO:
Most of the PIDs from the Kia Soul EV are working for Ioniq and Niro. Some values are based on Soul EV and need to be adjusted to the Niro specs.

## References:
All merits for this PIDs are from the original dev from https://github.com/JejuSoul
