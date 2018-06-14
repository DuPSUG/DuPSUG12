# Steps to install and run PowerShell

### Install prerequisites 
	sudo apt-get install libunwind8
### Grab the latest tar.gz
	wget https://github.com/PowerShell/PowerShell/releases/download/v6.0.2/powershell-6.0.2-linux-arm32.tar.gz

	cp /home/pi/Documents/Backup/powershell-6.0.2-linux-arm32.tar.gz /home/pi/Documents/Presentation/


### Create a folder and extract PowerShell into it
	mkdir /home/pi/Documents/Presentation/powershell

	tar -xvf /home/pi/Documents/Presentation/powershell-6.0.2-linux-arm32.tar.gz -C /home/pi/Documents/Presentation/powershell 

### Start PowerShell
	/home/pi/Documents/Presentation/powershell/pwsh

### allow powershell to execute from any path
	sudo ln -s /home/pi/Documents/Presentation/powershell/pwsh /usr/bin/pwsh
