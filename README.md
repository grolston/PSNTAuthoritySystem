# PowerShell Assume NT System
Run following to open up a powershell console under the NT Authority\System account.
```PowerShell
iex (New-Object Net.WebClient).DownloadString('https://github.com/grolston/PSNTAuthoritySystem/raw/master/assume-ntsystem.ps1')
```
