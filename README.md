Project : Exe_Dll_Test

Date : circa 2004-ish


Description : I always wanted to test how a DLL works, so I've altered my little DDraw library in a DLL form and have tested loading it dynamically. 

TODO 
- Debug the drawing part of the library that is broken, but the DLL loading works


WHAT YOU NEED TO COMPILE :
- Microsoft Visual C++ 6.0
- Microsoft DXSDK_Aug09.exe from https://download.microsoft.com/download/4/C/F/4CFED5F5-B11C-4159-9ADC-E133B7E42E5C/DXSDK_Aug09.exe


Files ID :
*.dsw : Visual Studio 6 Workspace
*.dsp : Visual Studio 6 project
*.opt, plg, ncb : Debug stuff
Debug/ : a windows XP compiled version Debug
	Note : you will need to have the dll in the current folder 
	Note : you will have to copy the Data directory in current folder

Release/ : a windows XP compiled version Release
	Note : you will need to have the dll in the current folder 
	Note : you will have to copy the Data directory in current folder

Data/ : Test textures and model
src/ : All source for the EXE part of the workspace
Lib/ : The DLL and lib project
Lib/*.dsp : Visual Studio 6 project
Lib/*.plg : Debug stuff
Lib/bin/ : compiled copy of DLL and lib
Lib/Debug : compiled copy of DLL and lib
Lib/inc : includes files for Exe
Lib/src : Sources files for Lib


