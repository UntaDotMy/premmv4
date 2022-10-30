Fresh VPS ONLY !

Autoscript installer VPS untuk jualan SSH / OVPN / Xray / SSR / SS

CARA INSTALL :

DEBIAN / UBUNTU

**COMMAND DEB10 > + ONLY 
> apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot

**UBUNTU ONLY
> apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && sleep 2 && reboot

lepas tu

> sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl wget tcpdump dsniff grepcidr dnsutils && wget https://raw.githubusercontent.com/UntaDotMy/premmv4/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh

>>> Service & Port  
- OpenSSH                 : 22  
- OpenVPN                 : TCP 1194, TCP 110 , UDP 2200 , UDP 2500 
- Stunnel4                : 443, 777  
- Dropbear                : 109, 143  
- Squid Proxy             : 3128, 8080 (limit to IP Server)  
- OHP OPENVPN             : 8087
- Badvpn                  : 7300  
- Nginx                   : 81  
- Wireguard               : 7070  
- Websocket SSH(HTTP)     : 2081
- Websocket SSL(HTTPS)    : 222
- Websocket OpenVPN       : 2084
- Shadowsocks-R           : 1443-1543  
- SS-OBFS TLS             : 2443-2543  
- SS-OBFS HTTP            : 3443-3543  
- Xray Vmess Ws Tls       : 443
- Xray Vless Ws Tls       : 443
- Xray Trojan Tcp Tls     : 443
- Xray Vless Tcp Xtls     : 443
- Xray Vmess Ws None Tls  : 80
- Xray Vless Ws None Tls  : 8080
- Xray Vless gRPC         : 880
- Xray Vmess gRPC         : 881
- Xray Trojan gRPC        : 2088
>>> Server Information & Other Features  
- Timezone                : Asia/Kuala_Lumpur (GMT +8)  
- Fail2Ban                : [ON]
- NO TORRENT              : [ON]  
- Dflate                  : [ON]  
- IPtables                : [ON]  
- Auto-Reboot             : [ON]  
- Auto-Remove-Expired     : [ON]  
- IPv6                    : [OFF]  

* VPS REKOMEN 2GB RAM KEATAS .

TESTED MACHINE : OVH , DIGITAL OCEAN , GOOGLE CLOUD , LINODE , VULTR , CONTABO

Boleh contact saya :

Telegram : @UntaDotMy

https://t.me/UntaDotMy