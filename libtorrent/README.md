libtorrent-rasterbar
====================

Arvid, from libtorrent-rasterbar has made a excellent work, writing a generic implementation of SAM library for libtorrent. Now, SAM features aren't totally implemented, but libtorrent work fine with I2P


I rewritten a part to load our compact announce format. I will rewrite pex and dht in future realeases


Remove all already installed version of libtorrent in your system

Download, extract and read the README to compile and install


If you try to build with ./compile, don't forget to compile with python binding (for Deluge) like this:

    ./configure --enable-python-binding && make && sudo make install

If you receive an error from boost lib, try with:

    ./compile --with-boost-libdir=/usr/lib/i386-linux-gnu --enable-python-binding && make && sudo make install

or

    ./configure --with-boost-libdir=/usr/lib/x86-64-linux-gnu --enable-python-binding && make && sudo make install

depending if your OS is 32 or 64bit


More infos can be found here: [libtorrent-rasterbar](http://www.rasterbar.com/products/libtorrent/) and here [Deluge libtorrent](http://dev.deluge-torrent.org/wiki/Building/libtorrent)
