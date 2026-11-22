**i probably wont update this in a while, so it will probably be broken**

# i3conf
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/6a8299ca-9e0f-47e3-b65b-96e2811e0f52" />

## setup

- **wm:** i3
- **compositor:** picom
- **bar:** polybar
- **launcher:** rofi
- **terminal:** kitty

---

## structure
```
~/i3conf/
├── i3 (i3 window manager config)
├── picom.conf (picom compositor config for transparency and rounded windows) 
├── config.ini (polybar config)
├── config.rasi (rofi theme/config)
└── kitty.conf (kitty terminal config)
```

## needed packages
```
git
fish
kitty
i3
polybar
feh
rofi
picom
autotiling
maim
slop
xclip
```

## installation

clone the repo and simply run the install script

```bash
git clone https://github.com/larpmaxxer/i3conf.git
cd i3conf
chmod +x install.sh
./install.sh
```
