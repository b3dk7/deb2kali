# deb2kali
A Script to Convert Debian 9 Linux into Kali Linux

Usage (as root):

    apt-get update && apt-get -y install git
    cd /opt
    git clone https://github.com/Wh1t3Rh1n0/deb2kali
    bash deb2kali/deb2kali.sh

Afterward, you can either install individual tools one by one or install them all with:

    apt-get -y install kali-linux-full
