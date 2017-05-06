# Unattended-LAMP-and-Apps

All files done for a Sys Admin class project
The setup of the server was done on a fresh Ubuntu 16.04 droplet.

These files I have uploaded show various web apps being downloaded, preseed, and finally setup. 
The goal of each script is to run them, and not have to install via a browser.
The to run, chmod +x and run as sudo, the order for running is as follows...
1) Initial_Install
2) Apache_SSL
3) ... Any App script afterwards

There were several methods done to acheive non-browser installs on the apps.
1) use curl to insert the correct information
2) run an php install script from the command lin
3) have a preconfigured file that will supersede the default install file (e.g. Sugar)

