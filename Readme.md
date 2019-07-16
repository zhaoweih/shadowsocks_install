![Shadowsocks](https://github.com/zhaoweih/shadowsocks_install/raw/master/shadowsocks.png)

For CentOS  

```bash
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/zhaoweih/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```

BBR  

```bash
wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh
```

```bash
#check bbr
lsmod | grep bbr
```

Please visit [Shadowsocks tutorial(Chinese version)](https://github.com/zhaoweih/Shadowsocks-Tutorial) !
