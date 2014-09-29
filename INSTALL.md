#Debian installation notes

##During setup

###Partitioning

    2GB /boot partition
    rest for encrypted filesystem
    LVM inside encrypted filesystem
    swap logical volume, size of RAM
    root logical volume, rest of size

##After setup

    i3_config contains ~/.i3/config
    packages contains dpkg --get-selections
    sources.list contains /etc/apt/sources.list
