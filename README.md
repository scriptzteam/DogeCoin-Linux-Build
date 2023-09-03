# DogeCoin-Linux-Build

```
apt install build-essential autoconf bsdmainutils pkg-config libtool libboost-dev libevent-dev autotools-dev automake libssl-dev libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-program-options-dev libboost-test-dev libboost-thread-dev

git clone https://github.com/dogecoin/dogecoin.git
cd dogecoin
./autogen.sh
./configure --disable-hardening --without-gui --without-bdb --disable-wallet #this is ours, change as you want..
make
make install
```
