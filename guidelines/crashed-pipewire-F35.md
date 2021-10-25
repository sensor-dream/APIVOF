# Crached pipewire in Fedora 35

## First check wireplumber service

`systemctl --user status wireplumber`

## Then check wireplumber packets and remove old versions

`sudo dnf list wireplumber --installed`
