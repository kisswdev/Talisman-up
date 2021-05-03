# Talisman-up
Talisman - server files by kIsSwdev
Talisman online clean server files

And download ssh secure shell (this supprt file transfer too ) from https://winscp.net/eng/index.php  SSH Secure Shell Client

Putty : https://www.chiark.greenend.org.uk/~sgtatham/putty/

Get Ubuntu 14.04 32 bit then follw this instructions ( TESTED BY ME WORKING )
Get Ubuntu 14.04 64 bit then follw this instructions ( TESTED BY ME WORKING )
Get Ubuntu 16.04 64 bit then follw this instructions ( TESTED BY ME WORKING )
Get Ubuntu 18.04 64 bit then follw this instructions ( NOT TESTED )

Here you get details to connect your vps details ip and password so use secure shell to connect vps using ip username is root and password

sudo apt-get update

sudo apt-get install lamp-server^ -y

sudo apt-get install phpmyadmin -y

this will ask for set Database Password So Make Strong Password

first of all

apt-get install sudo
apt-get install lib32stdc++6
sudo apt-get install libstdc++6



sudo get-install unzip

download files from here 
wget "https://store8.gofile.io/download/iLmli0/efa460f78797eab7446831e855551717/talismansvr.zip"

extract parts : 

unzip talismansvr.zip


then


Open WINSCP EDIT FILES:


cd

Open All.INI files from all folders and replace 192.168.52.128 this ip to your ip

then open db folder and file name db_server_user.ini and replace 22021982 to your sql database password

photo 1:
https://i.ibb.co/vZZ7KRM/Capture.png

photo 2:
https://i.ibb.co/gSgS2DD/Capture2.png


cd

then give execute permission to

chmod -R 777 /root/*


then

sudo dpkg -i *.deb





UNRAR EVP ( DISABLE ANTIVIRUS  >> ITS DETECTED LIKE VIRUS)
IN CASE IF YOU RECIVED A ERROR IN CHINESE CLOSE THE ERROR RUN >> Run.exe
AFTER OPEN AGAIN EvpTool.exe



AND FOLLOW THE video :



coming soon


and the last step to start server

then

sudo apt-get install screen -y

screen -d -m ./1

This will show nothing but wait to 3 minutes

screen -d -m ./2

This will show nothing but wait 6 minutes

screen -d -m ./3

This will show nothing but your talisman server is online and go play
