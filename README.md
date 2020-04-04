# games_server
add games to my server for covid


## tertrinet-server

#### server
```
apt-get install tetrinet-server
cp tetrinetd.service /etc/systemd/system/tetrinetd.service
systemctl enable tetrinetd.service
systemctl start.service

```
#### client
Window:

* http://tnet.slumserv.net/downloads.php?cat_id=1&download_id=1 
* allez dans Client Setting
* Client Mode: TetriNET

Linux:
```
sudo apt-get install gtetrinet
```

## Xonotic

https://dl.xonotic.org/xonotic-0.8.2.zip

#### server
gzip /xonotic-0.8.2.zip

#### client
./xonotic-linux-sdl.sh -sessionid aurelia
