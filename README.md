# Diablo II • Median XL • Linux
First of all I would like to thank the Median XL team for the great work! This zenity shell script downloads the latest Median XL mod and save this files locally. After that you can simple patch Diablo II with this script to work with the latest Median XL version. The patch also includes Sven's glide wrapper.

![d2launcher main](https://raw.githubusercontent.com/murkl/d2launcher/master/screenshots/main.png)
![d2launcher patches](https://raw.githubusercontent.com/murkl/d2launcher/master/screenshots/patches.png)


**Download latest version:** [d2launcher-1.0.3.tar.gz](https://github.com/murkl/d2launcher/releases/download/1.0.3/d2launcher-1.0.3.tar.gz)

## More features
* Median XL version management
* Includes Sven's Glide wrapper
* Wineprefix for Diablo II
* Userconfig
* Full conflict management

## Dependencies
```
sudo apt install -y zenity wine-stable p7zip jq
```

## Run the script
Simple execute the script directly from file manager. All available features are accessible from zenity gui!

Or you can execute d2launcher from command line:
```
./d2launcher
```
