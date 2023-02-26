### Packages of the Termux compileds by me.
# Notes
- this is not a guide to install docker. I just keep termux packages for ME to use. it's up to you to try

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
---

> if you think my work is cool or want to help me, make a small donation <3
#### send for btc address
```
 bc1qut3e70aakpdqgmc6ymva9tu92gme5g7w2h75hy
```
