# nasTpi
basic Raspberry Pi Nas using OpenMediaVaut and Plex

### Description
basically just a space for me to reprocude these projects quickly according to my note taking prefrence

## Resources used:
https://www.raspberrypi.com/software/ at the time of this note, OpenMediaVault supports only up until bullseye
https://github.com/OpenMediaVault-Plugin-Developers/installScript
https://youtu.be/gyMpI8csWis?si=8VfytvgTnKCO7XLZ
```bash
sudo wget -O - https://github.com/OpenMediaVault-Plugin-Developers/installScript/raw/master/install | sudo bash
```

### Plex Media 
```bash
curl https://downloads.plex.tv/plex-keys/PlexSign.key | sudo apt-key add -
```

```bash
echo deb https://downloads.plex.tv/repo/deb public main | sudo tee /etc/apt/sources.list.d/plexmediaserver.list
```
```
sudo apt update
```

``` 
sudo apt install plexmediaserver
```

Next you can open a browswer of your choice and navigate to your server's IP Address 
```
192.***.**.*:32400/web
```
Here you will login to your plexmedia account and continue with GUI setup




## adding NFS file sharing to MacOS
open a terminal and:
```
nfs://192.168.1.100/export/myshare

```
