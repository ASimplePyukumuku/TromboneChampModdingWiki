# Mocha

## SD Preparation {docsify-ignore}

We will now place the required CFW files and some additional homebrew files on the SD Card.

?> **Notice**
    Your SD Card will need to be formatted as FAT32. If your SD Card is not formatted to FAT32, use [GUIFormat](http://www.ridgecrop.demon.co.uk/index.htm?guiformat.htm) with 32k (32768) Allocation unit size to format it.

### What You Need

- The Mocha <a href="docs/files/config.ini" download>config</a>
- The latest release of [Homebrew Launcher Installer](https://github.com/wiiu-env/homebrew_launcher_installer/releases/latest)
  - You will need to download the `payload.zip` file.
- The 1.4 release of [The Homebrew Launcher](https://github.com/dimok789/homebrew_launcher/releases/tag/1.4)
  - You will need to download the v1.4 `homebrew_launcher.v1.4.zip` release of The Homebrew Launcher
- The latest release of [WUP Installer GX2](http://wiiubru.com/appstore/zips/wup_installer_gx2.zip)
- The latest release of [Wii U NAND Dumper](https://github.com/koolkdev/wiiu-nanddumper/releases/latest)
- The latest release of the [Homebrew App Store](https://github.com/vgmoose/hbas/releases/latest)
  - You will need to download the `wiiu-extracttosd.zip` file.
- The latest release of [Mocha](https://www.wiiubru.com/appstore/zips/mocha.zip)

### Instructions

?> **Notice**
    The info.json and manifest.install files are not needed for the modding process and therefore can be deleted.
1. Insert your Wii U's SD Card into your PC
1. Extract the `wup_installer_gx2.zip` file to the root of your SD Card
1. Extract the `nanddumper.zip` file to the root of your SD Card
1. Extract the `wiiu-extracttosd.zip` file to the root of your SD Card
1. Extract the `homebrew_launcher.v.1.4.zip` to the root of your SD Card
1. Extract the `mocha.zip` file to the root of your SD Card
1. Copy the `config.ini` file to the `/wiiu/apps/mocha` folder on your SD Card
1. Copy the `payload.elf` from the `payload.zip` to the `wiiu` folder on your SD Card