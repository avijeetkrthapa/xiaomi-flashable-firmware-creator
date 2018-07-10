# On Device Xiaomi Flashable Firmware Creator

You can easily create flashable firmware zip from Recovery MIUI, in your Android device

## Instructions
  - Install Termux from F-Droid or Playstore
  - Give storage permissions to Termux from Android app settings
  - Open Termux and run the below codes
      - update Termux packages
       `pkg upgrade`
      - install wget package to retrieve this script from Github
       `pkg install wget`
      - retrive the script, shorten the script name to keep the fingers happy and add required permissions
      > `
      wget -O odxffc.sh https://raw.githubusercontent.com/avijeetkrthapa/xiaomi-flashable-firmware-creator/On-Device-Xiaomi-Flashable-Firmware-Creator/create_flashable_firmware.sh && chmod 700 odxffc.sh
      `
  - Now you can extract firmware from MIUI recovery ROMS.
   `./odxffc.sh [ROM zipfile]`
   
  example: `./odxffc.sh /sdcard/Download/miui_HMNote4XGlobal_V9.2.1.0.NCFMIEK_095a79e80a_7.0.zip`

## Tip:
  - Use a file manager like ES File Explorer or MiXplorer to easily copy the path of the filename and paste it in Termux
  
