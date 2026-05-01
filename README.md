# AE-211-Final-Project-VEX-Drivetrain-Calculator
Read Me for VEX-Drivetrain-Calculator
VEX-Drivetrain-Calculator is a MATLAB tool which allows you to calculate the speed and torque of a tankdrive configuration VEX V5 drivetrain. This project is designed for analysis, robot design, and drivetrain optimization. It uses an public Excel‑based lookup table for real‑world wheel speeds and automatically filters out illegal or physically impossible gear ratios. The program features selections of RPM, wheel size, and gear ratios.

Status
[Unreleased]  
Creator: Reece Mumford  
Created: 2026.04.01  
Last Editor: Reece Mumford  
Last Edited: 2026.04.29

How to Use
download the MATLAB file and the Excel file
[drive_Speed_VEX.xlsx](https://github.com/user-attachments/files/27214018/drive_Speed_VEX.xlsx)

open the MATLAB file in MATLAB


Place the Excel file drive_Speed_VEX.xlsx in the same directory as the MATLAB script.

Open the main script in MATLAB.

Run the script.

select your
Motor RPM
Wheel size
Drivetrain type (Direct Drive or Geared Drive)
Input gear
Output gear

The program will automatically:
Notify user if the ratio and wheel size they have selected is impossible with VEX Spacing.
Display the final speed (in/s) and torque (Nm).
Be sure your Excel file contains valid wheel‑speed data before running the program.
