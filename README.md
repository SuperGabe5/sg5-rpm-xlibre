# rpm-xlibre

## Caution: This will erase existing Xorg and dependencies as those are conflicting. Currently only available packages are gdm and gnome-session(Only Gnome). Feel free to try with other desktop environment and post your dnf install output. I will try to package those if I have enough time. Also report if dnf install tries to erase more than it is going to install.

/etc/yum.repos.d/xlibre.repo
```
[xlibre]
name=RHEL $releasever - Xlibre
baseurl=https://raw.githubusercontent.com/COD3HUNT3R/rpm-xlibre/refs/heads/main/$releasever/$basearch/
enabled=1
gpgcheck=0
```

### How to install
```
dnf install xlibre* --allowerasing
```
