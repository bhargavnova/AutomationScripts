# Linux 
### Bash Script to change mac address in linux
How to Use :
1. Change permission to Execute \
	`sudo chmod +x change-mac`
2. Add this file to ~/.bashrc file \
	`nano ~/.bashrc` \
	Now Add This line \
	`source /path/to/change-mac`
3. `source ~/.bashrc` or restart the terminal
4. Run by \
	`change-mac` | will change the mac to the one, which is written in script \
	`change-mac 00:11:22:BD:DC:52` | will change to user provided mac address
