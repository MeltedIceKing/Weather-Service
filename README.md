# Weather-Service
weather service with linux systemd

**Welcome to Weather Service!**
To run this file please follow the following instructions:
- create a bin directory in your home folder if non-existent
- run > mkdir bin
- Put the weather file in this directory

Weather Service and Weather timer
- save files weather.service and weather.timer into your home directory
- if systemd is your init then proceed with the following commands:
- sudo cp weather.service /etc/systemd/system/weather.service
- sudo cp weather.timer /etc/systemd/system/weather.timer
- sudo systemctl daemon-reload
- sudo systemctl enable --now weather.timer

***Congratulations! You have succesfully Installed this service!***
