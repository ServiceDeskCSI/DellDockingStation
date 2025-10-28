# DellDockingStation

Store for Dell Docking Station Drivers

DellDockFirmwarePackage_WD19_WD22_HD22_WD25_SD25_01.XX.XX.exe

<img width="401" height="549" alt="DellDockFirmwarePackage_WD19_WD22_HD22_WD25_SD25_01 01 07_5LsCu4O6ml" src="https://github.com/user-attachments/assets/e980d5cf-2521-4fe3-aefd-25db694024d7" />

DellDockFirmwarePackage_WD19_WD22_HD22_WD25_SD25_01.XX.XX.exe [options]

(none)	Launches a guided Dell Dock firmware update with messages.
```/? or /h	Displays the help screen.
/s	Runs silently (suppresses the UI).
/r	Reboots the system after completing the update.
/l=<path>	Logs messages to the specified file.
/p=<password>	Supplies the BIOS password if required.
/components	Displays Dell Dock components and their versions.
/uod	Updates Thunderbolt and EC firmware on disconnected docks.
```
Examples
Silent update + reboot:
```
 DellDockFirmwarePackage_WD19_WD22_HD22_WD25_SD25_01.XX.XX.exe /s /r
```

Silent update + reboot + log to file:
```
DellDockFirmwarePackage_WD19_WD22_HD22_WD25_SD25_01.XX.XX.exe /s /r /l="C:\my path with spaces\log.txt"

```
Disconnected dock update mode:
```
DellDockFirmwarePackage_WD19_WD22_HD22_WD25_SD25_01.XX.XX.exe /uod
```

