# CBonsai
Grow a bonsai tree in your terminal :)

Project home page: https://gitlab.com/jallbrit/cbonsai

### Installation
Simple installation (precompiled)
```
sudo apt-get install libncurses-dev -y
wget -O cbonsai.deb https://github.com/chunky-milk/pi-bashscripts-files/raw/main/cbonsai/cbonsai_20210310-1_armhf.deb
sudo apt --fix-broken -y install ./cbonsai.deb
rm cbonsai.deb
```

### To compile:
```
sudo apt-get install libncurses-dev apt-transport-https wget -y
git clone https://gitlab.com/jallbrit/cbonsai
cd cbonsai

# Install for this user
make install PREFIX=~/.local

# Install for all users
sudo make install
```
