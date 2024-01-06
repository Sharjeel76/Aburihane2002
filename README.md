Install :
pkg update -y
pkg install -y root-repo 
pkg install -y git tsu python wpa-supplicant pixiewps 
iw openssl 
git clone --depth 1 https://github.com/drygdryg/Aburihane 
You need to run this command, if you want to hack wifi :
sudo python Aburihane/oneshot.py -i wlan0 --iface-down -K
