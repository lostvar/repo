# repo
A personal Cydia repository hosting a collection of iOS tweaks.

### Commonly Used Debian Pacakge Manipulation Commands:

* Extract control information files:
  * ```dpkg-deb -x xxx.deb dir```
* Extract package files:
  * ```dpkg-deb -e xxx.deb dir/DEBIAN/```
* Repackage:
  * ```dpkg-deb -b xxx.deb dir```
* Install:
  * ```dpkg -i xxx.deb```

### Cydia Cache Location:
```
/var/mobile/Library/Caches/com.saurik.Cydia/archives/
```

### iOS Symbolic Links:
```
/var -> /private/var
/tmp -> /private/var/tmp
/User -> /private/var/mobile
/etc -> /private/etc
```
