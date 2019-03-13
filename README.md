# Configure Teamviewer in Manjaro Linux

Instructions for configure Teamviewer in manjaro linux

![](header.gif)

## Installation

Manjaro:

```sh
Open a console:
sudo yaourt -S teamviewer
sudo touch /var/run/teamviewerd.pid
sudo teamviewer --daemon restart
#start daemon when reboot
sudo teamviewer daemon enable
sudo systemctl enable teamviewerd.service

```

## Meta

César R. Cid Méndez – [@YourTwitter](https://twitter.com/skypce) – skypce@gmail.com


