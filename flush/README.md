I2P-enabled Flush
=================

First, download and install [libtorrent-rasterbar i2p](../libtorrent/)

Download and extract Flush i2p, open a terminal in the extracted folder and type:

    ./configure && make

If you receive a boost error in configure , try

    ./configure --with-boost-libdir=/usr/lib/i386-linux-gnu
or

    ./configure --with-boost-libdir=/usr/lib/x86-64-linux-gnu

depending your system

If you want install Flush i2p, type: sudo make install (if your system use sudo), or install Flush as root user


Start Flush, go to 'Preferences'->Daemon->Network->Misc and uncheck all cases in the 'extra' part (DHT, UPnP, Peerexchange etc....)

Open the tab 'I2P', check the box 'Enable I2P /SAM Bridge', adjust SAM settings and apply

Your done.


Don't forget to enable SAM in your router console http://127.0.0.1:7657/configclients before starting Flush, for sure! 