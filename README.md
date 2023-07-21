
# Install kali linux without root on android using these commands. 

🅿🅺🅳


using this command you can easly Install kali linux on your android phone .

#1  first Install termux

#2 use these commands...








```bash
  pkg update && pkg upgrade
```

```bash
  termux-setup-storage
```
```bash
   pkg install wget
```
```bash
   wget -O pkdnh https://raw.githubusercontent.com/pranavkdileep/Install-linux/main/pkdnh
```
### you can use both of bellow
```bash
   chmod +x pkdnh
```
```bash
   ./pkdnh
```




#### here if you want to access of your storage in linux so follow..

```bash
  termux-setup-storage
```


### now start the nethunter server 
```
  nh
```
```nethunter
  sudo apt update
```
```
   password is => kali

```

### solve internet error

```
   nano /etc/resolv.conf
```
##### write there bellow after SAVE that ( ctrl + x + y and enter ) and remove all from there
```
    nameserver 8.8.8.8
    nameserver 8.8.4.4
```

#### now update the packages 
```nethunter
    sudo apt update
```

### now install vnc server for run our linux

```nethunter
sudo apt install kali-desktop-xfce dbus-x11 tigervnc-standalone-server -y
```

### make some change in vnc server
 ```
    nano .vnc/xstartup
 ```

 ##### write there bellow
 ```
#!/bin/bash
dbus-launch 
startxfce4 
 ```

#### make excutable vnc server
```
chmod +x .vnc/xstartup
```

## now start the vnc server for run kali linux on android.

```
kex
```
### for stop the kali linux 
```
kex stop
```





