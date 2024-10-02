# docker-apps
docker compose templates for my various applications

Useful commands

```
docker compose up -d
docker compose down
docker compose top
docker ps
docker top
docker compose pull
docker compose restart
docker compose update

ln .env ./tautulli/.env



docker compose up --force-recreate --build -d
docker image prune -f
docker network ls

```


For other repos and images checkout

https://github.com/novaspirit/pi-hosted/tree/master/images

https://github.com/ibracorp/templates

```
curl -sSL https://get.docker.com | sh || error "Failed to install Docker."
sudo usermod -aG docker $USER || error "Failed to add user to the Docker usergroup."
echo "Remember to logoff/reboot for the changes to take effect."

```


```
docker network create proxy
```

Clone this repo, copy the `sample.env` to `.env` and link it to every folder
``` 
ln /path/to/global/.env /path/to/app_folder/.env 
```

look at https://trash-guides.info/
