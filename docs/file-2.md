This is a second file that lives alongside index.md.

This page includes some PowerShell code

```powershell
$computer = Get-Computer -ComputerName mycomputer
Get-Process -ComputerName $computer | Select Name,PID
```

And eventually there will be more as well.
