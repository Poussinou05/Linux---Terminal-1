https://asciinema.org/a/KBTad4E5ZpFB7sZ4oYpx3L3qE
wilder@wilder-ThinkPad-T440p:~$ ping
Usage: ping [-aAbBdDfhLnOqrRUvV64] [-c count] [-i interval] [-I interface]
            [-m mark] [-M pmtudisc_option] [-l preload] [-p pattern] [-Q tos]
            [-s packetsize] [-S sndbuf] [-t ttl] [-T timestamp_option]
            [-w deadline] [-W timeout] [hop1 ...] destination
Usage: ping -6 [-aAbBdDfhLnOqrRUvV] [-c count] [-i interval] [-I interface]
             [-l preload] [-m mark] [-M pmtudisc_option]
             [-N nodeinfo_option] [-p pattern] [-Q tclass] [-s packetsize]
             [-S sndbuf] [-t ttl] [-T timestamp_option] [-w deadline]
             [-W timeout] destination
wilder@wilder-ThinkPad-T440p:~$ clear

wilder@wilder-ThinkPad-T440p:~$ ls
bonjour.sh  Documents         Images   Musique  Téléchargements
Bureau      examples.desktop  Modèles  Public   Vidéos
wilder@wilder-ThinkPad-T440p:~$ ls .
bonjour.sh  Documents         Images   Musique  Téléchargements
Bureau      examples.desktop  Modèles  Public   Vidéos
wilder@wilder-ThinkPad-T440p:~$ ls -a
.              bonjour.sh  examples.desktop  .local    .profile                   Vidéos
..             Bureau      .gconf            Modèles   Public
.bash_history  .cache      .gnupg            .mozilla  .ssh
.bash_logout   .config     .ICEauthority     Musique   .sudo_as_admin_successful
.bashrc        Documents   Images            .pki      Téléchargements
wilder@wilder-ThinkPad-T440p:~$ ls Images
'Capture d’écran de 2018-09-05 12-00-31.png'  'Capture d’écran de 2018-09-05 12-00-33.png'
wilder@wilder-ThinkPad-T440p:~$ ls /home/wilder
bonjour.sh  Documents         Images   Musique  Téléchargements
Bureau      examples.desktop  Modèles  Public   Vidéos
wilder@wilder-ThinkPad-T440p:~$ ls /home
wilder
wilder@wilder-ThinkPad-T440p:~$ ls ..
wilder
wilder@wilder-ThinkPad-T440p:~$ ls /bin
bash           fuser       nisdomainname  stty
brltty         fusermount  ntfs-3g        su
bunzip2        getfacl     ntfs-3g.probe  sync
busybox        grep        ntfscat        systemctl
bzcat          gunzip      ntfscluster    systemd
bzcmp          gzexe       ntfscmp        systemd-ask-password
bzdiff         gzip        ntfsfallocate  systemd-escape
bzegrep        hciconfig   ntfsfix        systemd-hwdb
bzexe          hostname    ntfsinfo       systemd-inhibit
bzfgrep        ip          ntfsls         systemd-machine-id-setup
bzgrep         journalctl  ntfsmove       systemd-notify
bzip2          kbd_mode    ntfsrecover    systemd-sysusers
bzip2recover   kill        ntfssecaudit   systemd-tmpfiles
bzless         kmod        ntfstruncate   systemd-tty-ask-password-agent
bzmore         less        ntfsusermap    tar
cat            lessecho    ntfswipe       tempfile
chacl          lessfile    open           touch
chgrp          lesskey     openvt         true
chmod          lesspipe    pidof          udevadm
chown          ln          ping           ulockmgr_server
chvt           loadkeys    ping4          umount
cp             login       ping6          uname
cpio           loginctl    plymouth       uncompress
dash           lowntfs-3g  ps             unicode_start
date           ls          pwd            vdir
dd             lsblk       rbash          wdctl
df             lsmod       readlink       which
dir            mkdir       red            whiptail
dmesg          mknod       rm             ypdomainname
dnsdomainname  mktemp      rmdir          zcat
domainname     more        rnano          zcmp
dumpkeys       mount       run-parts      zdiff
echo           mountpoint  sed            zegrep
ed             mt          setfacl        zfgrep
efibootdump    mt-gnu      setfont        zforce
efibootmgr     mv          setupcon       zgrep
egrep          nano        sh             zless
false          nc          sh.distrib     zmore
fgconsole      nc.openbsd  sleep          znew
fgrep          netcat      ss
findmnt        networkctl  static-sh
wilder@wilder-ThinkPad-T440p:~$ ls -l
total 48
-rwxr-xr-x 1 wilder wilder   79 sept.  5 21:59 bonjour.sh
drwxr-xr-x 2 wilder wilder 4096 sept.  5 11:25 Bureau
drwxr-xr-x 3 wilder wilder 4096 sept.  4 15:55 Documents
-rw-r--r-- 1 wilder wilder 8980 août  30 20:02 examples.desktop
drwxr-xr-x 2 wilder wilder 4096 sept.  5 12:00 Images
drwxr-xr-x 2 wilder wilder 4096 août  30 20:07 Modèles
drwxr-xr-x 2 wilder wilder 4096 août  30 20:07 Musique
drwxr-xr-x 2 wilder wilder 4096 août  30 20:07 Public
drwxr-xr-x 2 wilder wilder 4096 sept.  5 11:31 Téléchargements
drwxr-xr-x 2 wilder wilder 4096 août  30 20:07 Vidéos
wilder@wilder-ThinkPad-T440p:~$ pwd
/home/wilder
wilder@wilder-ThinkPad-T440p:~$ cd Images
wilder@wilder-ThinkPad-T440p:~/Images$ cd ..
wilder@wilder-ThinkPad-T440p:~$ cd /opt
wilder@wilder-ThinkPad-T440p:/opt$ cd ../
wilder@wilder-ThinkPad-T440p:/$ cd /usr/bin
wilder@wilder-ThinkPad-T440p:/usr/bin$ cd
wilder@wilder-ThinkPad-T440p:~$ cd ~
wilder@wilder-ThinkPad-T440p:~$ cd ~/Musique
wilder@wilder-ThinkPad-T440p:~/Musique$ 
