![Shadowsocks](https://github.com/zhaoweih/shadowsocks_install/raw/master/shadowsocks.png)

For CentOS  

```bash
wget --no-check-certificate -O shadowsocks-all.sh https://raw.githubusercontent.com/zhaoweih/shadowsocks_install/master/shadowsocks-all.sh
chmod +x shadowsocks-all.sh
./shadowsocks-all.sh 2>&1 | tee shadowsocks-all.log
```