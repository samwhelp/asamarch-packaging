
# asamos-mirrorlist

Config File Path: `/etc/pacman.conf`

``` ini
[asamos]
SigLevel = Optional TrustAll
Include = /etc/pacman.d/asamos-mirrorlist
```



## Reference

* https://wiki.archlinux.org/title/Creating_packages
* https://wiki.archlinux.org/title/Arch_User_Repository
* https://archlinux.org/groups/x86_64/base-devel/
* https://wiki.archlinux.org/title/pacman
* https://wiki.archlinux.org/title/makepkg
* https://wiki.archlinux.org/title/PKGBUILD
* https://wiki.archlinux.org/title/Arch_package_guidelines


## File List

run

``` sh
pacman -Ql asamos-mirrorlist -q
```

show

```
/etc/
/etc/pacman.d/
/etc/pacman.d/asamos-mirrorlist
```


* [/etc/pacman.d/asamos-mirrorlist](asset/overlay/etc/pacman.d/asamos-mirrorlist)
