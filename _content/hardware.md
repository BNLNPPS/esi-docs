---
title: "The GPU Server"
layout: base5
name: hardware
---

{{ site.HR }}


#### The GPU Host (Marquis C543-GTT)

* Supermicro X13SWA-TF W790 ATX motherboard
* Onboard Realtek ALC888S 8-channel (7.1) High Definition audio
* Onboard Intel i210-AT 1G and Marvell AQC113 10G Ethernet controllers
* 6xPCIe x16 v5
* 4xUSB 3.2 Gen2x1, 2xUSB 3.2 Gen2x2, 2xUSB 2.0 ports
* 1 x Intel Xeon W7-3445 2.6ghz (4.8Ghz Turbo), 52.5M L3, 20-core, 40 threads, 270W TDP
* 8 x Micron MTC10F1084S1RC48BA1R 16GB DDR5-4800 ECC registered module, 1Rx8
* 1 x Samsung 990 Pro MZ-V9P4T0B/AM 4TB NVMe PCIe4 SSD, 7450/6900MB/s (R/W), 2400 TBW (M.2 2280)
* Two PNY VCG409024TFXPB1 RTX 4090 (Ada Lovelace) VERTO,24GB GDDR6X, 16384 CUDA,1xHDMI 2.1,4xDP 1.4a,450W (3-slot) + custom 12VHPWR 16-pin cables
* Fractal Design Torrent, 2x18cm, 3x14cm, Seasonic SSR-1600PD 1600W PSU (Platinum-Level), Modular, Black
* Logitech Wireless Combo MK345 USB Keyboard & Optical Mouse, Black
* Rocky Linux 8.8 (based on Red Hat Enterprise Linux 8.8), 64-bit


#### Kernel compatible with the installed drivers

There are two kernels with matching installation of the NVidia drivers, on that machine.
Wre are using `4.18.0-513.9.1.el8_9.x86_64`. This is supposed to be the default the machine
would boot into.

