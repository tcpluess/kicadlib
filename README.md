To use the library, just clone it and then set the KICAD_CONFIG_HOME to the path where the `config` folder is.
For example:

    git clone git@github.com:tcpluess/kicadlib.git
    export KICAD_CONFIG_HOME="/home/tobias/kicadlib/config/"

From now on, KICAD will use all Symbols, Colors, Footprints, and Sheet Templates from the cloned library.

The library also includes the `osifont` font package. Make sure to copy the `osifont` font to your OS'
font directory and then, KICAD will use the ISO font for schematics and PCB drawings.
