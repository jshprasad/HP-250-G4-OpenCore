# HP-250-G4-OpenCore
Catalina Hackintosh Install - Dortaina Install Guide - Broadwell Chipset

HP 250 G4 
Processor i3 - 5005U 2.0Ghz
Intel HD Graphics 5500 - intergrated - iGPU

OpenCore - 0.6.9

Working

  Keyboard
  Ethernet
  Mouse, touchpad
  Graphics
  Battery
  Sleep
  Close lid to sleep
  USB
  iMessage
  Audio
  Microphone
  iCloud

Not Working

  Wifi - Realtek Wifi Card not supported
  Bluetooth
  

Kexts

  Lilu
  Virtual SMC
  VoodooHDA
  SMCSuperIO
  VoodooPS2Controller
  WhateverGreen
  AppleALC
  RealtkRTL8111 - NIC
  SMCBatteryManager
  SMCProcessor
  
ACPI

  SSDT -EC.aml
  SSDT -HPET.aml
  SSDT -PLUG.aml
  SSDT -PNLF.aml
  
Smbios - MacbookAir7,2

Graphics require patching for HD 5500 ( Fake ID with Frame Buffer to be entered in config.plist, as mentioned in Broadwell - Dortaina Guide)
