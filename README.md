# FluentooOS - Kernel

The CM4 has an on-board Gigabit Ethernet PHY — the Broadcom `BCM54210PE`

The built-in wireless module is based on the Cypress CYW43455 and requires the kernel module: `brcmfmac` 
which can be enabled with "Broadcom FullMAC WLAN driver" in the kernel.

## ToDos

- Remove all unnecessary storage drivers, keep only eMMC
- Adapt I2C support
- Adapt I3C support
- Enable Multimedia Support for WebCams
- Adapt USB Type-C Support 

## Links

- [Raspberry PI CM4 Datasheet](https://datasheets.raspberrypi.com/cm4/cm4-datasheet.pdf)





### Personal Information for ToDos

https://markus.wernig.net/de/it/gentoo-binary-kernel-package.phtml