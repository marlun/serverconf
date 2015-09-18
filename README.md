# Configuration files for my VPS servers

Start by getting this source code:

	mkdir ~/src
	git clone git@github.com:marlun/serverconf.git ~/src/serverconf

## E-mail

Get the Offlineimap source:

	git clone https://github.com/OfflineIMAP/offlineimap.git ~/src/offlineimap

Install the configuration file:

	ln -s ~/src/serverconf/offlineimaprc ~/.config/offlineimap/config

Done, you can now sync:

	cd ~/src/offlineimap && ./offlineimap.py
