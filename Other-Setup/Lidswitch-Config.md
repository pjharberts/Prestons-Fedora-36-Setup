# Lidswitch-Config

By default, laptops enter suspend mode when the lid is closed. Open ```/etc/systemd/logind.conf``` with Vim. Change the value for ```HandleLidSwitch``` to be ```poweroff```, and change the value for ```HandleLidSwitchExternalPower``` to be ```poweroff```. Make sure to uncomment these as well by removing the hashtag.
