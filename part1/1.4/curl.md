Terminal 1:
docker run -it sh -c 'while true; do echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website; done'
Terminal 2:
docker exec -it f3 sh
apt update && apt upgrade
apt install curl
Terminal 1:
helsinki.fi
