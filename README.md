# mongodb-compose

Modify `./init-mongo.js` with your desired username and password. Set the root username and password in `./docker-compose.yml`

You can login (i.e get a shell) to the container while it's running using the container name.
```bash
$ docker exec -it ${container name} bash
```