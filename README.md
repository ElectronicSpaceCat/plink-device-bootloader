# Firmware bootloader

The bootloader for the device is a separate application that sits in it's own secition of flash memory. Its job is to manage firmware updates to the device. This one in particular uses the nRF softdevice bluetooth stack to allow firmware updates wirelessly, either through nRF Connect BLE or a mobile application.

The difference between the two linkers in this project (Debug/Prod) is that Debug is compiled without optimization for better debugging.
