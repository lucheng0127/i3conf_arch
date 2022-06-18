Pre-Setup
=========

**Requirements**
* picom
* alsa-utils
* terminator
* i3
* feh
* i3lock
* falmeshot

**Setup**
cp -r .config/* ~/.config
```
cat <<EOF>>.xinitrc
picom -b
exec i3
EOF
```
