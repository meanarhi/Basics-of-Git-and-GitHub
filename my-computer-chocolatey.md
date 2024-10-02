## Step 1: Install CHOCOLATEY
**Run the following command in Powershell to install CHOCOLATEY**

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; iwr https://community.chocolatey.org/install.ps1 -UseBasicParsing | iex

!!! danger "This will remove chocolatey from your computer! For re-installing only!"
    ```powershell title="Powershell as Administrator"
    rm -Path "C:\ProgramData\chocolatey" -Recurse -Force
    rm -Path "C:\ProgramData\ChocolateyHttpCache" -Recurse -Force

## Step 2: Programs/Apps Installation
```powershell
choco install powershell-core git vscode putty greenshot notepadplusplus winscp 7zip paint.net windirstat zoom sudo vmrc vmware-horizon-client github-desktop obs-studio docker-desktop google-drive-file-stream googlechrome curl powertoys -y

```
## Step 3: Installing some useful VScode addons
* Restart your Powershell session 
* Run the following commands 
```powershell linenums="1"
code --install-extension ms-vscode.powershell
code --install-extension vsls-contrib.gistfs
code --install-extension ms-vscode-remote.remote-containers
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-vscode-remote.vscode-remote-extensionpack
code --install-extension GitHub.copilot
code --install-extension GitHub.vscode-pull-request-github

```
Olen ladannut koneelle mm. vscode, chrome, zoom, github-desktop, google docs, google sheets, word, paintnet, WMware-horizon-client. spotify

Hostname:
![image](https://github.com/user-attachments/assets/436682ec-57a1-4e20-b7ea-e1d7523b65f6)

