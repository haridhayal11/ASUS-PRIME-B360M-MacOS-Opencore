# ASUS-PRIME-B360M-MacOS-Opencore

OpenCore Version : 0.6.3

MacOS version    : 11.0.1

## What Works
Everything


## Configuration

| Components  | Mine | Compatible |
| ------------- | ------------- | ------------- |
| Motherbaord  | ASUS Prime B360M-A  | ASUS Prime B360M-X  |
| CPU  | Intel Core i5-8600 (non-k)  | Any Intel 8th Generation  |
| RAM  | 16GB 2666Mhz (2x8GB) | Any  |
| GPU  | RX 580 (iGPU is also enabled in BIOS)  | RX 560, 570, 580, 590 , VEGA56, VEGA64, 5500 XT, 5600, 5600 XT, 5700, 5700 XT, Radeon VII  |
| SMBIOS  | iMac19,1  | iMac19,1  |


## Instructions

1. Download these
   - EFI folder from this repo.
   - ProperTree https://github.com/corpnewt/ProperTree
    - GenSMBIOS https://github.com/corpnewt/GenSMBIOS
2. Copy the EFI folder to the root of EFI Partition. (delete everything else before doing this)
3. Run ProperTree and open EFI/OC/config.plist
4. Follow this guide https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html to fix iServices (Use iMac19,1).
5. Save and Reboot.


## Screenshots

