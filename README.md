# TOR-Linux-Build

***Building latest TOR v0.4.6.7 on Linux***
```
apt update
apt upgrade
apt install build-essential libevent-dev libssl-dev zlib1g zlib1g-dev
wget https://dist.torproject.org/tor-0.4.6.7.tar.gz
tar -xvf tor-0.4.6.7.tar.gz
cd tor-0.4.6.7
./configure
make
make install
tor --version
```

***Install Directories***
```
  Binaries:                                                      /usr/local/bin
  Configuration:                                                 /usr/local/etc/tor
  Man Pages:                                                     /usr/local/share/man
```
