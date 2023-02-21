### Packages of the Termux compileds by me.

<br>

#### Install package python `3.10.8` <br> (**Only** architeture **aarch64**):
```
 git clone https://github.com/AkariOficial/termux-packages; cd termux-packages; cd python3.10.8; dpkg -i *.deb; cd; rm -rf termux-packages
```
---

#### Install package docker `v20.10.23-ce` <br> (**Only** architeture **aarch64**):
```
 pkg in subversion -y
```

```
 svn export https://github.com/AkariOficial/termux-packages/trunk/docker; cd docker; dpkg -i *.deb; cd; rm -rf docker
```
