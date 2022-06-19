# install-arch-on-termux
## Intro
1. `pkg install wget openssl-tool proot tar -y && hash -r && wget https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/Installer/Arch/armhf/arch.sh && bash arch.sh`
2. `./start-arch.sh`
3. `chmod 755 ./additional && ./additional`
4. `pacman -Syu`

## Install Python
### Intro
1. `pacman -S python python-pip`

### Install Streamlit
1. `pacman -S gcc`
2. `pacman -S streamlit`
