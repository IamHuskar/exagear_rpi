# exgear_rpi

sudo apt-get update
sudo apt-get install -y bash coreutils findutils curl binfmt-support cron

sudo dpkg -i armhf/*.deb
sudo dpkg -i arm64/*.deb

sudo dpkg -i exagear-guest-debian-9_3428_all.deb


deb http://archive.debian.org/debian stretch main


build main.cc 

//run
/opt/exagear/bin/ubt_x32a32_al --path-prefix /opt/exagear/images/debian-9 --vpaths-list /opt/exagear/images/debian-9/.exagear/vpaths-list --opaths-list /opt/exagear/images/debian-9/.exagear/opaths-list --use-binfmt_misc --hifd-base 1048575 -f /home/pi/main -- ./main
