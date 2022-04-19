### Description
  - This is a script that installs Raspberry Pi OS Lite (64-bit) just the way I like it

# Instructions
  - Install Raspberry Pi OS Lite (64-bit) onto your SD card with Raspberry Pi Imager
  - Once installed, boot up the pi and set the keyboard layout to "English (US), then set username as "pi"

## 1) Set up the pi by running the following commands
  - sudo raspi-config
    - set up WiFi through "System Options"
    - enable SSH through "Interface Options"
    - select "Finish"
  - sudo apt update && sudo apt full-upgrade
  - sudo apt install git
  - git clone https://github.com/soberhippie3/pi
  - chmod a+x /home/pi/pi/install
  - sudo apt update
  - /home/pi/pi/install

## 2) Read files on desktop

## 3) Run config script
  - chmod a+x /home/pi/pi/config
  - sudo apt update
  - /home/pi/pi/config
