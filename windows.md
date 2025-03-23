# Windows Package Managers & OS Detection

## **Package Managers**
| Package Manager | Install Command | Usage Example |
|---------------|----------------|--------------|
| Winget | Pre-installed (Windows 10/11) | `winget install <package>` |
| Chocolatey | `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))` | `choco install <package>` |
| Scoop | `iwr -useb get.scoop.sh | iex` | `scoop install <package>` |

## **Check OS Version**
```powershell
winver
systeminfo | findstr /B /C:"OS Name" /C:"OS Version"
Get-ComputerInfo | Select-Object OsName, OsArchitecture, WindowsVersion
