https://wiki.alpinelinux.org/wiki/Raspberry_Pi

- Unpack the last folder in the tar.gz to SD card
- Switch on RPI
- I want static IP 192.168.1.31 on my RPI so:
  - Network interface of RPI is off so it needs to be turned on
  - `ip link set eth0 up`
  - And then restart should suffice
  - `/etc/init.d/networking restart`
  
