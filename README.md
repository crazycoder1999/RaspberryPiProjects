# RaspberryPiProjects


## Safe Usb Key
### Requirements
You need a pi zero w.
0. install a fresh raspbian (I install the version of november 2017)

### Install
1. sudo apt-get install hostapd dnsmasq  nodejs
2. sudo dpkg -i --force-overwrite safeusbkey.deb
3. rm /etc/wpa_supplicant/wpa_supplicant.conf
4. sudo halt
5. plug the pendrive to pizero w
6. power on the pizero w
7. connect to wifi SafeUsbKey with password raspberry
8. open the browser to: http://192.168.0.1:8000/browse
