# Schedule-I-Dump-Converter
I made this tool to give me an easy sdk to include in my internal cheat

Directions of use:
Use il2cpp online converter for executable input GameAssembly.dll at this path:
Code:
C:\Program Files (x86)\Steam\steamapps\common\Schedule I\GameAssembly.dll
after its complete input the global-metadata.dat at this path:

Code:
C:\Program Files (x86)\Steam\steamapps\common\Schedule I\Schedule I_Data\il2cpp_data\Metadata\global-metadata.dat
of course if your game is placed elsewhere finding the equivalent should be easy

Download the zip containing the dump and extract it.
build or download the Dumper.exe and take dump.cs from the dump folder.
Place it in the same folder as the Dumper.exe.

Run Dumper.exe and the dump.cs will be automatically output as an hpp with an sdk structure containing offsets.

Note: I'm actively working on my internal its not even close to done meaning this code is subject to change and this is also my first real release so please don't get cancer from my source
