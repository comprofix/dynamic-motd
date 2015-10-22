Debian Dynamic Message of the Day with Updates
================================================

# Installaion

  * sudo apt-get install figlet
  * sudo git clone https://github.com/mckinnon81/dynamic-motd.git /etc/update-motd.d
  * cd /etc/update-motd.d/
  * sudo rm -frv /etc/motd
  * sudo ln -s /var/run/motd /etc/motd
  * Reboot System for settings to take effect
