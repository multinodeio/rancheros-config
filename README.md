# rancheros-config

# Install cmd
sudo ros install -c cloud-config.yml -d /dev/nvme0d1 -p /dev/nvme0d1p1

# Format HDD
sudo /sbin/mkfs.ext4 /dev/sda

# Serial Number
sudo apt install dmidecode

sudo /usr/sbin/dmidecode -s system-serial-number

# Docker Volumes

docker volume create geth