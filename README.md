# Auto-Installer-VPS
Hallo pengunjung blog www.androhardcore.id, untuk tutorial kali ini saya akan membahas script auto installer VPS, ada beberapa services yang otomatis di instal antara lain:<br
# List-Service

OpenVPN  : TCP 1194 <br>
OpenSSH  : 22, 143<br>
Dropbear : 109, 110, 443<br>
Squid3   : 8080 (limit to IP SSH)<br>
badvpn   : badvpn-udpgw port 7300 <br>
Webmin <br>
VNSTAT <br>
MRTG <br>
Selengkapnya lihat di LOG setelah instalasi <br>

# Tutorial Installasi : <br>
1. Login VPS<br>
2. # wget https://raw.githubusercontent.com/ahwan0m/Auto-Installer-VPS/master/debian7-32.sh <br>
3. # chmod +x debian7-32.sh <br>
4. # ./debian7-32.sh <br>
5. tunggu sampai proses selesai > reboot vps anda<br>
<br>

<br>
@GraciesBlaugrana 1nG-9h0st | www.androhardcore.id | fb.com/groups/androhardcore1
