# Tweaks

## Hide Close Button For All Windows

Open Terminal, and run the following command to hide the close button for all windows:

```
gsettings set org.gnome.desktop.wm.preferences button-layout :
```

## Disable GDM Lockscreen Logo For All Users

Open Terminal, and run the following commands to disable the GDM lockscreen logo (the Fedora logo) for all users:

```
xhost +si:localuser:gdm
sudo -u gdm gsettings set org.gnome.login-screen logo ''
```
