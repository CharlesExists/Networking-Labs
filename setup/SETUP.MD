
# Ubuntu VM Setup Notes

## VM Specs
- OS: Ubuntu 22.04 LTS
- RAM: 2 GB
- CPU: 2 cores
- Disk: 20 GB (dynamic)
- Network: Bridged Adapter

## Software Installed
- net-tools (`ifconfig`, `netstat`)
- openssh-server (for SSH access)
- git
- curl, wget

## Setup Steps
sudo apt update && sudo apt upgrade -y
sudo apt install net-tools openssh-server git curl wget -y
