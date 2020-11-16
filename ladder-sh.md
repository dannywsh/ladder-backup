# SSR
```bash
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```
If `wget` is not installed , please use command:

CentOS：
```bash
yum -y install wget
```
Ubuntu/Debian：
```bash
apt-get -y install wget
```
# v2ray
```bash
bash <(curl -sL https://raw.githubusercontent.com/phlinhng/v2ray-tcp-tls-web/master/install.sh) && v2script
```
or
```bash
wget -N --no-check-certificate -q -O install.sh "https://raw.githubusercontent.com/wulabing/V2Ray_ws-tls_bash_onekey/master/install.sh" && chmod +x install.sh && bash install.sh
```
or
```bash
wget --no-check-certificate https://raw.githubusercontent.com/tcp-nanqinlang/general/master/General/CentOS/bash/tcp_nanqinlang-1.3.2.sh
bash tcp_nanqinlang-1.3.2.sh
```
