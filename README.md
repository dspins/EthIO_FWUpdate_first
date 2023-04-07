# ethio_fw_update
Eth-IO controller FW Update


## Flashing

1. Using Chrome or Edge, visit https://dspins.github.io/EthIO_FWUpdate_first/flash.html
2. Plug your board into your computer
3. Short the connection of the E-Stop connector
4. Click the `Connect` button
5. Select device on CP2102N USB to UART Controller. (This step requires drivers, presumably you already have them. Download from https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers)
6. Select `Install...`
7. In the Erase prompt just click `Next`
8. In the next prompt click `Install`
9. It should now start flashing, wait a couple minutes to finish
10. Boot the board in Restore Mode to complete the flashing process

To enter Restore Mode power the device while pressing the User Button for more than 9 seconds, you will see both LEDs turn steady on, then release the button. To continue the restore process, press the button once, then, LED 2 will blink 4 times before applying the factory configuration, to stop this or exit this mode simply unplug the device. After the restore is done the device will restart.
