# 🖥️ Install Software via PowerShell

PowerShell can automate the installation of common software using package managers like **Winget** or **Chocolatey**.

---

## 🚀 Method 1: Using Winget (Built-in for Windows 10/11)

### ✅ Example: Install Google Chrome

````powershell
winget install --id=Google.Chrome --source=winget

----------------------------Common apps---------------------------
VS Code 	        winget install --id=Microsoft.VisualStudioCode
Zoom	            winget install --id=Zoom.Zoom
7-Zip	            winget install --id=7zip.7zip
Firefox	            winget install --id=Mozilla.Firefox
VLC Media Player	winget install --id=VideoLAN.VLC
--------------------------------------------------------------------
## 📦 Method 2: Using Chocolatey (Requires Installation)
``` 🛠️ Install Chocolatey (Run in Admin PowerShell)
    "Set-ExecutionPolicy Bypass -Scope Process -Force; `
    [System.Net.ServicePointManager]::SecurityProtocol = `
    [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; `
    iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))"
### ✅ Example: Install Notepad++ with Chocolatey
 (Powersehell)
 "choco install notepadplusplus -y"

⚠️ Note:
-Winget comes with most Windows 10/11 systems.
-Chocolatey needs admin access and initial setup.
````
