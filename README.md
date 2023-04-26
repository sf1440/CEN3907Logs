# CEN3907Logs

This is Songyuhao Shi's CEN3907 logs file to track the work of the project that done by team Minetest in CEN 3907 class during Spring 2023. Our goal is making native api C++ files to call the lua functions from original lua script files so people can just use their c++ knowledge to edit and modify the code file without have decent amount of knowledge in Lua.




File Logs was seperate in following dates and weeks




Logs Summary 

03.27.23
Switching project from Lounge Lizard to Minetest and setting up the environment

03.28.23
Reasearch the relationship between C++ native api and original Lua files, Fixing CMake bugs for the setup

Week 4.3.23
Fixing Visual Studio bugs and compile and run the test game through debug mod

Week 4.10.23
Finish written part of Storage class and start writing test files for function l_get_mod_storage

Week 4.17.23
Finish testing and decided to work on Http class next, Finish the presentation

Week 4.24.23
Finish the documentation for the Engineering Capstone 1


Fixed Bugs in Setup Process:

Vckpg Problem:
Reinstall and choose the corrct location path for the Vckpg

CMake Problem:
cURL Lib cannot be find and need to be disable sound 
Check the Vcpkg installation since it might have some problems during the installation

Visual Studio Problem:
If we can debug the game through minetest api mode but not native-api mode, and spidermonkey settings in properties for minetest were gone after switching
Try use Visual Studio Installer to repair and add turnon command in CMakeList to check the LINK2019 files maunally.

Other Problem:
Make sure clone the game and everything locally under C:/User/"username"/DIR 
