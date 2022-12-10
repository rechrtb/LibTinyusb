# LibTinyusb
This is a project to build various configurations of tinyusb as libraries under Eclipse for use by RepRapFirmware and other projects.

The CoreN2G and FreeRTOS projects must be in the same Eclipse workspace as this one, because this project uses include files in those projects.

Build configurations currently supported are:
- SAME5x (for SAME51 and SAME54 processors, but probably also works on SAMD processors
- SAME70 (should also work on SAMV71 processors)
- RP2040
