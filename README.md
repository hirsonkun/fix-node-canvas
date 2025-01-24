# fix bugs node-canvas package
- related issue for node 22.xx (LTS)

node canvas installing issues windows 10/11

**1. Install GIT**<br />
```PowerShell
winget install --id Git.Git -e --source winget
```

**2. Install MSYS2**<br />
```PowerShell
winget install --id MSYS2.MSYS2 -e --source winget
```

**3. Install VS2022**<br />
```PowerShell
winget install Microsoft.VisualStudio.2022.BuildTools -e --source winget --silent --override "--wait --quiet --add ProductLang En-us --add Microsoft.VisualStudio.Workload.VCTools --includeRecommended"
```

**4. Install Python**<br />
```PowerShell
winget install --id Python.Python.3.13 -e --source winget
```
<!---
**5. Install gvsbuild**<br />
```PowerShell
py -3.13 -m pip install --user pipx
py -3.13 -m pipx ensurepath
pipx install gvsbuild
```
-->
**5. Download GTK and Unzip the contents in `C:\GTK`**<br />
[gtk+-bundle_2.22.1-20101229_win64.zip](https://ftp.gnome.org/pub/GNOME/binaries/win64/gtk+/2.22/gtk+-bundle_2.22.1-20101229_win64.zip)

**6. Download both libjpeg-turbo and install to its default location (`C:\libjpeg-turbo` if 32bit or `C:\libjpeg-turbo64` if 64bit)**<br />
[libjpeg-turbo-3.0.1-vc.exe](https://sourceforge.net/projects/libjpeg-turbo/files/3.0.1/libjpeg-turbo-3.0.1-vc.exe/download)<br />
[libjpeg-turbo-3.0.1-vc64.exe](https://sourceforge.net/projects/libjpeg-turbo/files/3.0.1/libjpeg-turbo-3.0.1-vc64.exe/download)
