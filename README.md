# AirCrackNG

# Depend

```
pkg update && pkg upgrade -y
pkg install wget -y
pkg install libc++ libnl libpcap libsqlite openssl pcre zlib -y

```

# Install

```
wget https://github.com/Mr-Beta-Version/AirCrackNG/raw/refs/heads/main/aircrack-ng_3_1.7_aarch64.deb
dpkg -i aircrack-ng_3_1.7_aarch64.deb
aircrack-ng
```

# pcap bruteforce

```
aircrack-ng -w pass.txt -b WI:FI:MAC -e "WIFI NAME" file.pcap
```
