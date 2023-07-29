# ubuntu-ssh-setup
A guide to setting up and configuring the OpenSSH server on Ubuntu.
# Setting up OpenSSH Server on Ubuntu

## Install OpenSSH Server

0000000000000000000000000

sudo apt update
sudo apt install openssh-server

Start SSH Server
Once installed, start the SSH service with:

00000000000000000000000000
 
sudo systemctl start ssh

00000000000000000000000000

Enable SSH at Boot
If you want SSH to start automatically at boot, run:

0000000000000000000000000

sudo systemctl enable ssh

0000000000000000000000000

Verify SSH Service Status
Check if the service is active with:

0000000000000000000000000
 
sudo systemctl status ssh

0000000000000000000000000

Adjust Firewall Settings
If you have UFW enabled (Uncomplicated Firewall), allow SSH:

0000000000000000000000000
 
sudo ufw allow ssh
0000000000000000000000000
