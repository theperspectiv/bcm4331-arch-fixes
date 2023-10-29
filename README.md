macbook pro 9,2
BCM4331

offline fix:
sudo mkdir /lib/firmware/b43 && sudo cp ./b43/*  /lib/firmware/b43 && sudo modprobe -rv b43 && sudo modprobe -v b43

aur fix:
install kernel-appropriate "linux-headers"
then install "broadcom-wl-dkms"
