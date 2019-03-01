![SuperGreenLab](assets/sgl.png?raw=true "SuperGreenLab")

[![SuperGreenLab](assets/reddit-button.png?raw=true "SuperGreenLab")](https://www.reddit.com/r/SuperGreenLab)

# Table of Contents

   * [SuperGreenBoards-301B](#supergreenboards-301b)
   * [SGB.301B Overview](#sgb301b-overview)
   * [Board specifications](#board-specifications)
      * [SGB 36.301B](#sgb-36301b)
      * [SGB 72.301B](#sgb-72301b)
      * [SGB 288.301B](#sgb-288301b)
   * [License](#license)
   * [Creative Commons Warranties Disclaimer](#creative-commons-warranties-disclaimer)

# SuperGreenBoards-301B

![SuperGreenLab](assets/SG-board-square-3.jpg?raw=true "SuperGreenLeds-301B")
First prototype of the SGB.301B family

SGB.301B are aluminium substrate led boards containing up to 288 Samsung's LM301B leds supergreenlab (https://supergreenlab.com/). This open hardware design is licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License.

Pull requests of relevant issues are warmly welcomed.

# SGB.301B Overview

* **LEDS** : up to 288 Samsung's [LM301B](https://www.samsung.com/led/lighting/mid-power-leds/3030-leds/lm301b/) 220 lm/W, CRI80 leds. Boards are setup with 2/3 2700K leds and 1/3 5000K leds for best grow and flowering performances. (spectum below)
* **ONBOARD LED drivers** (if applicable) : [AL8806MP8-13](https://www.diodes.com/assets/Datasheets/AL8806.pdf) buck step-down, up to 1.5A and 98% efficiency led driver.
* **POWER IN** : Standard 5*2.5mm Barrel/Jack or 3 pins JST-XH [S3B-XH-SM4-TB](http://www.jst-mfg.com/product/detail_e.php?series=277) or [screwless terminal block](https://www.metz-connect.com/us/system/files/productfiles/Data_sheet_SM99S01VBNN04G7_SM99S01VBNN04G7_OFF-031067R.pdf) (see each board specification)
* **DIMMER** : All Boards can be dimmed (see each board specification)
* **ADDITIONAL** : All boards have mouting holes compatible with VESA : 75x75mm, 100x100mm and additional M4 mounting holes on the sides.
* **THERMAL** : Boards are made from Aluminium Substrate panel for best thermal performances. Each boards is designed to be used without heatsink in standard ambient temperature.

**TODO** Add board spectrum

# Board specifications
 
## SGB 36.301B

* **LEDS** : 36 [LM301B](https://www.samsung.com/led/lighting/mid-power-leds/3030-leds/lm301b/) for 4K lumens total
* **ONBOARD LED drivers** : 1 
* **SIZE** : 130mmx110mm (5.1"x4.3")
* **CONNECTOR** : 3 pins JST-XH [S3B-XH-SM4-TB](http://www.jst-mfg.com/product/detail_e.php?series=277) for power and dimmer
* **POWER INPUT** : 24VDC/1A (Constant Voltage), Max Power : 20W. Designed to be powered by supergreenlab's [SGController](https://github.com/supergreenlab/SuperGreenController)
* **DIMMER** : 10V analog or PWM. Designed to be controlled by supergreenlab's [SGController]
* **MOUNTING HOLES** : VESA 75x75mm and 100x100m M4

## SGB 72.301B

* **LEDS** : 72 [LM301B](https://www.samsung.com/led/lighting/mid-power-leds/3030-leds/lm301b/) for 8K lumens total
* **ONBOARD LED drivers** : 2 (36 leds/driver) 
* **SIZE** : 250mmx130mm (9.8"x5.1")
* **CONNECTOR** : 3 pins JST-XH [S3B-XH-SM4-TB](http://www.jst-mfg.com/product/detail_e.php?series=277) for power and dimmer
* **POWER INPUT** : 24VDC/2A (Constant Voltage), Max Power : 40W. Designed to be powered by supergreenlab's [SGController](https://github.com/supergreenlab/SuperGreenController)
* **DIMMER** : 10V analog or PWM. Designed to be controlled by supergreenlab's [SGController](https://github.com/supergreenlab/SuperGreenController)
* **MOUNTING HOLES** : VESA 75x75mm and 100x100m M4, additionnal mounting holes on the side

## SGB 144.301B

* **LEDS** : 144 [LM301B](https://www.samsung.com/led/lighting/mid-power-leds/3030-leds/lm301b/) for 16K lumens total
* **ONBOARD LED drivers** : 4 (36 leds/driver) 
* **SIZE** : 250mmx230mm (9.8"x9")
* **CONNECTOR** : Standard 5*2.5mm Barrel/Jack for power and 3 pins JST-XH [S3B-XH-SM4-TB](http://www.jst-mfg.com/product/detail_e.php?series=277) for power and dimmer
* **POWER** : Input : 24VDC/5A (Constant Voltage Power supply : https://amzn.to/2DNSty4), Max Power : 80W.
* **DIMMER** : 10V analog or PWM. Designed to be controlled by supergreenlab's [SGController](https://github.com/supergreenlab/SuperGreenController)
* **MOUNTING HOLES** : VESA 75x75mm and 100x100m M4, VESA 200x200mm M6, additionnal mounting holes on the side

## SGB 288.301B

* **LEDS** : 288 [LM301B](https://www.samsung.com/led/lighting/mid-power-leds/3030-leds/lm301b/) for up to 32K total
* **SIZE** : 350mmx250mm (13.8"x9.8")
* **CONNECTORS** : [Screwless terminal block](https://www.metz-connect.com/us/system/files/productfiles/Data_sheet_SM99S01VBNN04G7_SM99S01VBNN04G7_OFF-031067R.pdf) 16-22AWG
* **POWER** : [Power supply guide](https://supergreenlab.com/sg-288301b-driver-guide)
* **MOUNTING HOLES** : VESA 75x75mm and 100x100m M4, VESA 200x200mm M6, additionnal mounting holes on the side

# License

This work is licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/3.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

# Creative Commons Warranties Disclaimer

UNLESS OTHERWISE MUTUALLY AGREED TO BY THE PARTIES IN WRITING, LICENSOR OFFERS THE WORK AS-IS AND MAKES NO REPRESENTATIONS OR WARRANTIES OF ANY KIND CONCERNING THE WORK, EXPRESS, IMPLIED, STATUTORY OR OTHERWISE, INCLUDING, WITHOUT LIMITATION, WARRANTIES OF TITLE, MERCHANTIBILITY, FITNESS FOR A PARTICULAR PURPOSE, NONINFRINGEMENT, OR THE ABSENCE OF LATENT OR OTHER DEFECTS, ACCURACY, OR THE PRESENCE OF ABSENCE OF ERRORS, WHETHER OR NOT DISCOVERABLE. SOME JURISDICTIONS DO NOT ALLOW THE EXCLUSION OF IMPLIED WARRANTIES, SO SUCH EXCLUSION MAY NOT APPLY TO YOU.
