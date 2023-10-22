# nasTpi
basic Raspberry Pi Nas using OpenMediaVaut and Plex

### Description
basically just a space for me to reprocude these projects quickly according to my note taking prefrence

## Resources used:
https://www.raspberrypi.com/software/ at the time of this note, OpenMediaVault supports only up until bullseye
https://github.com/OpenMediaVault-Plugin-Developers/installScript
```bash
sudo wget -O - https://github.com/OpenMediaVault-Plugin-Developers/installScript/raw/master/install | sudo bash
```

```
curl https://downloads.plex.tv/plex-keys/PlexSign.key | sudo apt-key add -
```

```echo deb https://downloads.plex.tv/repo/deb public main | sudo tee /etc/apt/sources.list.d/plexmediaserver.list```

``` sudo apt update ```

``` sudo apt install plexmediaserver```
