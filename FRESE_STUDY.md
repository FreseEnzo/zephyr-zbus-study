# Zbus-Zephyr-Study
This repository provides examples of using Zephyr's zbus for inter-thread communication on a nRF9160 DK development kit. Learning and making mistakes :)
## Good commands
### Build
`west build -b nrf9160dk/nrf9160`
### Flash
`west flash`
### Debug
`minicom -D /dev/ttyACM0 -b 115200` or install [nRF Connect for VS Code Extention Pack](https://marketplace.visualstudio.com/items?itemName=nordic-semiconductor.nrf-connect-extension-pack) (time saver)
