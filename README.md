# Buliding-Notepadqq-from-source
This has some tweaks, which notepadqq offical repository doesn't have and since the 2.0.0 build version is trash when installed directly or from Snap.


``1. git clone --recursive https://github.com/notepadqq/notepadqq.git``
``2. cd notepadqq``

The README is a bit out of date regarding dependencies. try this instead:
sudo apt-get install qtbase5-dev qtchooser qt5-qmake qttools5-dev-tools qtwebengine5-dev libqt5websockets5-dev libqt5svg5 libqt5svg5-dev libuchardet-dev pkg-config

``3. ./configure --prefix /usr``
``4. sudo make install``
