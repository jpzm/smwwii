# About smwwii

[Super Mario War](http://supermariowar.supersanctuary.net/) (SMW) is a Super Mario multiplayer game.
It's a tribute to Nintendo and Samuele Poletto and was mainly developed by Michael Schaffer and Florian Hufsky.
This fork has the purpose of improve the stability of SMW version 1.7 AFE and port it to Nintendo Wii.
The code basis is a fork from Super Mario War Wii version 1.2 by [Tantric](https://github.com/dborth/smw-wii/tree/7f5b39cb4f).

## Download

For public releases, please check the [releases](https://github.com/jpzm/smwwii/releases) page.
For the latest development version, you may clone the `master` branch with the below command.
```
$ git clone https://github.com/jpzm/smwwii.git
```
The content of the repository folder `hbc` has the files of the latest compiled version.

## Setup

In order to setup, you have to copy the content of the downloaded release (or the `hbc` repository folder) to your SD/SDHC card.

## Build

To build the Wii port, please use the provided `Makefile.wii`.
In the terminal, you may type `make -f Makefile.wii`.
If everything proceed successfully, there will be a new `smw-wii.dol` file.
This file is also copied to `hbc/apps/smw/boot.dol`.
There is also the possibility to build it for Linux (`Makefile.linux`).
Although this is mainly for debug purpose, the Linux version is also fully functional as well.

## Credits

In this Wii port I tried to modify the original code only to improve performance and stability.
Therefore, the game itself should be credited to Michael Schaffer and Florian Hufsky (original authors).
