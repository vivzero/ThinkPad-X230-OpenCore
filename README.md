# ThinkPad X230 Hackintosh
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
| WLAN | Centrino-N 6205 |
| BIOS | 2.70 |

## Issues
* AirportItlwm fails after OS install or update.
  * Workaround: Replace the kext.
* Brightness is dimmer than Windows.
  * Workaround: It'll be okay after waking from sleep.
* Screen remains black after opening the lid.
  * Workaround: Press a key to turn the display on.
* Sometimes shutdown performs restart instead.
