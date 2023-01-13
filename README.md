# TOR-Linux-Build

***Building latest TOR v0.4.7.13 on Linux***
```
apt update
apt upgrade
apt install build-essential libevent-dev libssl-dev zlib1g zlib1g-dev
wget https://dist.torproject.org/tor-0.4.7.13.tar.gz
tar -xvf tor-0.4.7.13.tar.gz
cd tor-0.4.7.13
./configure
make
make install
tor --version
tor -f /etc/tor/torrc
```

***Copy sample TOR config (DO NOT FORGET TO EDIT IT!)***
```
mkdir /etc/tor
cp /usr/local/etc/tor/torrc.sample /etc/tor/torrc
nano /etc/tor/torrc
```

***Install Directories***
```
  Binaries:                                                      /usr/local/bin
  Configuration:                                                 /usr/local/etc/tor
  Man Pages:                                                     /usr/local/share/man
```
