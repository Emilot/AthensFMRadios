**Athens (Greece) FM Radios pls files**

These pls files were heavily based on the following m3u file by [dennmtr](https://github.com/dennmtr):

https://gist.github.com/dennmtr/ac14e66adca47e5f7d60


Note: If you didn't find a specific radio this means:

1. I forgot it
2. I did not find a usable http stream
3. It's a religious radio station

For 1 and 2 and in cases where an existing pls is not functional, feel free to open issues, fork and send back etc.. 


In order to use these radios with Archphile, you will need to use the included script (arf.sh):

	wget https://raw.githubusercontent.com/archphile/AthensFMRadios/master/archphile-script/arf.sh
	chmod +x arf.sh
	./arf.sh

PS. These files were **created for real people** that want to listen to the radio and not for "audiophiles" (who gives a fuck about them anyway?)! 


**NOTE:** **0.99.73** is missing **unzip** which is required by **arf** script. In order to install unzip, edit mirrorlist:

	nano /etc/pacman.d/mirrorlist
	
enable the first server line, save and then install unzip command:

	pacman -Sy unzip
	
Now you are ready to follow the initial procedure.