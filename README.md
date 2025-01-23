# fix bugs node-canvas package
- related issue for node 22.xx (LTS)

node canvas installing issues windows 10/11

**1. install GIT**<br />
`winget install --id Git.Git -e --source winget`

**3. install MSYS2**<br />
`winget install --id MSYS2.MSYS2 -e --source winget`

**4. install VS2022**<br />
`winget install Microsoft.VisualStudio.2022.BuildTools -e --source winget --silent --override "--wait --quiet --add ProductLang En-us --add Microsoft.VisualStudio.Workload.VCTools --includeRecommended"`

**5. install Python**<br />
`winget install --id Python.Python.3.13 -e --source winget`

**6. download GTK and Unzip the contents in `C:\GTK`**<br />
[gtk+-bundle_2.22.1-20101229_win64.zip](https://ftp.gnome.org/pub/GNOME/binaries/win64/gtk+/2.22/gtk+-bundle_2.22.1-20101229_win64.zip)

**7. Download both libjpeg-turbo and install to its default location (`C:\libjpeg-turbo` if 32bit or `C:\libjpeg-turbo64` if 64bit)**<br />
[libjpeg-turbo-3.0.1-vc.exe](https://sourceforge.net/projects/libjpeg-turbo/files/3.0.1/libjpeg-turbo-3.0.1-vc.exe/download)<br />
[libjpeg-turbo-3.0.1-vc64.exe](https://sourceforge.net/projects/libjpeg-turbo/files/3.0.1/libjpeg-turbo-3.0.1-vc64.exe/download)
