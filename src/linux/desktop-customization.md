# Desktop Customization

---

## Installing wallpaper changer (variety)

1: Install variety

```bash
sudo apt install variety
```

2: Run this command to make it work in dark mode.

```bash
sed -i '/^# Gnome 3, Unity*/a gsettings set org.gnome.desktop.background picture-uri-dark "file://$WP" 2> /dev/null' /home/$USER/.config/variety/scripts/set_wallpaper
```
