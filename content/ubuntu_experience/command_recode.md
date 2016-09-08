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
* [安裝 nodejs](#安裝-nodejs)
* [安裝 Heroku 工具](#安裝-Heroku-工具)
* [開啟共享資料夾功能](#開啟共享資料夾功能)



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



## 安裝 nodejs


```
$ sudo apt install nodejs npm
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libpango1.0-0 libpangox-1.0-0
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  gyp javascript-common libjs-inherits libjs-jquery libjs-node-uuid libjs-underscore libssl-dev libssl-doc libuv1 libuv1-dev node-abbrev node-ansi node-ansi-color-table
  node-archy node-async node-block-stream node-combined-stream node-cookie-jar node-delayed-stream node-forever-agent node-form-data node-fstream node-fstream-ignore
  node-github-url-from-git node-glob node-graceful-fs node-gyp node-inherits node-ini node-json-stringify-safe node-lockfile node-lru-cache node-mime node-minimatch
  node-mkdirp node-mute-stream node-node-uuid node-nopt node-normalize-package-data node-npmlog node-once node-osenv node-qs node-read node-read-package-json node-request
  node-retry node-rimraf node-semver node-sha node-sigmund node-slide node-tar node-tunnel-agent node-underscore node-which nodejs-dev python-pkg-resources zlib1g-dev
Suggested packages:
  apache2 | lighttpd | httpd node-hawk node-aws-sign node-oauth-sign node-http-signature debhelper python-setuptools
The following NEW packages will be installed:
  gyp javascript-common libjs-inherits libjs-jquery libjs-node-uuid libjs-underscore libssl-dev libssl-doc libuv1 libuv1-dev node-abbrev node-ansi node-ansi-color-table
  node-archy node-async node-block-stream node-combined-stream node-cookie-jar node-delayed-stream node-forever-agent node-form-data node-fstream node-fstream-ignore
  node-github-url-from-git node-glob node-graceful-fs node-gyp node-inherits node-ini node-json-stringify-safe node-lockfile node-lru-cache node-mime node-minimatch
  node-mkdirp node-mute-stream node-node-uuid node-nopt node-normalize-package-data node-npmlog node-once node-osenv node-qs node-read node-read-package-json node-request
  node-retry node-rimraf node-semver node-sha node-sigmund node-slide node-tar node-tunnel-agent node-underscore node-which nodejs nodejs-dev npm python-pkg-resources
  zlib1g-dev
0 upgraded, 61 newly installed, 0 to remove and 0 not upgraded.
Need to get 8722 kB of archives.
After this operation, 41.5 MB of additional disk space will be used.
Do you want to continue? [Y/n]
```


版本過舊


```
$ nodejs -v
v4.2.6
```


參考教學安裝最新版


```
$ curl -sl https://deb.nodesource.com/setup_6.x | sudo -E bash -

## Installing the NodeSource Node.js v6.x repo...


## Populating apt-get cache...

+ apt-get update
Hit:1 http://tw.archive.ubuntu.com/ubuntu xenial InRelease
Hit:2 http://tw.archive.ubuntu.com/ubuntu xenial-updates InRelease
Hit:3 http://tw.archive.ubuntu.com/ubuntu xenial-backports InRelease
Hit:4 http://security.ubuntu.com/ubuntu xenial-security InRelease
Reading package lists... Done

## Confirming "xenial" is supported...

+ curl -sLf -o /dev/null 'https://deb.nodesource.com/node_6.x/dists/xenial/Release'

## Adding the NodeSource signing key to your keyring...

+ curl -s https://deb.nodesource.com/gpgkey/nodesource.gpg.key | apt-key add -
OK

## Creating apt sources list file for the NodeSource Node.js v6.x repo...

+ echo 'deb https://deb.nodesource.com/node_6.x xenial main' > /etc/apt/sources.list.d/nodesource.list
+ echo 'deb-src https://deb.nodesource.com/node_6.x xenial main' >> /etc/apt/sources.list.d/nodesource.list

## Running `apt-get update` for you...

+ apt-get update
Hit:1 http://tw.archive.ubuntu.com/ubuntu xenial InRelease
Hit:2 http://tw.archive.ubuntu.com/ubuntu xenial-updates InRelease
Hit:3 http://tw.archive.ubuntu.com/ubuntu xenial-backports InRelease
Hit:4 http://security.ubuntu.com/ubuntu xenial-security InRelease
Get:5 https://deb.nodesource.com/node_6.x xenial InRelease [3914 B]
Get:6 https://deb.nodesource.com/node_6.x xenial/main Sources [762 B]
Get:7 https://deb.nodesource.com/node_6.x xenial/main amd64 Packages [968 B]
Get:8 https://deb.nodesource.com/node_6.x xenial/main i386 Packages [964 B]
Fetched 6608 B in 1s (3596 B/s)
Reading package lists... Done

## Run `apt-get install nodejs` (as root) to install Node.js v6.x and npm
```


```
$ sudo apt install nodejs
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following packages were automatically installed and are no longer required:
  gyp javascript-common libjs-inherits libjs-jquery libjs-node-uuid libjs-underscore libpango1.0-0
  libpangox-1.0-0 libssl-dev libssl-doc libuv1 libuv1-dev node-abbrev node-ansi node-ansi-color-table
  node-archy node-async node-block-stream node-combined-stream node-cookie-jar node-delayed-stream
  node-forever-agent node-form-data node-fstream node-fstream-ignore node-github-url-from-git node-glob
	node-graceful-fs node-gyp node-inherits node-ini node-json-stringify-safe node-lockfile node-lru-cache
  node-mime node-minimatch node-mkdirp node-mute-stream node-node-uuid node-nopt node-normalize-package-data
  node-npmlog node-once node-osenv node-qs node-read node-read-package-json node-request
  node-retry node-rimraf node-semver node-sha node-sigmund node-slide node-tar node-tunnel-agent
  node-underscore node-which python-pkg-resources zlib1g-dev
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  rlwrap
The following packages will be REMOVED:
  nodejs-dev npm
The following NEW packages will be installed:
  rlwrap
The following packages will be upgraded:
  nodejs
1 upgraded, 1 newly installed, 2 to remove and 0 not upgraded.
Need to get 10.2 MB of archives.
After this operation, 25.4 MB of additional disk space will be used.
Do you want to continue? [Y/n]
```


```
$ node -v
v6.5.0
$ nodejs -v
v6.5.0
```



## 安裝 Heroku 工具


```
$ wget -O- https://toolbelt.hero
ku.com/install-ubuntu.sh | sh
--2016-09-06 19:14:20--  https://toolbelt.heroku.com/install-ubuntu.sh
Resolving toolbelt.heroku.com (toolbelt.heroku.com)... 50.19.124.218, 54.225.
160.167, 54.225.165.73
Connecting to toolbelt.heroku.com (toolbelt.heroku.com)|50.19.124.218|:443...
 connected.
HTTP request sent, awaiting response... 200 OK
Length: 719 [text/plain]
Saving to: ‘STDOUT’

-                     0%[                 ]       0  --.-KB/s               T
his script requires superuser access to install apt packages.
You will be prompted for your password by sudo.
-                   100%[================>]     719  --.-KB/s    in 0s

2016-09-06 19:14:21 (79.4 MB/s) - written to stdout [719/719]

[sudo] password for bwaycer:
--2016-09-06 19:14:34--  https://toolbelt.heroku.com/apt/release.key
Resolving toolbelt.heroku.com (toolbelt.heroku.com)... 54.225.165.73, 50.19.1
24.218, 54.225.160.167
Connecting to toolbelt.heroku.com (toolbelt.heroku.com)|54.225.165.73|:443...
 connected.
HTTP request sent, awaiting response... 200 OK
Length: 1737 (1.7K) [application/octet-stream]
Saving to: ‘STDOUT’

-                   100%[================>]   1.70K  --.-KB/s    in 0s

2016-09-06 19:14:35 (408 MB/s) - written to stdout [1737/1737]

OK
Hit:1 http://tw.archive.ubuntu.com/ubuntu xenial InRelease
Get:2 http://tw.archive.ubuntu.com/ubuntu xenial-updates InRelease [95.7 kB]
Hit:3 http://tw.archive.ubuntu.com/ubuntu xenial-backports InRelease
Get:4 http://tw.archive.ubuntu.com/ubuntu xenial-updates/universe amd64 Packa
ges [323 kB]
Get:5 http://tw.archive.ubuntu.com/ubuntu xenial-updates/universe i386 Packag
es [320 kB]
Hit:6 http://security.ubuntu.com/ubuntu xenial-security InRelease
Ign:7 http://toolbelt.heroku.com/ubuntu ./ InRelease
Hit:9 https://deb.nodesource.com/node_6.x xenial InRelease
Get:8 http://toolbelt.heroku.com/ubuntu ./ Release [1609 B]
Get:10 http://toolbelt.heroku.com/ubuntu ./ Release.gpg [473 B]
Get:11 http://toolbelt.heroku.com/ubuntu ./ Packages [722 B]
Fetched 742 kB in 3s (245 kB/s)
Reading package lists... Done
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following packages were automatically installed and are no longer require
d:
  gyp libjs-inherits libjs-node-uuid libjs-underscore libpango1.0-0
  libpangox-1.0-0 libssl-dev libssl-doc libuv1 libuv1-dev node-abbrev
  node-ansi node-ansi-color-table node-archy node-async node-block-stream
  node-combined-stream node-cookie-jar node-delayed-stream
  node-forever-agent node-form-data node-fstream node-fstream-ignore
  node-github-url-from-git node-glob node-graceful-fs node-gyp
  node-inherits node-ini node-json-stringify-safe node-lockfile
  node-lru-cache node-mime node-minimatch node-mkdirp node-mute-stream
  node-node-uuid node-nopt node-normalize-package-data node-npmlog
  node-once node-osenv node-qs node-read node-read-package-json
  node-request node-retry node-rimraf node-semver node-sha node-sigmund
  node-slide node-tar node-tunnel-agent node-underscore node-which
  python-pkg-resources zlib1g-dev
Use 'sudo apt autoremove' to remove them.
The following additional packages will be installed:
  fonts-lato heroku libruby2.3 rake ruby ruby-did-you-mean ruby-minitest
  ruby-net-telnet ruby-power-assert ruby-test-unit ruby2.3
  rubygems-integration
Suggested packages:
  ri ruby-dev bundler
The following NEW packages will be installed:
  fonts-lato heroku heroku-toolbelt libruby2.3 rake ruby ruby-did-you-mean
  ruby-minitest ruby-net-telnet ruby-power-assert ruby-test-unit ruby2.3
  rubygems-integration
0 upgraded, 13 newly installed, 0 to remove and 0 not upgraded.
Need to get 7710 kB of archives.
After this operation, 26.8 MB of additional disk space will be used.
```



## 開啟共享資料夾功能


參考 [vmware workstation 12 使用open-vm-tools配置ubuntu共享文件夹 - ok2222991 的个人空间 - 开源中国社区](http://my.oschina.net/u/1158620/blog/712253)


```
$ cd /etc/systemd/system
$ sudo touch mnt.hgfs.service
```


```
$ sudo vim mnt.hgfs.service
[Unit]

Description=Load VMware shared folders

Requires=vmware-vmblock-fuse.service

After=vmware-vmblock-fuse.service

ConditionPathExists=.host:/

ConditionVirtualization=vmware



[Service]

Type=oneshot

RemainAfterExit=yes

ExecStart=

ExecStart=/usr/bin/vmhgfs-fuse -o allow_other -o auto_unmount .host:/ /mnt/hgfs





[Install]

WantedBy=multi-user.target
```


```
$ sudo systemctl enable mnt.hgfs.service
Created symlink from /etc/systemd/system/multi-user.target.wants/mnt.hgfs.service to /etc/systemd/system/mnt.hgfs.service.
```


```
$ cd /mnt
$ sudo mkdir hgfs
$ sudo reboot
```

