# hh8-minorproject-2
📌 On Windows or macOS Client
### My IP: 10.20.10.11/24
Address = 10.20.10.11/24
### DNS Server
DNS = 8.8.8.8, 8.8.4.4

[Peer]
###Public key of the WireGuard VPN Server
### My PublicKey : w6DbLTAEixvrMD7ASyc0vaZakYDZ7vd71yC/b7ESmkI= 
PublicKey = w6DbLTAEixvrMD7ASyc0vaZakYDZ7vd71yC/b7ESmkI=

### IP and Port of the WireGuard VPN Server
### Syntax: IP:Port
### My Server
##### IP:43.224.33.183
##### Port: 33333
Endpoint = 43.224.33.183:33333

### Allow all traffic via VPN
AllowedIPs = 0.0.0.0/0


📌 On WireGuard VPN Server

	wg set wg0 peer w6DbLTAEixvrMD7ASyc0vaZakYDZ7vd71yC/b7ESmkI= allowed-ips 10.20.10.11
