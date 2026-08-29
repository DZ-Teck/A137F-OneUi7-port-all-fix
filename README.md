# Galaxy A13 4G (MTK) touchGrassKernel Fork

WARNING: This is a fork of the TouchGrassKernel of @micr0softstore thank for this kernel !

## The official kernel had KernelSU Next 1.0.9, but that's outdated. So i decided to fork this kernel for add ResukiSU 4.2.0rc1 with driver version 35081. 
[SEE] in the future, I plan to add SusFS 2.2.0 backported by @Jack1man .I tried to add it, but i have Encountered a problem. View the susfs-rksu branch for more information.

> [!NOTE]
> Feel free to FORK or create PR.

> [!NOTE]
> Make sure you have build tools/packages installed, else it won't compile properly.

## Looking for linux readme?
- [Click here](https://github.com/micr0softstore/samsung_kernel_a13ve/blob/enforcing-u8/README)

## To compile:
- $ git clone --depth=1 https://github.com/DZ-Teck/A137F-OneUi7-port-all-fix.git -b enforcing-u8
- $ cd A137F-OneUi7-port-all-fix
- $ sudo bash build_kernel.sh

## Download:
- [LATEST](https://github.com/DZ-Teck/A137F-OneUi7-port-all-fix/releases/tag/v1.0.0) latest release of kernel with ResukiSU:



### Features
- Bootable upto OneUI7
- Dex TouchPad [SEC_TOUCHPAD] (Not yet)
- ResukiSU 4.2.0rc1 (35081)
- erofs
- more in future

### About kernel:
- Got some commits from others like:
  - bpf commit from: t.me/nnhglong
  - sdfs upstream commit by Extreme XT
- Tested on: Binary C (latest binary), it work on old binary, (8 to C)
- telegram channel on: t.me/a13vedev
- Discussion on: https://t.me/a13mtkdiscuss
