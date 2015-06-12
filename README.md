Debian Dynamic Message of the Day with Updates
================================================

# install figlet to enable ASCII art
sudo apt-get install figlet

# create directory
sudo git clone https://github.com/mckinnon81/dynamic-motd.git /etc/update-motd.d

# change to new directory
cd /etc/update-motd.d/

# remove MOTD file
sudo rm -frv /etc/motd

# symlink dynamic MOTD file
sudo ln -s /var/run/motd /etc/motd

# Reboot System for settings to take effect

