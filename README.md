# Sonic Robo Blast Gamemaker

## About

*Sonic Robo Blast Gamemaker*, also known as *SRBGM*, is a recreation of [SRB2](https://www.srb2.org), based on the lost media game, SRBG2. ([This](https://www.youtube.com/watch?v=rnhwXgkZ69o) is the only video I can find that had clips of the original game)

## Requirments
This game requires

* Windows XP, or a system that has the ability to play games of that era and above ([Wine](https://www.winehq.org/) *IS* supported)
* 1 Gigabyte of RAM
* DirectX 9
* 30 MB free space
* Intel Pentium 3 450 MHz (__WARNING__:I have *not* tested if this works on older CPUs, if it *does*, please reach out to me.)

## Building
To build the game, you __MUST__ have

* A copy of Gamemaker 8.1 Standard, Gamemaker 8.1 Pro, or Gamemaker 8.2
* At least 100 MB of free space, excluding your Gamemaker copy
* The previous stated requirments

Download all the source code, and install the fonts inside the source code. For Windows, right click the file in Explorer and press "Install". For Wine, use WineTricks to install them, or copy the font files in a folder resembling `~/.wine/drive_c/windows/Fonts`.

Opening up the .gm81 or .gb1 file from your Gamemaker copy and attempting to run the test build will have an error telling you it could not locate include file P3DC.dll. To fix this, go to "Manage Included Files" and change the included DLL file to the location of your DLL.

Now you can run the test build from Gamemaker, have fun!
#
