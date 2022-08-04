# OpenCore-i510500-B460M
Hackintosh OpenCore setup for my i5 10500 PC


## PC
- CPU: Intel(R) Core(TM) i5-10500 CPU @ 3.10GHz
- RAM: 32GB
- Motherboard: Gigabyte-B460M-Aorus-Pro
    - Sleep mode works
- IGPU: Intel CometLake-S GT2 [UHD Graphics 630]
    - Total VRAM: 1536MB (Shared)
- Monitors: 
    1. LG Ultrawide (28.5-inch (2560 × 1080))
    2. LG FULL HD (21.5-inch (1920 × 1080))
- Network cards:
    1. Broadcom - BCM4360 802.11ac
    2. Intel - Ethernet Connection (12) 1219-V
- Bluetooth:
    1. Broadcom - BCM2046B1 (come with the network interface)
        - AirDrop works
        - Can unlock with Apple Watch

## MacOS
- OpenCore version: 0.8.0
- OS: macOS Monterey Version 12.5 (Build 21G72)
- Model Identifier: iMac20,1
- Known issues:
    - Universal Control has high latency (tested with a M1 MacbookAir)

## Steps
- Copy all files in the `./EFI` to the EFI section
- Replace `MLB`, `ProcessorType`, `ROM`, `SystemProductName`, `SystemSerialNumber`, and `SystemUUID` values
