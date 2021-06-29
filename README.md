# IPTV - DVBLAST/DVBAPPS/UDPXY
Local Central Queensland TV Over Multicast TCP - Using an RTL SDR

To Do List

Comfirm Channels Are working

Get SAP Server Working across the network

Build - Auto Start All Script

# Basic Install - Start (Ubuntu/Debian)

This installs the Basic packages that you will need to get this working

Sudo apt-get update && sudo apt-get upgrade -y

Sudo apt-get install rtl-sdr

Sudo apt-get install dvblast

Sudo apt-Get install dvb-apps

Sudo apt-get install git (if you don't have it already)

UPDPXY Setup:

wget http://udpxy.com/download/udpxy/udpxy-src.tar.gz

tar xvf udpxy-src.tar.gz

cd udpxy-src.tar.gz

make install

git clone https://github.com/BenJaminL11/IPTV

cd

cd IPTV

sudo chmod +x (bash script name here) example - sudo chmod +x Start-ABC.sh

bash script name example - sudo bash Start-ABC.sh
