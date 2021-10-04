# ESP32 Programmer

This is a USB-C programmer for ESP32 chips, including autoreset as documented by espressif.  The pinout is compatible with the ESPFlash convention proposed by SuperHouse at https://www.superhouse.tv/espflash/ .

Additionally, 5V is exposed from the USB port (after the protection fuse) - this allows the ESP programmer to be used as a USB to serial module providing both 5V and 3.3V.  The 5V can either be connected via a jumper wire (if the programmer is mounted vertically) or directly via a pin (if mounted horizontally)
