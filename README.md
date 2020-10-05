# Lenovo-Xiaoxin-Air-15-2019-IWL-Hackintosh
 
## Description
* OpenCore 0.6.2 beta is used in this repository, can both boot Catalina and Big Sur (Tested).
* Wifi is drived by AirportItlwm.kext, which is can only be used under Big Sur. If you want to use wifi under Catalina, please switch to AirportItlwm.kext(Catalina) [Download here](https://github.com/OpenIntelWireless/itlwm/releases/)
* AirportItlwm currently supports native Wi-Fi selection and switching with WPA/WPA2/Unencrypted Wi-Fi Networks, Location Services, Handoff and Universal Clipboard. If you want to connect to hidden wifi, personal hotspot from iPhone, use [itlwm.kext](https://github.com/OpenIntelWireless/itlwm/releases/) with [Heliport](https://github.com/OpenIntelWireless/HeliPort/releases/)
* I forget where did the basis of the SSDTs used in this repository, if the author recognized them, please contect me, I will lable the source. 😂
* All platforminfo is deleted, input yours before logging into your Apple ID.

## Device information
| Specifications | Details |
|:-: |:-: |
| Processor | Intel Core i5-10210U  |
| Memory | 12GB DDR4 2400MHz |
| HDD | Western Digital SN550 500GB |
| Graphics Card | Intel UHD Graphics 630|
| ex. Graphics Card |  Nvidia MX250 2GB |
| Monitor | 15.6 inch 1920x1080 |
| Sound Card | Realtek ALC257 |
| Card reader | O2 Card Reader |
| Finger print reader | Goodix |
| Network Card | Intel AC 9560 |
| BIOS Version | CNCN11WW |
    
## Working:
* Sound / Microphone
* Graphics Card (Intel)
* Keyboard
* Touchpad
* Camera
* USB
* Sleep / Wake
* Wifi / Bluetooth
* Brightness adjustment (in system preferences)
* Battery

## Not working:
* Card reader
* Fingerprint reader
* Brightness Fn keys
* Nvidia MX 250
