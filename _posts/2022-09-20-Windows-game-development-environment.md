## Windows game development environment

Author: [<img src="https://nott-gaming.github.io/assets/images/Axel_agent.png" alt="Axel" width="16" height="16">](https://nott-gaming.github.io/aboutus#AXEL) [Axel Fernández Curros](https://nott-gaming.github.io/aboutus#AXEL)

Guide to set up a Windows workstation for videogame development.

#### Check you have winget installed
```powershell
winget --version
```
If is not, do install it, is super useful. 
[External Link](https://learn.microsoft.com/en-us/windows/package-manager/winget/)

#### Install Microsoft Visual Studio and C & C++ Build Tools
Install Visual Studio
[External Link](https://learn.microsoft.com/en-us/cpp/build/vscpp-step-0-installation?view=msvc-170)

Install MSVS v14x VS 201x C++ Build Tools also to prevent possible errors from now on.
[External link](https://visualstudio.microsoft.com/es/visual-cpp-build-tools)
[External link](https://www.microsoft.com/es-ES/download/confirmation.aspx?id=48159)
<br/>

#### Download and Install MinGW and add MinGW Path variable to Windows Path (optional but recommended)
If any errors occur, you might want to try to install g++ and gcc compilers with MinGW.
[External Link](https://www.geeksforgeeks.org/installing-mingw-tools-for-c-c-and-changing-environment-variable)

Be sure to have installed gcc and g++ compilers for developing purposes.

#### With gcc and g++ installed
We are able to write and develop programs written in C and C++ and compile them successfully.

#### Instal Rust Language
[External Link](https://www.rust-lang.org/learn/get-started)
Add Rust folder to Windows path's variables:
My user rust installation path location as default: 'C:\Users\AxelFC\.cargo\bin'

#### Install Python3
```powershell
winget install -e --id "Python.Python.3.8"
```
Add Python to path's variables. Check if you can call it too from terminal.
```powershell
python --version
```

#### Install Unreal Engine
Install Windows .NET Core 3.1 for being able to export games for Windows.
[External Link](https://dotnet.microsoft.com/en-us/download/dotnet/3.1)
```powershell
winget install -e --id "EpicGames.EpicGamesLauncher"
```

#### Install Blender
```powershell
winget install -e --id "BlenderFoundation.Blender"
```
