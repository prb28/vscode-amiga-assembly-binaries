# vscode-amiga-assembly-binaries
Pre-built binaries used by VSCode Amiga Assembly extension

# Getting the binaires in your workspace
## Cloning the repository
- Open a cmd or power shell
- Go to you amiga assembly workspace dir

`cd vscode-amiga-wks-example`

- Clone the binaries in the bin dir

- For Windows 64b: branch **windows_x64**

`git clone --single-branch --branch windows_x64 https://github.com/prb28/vscode-amiga-assembly-binaries.git bin`

- For OSX: branch **osx**

`git clone --single-branch --branch osx https://github.com/prb28/vscode-amiga-assembly-binaries.git bin`

- For Debian 64b: branch **debian_64**

`git clone --single-branch --branch debian_64 https://github.com/prb28/vscode-amiga-assembly-binaries.git bin`

## Getting the Zip files
- Select the branch in Github according to your os 
    - For Windows 64b: **windows_x64**
    - For OSX: **osx**
    - For Debian 64b: **debian_64**
- Click on the *Clone or doawnload* button
- Select *Download ZIP*
- Unzip the file
- Rename the directory in *bin*

You should have a path like: vscode-amiga-wks-example/bin/fs-uae.exe