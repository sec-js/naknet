# NAKNET
A proof of concept Centralized Botnet based on the botnet given by ![Aoyama](https://github.com/Leeon123/Aoyama) by ![Leeon123](https://github.com/Leeon123).

## Currently expanded functionality:
	DOOM tab opener	: Increases volume on clients and opens a url based on two settings: annoy and kill
	CMD exec	: Remote command execution that sends output from client to CNC and to the commander
	ARP Snoop	: Reads the ARP Table and returns the IP to the Commander should Port 22 be open.
	Brute Force SSH	: Attempts to brute force logins on a victim and returns results to Commander

```
 _   _   ___   _   __ _   _  _____ _____ 
| \ | | / _ \ | | / /| \ | ||  ___|_   _|
|  \| |/ /_\ \| |/ / |  \| || |__   | |  
| . ` ||  _  ||    \ | . ` ||  __|  | |  
| |\  || | | || |\  \| |\  || |___  | |  
\_| \_/\_| |_/\_| \_/\_| \_/\____/  \_/  
                                         
========================================
naknet@NAKNET:█
```

Use telnet into a known port(default is 1337) on the CNC server to access it.
