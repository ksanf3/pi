# Instructions
  - Install Raspberry Pi OS Lite (64-bit) onto your SD card with Raspberry Pi Imager
  - Once installed, boot up the pi and login

## Default Login
  - Username: pi
  - Password: raspberry

## Set up the pi by running the following commands
  - sudo raspi-config
    - set up WiFi through "System Options"
    - select "Finish"
  - sudo apt update && sudo apt full-upgrade

### Run install script
  - sudo apt install git
  - git clone https://github.com/soberhippie3/pi
  - chmod a+x /home/pi/pi/install
  - sudo apt update (to refresh sudo timeout)
  - /home/pi/pi/install

## Read files on desktop

## Run config script
  - chmod a+x /home/pi/pi/config
  - sudo apt update (to refresh sudo timeout)
  - /home/pi/pi/config
