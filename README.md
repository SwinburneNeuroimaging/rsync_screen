# rsync_screen

Usage: rsync_screen SOURCEDIR TARGETHOST:TARGETDIR 

rsync_screen copies folders using rsync, with the transfer continuing in the background also in case of network disruption. 
It also automatically saves the rsync log in the user's home directory, and prints the exit status at the end
