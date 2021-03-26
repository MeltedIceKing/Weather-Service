# Weather Service with Linux systemd

**Welcome to Weather Service!**
<br>
To run this file please follow the following instructions:

Weather Script
1. create a bin directory in your home folder if non-existent
2. run > mkdir bin
3. Put the weather file in this directory

Weather Service and Weather timer
1. save files weather.service and weather.timer into your home directory
2. if systemd is your init then proceed with the following commands:
3. sudo cp weather.service /etc/systemd/system/weather.service
4. sudo cp weather.timer /etc/systemd/system/weather.timer
5. sudo systemctl daemon-reload
6. sudo systemctl enable --now weather.timer

***Congratulations! You have succesfully Installed this service!***
