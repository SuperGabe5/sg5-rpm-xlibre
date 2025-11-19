# rpm-xlibre

## RPMs of XLibre for Enterprise Linux 10

I created this fork to allow me to have a starting point for me to create a viable Free Enterprise Linux Distribution

Based on Almalinux 10

Why not use Wayland?

there's several factors

1. it's not viable for the needs of a Server System
(that's one of the reasons I'm packaging this, so I can also compile and package xfce4)

2. it's just more functional

3. proper screensaver support

i know that seems redundant in this day and age but I feel that a screensaver gives good vibes :)

4. I find it easier to work with and troubleshoot

5. it's genuinely more compatible with older hardware

   (very important for me)

(infact I'm going to start making Debs aswell)

(and I'm going to attempt to Package for alpine because I could care less of their opinion as the results are noticably showing)

(Seriously if this keeps up I'm going to fork the entire kernel)

(infact I already have)

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
