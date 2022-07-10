# EFI-AMD-ASUS-Strix-X570-E_Ryzentosh
BASE EFI AMD - Ryzen for [ASUS Strix-X570-E](https://rog.asus.com/motherboards/rog-strix/rog-strix-x570-e-gaming-model/).
This EFI is ready to use for ROG Strix X570-E Gaming Hardware 

## To not Forget
1. Update to last Bios 
2. Edit Config.plist by:
   1. Replace `SystemSerialNumber` value to your own 
   2. Replace `MLB` value to your own 
   3. Replace `SystemUUID` value to your own
3. Use bellow config on your bios
4. Use Updated Kexts

## Saved BIOS Configuration 
TPM 2.0 UEFI Spec Version [TCG_2]

Disable Block Sid [Disabled]

Selects TPM device [Enable Firmware TPM]

Erase fTPM NV for factory reset [Enabled]

PSS Support [Enabled]

NX Mode [Enabled]

SVM Mode [Enabled]

SMT Mode [Auto]

Core Leveling Mode [Automatic mode]

SATA Port Enable [Enabled]

SATA Mode [AHCI]

When system is in working state [All On]

Q-Code LED Function [POST Code Only]

When system is in sleep, hibernate or soft off states [All On]

Realtek 2.5G LAN Controller [Auto]

Intel LAN Controller [Auto]

Wi-Fi Controller [Disabled]

Bluetooth Controller [Disabled]

USB power delivery in Soft Off state (S5) [Enabled]

Restore AC Power Loss [Power Off]

Power On By PCI-E [Disabled]

Power On By RTC [Disabled]

Above 4G Decoding [Enabled]

Resize BAR Support [Disabled]

SR-IOV Support [Disabled]

Legacy USB Support [Disabled]

XHCI Hand-off [Enabled]

USB Device Enable [Enabled]

Fast Boot [Disabled]

Boot Logo Display [Auto]

POST Delay Time [3 sec]

Bootup NumLock State [On]

Wait For 'F1' If Error [Enabled]

Option ROM Messages [Force BIOS]

Interrupt 19 Capture [Disabled]

AMI Native NVMe Driver Support [Auto]

Setup Mode [Advanced Mode]

Launch CSM [Disabled]

OS Type [Windows UEFI mode]


## Build Spec

## ACPI SSDT's

## Kexts
- AMDRyzenCPUPowerManagement.kext
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- Lilu.kext
- LucyRTL8125Ethernet.kext
- NVMeFix.kext
- RadeonSensor.kext
- RestrictEvents.kext
- SmallTreeIntel82576.kext
- SMCAMDProcessor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext


## What Works

## What Doesn't Work

## Nvram -> boot args

## Thanks to 
- https://github.com/AMD-OSX/AMD_Vanilla
- https://github.com/luchina-gabriel

