# Repositories

## Flatpak

Open Terminal, and run the following command to add the Flatpak repository:

```
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```

## RPM Fusion

Open Terminal, and run the following commands to ad the RPM Fusion repository:
 
 ```
sudo dnf install https://mirrors.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm https://mirrors.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm
 ```

## Copr

Open Terminal, and run the following command to add the respective Copr repository:

```
dnf copr enable zirix/gdm-wallpaper
```
