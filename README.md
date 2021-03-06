MK2000 Kernel
=============

### Some links
* [LG G5] XDA thread.
* [LG V20] XDA thread.
* [LG G6] XDA thread.

This kernel is for the following LG Devices:
-----------------------------------------------
### G5
- `H850` - International (Global)

* `H830` - T-Mobile (US)

* `RS988` - Unlocked (US)

### V20
- `H910` - AT&T (US)

* `H918` - T-Mobile (US)

* `US996` - US Cellular & Unlocked (US)

* `US996Santa` - US Cellular & Unlocked (US)
  * Unlocked with Engineering Bootloader

* `VS995` - Verizon (US)

* `H990DS` - International (Global)

* `H990TR` - Turkey (TR)

* `LS997` - Sprint (US)

* `H915` - Canada (CA)

* `F800K/L/S` - Korea (KR)

### G6
- `H870` - International (Global)

* `US997` - US Cellular & Unlocked (US)

* `H872` - T-Mobile (US)

## COMPILE THE KERNEL

### Clone
	git clone https://github.com/stendro/msm8996_lge_kernel.git -b mko-v2

### Build
	./build.sh DEVICE && ./copy_finished.sh

* "DEVICE" will be one of the above names (case sensitive).
* You should also configure your compiler path in ´build.sh´.

## A bit of info

This is the Oreo branch (v2).
It builds workable kernels for all above devices.

Branch 'lge-3.18-stable', like the name implies, is an upstreamed base LG kernel with
various fixes - for convenience sake. It can be an ideal starting point for other's
wanting to try kernel development for LG's MSM8996 devices.

[LG G5]: <https://forum.xda-developers.com/lg-g5/development/h850-mk2000-kernel-t3707822>
[LG V20]: <https://forum.xda-developers.com/v20/development/h918-h910-us996-ucl-mk2000-kernel-t3708330>
[LG G6]: <https://forum.xda-developers.com/lg-g6/development/us997-h870-mk2000-kernel-t3739494>
