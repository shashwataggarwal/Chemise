# Chemise
Chemise - A new way of interacting with your smartphone

## Getting Started
### Raspberrypi Zero W Setup
1. Install [python-firebase](https://pypi.org/project/python-firebase/)
2. Download chemiseFirebase.py to your desired location in your Raspberrypi Zero W.
3. Make sure your have Wait for Network at Boot setting set as ON on your Raspberrypi Zero W. You can do so by opening the setting pannel in GUI mode (via desktop) or using the terminal (via desktop or SSH)
```
$ sudo rpi-config
```
3. Open terminal on your Raspberyypi Zero W via desktop or SSH
```
$ sudo nano /etc/rc.local
```
Scroll down to just before *exit 0* and write the following command to execute the python script chemiseFirebase.py on boot everytime.
```
python <location_of_file>/chemiseFirebase.py &
```
eg: ``` python /home/pi/chemiseFirebase.py & ```



