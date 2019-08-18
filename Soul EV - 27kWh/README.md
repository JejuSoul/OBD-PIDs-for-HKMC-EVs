# OBD PIDs for the 27kWh Kia Soul EV - Years 2014 to 2017

## How to use:

These codes are primarily for use with Torque Pro which runs on Android phones and tablets.
To input the codes to the phone : [How to use Torque with a Hyundai / Kia EV](https://jejusoul.github.io/OBD-PIDs-for-HKMC-EVs/)

For some info on using Torque Pro. [Tips for using Torque Pro](https://jejusoul.github.io/OBD-PIDs-for-HKMC-EVs/tips.html)

## List of files: 

OBD PIDs in the extendedpids folder

- `Kia_Soul_EV_BMS_cell_data` :- The 96 cell voltages of the High Voltage battery.
- `Kia_Soul_EV_BMS_data.csv` :- Data from the High Voltage battery.
- `Kia_Soul_EV_Extra_gauges.csv` :- Extra values calculated from the PID data.
- `Kia_Soul_EV_LDC_data.csv` :- Low-Voltage DC-DC Converter data.
- `Kia_Soul_EV_OBC2016_data.csv` :- On Board Charger data.
- `Kia_Soul_EV_TPMS_data.csv` :- Tire Pressure data.
- `Kia_Soul_EV_VIN_data.csv` :- Vehicle Identification Number data.
- `Kia_Soul_EV_VMCU_data.csv` :- Vehicle Motor Control System data.

For Analysis
- `Spreadsheet_Kia_Soul_EV_BMS_2101_2105.xls` :- Response of PID and sensor mapping

## Available ECUs:

ECU  | Send  | Reply
---- | ----- | -----
VMCU | `7E2` | `7EA`
BMS  | `7E4` | `7EC`
OBC  | `794` | `79C`
LDC  | `7C5` | `7CD`
TPMS | `7D6` | `7DE`

## Glossary:

For an explanation of the acronyms see the [Glossary](https://jejusoul.github.io/OBD-PIDs-for-HKMC-EVs/glossary.html)
