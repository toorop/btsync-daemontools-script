daemaontool script to supervise (watch & relaunch if needed) btsync daemon

## How to use
1. Install djb [daemontools](http://cr.yp.to/daemontools.html)
On Ubuntu/debian :
	apt-get install daemontools

2. Edit run script and change :
	BTSYNC -> btsync bin path
	CONFIGFILE -> btsync config file
	USER -> user used to run btsync daemon

3. Make a symlink from your run script path to your daemontools services path
	chmod +x run
	ln -s /home/toorop/btsync/service /etc/service/btsync 

4. Enjoy