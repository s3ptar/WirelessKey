lokaler Server mit UbunutServer der als Tastatur eingabe dient. 
qt-py-esp32-S2 als remote tastatur

[QTPy](https://learn.adafruit.com/adafruit-qt-py-esp32-s2/overview)


# Server installation
Ubuntu24.04
  - remove hostapd + dnsmasq
  - install network-manager + wireless-tools
  - install docker
    - add mosquitto
    - add node red
    - add nginx
  - add wifi interface in nmtui and create an Hotspot
