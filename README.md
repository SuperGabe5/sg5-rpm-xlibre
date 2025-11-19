# rpm-xlibre

## RPMs of XLibre for Enterprise Linux 10

/etc/yum.repos.d/xlibre.repo
```
[xlibre]
name=RHEL $releasever - Xlibre
baseurl=https://raw.githubusercontent.com/COD3HUNT3R/rpm-xlibre/refs/heads/main/$releasever/$basearch/
enabled=1
gpgcheck=0
priority=1
```

### How to install
```
dnf install xlibre*
```
