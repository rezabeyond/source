# [BeyondTeam Channel](https://telegram.me/BeyondTeam)
-------------------
# [Developer](http://telegram.me/mr_anti_admin)
-------------------
# Installation
```sh
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev
cd $HOME
git clone https://github.com/rezabeyond/source.git
cd source
chmod +x launchfix2.sh
chmod +x launch.sh
chmod +x autolaunch.sh
./launchfix2.sh install
cd .luarocks
cd bin
./luarocks-5.2 install luafilesystem
./luarocks-5.2 install lub
./luarocks-5.2 install luaexpat
cd $HOME
cd source
./launchfix2.sh install
./autolaunch.sh
```
# ANTI CRASH
```sh
tmux new-session -s script "bash steady.sh -t"
```
# NEW TERMINAL ANTI CRASH
```sh
cd source
screen ./launch.sh
```
