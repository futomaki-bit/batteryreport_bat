# batteryreport_bat
Make Windows' battery report with .bat

**Don't need admin privilege!!**
```
@ECHO OFF
powercfg /batteryreport /output "%userprofile%\Desktop\battery_report.html"
PAUSE
```
