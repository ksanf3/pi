# Install Raspberry Pi OS Lite with Raspberry Pi Imager

## Default Login
- Username: pi
- Password: raspberry

## Setup Instructions
- After logging in, run "sudo raspi-config" to set up WiFi through "System Options"
- sudo apt update && sudo apt full-upgrade
- sudo apt install git
- git clone https://github.com/soberhippie3/pi

## Run install script  
- chmod a+x /home/pi/pi/install
- sudo apt update (to refresh sudo timeout)
- /home/pi/pi/install

## Run config script
- chmod a+x /home/pi/pi/config
- sudo apt update (to refresh sudo timeout)
- /home/pi/pi/config

## Configuration
- In display settings, disable compositor on startup
