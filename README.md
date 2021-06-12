# Welcome to my handy toolbox for windows 10

![Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Windows_10_Logo.svg/1280px-Windows_10_Logo.svg.png)


This has been made with the intent of making it easier to tweak Windows and it's settings, quickly install & configure programs.


**Debloat Windows**

- [builtbybel/privatezilla: Performs a privacy and security check of Windows 10](https://github.com/builtbybel/privatezilla)



**Perform a clean install of nvidia driver**

- [Display Driver Uninstaller Download version 18.0.3.9](https://www.guru3d.com/files-get/display-driver-uninstaller-download,1.html)

- [NVClean install](https://uk1-dl.techpowerup.com/files/L-19L5KAfsWEo_sdDoUUMA/1623511260/NVCleanstall_1.9.0.exe)



**Tools**

- [winget.cli](https://github.com/microsoft/winget-cli)


**Basic tool list**

- Brave browser

- Mozilla Firefox

- Telgram Desktop

- Spotify

- VSCodium

- Windows Terminal

- Git


**Powershell script**

```powershell
winget install --id=Telegram.TelegramDesktop -e  ; winget install --id=Mozilla.Firefox -e  ; winget install --id=Spotify.Spotify -e  ; winget install --id=BraveSoftware.BraveBrowser -e  ; winget install --id=VSCodium.VSCodium -e  ; winget install --id=Microsoft.WindowsTerminal -e  ; winget install --id=Git.Git -e 
```


## Christitus Script

This script can do:

- Installs Chocolatey, Notepad++, Irfanview, VLC, Java, and asks if you want Adobe Reader or Brave.
- Removes all Windows Store Apps EXCEPT office, xbox, and WSL.
- Removed Telemetry
- Disables Cortana
- Deletes various schedules tasks that rebloat the system
- Removes Other Bloatware (Candy Crush, etc.)
- Fixes problems that other scripts causes (lock screen and personalization options restricted)

```powershell
iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JJ8R4'))
```

**Factory default options**

```powershell
iex ((New-Object System.Net.WebClient).DownloadString('https://git.io/JJ8R4'))
```








