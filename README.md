# batteryreport_bat
Make Windows' battery report with .bat
The report will be placed on your desktop as .html file.

**Don't need admin privilege!!**
```
@ECHO OFF
powercfg /batteryreport /output "%userprofile%\Desktop\battery_report.html"
PAUSE
```
