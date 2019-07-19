# JETSON-npm-Install
commando nmp Install Jetson Nano Ubuntu 18.04.2 LTS


Ubuntu Server 18.04 Node.js and npm install

sudo apt remove --purge nodejs npm
sudo apt clean
sudo apt autoclean
sudo apt install -f
sudo apt autoremove

Find the latest version at https://github.com/nodesource/distributions#debinstall Latest version 10.x now

sudo apt install curl
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
sudo apt-get install -y nodejs
curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
sudo apt-get update && sudo apt-get install yarn

npm -version
6.1.0
nodejs -v
v10.7.0
