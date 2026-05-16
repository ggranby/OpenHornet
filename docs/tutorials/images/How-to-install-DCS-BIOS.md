# How to Install DCS-BIOS

## Prerequisites

Download the latest versions of these first:

1. DCS-BIOS:
	- [DCS-BIOS GitHub Repository](https://github.com/DCS-Skunkworks/dcs-bios)
    - Download The source code zip from the most recent release or from the code drop down on the repo main page.
2. BORT:
	- [BORT GitHub Repository](https://github.com/DCS-Skunkworks/bort)
3. DCS-BIOS Arduino Library:
	- [DCS-BIOS Arduino Library Releases](https://github.com/DCS-Skunkworks/dcs-bios-arduino-library)


## Installation Steps

1. Extract DCS-BIOS

2. Install DCS-BIOS into your saved games folder
    - DCS Saved Games folder should be in path `C:\Users\<Username>\Saved Games\DCS`
    ### If Scripts folder does not exist in your DCS folder
    - From your extracted DCS-BIOS folder move `Scripts` into your DCS Folder
    ![alt text](<Scripts folder install.png>)


    ### If Scripts Folder does exist 
    - From your extracted DCS-BIOS/Scripts folder move `DCS-BIOS` into your scripts folder
    ![alt text](<DCS-BIOS Install.png>)

3. Install export.lua file
    
    ### If you already had a `Scripts` folder
    - Open the Export.lua file in the extracted DCS-BIOS folder in a text editor
    - Copy the line of code
    - Paste that line into the existing Export.lua file in the DCS `Scripts` folder

    ### Otherwise
    - Copy the Export.lua file from the DCS-BIOS download
    - Paste into the DCS `Scripts` folder

4. Install Programs folder

    - Move the programs folder from your DCS-BIOS download into your DCS Scripts folder
    - Within this folder is both the `connect-serial-port` and `multiple-com-ports` cmd files. It is recommended to add desktop shortcuts for these as well as running `ensure-socat`
    - 




 