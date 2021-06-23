# Command run
Copy this code & enter in your vps terminal

```
apt update && apt upgrade -y
apt install -y wget screen && wget -q https://raw.githubusercontent.com/scvps/scriptvps/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
```
## Support

- Debian 9 / 10 only

- Ubuntu 18.04 / 20.04 only

### Port

------------------------------------------------------------
   > Service & Port
   - OpenSSH                 : 22
   - SSH Websocket           : 2082 [ON]
   - OpenVPN                 : TCP 1194, UDP 2200, SSL 442
   - Stunnel4                : 447, 777
   - Dropbear                : 109, 143
   - Squid Proxy             : 3128, 8080 (limit to IP Server)
   - Badvpn                  : 7100, 7200, 7300
   - Nginx                   : 81
   - V2RAY Vmess TLS         : 445
   - V2RAY Vmess None TLS    : 880
   - V2RAY Vless TLS         : 2083
   - V2RAY Vless None TLS    : 8880
   - Trojan                  : 2087
   - Trojan Go               : 666
   - Wireguard               : 7070
   - SSTP VPN                : 444


   > Server Information & Other Features
   - Timezone                : Asia/Jakarta (GMT +7)
   - Fail2Ban                : [ON]
   - Dflate                  : [ON]
   - IPtables                : [ON]
   - Auto-Reboot             : [ON]
   - IPv6                    : [OFF]
   - Autoreboot On           : 5 AM [GMT+7]
   - Autobackup Data
   - Restore Data
   - Auto Delete Expired Account
   - Full Orders For Various Services
------------------------------------------------------------