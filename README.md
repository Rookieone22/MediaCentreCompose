# MediaCentreCompose

Really basic Docker compose running the containers I need for my media.
Requires a .env file in the some path as the top compose with the following values:

PUID=1000
PGID=1000
TZ="Australia/Canberra"
USERDIR="/home/docker"
DOCKERDIR="/home/docker/docker"
DATADIR="/media/storage"
HOSTNAME="hostname"
LOCAL_IPS=127.0.0.1/32,10.0.0.0/8,192.168.0.0/16,172.16.0.0/12
SERVER_IP=static ip address





