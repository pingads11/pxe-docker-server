# pxe-docker-server
This is PXE and dhcp enabled docker container when you dont have USB device available. It can help you boot and install linux os from internet downloading.


# Just update install.sh script
the 

```
cd ~/netbootxyz
docker compose up -d --force-recreate
```
For logging

```
docker compose ps
docker logs pxe-dhcp --tail 30
```
