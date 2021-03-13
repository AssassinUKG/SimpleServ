# SimpServ

Serving files for linunx and windows.


## Screenshots

![](/assets/simserv1.png)

Tip: 
Set a dir like "/opt/tools" for common scripts. 
```
cd /opt/tools && sudo simpserv
```

## Install & Usage
### Linux
Quick install, use anywhere
```
sudo wget "https://raw.githubusercontent.com/AssassinUKG/SimpleServ/main/simpserv" -O simpserv && sudo mv simpserv /usr/local/bin/simpserv &&  sudo chmod +x /usr/local/bin/simpserv
```
### Usage
Open a new terminal and type
```
simpserv
or
simpserv -d /tmp/somepath
```


### Windows
Quick install, use where you download (Windows)
```
wget https://raw.githubusercontent.com/AssassinUKG/SimpleServ/main/simpserv -o simpserv
```

### Usage
```
python.exe .\simpserv
or
python.exe .\simpserv -d "C:\\Users\\Usernam\\Desktop"
```
