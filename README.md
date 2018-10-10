# DarkThemeSwitcher-SumatraPDF
Powershell scripts to set dark theme in SumatraPDF

To switch to dark theme
```
.\SetDarkTheme.ps1
```

To restore the previous settings
```
.\RestoreSettings.ps1
```

If you get an error, it's probably because the scripts aren't digitally signed, so you'll need to run 
```
Set-ExecutionPolicy RemoteSigned
```
