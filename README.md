## Packages of the Termux compileds by me.

### Note
- this is not a guide to install docker. I just keep termux packages for my to use. it's up to you to try

### Install package python `3.10.8` <br> (**Only** architeture **aarch64**):
```
 pkg in subversion -y; clear; svn export https://github.com/whyakari/termux-packages/trunk/python3.10.8; cd python3.10.8; dpkg -i *.deb; cd; rm -rf python3.10.8
```

### Install package docker `v20.10.23-ce` <br> (**Only** architeture **aarch64**):
```
 pkg in subversion -y; clear; svn export https://github.com/whyakari/termux-packages/trunk/docker; cd docker; dpkg -i *.deb; cd; rm -rf docker
```
----
