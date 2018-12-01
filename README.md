# gswitch-gui-deb

Hello!

This is how you build and install the debian package for the gswitch-gui application:

git clone https://github.com/karli-sjoberg/gswitch-gui-deb</br>
cd gswitch-gui-deb/gswitch-gui</br>
dpkg-buildpackage</br>
cd ..</br>
sudo dpkg -i \*.deb</br>
rm -rf gswitch\*</br>
