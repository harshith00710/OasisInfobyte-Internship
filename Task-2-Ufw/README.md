#Basic Firewall Configuration with UFW

##Objective
Configure a basic firewall using UFW on Linux.

##Steps Performed
Installed UFW.
Allowed SSH traffic.
Denied HTTP traffic.
Enabled Firewall.
Checked Firewall status.

##Commands Used
'''bash
sudo apt install ufw -y
sudo ufw allow ssh
sudo ufw deny http
sudo ufw enable
sudo ufw status numbered

##Result
UFW firewall was successfully installed and configured.SSH traffic was allowed,HTTP traffic was blocked,and the Firewall was enabled.The firewall status confirmed.

##Conclusion
UFW provides a simple and effective method for managing firewall rules and protecting network resources.
