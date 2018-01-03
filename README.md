# mac_spoof
### Written by Yoji Watanabe - January 3rd, 2018
_mac\_spoof_ is a small shell script that lets users spoof their MAC address on newer macOS operating systems. Tested on macOS High Sierra v10.13.1.
***


#### Installing:

1. Move the _mac\_spoof_ file to `usr/local/bin` or desired location.

2. Give _mac\_spoof_ permission to run as an executable shell script with:

	```
	sudo chmod u+x mac_spoof
	```

3. (Optional) Make an alias to the script by adding the following line to `.bash_profile` to make script executable with only the command `mac_spoof` given to the Terminal:
	```
	alias mac_spoof=". mac_spoof"
	```

#### Usage:

To change your MAC address, simply run ```mac_spoof``` or ```. mac_spoof``` (depending on your installation). Take note of the initial MAC address if you wish to revert back to your original MAC address without restarting your computer.

To revert back to your initial MAC address (or use a custom MAC address), run ```mac_spoof <MAC address>``` substituting MAC address with the address noted earlier. In the case where the original address cannot be retrieved, restart your computer.


#### Disclaimer:

This script is for educational purposes only. The author, Yoji Watanabe, is not responsible for the use of this script, repository, or any information contained inside it. Any action the user takes with this script (or any information) in it is solely the user's responsibility. *Use at your own risk.*