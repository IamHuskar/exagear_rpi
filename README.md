# exagear_rpi

sudo apt-get update
sudo apt-get install -y bash coreutils findutils curl binfmt-support cron

sudo dpkg -i armhf/*.deb
sudo dpkg -i arm64/*.deb

sudo dpkg -i exagear-guest-debian-9_3428_all.deb


deb http://archive.debian.org/debian stretch main
