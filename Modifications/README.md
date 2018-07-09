This folder contains modifications to files in other libraries. Copy these files to the corresponding folders to overwrite the existing files there.

## Updater.h
Added a public reset function to allow OTA update to abort and reset upon error.

### Apply patch
```sh
patch ~/.platformio/packages/framework-arduinoespressif8266/cores/esp8266/Updater.h Updater.patch 
```
