# Chemise
Chemise - A new way of interacting with your smartphone

## Getting Started
### 1. Raspberrypi Zero W Setup
1. Install [python-firebase](https://pypi.org/project/python-firebase/)
2. Download chemiseFirebase.py to your desired location in your Raspberrypi Zero W.
3. Make sure your have Wait for Network at Boot setting set as ON on your Raspberrypi Zero W. You can do so by opening the setting pannel in GUI mode (via desktop) or using the terminal (via desktop or SSH)
```
$ sudo rpi-config
```
4. Open terminal on your Raspberyypi Zero W via desktop or SSH
```
$ sudo nano /etc/rc.local
```
Scroll down to just before *exit 0* and write the following command to execute the python script chemiseFirebase.py on boot everytime.
```
python <location_of_file>/chemiseFirebase.py &
```
eg: ``` python /home/pi/chemiseFirebase.py & ```

### 2. Download the Chemise companion app on your Android Phone
Download the [Chemise companion app](https://github.com/Akkk1881/ChemiseApp) on your android smartphone while you want to control via your t-shirt.

## Made by 
**Noisy Boys**
**Group T-24**
**Website: https://chemise.netlify.com/ **
#### Members:

1. Ayaan Kakkar (2018028)
2. Daksh Thapar (2018137)
3. Samik Prakash (2018090)
4. Shashwat Aggarwal (2018097)









