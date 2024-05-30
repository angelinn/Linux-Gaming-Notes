# Linux-Gaming-Notes

## These are my notes to make my laptop run my favourite games on Linux Mint 20 with Cinnamon
Laptop is running i5-4200H and GTX 850M

* Install Lutris from lutris website (apt one is older)
* Install wine-ge as a runner https://github.com/GloriousEggroll/wine-ge-custom
* Build mangohud from source https://github.com/flightlessmango/MangoHud
* Install winetricks and install all VC libraries (might be required for different games)
* In Lutris set the wine prefix to the one you installed your VC libraries into

### Have butter smooth gaming experience. Before doing these options I had lag at high FPS
* Disable compositor -> start menu -> general.
* Do not use cpupower to limit CPU -> directly limit it via /sys/. 
* Close battle.net launcher before running WoW!
* 
