# OBD PIDs for the Kia Soul EV

## How to use:

These codes are primarily for use with Torque Pro which runs on Android phones and tablets. The preferred method of inputting them to the phone is via the plugin, HKMC-EV-Torque-Plugin.
Or this can be done manually. [Setting up Torque to show BMS data](http://www.mykiasoulev.com/forum/viewtopic.php?f=6&t=471)

## List of files: 

OBD PIDs 

- Kia_Soul_EV_BMS_cell_data : The 96 cell voltages of the High Voltage battery.
- Kia_Soul_EV_BMS_data.csv : Data from the High Voltage battery.
- Kia_Soul_EV_Extra_gauges.csv : Extra values calculated from the PID data.
- Kia_Soul_EV_LDC_data.csv : Low-Voltage DC-DC Converter data.
- Kia_Soul_EV_OBC2015_data.csv : On Board Charger data for MY2015 and earlier cars.
- Kia_Soul_EV_OBC2016_data.csv : On Board Charger data for MY2016 and later cars.
- Kia_Soul_EV_TPMS_data.csv : Tire Pressure data.
- Kia_Soul_EV_VIN_data.csv : Vehicle Identification Number data.
- Kia_Soul_EV_VMCU_data.csv : Vehicle Motor Control System data.

For Analysis
- Spreadsheet_Kia_Soul_EV_BMS_2101_2105.xls - Response of PID and sensor mapping

## Tips for the Torque Pro user:

The following units can be converted by changing the unit settings in Torque itself.
There is no need to change these files.

- Temperatures: Celsius -> Fahrenheit.
- Pressures: psi -> bar.
- Speed: km/h -> mph

## Available ECUs:

ECU  | Send  | Reply
---- | ----- | -----
VMCU | `7E2` | `7EA`
BMS  | `7E4` | `7EC`
OBC  | `794` | `79C`
LDC  | `7C5` | `7CD`
TPMS | `7D6` | `7DE`

## Glossary:

**BMS** is the Battery Management System for the High Voltage battery.

**TPMS** codes measure Tire Pressure.

**OBC** is the On Board Charger, used for slow L1 and L2 AC charging.

**VMCU** is Vehicle Motor Control System.

**LDC** is Low-Voltage DC-DC Converter, used to charge the 12V battery and run the car electronics.

**VIN** is the vehicle identification number, also called a chassis number.