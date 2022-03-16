# freescale-build-tools
Compiler build tools for Freescale 68hc11, 68hc12, S12, S12X, XGATE

This is a mirror of the files from https://www.msextra.com/tools/. It hasn't be updated since 2012, and this repo exists as a means to preserve it.

Binaries can be found in the [releases](https://github.com/ksmarty/freescale-build-tools/releases) section.

## How to Use

First, download the desired archive from [releases](https://github.com/ksmarty/freescale-build-tools/releases).

Extract the archive, then rename the folder `usr` to `gcc`.

Copy the `gcc` folder to the root of an existing HC12 project. An example one can be found in [ExampleProject](ExampleProject).

Update the `Makefile` to point to 
- Linux/MacOS: `gcc/bin/m68hc11-elf-gcc`
- Windows: `gcc/bin/m68hc11-elf-gcc.exe`

Open the project in an IDE of your choosing and you're good to go!
