# ESSI INVADERS

This is a recreation of the classic space invaders video game. Loosly based on the AtariST version by
Robert HC Leong(1990)

Implemented in the C programming language, using SDL library to display graphics on the screen.

To compile you need to have SDL installed on your system and the header files
available to you operating systems PATH environment variable

`gcc si.c -lSDL -o invaders`

note that there is no sound added so far. the goal was to create a working complete version of the gameplay only

## Controls
* space bar to start a game
* when in game space fires a bullet
* right and left arrow keys for movement
* up and down for chosing the weapon to shot
* ESC to exit game

Passos a seguir per instal·lar la llibreria en un entorn Linux (Testejat en CentOS, Red Hat i Debian)

SO: Linux arch
Dependencies: SDL Libraries

How to play the Essi Invaders Game:

Download the zip file from SDL oficial page:

https://www.libsdl.org/release/SDL-1.2.15.tar.gz

Once downloaded, extract the files as follows: tar -xvzf  SDL-1.2.15.tar.gz

OPTIONAL [ Get in the folder and make a folder called build:  mkdir build

Enter the folder: cd build ]

Once in, run the configure program if we are in build folder: ../configure or as ./configure if we are in the main folder.

This will put all the new files into build folder

Compile: make

Install: make install

When SDL libraries are compiled and installed we can generate the Essi Invaders runable file

* (We must have C compiler installed in our machine: yum install gcc)

Compile and generate the runable: gcc si.c -lSDL -o invaders

We play Essi Invaders games with the file created: ./invaders


# EssiInvaders
