# kicad-my-libs

My KiCad libraries.

## Installation

```
git clone https://github.com/sebmalissard/kicad-my-libs ${HOME}/ws/kicad/kicad-my-libs
```

## Configuration

Define the KICAD_MY_LIBS_DIR variable, go to "Preferences" > "Configure Paths..."

Then add:
KICAD_MY_LIBS_DIR = ${HOME}/ws/kicad/kicad-my-libs

## Symbols

Add the library in KiCad Eeschema, go to "Preferences" > "Manage Symbol Libraries..."

Then set the library path "${HOME}/ws/kicad/kicad-my-libs/symbols/sym-lib-table"

To finish set library format **Table**.

## Sources

### Symbols

* converter_ACDC_ext
* ESP8266               https://github.com/jdunmire/kicad-ESP8266.git (1f3d2c6e49285d4ab4976efc04913bd3974290c1)
* max                   https://github.com/aleksmk/kicad-libs
* Pololu
* promicro              https://github.com/Biacco42/ProMicroKiCad.git
* teensy                https://github.com/XenGi/teensy_library.git (a57cd10e8221a7deaeb15a078e3f892c6f2311ad)
* transistor_fet_ext
* Transistor_FET
* w_logic               http://smisioto.no-ip.org/kicad_libs/library/lib_w_logic.zip
