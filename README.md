# ThinkPad X230 Hackintosh
Tested with macOS Catalina and Big Sur

## Specs
| Parts | Details |
| - | - |
| CPU | Core i5-3320M |
| GPU | HD Graphics 4000 |
| RAM | 4 GB PC3-12800S |
| Storage | 128 GB SATA SSD |
| Display | LP125WH2-SLB3 |
| Audio | ALC269 |
| LAN | 82579LM |
| WLAN | 62205ANHMW |
| BIOS | 2.70 |

## Issues
* POST hangs after OS reboot.
  * Workaround: Remove USB stick before reboot. If you didn't, just wait until the Boot Menu appears, then remove it.
* AirportItlwm fails after OS install or update.
  * Workaround: Replace the kext.
* Docking station is not hot-swappable.

## Not Tested
* Mini DisplayPort
* ExpressCard
* Hibernation (S4)

## Not Working
* SD Card Reader
