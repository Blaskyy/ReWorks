system_monitor
=======

A superkaramba theme for KDE 4.x
based on http://kde-look.org/content/show.php?content=134117

changes
-------
1.change eth0 to enp3s0(get from `ifconfig`), for that the new version systemd change the devices name
......

required on Chakra(or Archlinux)
-------
pacman -S lm_sensors mesa-demos `#mesa-demos contain the gfxinfo file to get the info of video card`
