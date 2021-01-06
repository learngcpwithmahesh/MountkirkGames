# Mountkirk Games Implementation on Google Compute Engine or Managed Instance Group

A WebGL maze game built with Three.js and Box2dWeb. 
Credits & Source from: https://github.com/wwwtyro/Astray

### Launching

1. Provision a Google Compute Engine (GCE) with Apache Web Server and Git Installed using below startup script
apt update
apt install -y git
apt install -y apache2
cd /var/www/html
git clone https://github.com/learngcpwithmahesh/MountkirkGames.git

2. Open http://EXTERNAL-IP-GCE/MountkirkGames in your browser
3. Enjoy!
