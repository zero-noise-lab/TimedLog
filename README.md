Unreal Plugin for creating a Timed Log
=======================================

This is a plugin for Unreal Engine that provides a Game Mode base 
class that can be added to any project. TimedLogGamemode provides 
methods to create a detailed log with corrected timing when the Game
is run in fullscreen Developer mode. 

Actor Component blueprint classes BaseLoggingComponent and 
MovingActorLoggingComponent are included to illustrate its functionallity. 

Please be aware that no binaries are included and the plugin therefore only 
works in C++ UE4 projects where it is properly recompiled. To switch your 
Blueprint only project to include C++ simply go to File → New C++ Class in 
the editor. Make sure Visual Studio is installed on your machine.
