Script to to place Authentication by User and Password in the Squid distribution. 

DEBIAN UBUNTU
apt-get install dos2unix -y
apt-get install figlet

CENT OS
yum install dos2unix -y


wget -O /bin/proxy http://raw.githubusercontent.com/wilking2k7/Elite/master/proxy && chmod +x /bin/proxy && dos2unix /bin/proxy && proxy
