     Ubuntu Server OVA Images
     Ubuntu 14.04.6 LTS
     Ubuntu 16.04.6 LTS
     Ubuntu 20.04 LTS (You need to configure only sql server)
     
     [1] Download & Install VirtualBox
     Link For ALL
     https://mega.nz/#F!COJVxCTB!2zP-wpOfuE6UuBX4opdF_w

    [2] OPEN VirtualBox > File > Import Appliance

    Login For All Images
    SSH & phpmyadmin
    User: root
    Pass: root

    NOTE: IF PHP SERVER NOT WORK RE-GENERATE GRUB CONFIGURATION FOR YOUR SYSTEM UID

    [1] apt-get -y --force-yes -q update && apt-get -y --force-yes -q upgrade && apt-get -y --force-yes -q install lsb-release

    [2] sudo updatedb

    [3] service mysql restart
 
    Or reboot System
    [4] service apache2 reload && service apache2 restart
