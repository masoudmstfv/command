
apt update -y && apt upgrade -y 
passwd 
systemctl restart sshd



cd /opt
wget https://raw.githubusercontent.com/DEAD-EYE-AKPRO/v2ray-IR/main/faren-server.sh
chmod +x faren-server.sh
./faren-server.sh


opt# cat upstream-install.log


netstat -tulnp | grep ssh
nano /etc/ssh/sshd_config

sudo sed -i 's/#PermitRootLogin prohibit-password/PermitRootLogin yes/' /etc/ssh/sshd_config && sudo systemctl restart ssh && sudo passwd

bash <(curl -Ls https://raw.githubusercontent.com/NidukaAkalanka/x-ui-english/master/install.sh)


bash <(curl -Ls https://raw.githubusercontent.com/alireza0/x-ui/master/install.sh)


history -c && history -w


apt-get clean
