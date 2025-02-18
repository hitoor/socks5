# socks5

A socks5 server for testing libevent, Can support linux/windows/macos, but only tested on macos

build

```shell
git clone https://github.com/hitoor/socks5.git
cd socks5
git submodule update --init --recursive
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

usage

```shell
./socks5 0.0.0.0:1080 admin passwd 8.8.8.8
```
