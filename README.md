# Mountkirk Games Implementation on Google Compute Engine or Managed Instance Group

A WebGL maze game built with Three.js and Box2dWeb. 
Credits & Source from: https://github.com/wwwtyro/Astray

### Launching

1. Provision a Google Compute Engine (GCE) with Apache Web Server and Git Installed using below startup script
apt update <br/>
apt install -y git <br/>
apt install -y apache2 <br/>
cd /var/www/html <br/>
git clone https://github.com/learngcpwithmahesh/MountkirkGames.git <br/>

2. Open http://EXTERNAL-IP-GCE/MountkirkGames in your browser
3. Enjoy!
