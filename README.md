# M710Q-Hackintosh
Hackintosh files for the Lenovo M710q SFF PC

## Device Information

| Parts       | Variant                        |
| ----------- | ------------------------------ |
| CPU         | Intel i5-7600 non T            |
| iGPU        | Intel HD 630                   |
| dGPU        | None                           |
| WiFi / BT   | BCM94360NG                     |
| Nvme        | Samsung PM981a for Ubuntu      |
| Sata HDD    | Western Digital WD5000BEVT     |
| RAM         | SKhynix 2400Mhz 8G x 2         |
| MacOS       | 12.6.8 (21G725)                |
| OpenCore    | 0.9.4                          |

## What's Working

* WiFi
* Bluetooth
* Ethernet
* All 6 USB ports, 2.0 & 3.0
* Built-in speaker
* AppStore login
* Dual Screen setup (1 DP + 1 DP to HDMI)
* Boot chime
* Native style boot drive selector
* ... and much more!

## What's Not Working

* Sleep and wake (currently disabled sleeping, only allow screen to turn off)

## Thanks to

* [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
* [@revunix's M710q Opencore repo](https://github.com/revunix/ThinkCentre-M710Q/)
* [@FrzMtrsprt](https://github.com/FrzMtrsprt) for the i5-7600 to replace my i3-6100T
