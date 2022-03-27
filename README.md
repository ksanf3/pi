# pi

## Default Login
- Username: pi
- Password: raspberry

## Setup Instructions
- After logging in, run "sudo raspi-config" to set up WiFi through "System Options". Under "Localisation Options", set Locale to "en_US.UTF-8", set 
- Update the system with "sudo apt update && sudo apt full-upgrade"
- Install git and clone the repo with "git clone https://github.com/soberhippie3/pi"

## Run install script  
- chmod a+x /home/pi/pi/install
- sudo apt update (to refresh sudo timeout)
- /home/pi/pi/install

## Run config script
- chmod a+x /home/pi/pi/config
- sudo apt update (to refresh sudo timeout)
- /home/pi/pi/config
