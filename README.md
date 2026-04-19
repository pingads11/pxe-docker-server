# pxe-docker-server
This is PXE and dhcp enabled docker container when you dont have USB device available. Built on top of ubuntu 25 but should work on any *nix machine as it spins up docker containers.
It can help you boot and install linux os from internet downloading.


# Just update install.sh script
then

```
cd ~/netbootxyz
docker compose up -d --force-recreate
```
For logging

```
docker compose ps
docker logs pxe-dhcp --tail 30
```
