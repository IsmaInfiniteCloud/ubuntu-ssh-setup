# ubuntu-ssh-setup
A guide to setting up and configuring the OpenSSH server on Ubuntu.
# Setting up OpenSSH Server on Ubuntu

## Install OpenSSH Server

******************************

sudo apt update
sudo apt install openssh-server


******************************

## Start SSH Server
Once installed, start the SSH service with:

******************************
 
sudo systemctl start ssh

******************************

## Enable SSH at Boot
If you want SSH to start automatically at boot, run:

******************************

sudo systemctl enable ssh

******************************

## Verify SSH Service Status
Check if the service is active with:

******************************
 
sudo systemctl status ssh

******************************

## Adjust Firewall Settings
If you have UFW enabled (Uncomplicated Firewall), allow SSH:

******************************
 
sudo ufw allow ssh

******************************
