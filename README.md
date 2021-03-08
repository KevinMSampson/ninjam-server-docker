# ninjam-docker
Ninjam Server using Docker Compose - [Ninjam Docker Tags](https://hub.docker.com/r/zeppelinux/ninjam-server/tags)

## Setting up the Ninjam Server
### Config Files
```
mv cclicense.txt.example cclicense.txt
mv config.cfg.example config.cfg
```
Update the `cclicense.txt` file to fit for your server. This is what Ninjam users will see when connecting.

Update the `config.cfg` file with User(s) & password(s) so you and anyone else you set up can log in.

This [Setup Guide](https://www.cockos.com/ninjam/server-guide.php) has all the config descriptions

### Spin it up
```
NINJAM_PATH=/path/to/folder docker-compose up -d
```
