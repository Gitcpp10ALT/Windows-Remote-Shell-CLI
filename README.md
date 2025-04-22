# Windows/Linux-Remote-Shell-CLI
Windows Remote Shell is a remote shell built off the NotSSH remote shell! It uses the ArgParse library.

# Installation
1. Download wrs.exe.
2. Copy the file and paste it into a folder you want it to stay in.
3. Copy the directory.
4. Go to the windows search box and search "edit the system enviroment variables" and click on the first thing that shows.
5. Once in, go to Advanced, then Enviroment Variables.
6. Go to system variables then double-click.
7. Click new then paste the copied path there.
8. Click OK until all those windows close.
9. Go to PowerShell or Command Prompt
10. Now you can use the wrs command!

**NOTE: If the full output doesn't load, press enter until you see "Shell ~ C:\The\Current\Dir\You\Are\In"**
# Usage
wrs -ip [IP address] -p [PORT number] -c [connect] -l [listen] -f [listen forever flag]
# Linux Installation (Debian)
1. Go to Linux Packages and download one of the files.
2. Go to the directory where downloaded and open the terminal there.
3. Run the command "sudo dpkg -i NotSSH-server_debian.deb/lrs-package.deb".
4. Go to the directory /usr/local/bin and the install will be there.
5. To execute, run ./ <name_of_install>
