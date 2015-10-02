# PowerTowerRX

## Firmware

Use the type 7 (Brotronics PowerTowerRX) firmware image.

## BOM

The PowerTowerRX has three distinct features.  If your build doesn't
require all of them, you may omit them and save some time and effort.

### Core

The core radio operation.

* [C6, C12, C13 - 0603 1μF](http://www.digikey.com/product-detail/en/0/1276-1946-1-ND) [opt + C18]
* [C7, C8, C9  - 0603 0.1μF](http://www.digikey.com/product-detail/en/0/490-1532-1-ND/587771) [opt + C17, C19]
* [C14 - 0603 220nF](http://www.digikey.com/product-detail/en/0/587-1246-1-ND/0)
* [C15, C16 - 0805 12pF](http://www.digikey.com/product-detail/en/0/1276-1120-1-ND/3889206)
* [D1, D4, D6 - 0805 Schottky diode](http://www.digikey.com/product-detail/en/0/478-7802-1-ND) [opt + D5]
* [D2 - 0805 red LED](http://www.digikey.com/product-detail/en/0/160-1427-1-ND/386800) [opt + D8]
* [D3 - 0805 green LED](http://www.digikey.com/product-detail/en/0/160-1423-1-ND/386792)
* [LP1 - LP5907](http://www.digikey.com/product-detail/en/0/296-40365-1-ND)
* [R1, R8 - 0603 10kΩ](http://www.digikey.com/product-detail/en/0/RMCF0603FT10K0CT-ND) [opt + R3, R14]
* [R2 - 0603 2.2kΩ](http://www.digikey.com/product-detail/en/0/RMCF0603FT2K20CT-ND/1943011)
* [R4, R5, R6, R8, R10 - 0603 1kΩ](http://www.digikey.com/product-detail/en/0/P1.00KHCT-ND)
* [R6, R7 - 220Ω](http://www.digikey.com/product-detail/en/0/RMCF0603FT220RCT-ND)
* [U2 - RFM22SMD](http://www.ebay.com/itm/RFM22B-433Mhz-Wireless-Transceiver-from-HopeRF-/171728634731)
* [U3 - Atmega 328](http://www.digikey.com/product-detail/en/0/ATMEGA328P-AU-ND)
* [U5 - LFCN-490 (+)](http://www.minicircuits.com/products/filters_sm_low.shtml)
* [U7 - SOT23 NPN transistor](http://www.digikey.com/product-detail/en/0/ZXTN07012EFFCT-ND)
* [X1 - 16MHz xtal](http://www.digikey.com/product-detail/en/0/644-1049-1-ND/1128921)


### USB Port (optional)

* [C17, C19 - 0603 0.1μF](http://www.digikey.com/product-detail/en/0/490-1532-1-ND/587771)
* [C18 - 0603 1μF](http://www.digikey.com/product-detail/en/0/1276-1946-1-ND)
* [D5 - 0805 Schottky diode](http://www.digikey.com/product-detail/en/0/478-7802-1-ND)
* [R14 - 0603 10kΩ](http://www.digikey.com/product-detail/en/0/RMCF0603FT10K0CT-ND)
* [U9 - CP2102](http://www.digikey.com/product-detail/en/0/336-1160-1-ND)
* [U10 - USB Jack](http://www.digikey.com/product-detail/en/0/609-4050-1-ND)


### Backup Battery Management (optional)

* [C1 - 0603 4.7μF](http://www.digikey.com/product-detail/en/0/587-2786-1-ND)
* [D7 - 0805 blue LED](http://www.digikey.com/product-detail/en/0/160-1579-1-ND/564889)
* [D8 - 0805 red LED](http://www.digikey.com/product-detail/en/0/160-1427-1-ND/386800)
* [R11, R12, R13 - 0603 1.5kΩ](http://www.digikey.com/product-detail/en/0/RMCF0603FT1K50CT-ND/1943003)
* [R15 - 0603 4.7kΩ](http://www.digikey.com/product-detail/en/0/P4.70KHCT-ND)
* [R3 - 0603 10kΩ](http://www.digikey.com/product-detail/en/0/RMCF0603FT10K0CT-ND)
* [U6 - BQ24075](http://www.digikey.com/product-detail/en/0/296-23840-1-ND)

** Board

![Top](http://i.imgur.com/0YoKvxP.png)

![Bottom](http://i.imgur.com/eQBjqIf.png)

# License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

