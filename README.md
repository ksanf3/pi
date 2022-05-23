### Description
  - This is a script that installs Raspberry Pi OS Lite (64-bit) just the way I like it

# Instructions
  - Install Raspberry Pi OS Lite (64-bit) onto your SD card with Raspberry Pi Imager
  - Once installed, boot up the pi and set the keyboard layout and set your username as "pi"

## 1) Set up the pi by running the following commands
  1. `sudo raspi-config`
    - set up WiFi through "System Options"
    - enable SSH through "Interface Options"
    - set locale & timezone through "Localisation Options"
    - select "Finish"
  2. `sudo apt update && sudo apt full-upgrade`
  3. `sudo apt install git`
  4. `git clone https://github.com/ksanf3/pi`
  5. `chmod +x /home/pi/pi/install`
  6. `sudo apt update`
  7. `/home/pi/pi/install`
  8. once the script finishes, run `sudo raspi-config`
    - enable boot to desktop through "System Options"

## 2) Read files on desktop

## 3) Run config script
  - `chmod a+x /home/pi/pi/config`
  - `sudo apt update`
  - `/home/pi/pi/config`
