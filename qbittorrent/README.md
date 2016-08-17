I2P-enabled qBittorrent
=======================


Download and extract qBittorrent, open a terminal in the extracted folder and enter: ./configure && make

Your builded soft in now located in ./src

If you want install, remove previous installed version and enter: make install as root user in your terminal

Start qBittorrent, open settings, i2p, adjust router address and port and apply. Go to network tab and uncheck all checkbox related to DHT, Pex, ... It's all!


If you change settings many time in one session, you will receive a beautifull "core dump", try to be cool with settings! 