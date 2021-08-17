# Remove_ShareWithSkype

Deletes Share With Skype option from context menu in Windows.

![alt text](https://github.com/barbadosas/Remove_ShareWithSkype/blob/main/whatmustbegone.jpg "Logo Title Text 1")

# Use

Launch Powershell.exe with Administrator rights and run command below.

```Remove-Itemproperty -path "HKLM:SOFTWARE\Classes\PackagedCom\Package\Microsoft.SkypeApp_15.75.140.0_x86__kzf8qxf38zg5c\Class\{776DBC8D-7347-478C-8D71-791E12EF49D8}" -Name DllPath```
