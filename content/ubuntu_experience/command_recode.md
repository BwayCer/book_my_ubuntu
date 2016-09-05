終端機紀錄
=======


## 頁籤


* [軟體包更新（查看未更新）](#軟體包更新（查看未更新）)
* [安裝 git](#安裝-git)
* [軟體包更新](#軟體包更新)
* [安裝 openssh-server](#安裝-openssh-server)
* [安裝 Vim](#安裝-vim)
* [安裝 tmux](#安裝-tmux)
* [安裝虛擬機工具](#安裝虛擬機工具)



## 軟體包更新（查看未更新）


```
$ sudo apt update
Hit:1 http://tw.archive.ubuntu.com/ubuntu xenial InRelease
Hit:2 http://tw.archive.ubuntu.com/ubuntu xenial-updates InRelease
Hit:3 http://tw.archive.ubuntu.com/ubuntu xenial-backports InRelease
Hit:4 http://security.ubuntu.com/ubuntu xenial-security InRelease
AppStream cache update completed, but some metadata was ignored due to errors.
Reading package lists... Done
Building dependency tree
Reading state information... Done
354 packages can be upgraded. Run 'apt list --upgradable' to see them.

$ sudo apt upgrade
Reading package lists... Done
Building dependency tree
Reading state information... Done
Calculating upgrade... Done
The following packages were automatically installed and are no longer required:
  libpango1.0-0 libpangox-1.0-0
Use 'sudo apt autoremove' to remove them.
The following NEW packages will be installed:
  linux-headers-4.4.0-36 linux-headers-4.4.0-36-generic
  linux-image-4.4.0-36-generic linux-image-extra-4.4.0-36-generic snap-confine
The following packages will be upgraded:
  accountsservice adium-theme-ubuntu adwaita-icon-theme apparmor apport
  apport-gtk appstream apt apt-transport-https apt-utils apturl apturl-common
  bamfdaemon base-files bash bash-completion bind9-host binutils brltty
  bsdutils command-not-found command-not-found-data compiz compiz-core
  compiz-gnome compiz-plugins-default console-setup console-setup-linux cpp-5
  cups-browsed cups-filters cups-filters-core-drivers curl dh-python
  distro-info-data dmidecode dnsmasq-base dnsutils dosfstools dpkg dpkg-dev
  eog file-roller firefox fontconfig fontconfig-config fonts-noto-cjk
  fonts-opensymbol fuse fwupd g++-5 gcc-5 gcc-5-base gdb gdbserver
  gir1.2-gst-plugins-base-1.0 gir1.2-gstreamer-1.0 gir1.2-gtk-3.0
  gir1.2-packagekitglib-1.0 gir1.2-soup-2.4 gir1.2-unity-5.0 glib-networking
  glib-networking-common glib-networking-services gnome-calendar
  gnome-font-viewer gnome-menus gnome-session-bin gnome-session-common
  gnome-settings-daemon-schemas gnome-software gnome-software-common
  gnome-sudoku gnome-system-monitor gnupg gpgv grep grub-common grub-pc
  grub-pc-bin grub2-common gstreamer1.0-alsa gstreamer1.0-plugins-base
  gstreamer1.0-plugins-base-apps gstreamer1.0-plugins-good
  gstreamer1.0-pulseaudio gstreamer1.0-tools gstreamer1.0-x
  gtk2-engines-murrine gvfs gvfs-backends gvfs-bin gvfs-common gvfs-daemons
  gvfs-fuse gvfs-libs imagemagick imagemagick-6.q16 imagemagick-common
  indicator-bluetooth init init-system-helpers initramfs-tools
  initramfs-tools-bin initramfs-tools-core isc-dhcp-client isc-dhcp-common
  keyboard-configuration klibc-utils language-selector-common
  language-selector-gnome less libaccountsservice0 libapparmor-perl
  libapparmor1 libappstream-glib8 libappstream3 libapt-inst2.0 libapt-pkg5.0
  libarchive13 libasan2 libatomic1 libbamf3-2 libbind9-140 libblkid1
  libboost-date-time1.58.0 libboost-filesystem1.58.0 libboost-iostreams1.58.0
  libboost-system1.58.0 libbrlapi0.6 libcc1-0 libcilkrts5 libcompizconfig0
  libcupsfilters1 libcurl3 libcurl3-gnutls libdecoration0 libdfu1
  libdns-export162 libdns162 libdpkg-perl libdrm-amdgpu1 libdrm-intel1
  libdrm-nouveau2 libdrm-radeon1 libdrm2 libegl1-mesa libexpat1 libfdisk1
  libfontconfig1 libfontembed1 libframe6 libfuse2 libfwupd1 libgail-3-0
  libgbm1 libgcc-5-dev libgcrypt20 libgd3 libgl1-mesa-dri libgl1-mesa-glx
  libglapi-mesa libglib2.0-0 libglib2.0-bin libglib2.0-data libgnome-menu-3-0
  libgnutls-openssl27 libgnutls30 libgomp1 libgstreamer-plugins-base1.0-0
  libgstreamer-plugins-good1.0-0 libgstreamer1.0-0 libgtk-3-0 libgtk-3-bin
  libgtk-3-common libharfbuzz-icu0 libharfbuzz0b libidn11 libimobiledevice6
  libisc-export160 libisc160 libisccc140 libisccfg140 libitm1 libklibc
  libksba8 libldap-2.4-2 liblightdm-gobject-1-0 libllvm3.8 liblsan0
  liblwres141 libmagickcore-6.q16-2 libmagickcore-6.q16-2-extra
  libmagickwand-6.q16-2 libmetacity-private3a libmount1 libmpx0
  libnautilus-extension1a libndp0 libnm-glib-vpn1 libnm-glib4 libnm-gtk-common
  libnm-gtk0 libnm-util2 libnm0 libnma-common libnma0 libnspr4 libnss3
  libnss3-nssdb libnux-4.0-0 libnux-4.0-common liboxideqt-qmlplugin
  liboxideqtcore0 liboxideqtquick0 libpackagekit-glib2-16 libpam-systemd
  libplymouth4 libpoppler-glib8 libpoppler58 libpython2.7 libpython2.7-minimal
  libpython2.7-stdlib libpython3.5 libpython3.5-minimal libpython3.5-stdlib
  libqt5core5a libqt5dbus5 libqt5gui5 libqt5network5 libqt5opengl5
  libqt5printsupport5 libqt5sql5 libqt5sql5-sqlite libqt5test5 libqt5widgets5
  libqt5xml5 libquadmath0 libsmartcols1 libsmbclient libsoup-gnome2.4-1
  libsoup2.4-1 libssl1.0.0 libstdc++-5-dev libstdc++6 libsystemd0 libtasn1-6
  libtevent0 libtsan0 libubsan0 libudev1 libunity-control-center1
  libunity-core-6.0-9 libunity-protocol-private0
  libunity-scopes-json-def-desktop libunity-settings-daemon1 libunity9
  libupower-glib3 libusbmuxd4 libuuid1 libwayland-egl1-mesa libwbclient0
  libwhoopsie0 libxatracker2 libxml2 light-themes lightdm linux-firmware
  linux-generic linux-headers-generic linux-image-generic linux-libc-dev
  lsb-base lsb-release lshw metacity-common mount mtr-tiny nautilus
  nautilus-data network-manager network-manager-gnome nux-tools openssh-client
  openssl oxideqt-codecs plymouth plymouth-label plymouth-theme-ubuntu-logo
  plymouth-theme-ubuntu-text poppler-utils printer-driver-brlaser python2.7
  python2.7-minimal python3-apport python3-brlapi python3-commandnotfound
  python3-distupgrade python3-problem-report python3-pyparsing
  python3-software-properties python3-urllib3 python3.5 python3.5-minimal
  samba-libs sbsigntool shared-mime-info snapd software-properties-common
  software-properties-gtk sudo suru-icon-theme systemd systemd-sysv thermald
  tzdata ubuntu-artwork ubuntu-core-launcher ubuntu-docs ubuntu-drivers-common
  ubuntu-mobile-icons ubuntu-mono ubuntu-release-upgrader-core
  ubuntu-release-upgrader-gtk ubuntu-session ubuntu-software udev unity
  unity-control-center unity-control-center-faces unity-lens-applications
  unity-schemas unity-scopes-runner unity-services unity-settings-daemon
  uno-libs3 update-notifier update-notifier-common upower upstart ure
  util-linux uuid-runtime vim-common vim-tiny vino wget whoopsie xbrlapi
  xdiagnose xinit xserver-common xserver-xorg-core xserver-xorg-video-intel
354 upgraded, 5 newly installed, 0 to remove and 0 not upgraded.
Need to get 418 MB of archives.
After this operation, 333 MB of additional disk space will be used.
Do you want to continue? [Y/n]
```



## 安裝 git


```
$ sudo apt install git
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following additional packages will be installed:
  git-man liberror-perl
Suggested packages:
  git-daemon-run | git-daemon-sysvinit git-doc git-el git-email git-gui gitk
  gitweb git-arch git-cvs git-mediawiki git-svn
The following NEW packages will be installed:
  git git-man liberror-perl
0 upgraded, 3 newly installed, 0 to remove and 354 not upgraded.
Need to get 3760 kB of archives.
After this operation, 25.6 MB of additional disk space will be used.
Do you want to continue? [Y/n]
```



## 軟體包更新


```
$ sudo apt upgrade
Reading package lists... Done
Building dependency tree
Reading state information... Done
Calculating upgrade... Done
The following packages were automatically installed and are no longer required:
  libpango1.0-0 libpangox-1.0-0
Use 'sudo apt autoremove' to remove them.
The following NEW packages will be installed:
  linux-headers-4.4.0-36 linux-headers-4.4.0-36-generic
  linux-image-4.4.0-36-generic linux-image-extra-4.4.0-36-generic
  snap-confine
The following packages will be upgraded:
  accountsservice adium-theme-ubuntu adwaita-icon-theme apparmor
  apport apport-gtk appstream apt apt-transport-https apt-utils
  apturl apturl-common bamfdaemon base-files bash bash-completion
  bind9-host binutils brltty bsdutils command-not-found
  command-not-found-data compiz compiz-core compiz-gnome
  compiz-plugins-default console-setup console-setup-linux cpp-5
  cups-browsed cups-filters cups-filters-core-drivers curl dh-python
  distro-info-data dmidecode dnsmasq-base dnsutils dosfstools dpkg
  dpkg-dev eog file-roller firefox fontconfig fontconfig-config
  fonts-noto-cjk fonts-opensymbol fuse fwupd g++-5 gcc-5 gcc-5-base
  gdb gdbserver gir1.2-gst-plugins-base-1.0 gir1.2-gstreamer-1.0
  gir1.2-gtk-3.0 gir1.2-packagekitglib-1.0 gir1.2-soup-2.4
  gir1.2-unity-5.0 glib-networking glib-networking-common
  glib-networking-services gnome-calendar gnome-font-viewer
  gnome-menus gnome-session-bin gnome-session-common
  gnome-settings-daemon-schemas gnome-software gnome-software-common
  gnome-sudoku gnome-system-monitor gnupg gpgv grep grub-common
  grub-pc grub-pc-bin grub2-common gstreamer1.0-alsa
  gstreamer1.0-plugins-base gstreamer1.0-plugins-base-apps
  gstreamer1.0-plugins-good gstreamer1.0-pulseaudio
  gstreamer1.0-tools gstreamer1.0-x gtk2-engines-murrine gvfs
  gvfs-backends gvfs-bin gvfs-common gvfs-daemons gvfs-fuse gvfs-libs
  imagemagick imagemagick-6.q16 imagemagick-common
  indicator-bluetooth init init-system-helpers initramfs-tools
  initramfs-tools-bin initramfs-tools-core isc-dhcp-client
  isc-dhcp-common keyboard-configuration klibc-utils
  language-selector-common language-selector-gnome less
  libaccountsservice0 libapparmor-perl libapparmor1
  libappstream-glib8 libappstream3 libapt-inst2.0 libapt-pkg5.0
  libarchive13 libasan2 libatomic1 libbamf3-2 libbind9-140 libblkid1
  libboost-date-time1.58.0 libboost-filesystem1.58.0
  libboost-iostreams1.58.0 libboost-system1.58.0 libbrlapi0.6
  libcc1-0 libcilkrts5 libcompizconfig0 libcupsfilters1 libcurl3
  libcurl3-gnutls libdecoration0 libdfu1 libdns-export162 libdns162
  libdpkg-perl libdrm-amdgpu1 libdrm-intel1 libdrm-nouveau2
  libdrm-radeon1 libdrm2 libegl1-mesa libexpat1 libfdisk1
  libfontconfig1 libfontembed1 libframe6 libfuse2 libfwupd1
  libgail-3-0 libgbm1 libgcc-5-dev libgcrypt20 libgd3 libgl1-mesa-dri
  libgl1-mesa-glx libglapi-mesa libglib2.0-0 libglib2.0-bin
  libglib2.0-data libgnome-menu-3-0 libgnutls-openssl27 libgnutls30
  libgomp1 libgstreamer-plugins-base1.0-0
  libgstreamer-plugins-good1.0-0 libgstreamer1.0-0 libgtk-3-0
  libgtk-3-bin libgtk-3-common libharfbuzz-icu0 libharfbuzz0b
  libidn11 libimobiledevice6 libisc-export160 libisc160 libisccc140
  libisccfg140 libitm1 libklibc libksba8 libldap-2.4-2
  liblightdm-gobject-1-0 libllvm3.8 liblsan0 liblwres141
  libmagickcore-6.q16-2 libmagickcore-6.q16-2-extra
  libmagickwand-6.q16-2 libmetacity-private3a libmount1 libmpx0
  libnautilus-extension1a libndp0 libnm-glib-vpn1 libnm-glib4
  libnm-gtk-common libnm-gtk0 libnm-util2 libnm0 libnma-common
  libnma0 libnspr4 libnss3 libnss3-nssdb libnux-4.0-0
  libnux-4.0-common liboxideqt-qmlplugin liboxideqtcore0
  liboxideqtquick0 libpackagekit-glib2-16 libpam-systemd libplymouth4
  libpoppler-glib8 libpoppler58 libpython2.7 libpython2.7-minimal
  libpython2.7-stdlib libpython3.5 libpython3.5-minimal
  libpython3.5-stdlib libqt5core5a libqt5dbus5 libqt5gui5
  libqt5network5 libqt5opengl5 libqt5printsupport5 libqt5sql5
  libqt5sql5-sqlite libqt5test5 libqt5widgets5 libqt5xml5
  libquadmath0 libsmartcols1 libsmbclient libsoup-gnome2.4-1
  libsoup2.4-1 libssl1.0.0 libstdc++-5-dev libstdc++6 libsystemd0
  libtasn1-6 libtevent0 libtsan0 libubsan0 libudev1
  libunity-control-center1 libunity-core-6.0-9
  libunity-protocol-private0 libunity-scopes-json-def-desktop
  libunity-settings-daemon1 libunity9 libupower-glib3 libusbmuxd4
  libuuid1 libwayland-egl1-mesa libwbclient0 libwhoopsie0
  libxatracker2 libxml2 light-themes lightdm linux-firmware
  linux-generic linux-headers-generic linux-image-generic
  linux-libc-dev lsb-base lsb-release lshw metacity-common mount
  mtr-tiny nautilus nautilus-data network-manager
  network-manager-gnome nux-tools openssh-client openssl
  oxideqt-codecs plymouth plymouth-label plymouth-theme-ubuntu-logo
  plymouth-theme-ubuntu-text poppler-utils printer-driver-brlaser
  python2.7 python2.7-minimal python3-apport python3-brlapi
  python3-commandnotfound python3-distupgrade python3-problem-report
  python3-pyparsing python3-software-properties python3-urllib3
  python3.5 python3.5-minimal samba-libs sbsigntool shared-mime-info
  snapd software-properties-common software-properties-gtk sudo
  suru-icon-theme systemd systemd-sysv thermald tzdata ubuntu-artwork
  ubuntu-core-launcher ubuntu-docs ubuntu-drivers-common
  ubuntu-mobile-icons ubuntu-mono ubuntu-release-upgrader-core
  ubuntu-release-upgrader-gtk ubuntu-session ubuntu-software udev
  unity unity-control-center unity-control-center-faces
  unity-lens-applications unity-schemas unity-scopes-runner
  unity-services unity-settings-daemon uno-libs3 update-notifier
  update-notifier-common upower upstart ure util-linux uuid-runtime
  vim-common vim-tiny vino wget whoopsie xbrlapi xdiagnose xinit
  xserver-common xserver-xorg-core xserver-xorg-video-intel
354 upgraded, 5 newly installed, 0 to remove and 0 not upgraded.
Need to get 418 MB of archives.
After this operation, 333 MB of additional disk space will be used.
Do you want to continue? [Y/n]
```



## 安裝 openssh-server


```
$ sudo apt-get install openssh-server
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libpango1.0-0 libpangox-1.0-0
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  ncurses-term openssh-sftp-server ssh-import-id
Suggested packages:
  ssh-askpass rssh molly-guard monkeysphere
The following NEW packages will be installed:
  ncurses-term openssh-server openssh-sftp-server ssh-import-id
0 upgraded, 4 newly installed, 0 to remove and 0 not upgraded.
Need to get 636 kB of archives.
After this operation, 5145 kB of additional disk space will be used.
Do you want to continue? [Y/n]
```


修改設定檔： /etc/ssh/sshd_config


```
# PermitRootLogin prohibit-password
PermitRootLogin No # 不允許
```


重啟 SSH Server


```
$ sudo /etc/init.d/ssh restart
```



## 安裝 Vim


```
$ sudo apt install vim
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libpango1.0-0 libpangox-1.0-0
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  vim-runtime
Suggested packages:
  ctags vim-doc vim-scripts vim-gnome-py2 | vim-gtk-py2 | vim-gtk3-py2 | vim-athena-py2 | vim-nox-py2
The following NEW packages will be installed:
  vim vim-runtime
0 upgraded, 2 newly installed, 0 to remove and 0 not upgraded.
Need to get 6210 kB of archives.
After this operation, 30.0 MB of additional disk space will be used.
Do you want to continue? [Y/n]
```



## 安裝 tmux


```
$ sudo apt install tmux
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libpango1.0-0 libpangox-1.0-0
Use 'sudo apt autoremove' to remove them.
The following NEW packages will be installed:
  tmux
0 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 223 kB of archives.
After this operation, 601 kB of additional disk space will be used.
```



## 安裝虛擬機工具


```
$ sudo apt install open-vm-tools open-vm-tools-desktop
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libpango1.0-0 libpangox-1.0-0
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  dkms libdumbnet1 libgtkmm-2.4-1v5 libmspack0 open-vm-tools-dkms zerofree
The following NEW packages will be installed:
  dkms libdumbnet1 libgtkmm-2.4-1v5 libmspack0 open-vm-tools open-vm-tools-desktop open-vm-tools-dkms zerofree
0 upgraded, 8 newly installed, 0 to remove and 0 not upgraded.
Need to get 1790 kB of archives.
After this operation, 14.3 MB of additional disk space will be used.
Do you want to continue? [Y/n]
```

