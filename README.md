# ASUS-PRIME-B360M-MacOS-Opencore

## My Configuration

Motherbaord : ASUS Prime B360M-A
CPU         : Intel Core i5-8600 (non-k)
RAM         : 16GB 2666Mhz (2x8GB)
GPU         : RX 580 (iGPU disabled in BIOS)
SMBIOS      : iMac19,1


## Instructions

1. Download these
                - EFI folder from this repo.
                - ProperTree https://github.com/corpnewt/ProperTree
                - GenSMBIOS https://github.com/corpnewt/GenSMBIOS
2. Copy the EFI folder to the root of EFI Partition. (delete everything else before doing this)
3. Run ProperTree and open EFI/OC/config.plist
4. Follow this guide https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/post-install/post-install/iservices to fix iServices (Use iMac19,1).
5. Save and Reboot.


## What Works
Everything
