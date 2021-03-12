# MKS-TFT28-for-JGAurora-A5
MKS-TFT28 for JGAurora A5

- - -

**Current firmware version: V3.0.6**

and current UI:

![MKS-TFT28-LOGO.jpg](https://github.com/frolbel/MKS-TFT28-for-JGAurora-A5/blob/main/MKS-TFT28-UI/MY-WIN8-Tiles/MKS-TFT28-LOGO.jpg)


## Updating firmware

According to the content that needs to be updated, copy the following file to the SD card from [MKS-TFT28-SD](https://github.com/frolbel/MKS-TFT28-for-JGAurora-A5/tree/main/MKS-TFT28-SD)([JGAuroraA5-TFT28-VX..X.zip](https://github.com/frolbel/MKS-TFT28-for-JGAurora-A5/releases))folder:

- update the config file：mks_config.txt  
- update images：         mks_pic  
- update font：           mks_font  
- update TFT firmware：   mkstft28.bin  
- update Wifi firmware：  MksWifi.bin  

## Note

The repository contains the following:

- [MKS-GEN_L](https://github.com/makerbase-mks/MKS-GEN_L/tree/87f95dc5099278dc6b025fe3fcc2ff7f64c200f2);  
- [MKS-Power-Control](https://github.com/makerbase-mks/MKS-Power-Control/tree/57d559e5fd70b217e29de253b9fcf71db54e3478);  
- [MKS-TFT28-SD](https://github.com/frolbel/MKS-TFT28-for-JGAurora-A5/tree/main/MKS-TFT28-SD) - SD card content;  
- [MKS-TFT28-Source](https://github.com/makerbase-mks/MKS-TFT28-32-Firmware/tree/e00edf58c4442d24cfb39119bd5cc32b5575ffb1);  
- [MKS-TFT28-UI](https://github.com/frolbel/MKS-TFT28-for-JGAurora-A5/tree/main/MKS-TFT28-UI) - current UI elements (tiles, etc.);  
- [MKS-TFT-Releases](https://github.com/makerbase-mks/MKS-TFT/tree/eed5a6e1aae4564181d53524c7f54a56a7cdc777);  
- [MKS-WIFI](https://github.com/makerbase-mks/MKS-WIFI/tree/fc1e671eb5e11ab2283b81980bd70c745e7f08f4);  
- [MKS-WIFI-CuraPlugin](https://github.com/makerbase-mks/mks-wifi-plugin/tree/87df6145129c39b1a1a4725bc33b44591b60314f).  

SD card content [MKS-TFT28-SD](https://github.com/frolbel/MKS-TFT28-for-JGAurora-A5/tree/main/MKS-TFT28-SD) is prepared based on this:  
[.\MKS-TFT-Releases\MKS-TFT2.8-3.2\TFT28_32_v3.0.6 Release file.rar\TFT28_32_v3.0.6 Release file\Examples\Classic_En_Win8](https://raw.githubusercontent.com/makerbase-mks/MKS-TFT/eed5a6e1aae4564181d53524c7f54a56a7cdc777/MKS-TFT2.8-3.2/TFT28_32_v3.0.6%20Release%20file.rar)

## History of firmware changes

The firmware of V3.0.4 modified content:
- Added babystep adjustment buttons to the "More" screen during printing.

The firmware of V3.0.5 modified content:
- Fix the problem that the babystep adjustment value is too large.

The firmware of V3.0.6 modified content:
- Add the function of mks ups.
