# gswitch-gui-lp

Hello!

This is how you build and install the debian package for the gswitch-gui application:

git clone https://github.com/karli-sjoberg/gswitch-gui-lp
cd gswitch-gui-lp/gswitch-gui
dpkg-buildpackage
cd ..
sudo dpkg -i *.deb
rm -rf gswitch*
