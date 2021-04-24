# For letter r, information about installed packages

<details>
<summary>radeon-profile</summary>

```
Из репозитор : fedora
Краткое опис : Application to read current clocks of ATi Radeon cards
URL          : https://github.com/marazmista/radeon-profile
Лицензия     : GPLv2+
Описание     : Simple application to read current clocks of ATi Radeon cards (xf86-video-ati,
             : xf86-video-amdgpu).
             : 
             : Functionality:
             : 
             : - Monitoring of basic GPU parameters (frequencies, voltages, usage,
             :   temperature, fan speed)
             : - DPM profiles and power levels
             : - Fan control (HD 7000+), definition of multiple custom curves or fixed speed
             : - Overclocking (amdgpu) (Wattman, Overdrive, PowerPlay etc)
             : - Per app profiles/Event definitions (i.e. change fan profile when temp above
             :   defined or set DPM to high when selected binary executed)
             : - Define binaries to run with set of environment variablees (i.e. GALLIUM_HUD,
             :   MESA, LIBGL etc)
```

</details>

<details>
<summary>radeon-profile-daemon</summary>

```
Из репозитор : fedora
Краткое опис : Daemon for radeon-profile GUI
URL          : https://github.com/marazmista/radeon-profile-daemon
Лицензия     : GPLv2+
Описание     : System daemon for reading info about Radeon GPU clocks and volts as well as
             : control card power profiles so the GUI radeon-profile application can be run
             : as normal user.
             : 
             : Supports opensource xf86-video-ati and xf86-video-amdgpu drivers.
```

</details>

<details>
<summary>radeontool</summary>

```
Из репозитор : fedora
Краткое опис : Backlight and video output configuration tool for radeon cards
URL          : http://people.freedesktop.org/~airlied/radeontool/
Лицензия     : zlib
Описание     : radeontool is used for debugging radeon related issues. In the past it has
             : been used for backlight control, but this should no longer be required.
```

</details>

<details>
<summary>radeontop</summary>

```
Из репозитор : fedora
Краткое опис : AMD Radeon video cards monitoring utility
URL          : https://github.com/clbr/radeontop
Лицензия     : GPLv3
Описание     : RadeonTop is a monitoring utility for AMD Radeon cards from R600 and up.
```

</details>

<details>
<summary>radvd</summary>

```
Из репозитор : anaconda
Краткое опис : A Router Advertisement daemon
URL          : http://www.litech.org/radvd/
Лицензия     : BSD with advertising
Описание     : radvd is the router advertisement daemon for IPv6.  It listens to router
             : solicitations and sends router advertisements as described in "Neighbor
             : Discovery for IP Version 6 (IPv6)" (RFC 2461).  With these advertisements
             : hosts can automatically configure their addresses and some other
             : parameters.  They also can choose a default router based on these
             : advertisements.
             : 
             : Install radvd if you are setting up IPv6 network and/or Mobile IPv6
             : services.
```

</details>

<details>
<summary>raptor2</summary>

```
Из репозитор : anaconda
Краткое опис : RDF Parser Toolkit for Redland
URL          : http://librdf.org/raptor/
Лицензия     : GPLv2+ or LGPLv2+ or ASL 2.0
Описание     : Raptor is the RDF Parser Toolkit for Redland that provides
             : a set of standalone RDF parsers, generating triples from RDF/XML
             : or N-Triples.
```

</details>

<details>
<summary>rasqal</summary>

```
Из репозитор : anaconda
Краткое опис : RDF Query Library
URL          : http://librdf.org/rasqal/
Лицензия     : LGPLv2+ or ASL 2.0
Описание     : Rasqal is a library providing full support for querying Resource
             : Description Framework (RDF) including parsing query syntaxes, constructing
             : the queries, executing them and returning result formats.  It currently
             : handles the RDF Data Query Language (RDQL) and SPARQL Query language.
```

</details>

<details>
<summary>rav1e-libs</summary>

```
Из репозитор : updates-testing
Краткое опис : Library files for rav1e
URL          : https://crates.io/crates/rav1e
Лицензия     : BSD and ASL 2.0 and ISC and MIT and zlib
Описание     : Library files for rav1e, the fastest and safest AV1 encoder.
```

</details>

<details>
<summary>rb_libtorrent</summary>

```
Из репозитор : updates-testing
Краткое опис : A C++ BitTorrent library aiming to be the best alternative
URL          : https://www.libtorrent.org
Лицензия     : BSD
Описание     : rb_libtorrent is a C++ library that aims to be a good alternative to all
             : the other BitTorrent implementations around. It is a library and not a full
             : featured client, although it comes with a few working example clients.
             : 
             : Its main goals are to be very efficient (in terms of CPU and memory usage) as
             : well as being very easy to use both as a user and developer.
```

</details>

<details>
<summary>rdiff-backup</summary>

```
Из репозитор : fedora
Краткое опис : Convenient and transparent local/remote incremental mirror/backup
URL          : https://rdiff-backup.net/
Лицензия     : GPLv2+
Описание     : rdiff-backup is a script, written in Python, that backs up one
             : directory to another and is intended to be run periodically (nightly
             : from cron for instance). The target directory ends up a copy of the
             : source directory, but extra reverse diffs are stored in the target
             : directory, so you can still recover files lost some time ago. The idea
             : is to combine the best features of a mirror and an incremental
             : backup. rdiff-backup can also operate in a bandwidth efficient manner
             : over a pipe, like rsync. Thus you can use rdiff-backup and ssh to
             : securely back a hard drive up to a remote location, and only the
             : differences from the previous backup will be transmitted.
```

</details>

<details>
<summary>re2</summary>

```
Эпоха        : 1
Из репозитор : updates-testing
Краткое опис : C++ fast alternative to backtracking RE engines
URL          : http://github.com/google/re2/
Лицензия     : BSD
Описание     : RE2 is a C++ library providing a fast, safe, thread-friendly alternative to
             : backtracking regular expression engines like those used in PCRE, Perl, and
             : Python.
             : 
             : Backtracking engines are typically full of features and convenient syntactic
             : sugar but can be forced into taking exponential amounts of time on even small
             : inputs.
             : 
             : In contrast, RE2 uses automata theory to guarantee that regular expression
             : searches run in time linear in the size of the input, at the expense of some
             : missing features (e.g back references and generalized assertions).
```

</details>

<details>
<summary>readline</summary>

```
Из репозитор : anaconda
Краткое опис : A library for editing typed command lines
URL          : https://tiswww.case.edu/php/chet/readline/rltop.html
Лицензия     : GPLv3+
Описание     : The Readline library provides a set of functions that allow users to
             : edit command lines. Both Emacs and vi editing modes are available. The
             : Readline library includes additional functions for maintaining a list
             : of previously-entered command lines for recalling or editing those
             : lines, and for performing csh-like history expansion on previous
             : commands.
```

</details>

<details>
<summary>realmd</summary>

```
Из репозитор : anaconda
Краткое опис : Kerberos realm enrollment service
URL          : https://gitlab.freedesktop.org/realmd/realmd
Лицензия     : LGPLv2+
Описание     : realmd is a DBus system service which manages discovery and enrollment in realms
             : and domains like Active Directory or IPA. The control center uses realmd as the
             : back end to 'join' a domain simply and automatically configure things correctly.
```

</details>

<details>
<summary>realmd</summary>

```
Из репозитор : updates-testing
Краткое опис : Kerberos realm enrollment service
URL          : https://gitlab.freedesktop.org/realmd/realmd
Лицензия     : LGPLv2+
Описание     : realmd is a DBus system service which manages discovery and enrollment in realms
             : and domains like Active Directory or IPA. The control center uses realmd as the
             : back end to 'join' a domain simply and automatically configure things correctly.
```

</details>

<details>
<summary>rear</summary>

```
Из репозитор : fedora
Краткое опис : Relax-and-Recover is a Linux disaster recovery and system migration tool
URL          : http://relax-and-recover.org/
Лицензия     : GPLv3
Описание     : Relax-and-Recover is the leading Open Source disaster recovery and system
             : migration solution. It comprises of a modular
             : frame-work and ready-to-go workflows for many common situations to produce
             : a bootable image and restore from backup using this image. As a benefit,
             : it allows to restore to different hardware and can therefore be used as
             : a migration tool as well.
             : 
             : Currently Relax-and-Recover supports various boot media (incl. ISO, PXE,
             : OBDR tape, USB or eSATA storage), a variety of network protocols (incl.
             : sftp, ftp, http, nfs, cifs) as well as a multitude of backup strategies
             : (incl.  IBM TSM, MircroFocus Data Protector, Symantec NetBackup, EMC NetWorker,
             : Bacula, Bareos, BORG, Duplicity, rsync).
             : 
             : Relax-and-Recover was designed to be easy to set up, requires no maintenance
             : and is there to assist when disaster strikes. Its setup-and-forget nature
             : removes any excuse for not having a disaster recovery solution implemented.
             : 
             : Professional services and support are available.
```

</details>

<details>
<summary>redhat-menus</summary>

```
Из репозитор : anaconda
Краткое опис : Configuration and data files for the desktop menus
URL          : http://www.redhat.com
Лицензия     : GPL+
Описание     : This package contains the XML files that describe the menu layout for
             : GNOME and KDE, and the .desktop files that define the names and icons
             : of "subdirectories" in the menus.
```

</details>

<details>
<summary>redhat-rpm-config</summary>

```
Из репозитор : updates-testing
Краткое опис : Red Hat specific rpm configuration files
URL          : https://src.fedoraproject.org/rpms/redhat-rpm-config
Лицензия     : GPL+
Описание     : Red Hat specific rpm configuration files.
```

</details>

<details>
<summary>redland</summary>

```
Из репозитор : anaconda
Краткое опис : RDF Application Framework
URL          : http://librdf.org/
Лицензия     : LGPLv2+ or ASL 2.0
Описание     : Redland is a library that provides a high-level interface for RDF
             : (Resource Description Framework) implemented in an object-based API.
             : It is modular and supports different RDF/XML parsers, storage
             : mechanisms and other elements. Redland is designed for applications
             : developers to provide RDF support in their applications as well as
             : for RDF developers to experiment with the technology.
```

</details>

<details>
<summary>redland</summary>

```
Из репозитор : updates-testing
Краткое опис : RDF Application Framework
URL          : http://librdf.org/
Лицензия     : LGPLv2+ or ASL 2.0
Описание     : Redland is a library that provides a high-level interface for RDF
             : (Resource Description Framework) implemented in an object-based API.
             : It is modular and supports different RDF/XML parsers, storage
             : mechanisms and other elements. Redland is designed for applications
             : developers to provide RDF support in their applications as well as
             : for RDF developers to experiment with the technology.
```

</details>

<details>
<summary>remmina</summary>

```
Из репозитор : fedora
Краткое опис : Remote Desktop Client
URL          : http://remmina.org
Лицензия     : GPLv2+ and MIT
Описание     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
             : system administrators and travelers, who need to work with lots of remote
             : computers in front of either large monitors or tiny net-books.
             : 
             : Remmina supports multiple network protocols in an integrated and consistent
             : user interface. Currently RDP, VNC, XDMCP and SSH are supported.
             : 
             : Please don't forget to install the plugins for the protocols you want to use.
```

</details>

<details>
<summary>remmina-plugins-exec</summary>

```
Из репозитор : fedora
Краткое опис : External execution plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
Лицензия     : GPLv2+ and MIT
Описание     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
             : system administrators and travelers, who need to work with lots of remote
             : computers in front of either large monitors or tiny net-books.
             : 
             : This package contains the plugin to execute external processes (commands or
             : applications) from the Remmina window.
```

</details>

<details>
<summary>remmina-plugins-nx</summary>

```
Из репозитор : fedora
Краткое опис : NX plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
Лицензия     : GPLv2+ and MIT
Описание     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
             : system administrators and travelers, who need to work with lots of remote
             : computers in front of either large monitors or tiny net-books.
             : 
             : This package contains the NX plugin for the Remmina remote desktop client.
```

</details>

<details>
<summary>remmina-plugins-rdp</summary>

```
Из репозитор : fedora
Краткое опис : RDP plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
Лицензия     : GPLv2+ and MIT
Описание     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
             : system administrators and travelers, who need to work with lots of remote
             : computers in front of either large monitors or tiny net-books.
             : 
             : This package contains the Remote Desktop Protocol (RDP) plugin for the Remmina
             : remote desktop client.
```

</details>

<details>
<summary>remmina-plugins-secret</summary>

```
Из репозитор : fedora
Краткое опис : Keyring integration for Remmina Remote Desktop Client
URL          : http://remmina.org
Лицензия     : GPLv2+ and MIT
Описание     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
             : system administrators and travelers, who need to work with lots of remote
             : computers in front of either large monitors or tiny net-books.
             : 
             : This package contains the plugin with keyring support for the Remmina remote
             : desktop client.
```

</details>

<details>
<summary>remmina-plugins-st</summary>

```
Из репозитор : fedora
Краткое опис : Simple Terminal plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
Лицензия     : GPLv2+ and MIT
Описание     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
             : system administrators and travelers, who need to work with lots of remote
             : computers in front of either large monitors or tiny net-books.
             : 
             : This package contains the Simple Terminal plugin for the Remmina remote desktop
             : client.
```

</details>

<details>
<summary>remmina-plugins-vnc</summary>

```
Из репозитор : fedora
Краткое опис : VNC plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
Лицензия     : GPLv2+ and MIT
Описание     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
             : system administrators and travelers, who need to work with lots of remote
             : computers in front of either large monitors or tiny net-books.
             : 
             : This package contains the VNC plugin for the Remmina remote desktop
             : client.
```

</details>

<details>
<summary>remmina-plugins-xdmcp</summary>

```
Из репозитор : fedora
Краткое опис : XDMCP plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
Лицензия     : GPLv2+ and MIT
Описание     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
             : system administrators and travelers, who need to work with lots of remote
             : computers in front of either large monitors or tiny net-books.
             : 
             : This package contains the XDMCP plugin for the Remmina remote desktop
             : client.
```

</details>

<details>
<summary>reptyr</summary>

```
Из репозитор : fedora
Краткое опис : Attach a running process to a new terminal
URL          : http://github.com/nelhage/reptyr
Лицензия     : MIT
Описание     : reptyr is a utility for taking an existing running program and
             : attaching it to a new terminal.  Started a long-running process over
             : ssh, but have to leave and don't want to interrupt it?  Just start a
             : screen, use reptyr to grab it, and then kill the ssh session and head
             : on home.
```

</details>

<details>
<summary>rest</summary>

```
Из репозитор : anaconda
Краткое опис : A library for access to RESTful web services
URL          : http://www.gnome.org
Лицензия     : LGPLv2
Описание     : This library was designed to make it easier to access web services that
             : claim to be "RESTful". A RESTful service should have urls that represent
             : remote objects, which methods can then be called on. The majority of services
             : don't actually adhere to this strict definition. Instead, their RESTful end
             : point usually has an API that is just simpler to use compared to other types
             : of APIs they may support (XML-RPC, for instance). It is this kind of API that
             : this library is attempting to support.
```

</details>

<details>
<summary>rgb</summary>

```
Из репозитор : fedora
Краткое опис : X color name database
URL          : https://www.x.org
Лицензия     : MIT
Описание     : This package includes both the list mapping X color names to RGB values
             : (rgb.txt) and, if configured to use a database for color lookup, the
             : rgb program to convert the text file into the binary database format.
```

</details>

<details>
<summary>rhash</summary>

```
Из репозитор : fedora
Краткое опис : Great utility for computing hash sums
URL          : https://github.com/rhash/RHash
Лицензия     : MIT
Описание     : RHash is a console utility for calculation  and verification of magnet links
             : and a wide range of hash sums like  CRC32,  MD4, MD5,  SHA1, SHA256, SHA512,
             : SHA3,   AICH,  ED2K,  Tiger,  DC++ TTH,  BitTorrent BTIH,   GOST R 34.11-94,
             : RIPEMD-160, HAS-160, EDON-R, Whirlpool and Snefru.
             : 
             : Hash sums are used to  ensure and verify integrity  of large volumes of data
             : for a long-term storing or transferring.
             : 
             : Features:
             :  * Output in a predefined (SFV, BSD-like) or a user-defined format.
             :  * Can calculate Magnet links.
             :  * Updating hash files (adding hash sums of files missing in the hash file).
             :  * Calculates several hash sums in one pass
             :  * Ability to process directories recursively.
             :  * Portability: the program works the same on Linux, *BSD or Windows.
```

</details>

<details>
<summary>rhythmbox</summary>

```
Из репозитор : anaconda
Краткое опис : Music Management Application
URL          : https://wiki.gnome.org/Apps/Rhythmbox
Лицензия     : GPLv2+ with exceptions and GFDL
Описание     : Rhythmbox is an integrated music management application based on the powerful
             : GStreamer media framework. It has a number of features, including an easy to
             : use music browser, searching and sorting, comprehensive audio format support
             : through GStreamer, Internet Radio support, playlists and more.
             : 
             : Rhythmbox is extensible through a plugin system.
```

</details>

<details>
<summary>rlwrap</summary>

```
Из репозитор : fedora
Краткое опис : Wrapper for GNU readline
URL          : https://github.com/hanslub42/rlwrap
Лицензия     : GPLv2+
Описание     : rlwrap is a 'readline wrapper' that uses the GNU readline library to
             : allow the editing of keyboard input for any other command. Input
             : history is remembered across invocations, separately for each command;
             : history completion and search work as in bash and completion word
             : lists can be specified on the command line.
```

</details>

<details>
<summary>rocm-opencl</summary>

```
Из репозитор : ROCm
Краткое опис : OpenCL: Open Computing Language on ROCclr
Лицензия     : unknown
Описание     : DESCRIPTION
             : ===========
             : 
             : This is an installer created using CPack (https://cmake.org). No additional installation instructions provided.
```

</details>

<details>
<summary>rocminfo</summary>

```
Краткое опис : ROCm system info utility
URL          : https://github.com/RadeonOpenCompute/rocminfo
Лицензия     : NCSA
Описание     : ROCm system info utility
```

</details>

<details>
<summary>rootfiles</summary>

```
Из репозитор : anaconda
Краткое опис : The basic required files for the root user's directory
Лицензия     : Public Domain
Описание     : The rootfiles package contains basic required files that are placed
             : in the root user's account.  These files are basically the same
             : as those in /etc/skel, which are placed in regular
             : users' home directories.
```

</details>

<details>
<summary>rootsh</summary>

```
Из репозитор : fedora
Краткое опис : Shell wrapper for auditing
URL          : http://sourceforge.net/projects/rootsh
Лицензия     : GPLv3+
Описание     : Rootsh is a wrapper for shells which logs all echoed keystrokes and
             : terminal output to a file and/or to syslog. Its main purpose is the
             : auditing of users who need a shell with root privileges. They start
             : rootsh through the sudo mechanism.
```

</details>

<details>
<summary>rpcbind</summary>

```
Из репозитор : anaconda
Краткое опис : Universal Addresses to RPC Program Number Mapper
URL          : http://nfsv4.bullopensource.org
Лицензия     : BSD
Описание     : The rpcbind utility is a server that converts RPC program numbers into
             : universal addresses.  It must be running on the host to be able to make
             : RPC calls on a server on that machine.
```

</details>

<details>
<summary>rpkg-common</summary>

```
Из репозитор : fedora
Краткое опис : Common files for rpkg
URL          : https://pagure.io/rpkg
Лицензия     : GPLv2+ and LGPLv2
Описание     : Common files for python2-rpkg and python3-rpkg.
```

</details>

<details>
<summary>rpm</summary>

```
Из репозитор : anaconda
Краткое опис : The RPM package management system
URL          : http://www.rpm.org/
Лицензия     : GPLv2+
Описание     : The RPM Package Manager (RPM) is a powerful command line driven
             : package management system capable of installing, uninstalling,
             : verifying, querying, and updating software packages. Each software
             : package consists of an archive of files along with information about
             : the package like its version, a description, etc.
```

</details>

<details>
<summary>rpm</summary>

```
Из репозитор : updates-testing
Краткое опис : The RPM package management system
URL          : http://www.rpm.org/
Лицензия     : GPLv2+
Описание     : The RPM Package Manager (RPM) is a powerful command line driven
             : package management system capable of installing, uninstalling,
             : verifying, querying, and updating software packages. Each software
             : package consists of an archive of files along with information about
             : the package like its version, a description, etc.
```

</details>

<details>
<summary>rpm-build</summary>

```
Из репозитор : updates-testing
Краткое опис : Scripts and executable programs used to build packages
URL          : http://www.rpm.org/
Лицензия     : GPLv2+
Описание     : The rpm-build package contains the scripts and executable programs
             : that are used to build packages using the RPM Package Manager.
```

</details>

<details>
<summary>rpm-build-libs</summary>

```
Из репозитор : anaconda
Краткое опис : Libraries for building RPM packages
URL          : http://www.rpm.org/
Лицензия     : GPLv2+ and LGPLv2+ with exceptions
Описание     : This package contains the RPM shared libraries for building packages.
```

</details>

<details>
<summary>rpm-build-libs</summary>

```
Из репозитор : updates-testing
Краткое опис : Libraries for building RPM packages
URL          : http://www.rpm.org/
Лицензия     : GPLv2+ and LGPLv2+ with exceptions
Описание     : This package contains the RPM shared libraries for building packages.
```

</details>

<details>
<summary>rpm-libs</summary>

```
Из репозитор : anaconda
Краткое опис : Libraries for manipulating RPM packages
URL          : http://www.rpm.org/
Лицензия     : GPLv2+ and LGPLv2+ with exceptions
Описание     : This package contains the RPM shared libraries.
```

</details>

<details>
<summary>rpm-libs</summary>

```
Из репозитор : updates-testing
Краткое опис : Libraries for manipulating RPM packages
URL          : http://www.rpm.org/
Лицензия     : GPLv2+ and LGPLv2+ with exceptions
Описание     : This package contains the RPM shared libraries.
```

</details>

<details>
<summary>rpm-plugin-selinux</summary>

```
Из репозитор : anaconda
Краткое опис : Rpm plugin for SELinux functionality
URL          : http://www.rpm.org/
Лицензия     : GPLv2+
Описание     : Rpm plugin for SELinux functionality.
```

</details>

<details>
<summary>rpm-plugin-selinux</summary>

```
Из репозитор : updates-testing
Краткое опис : Rpm plugin for SELinux functionality
URL          : http://www.rpm.org/
Лицензия     : GPLv2+
Описание     : Rpm plugin for SELinux functionality.
```

</details>

<details>
<summary>rpm-plugin-systemd-inhibit</summary>

```
Из репозитор : anaconda
Краткое опис : Rpm plugin for systemd inhibit functionality
URL          : http://www.rpm.org/
Лицензия     : GPLv2+
Описание     : This plugin blocks systemd from entering idle, sleep or shutdown while an rpm
             : transaction is running using the systemd-inhibit mechanism.
```

</details>

<details>
<summary>rpm-plugin-systemd-inhibit</summary>

```
Из репозитор : updates-testing
Краткое опис : Rpm plugin for systemd inhibit functionality
URL          : http://www.rpm.org/
Лицензия     : GPLv2+
Описание     : This plugin blocks systemd from entering idle, sleep or shutdown while an rpm
             : transaction is running using the systemd-inhibit mechanism.
```

</details>

<details>
<summary>rpm-sign-libs</summary>

```
Из репозитор : anaconda
Краткое опис : Libraries for signing RPM packages
URL          : http://www.rpm.org/
Лицензия     : GPLv2+ and LGPLv2+ with exceptions
Описание     : This package contains the RPM shared libraries for signing packages.
```

</details>

<details>
<summary>rpm-sign-libs</summary>

```
Из репозитор : updates-testing
Краткое опис : Libraries for signing RPM packages
URL          : http://www.rpm.org/
Лицензия     : GPLv2+ and LGPLv2+ with exceptions
Описание     : This package contains the RPM shared libraries for signing packages.
```

</details>

<details>
<summary>rpmdevtools</summary>

```
Из репозитор : fedora
Краткое опис : RPM Development Tools
URL          : https://pagure.io/rpmdevtools
Лицензия     : GPLv2+ and GPLv2
Описание     : This package contains scripts and (X)Emacs support files to aid in
             : development of RPM packages.
             : rpmdev-setuptree    Create RPM build tree within user's home directory
             : rpmdev-diff         Diff contents of two archives
             : rpmdev-newspec      Creates new .spec from template
             : rpmdev-rmdevelrpms  Find (and optionally remove) "development" RPMs
             : rpmdev-checksig     Check package signatures using alternate RPM keyring
             : rpminfo             Print information about executables and libraries
             : rpmdev-md5/sha*     Display checksums of all files in an archive file
             : rpmdev-vercmp       RPM version comparison checker
             : rpmdev-spectool     Expand and download sources and patches in specfiles
             : rpmdev-wipetree     Erase all files within dirs created by rpmdev-setuptree
             : rpmdev-extract      Extract various archives, "tar xvf" style
             : rpmdev-bumpspec     Bump revision in specfile
             : ...and many more.
```

</details>

<details>
<summary>rpmfusion-free-appstream-data</summary>

```
Из репозитор : rpmfusion-free
Краткое опис : Appstream metadata for the RPM Fusion free repository
URL          : http://rpmfusion.org
Лицензия     : CC0
Описание     : Appstream metadata for packages in the RPM Fusion free repository
```

</details>

<details>
<summary>rpmfusion-free-obsolete-packages</summary>

```
Из репозитор : rpmfusion-free
Краткое опис : A package to obsolete retired packages from rpmfusion-free
URL          : http://rpmfusion.org
Лицензия     : MIT
Описание     : This package exists only to obsolete other packages which need to be removed
             : from the RPM Fusion free for some reason.
```

</details>

<details>
<summary>rpmfusion-free-release</summary>

```
Из репозитор : @commandline
Краткое опис : RPM Fusion (free) Repository Configuration
URL          : http://rpmfusion.org
Лицензия     : BSD
Описание     : RPM Fusion free package repository files for yum and dnf
             : along with gpg public keys
```

</details>

<details>
<summary>rpmfusion-nonfree-appstream-data</summary>

```
Из репозитор : rpmfusion-nonfree
Краткое опис : Appstream metadata for the RPM Fusion nonfree repository
URL          : http://rpmfusion.org
Лицензия     : CC0
Описание     : Appstream metadata for packages in the RPM Fusion nonfree repository
```

</details>

<details>
<summary>rpmfusion-nonfree-release</summary>

```
Из репозитор : @commandline
Краткое опис : RPM Fusion (nonfree) Repository Configuration
URL          : http://rpmfusion.org
Лицензия     : BSD
Описание     : RPM Fusion nonfree package repository files for yum and dnf
             : along with gpg public keys
```

</details>

<details>
<summary>rpmlint</summary>

```
Из репозитор : fedora
Краткое опис : Tool for checking common errors in RPM packages
URL          : https://github.com/rpm-software-management/rpmlint
Лицензия     : GPLv2
Описание     : rpmlint is a tool for checking common errors in RPM packages. Binary
             : and source packages as well as spec files can be checked.
```

</details>

<details>
<summary>rsnapshot</summary>

```
Из репозитор : fedora
Краткое опис : Local and remote filesystem snapshot utility
URL          : https://rsnapshot.org/
Лицензия     : GPLv2+
Описание     : This is a remote backup program that uses rsync to take backup snapshots of
             : filesystems.  It uses hard links to save space on disk.
```

</details>

<details>
<summary>rsync</summary>

```
Из репозитор : anaconda
Краткое опис : A program for synchronizing files over a network
URL          : https://rsync.samba.org/
Лицензия     : GPLv3+
Описание     : Rsync uses a reliable algorithm to bring remote and host files into
             : sync very quickly. Rsync is fast because it just sends the differences
             : in the files over the network instead of sending the complete
             : files. Rsync is often used as a very powerful mirroring process or
             : just as a more capable replacement for the rcp command. A technical
             : report which describes the rsync algorithm is included in this
             : package.
```

</details>

<details>
<summary>rtkit</summary>

```
Из репозитор : anaconda
Краткое опис : Realtime Policy and Watchdog Daemon
URL          : http://git.0pointer.net/rtkit.git/
Лицензия     : GPLv3+ and BSD
Описание     : RealtimeKit is a D-Bus system service that changes the
             : scheduling policy of user processes/threads to SCHED_RR (i.e. realtime
             : scheduling mode) on request. It is intended to be used as a secure
             : mechanism to allow real-time scheduling to be used by normal user
             : processes.
```

</details>

<details>
<summary>ruby</summary>

```
Из репозитор : updates-testing
Краткое опис : An interpreter of object-oriented scripting language
URL          : https://www.ruby-lang.org/
Лицензия     : (Ruby or BSD) and Public Domain and MIT and CC0 and zlib and UCD
Описание     : Ruby is the interpreted scripting language for quick and easy
             : object-oriented programming.  It has many features to process text
             : files and to do system management tasks (as in Perl).  It is simple,
             : straight-forward, and extensible.
```

</details>

<details>
<summary>ruby-augeas</summary>

```
Из репозитор : fedora
Краткое опис : Ruby bindings for Augeas
URL          : http://augeas.net
Лицензия     : LGPLv2+
Описание     : Ruby bindings for augeas.
```

</details>

<details>
<summary>ruby-default-gems</summary>

```
Из репозитор : updates-testing
Краткое опис : Default gems which are part of Ruby StdLib
URL          : https://www.ruby-lang.org/
Лицензия     : (Ruby or BSD) and Public Domain and MIT and CC0 and zlib and UCD
Описание     : The .gemspec files and executables of default gems, which are part of Ruby
             : StdLib.
```

</details>

<details>
<summary>ruby-facter</summary>

```
Из репозитор : fedora
Краткое опис : Ruby bindings for facter
URL          : https://puppetlabs.com/facter
Лицензия     : ASL 2.0
Описание     : The ruby bindings for libfacter.
```

</details>

<details>
<summary>ruby-libs</summary>

```
Из репозитор : updates-testing
Краткое опис : Libraries necessary to run Ruby
URL          : https://www.ruby-lang.org/
Лицензия     : Ruby or BSD
Описание     : This package includes the libruby, necessary to run Ruby.
```

</details>

<details>
<summary>rubygem-bigdecimal</summary>

```
Из репозитор : updates-testing
Краткое опис : BigDecimal provides arbitrary-precision floating point decimal arithmetic
URL          : https://www.ruby-lang.org/
Лицензия     : Ruby or BSD
Описание     : Ruby provides built-in support for arbitrary precision integer arithmetic.
             : For example:
             : 
             : 42**13 -> 1265437718438866624512
             : 
             : BigDecimal provides similar support for very large or very accurate floating
             : point numbers. Decimal arithmetic is also useful for general calculation,
             : because it provides the correct answers people expect–whereas normal binary
             : floating point arithmetic often introduces subtle errors because of the
             : conversion between base 10 and base 2.
```

</details>

<details>
<summary>rubygem-bundler</summary>

```
Из репозитор : updates-testing
Краткое опис : Library and utilities to manage a Ruby application's gem dependencies
URL          : https://www.ruby-lang.org/
Лицензия     : MIT
Описание     : Bundler manages an application's dependencies through its entire life, across
             : many machines, systematically and repeatably.
```

</details>

<details>
<summary>rubygem-io-console</summary>

```
Из репозитор : updates-testing
Краткое опис : IO/Console is a simple console utilizing library
URL          : https://www.ruby-lang.org/
Лицензия     : (Ruby or BSD) and Public Domain and MIT and CC0 and zlib and UCD
Описание     : IO/Console provides very simple and portable access to console. It doesn't
             : provide higher layer features, such like curses and readline.
```

</details>

<details>
<summary>rubygem-json</summary>

```
Из репозитор : fedora
Краткое опис : A JSON implementation in Ruby
URL          : http://json.rubyforge.org
Лицензия     : Ruby or GPLv2
Описание     : This is a implementation of the JSON specification according
             : to RFC 4627 in Ruby.
             : You can think of it as a low fat alternative to XML,
             : if you want to store data to disk or transmit it over
             : a network rather than use a verbose markup language.
```

</details>

<details>
<summary>rubygem-multi_json</summary>

```
Из репозитор : fedora
Краткое опис : A common interface to multiple JSON libraries
URL          : https://github.com/intridea/multi_json
Лицензия     : MIT
Описание     : A common interface to multiple JSON libraries, including Oj, Yajl, the JSON
             : gem (with C-extensions), the pure-Ruby JSON gem, NSJSONSerialization, gson.rb,
             : JrJackson, and OkJson.
```

</details>

<details>
<summary>rubygem-pathspec</summary>

```
Из репозитор : fedora
Краткое опис : Use to match path patterns such as gitignore
URL          : https://rubygems.org/gems/pathspec
Лицензия     : ASL 2.0
Описание     : Use to match path patterns such as gitignore.
```

</details>

<details>
<summary>rubygem-psych</summary>

```
Из репозитор : updates-testing
Краткое опис : A libyaml wrapper for Ruby
URL          : https://www.ruby-lang.org/
Лицензия     : MIT
Описание     : Psych is a YAML parser and emitter. Psych leverages
             : libyaml[http://pyyaml.org/wiki/LibYAML] for its YAML parsing and emitting
             : capabilities. In addition to wrapping libyaml, Psych also knows how to
             : serialize and de-serialize most Ruby objects to and from the YAML format.
```

</details>

<details>
<summary>rubygem-rdoc</summary>

```
Из репозитор : updates-testing
Краткое опис : A tool to generate HTML and command-line documentation for Ruby projects
URL          : https://www.ruby-lang.org/
Лицензия     : GPLv2 and Ruby and MIT and OFL
Описание     : RDoc produces HTML and command-line documentation for Ruby projects.  RDoc
             : includes the 'rdoc' and 'ri' tools for generating and displaying online
             : documentation.
```

</details>

<details>
<summary>rubygem-rgen</summary>

```
Из репозитор : fedora
Краткое опис : Ruby Modelling and Generator Framework
URL          : https://github.com/mthiede/rgen
Лицензия     : MIT
Описание     : RGen is a framework for Model Driven Software Development (MDSD) in Ruby. This
             : means that it helps you build Metamodels, instantiate Models, modify and
             : transform Models and finally generate arbitrary textual content from it.
```

</details>

<details>
<summary>rubygem-ruby-shadow</summary>

```
Из репозитор : fedora
Краткое опис : Ruby shadow password module
URL          : https://github.com/apalmblad/ruby-shadow
Лицензия     : Public Domain
Описание     : This module provides access to shadow passwords on Linux and Solaris.
```

</details>

<details>
<summary>rubygems</summary>

```
Из репозитор : updates-testing
Краткое опис : The Ruby standard for packaging ruby libraries
URL          : https://www.ruby-lang.org/
Лицензия     : Ruby or MIT
Описание     : RubyGems is the Ruby standard for publishing and managing third party
             : libraries.
```

</details>

<details>
<summary>rubypick</summary>

```
Из репозитор : fedora
Краткое опис : Stub to allow choosing Ruby runtime
URL          : https://github.com/fedora-ruby/rubypick
Лицензия     : MIT
Описание     : Fedora /usr/bin/ruby stub to allow choosing Ruby runtime. Similarly to rbenv
             : or RVM, it allows non-privileged user to choose which is preferred Ruby
             : runtime for current task.
```

</details>

<details>
<summary>runc</summary>

```
Эпоха        : 2
Из репозитор : fedora
Краткое опис : CLI for running Open Containers
URL          : https://github.com/opencontainers/runc
Лицензия     : ASL 2.0
Описание     : The runc command can be used to start containers which are packaged
             : in accordance with the Open Container Initiative's specifications,
             : and to manage containers running under runc.
```

</details>

<details>
<summary>rust-srpm-macros</summary>

```
Из репозитор : fedora
Краткое опис : RPM macros for building Rust source packages
URL          : https://pagure.io/fedora-rust/rust2rpm
Лицензия     : MIT
Описание     : RPM macros for building Rust source packages.
```

</details>

<details>
<summary>rxvt-unicode</summary>

```
Из репозитор : fedora
Краткое опис : Unicode version of rxvt
URL          : http://software.schmorp.de/
Лицензия     : GPLv3
Описание     : rxvt-unicode is a clone of the well known terminal emulator rxvt, modified to
             : store text in Unicode (either UCS-2 or UCS-4) and to use locale-correct input
             : and output. It also supports mixing multiple fonts at the same time, including
             : Xft fonts.
```

</details>

<details>
<summary>rygel</summary>

```
Из репозитор : anaconda
Краткое опис : A collection of UPnP/DLNA services
URL          : https://wiki.gnome.org/Projects/Rygel
Лицензия     : LGPLv2+
Описание     : Rygel is a home media solution that allows you to easily share audio, video and
             : pictures, and control of media player on your home network. In technical terms
             : it is both a UPnP AV MediaServer and MediaRenderer implemented through a plug-in
             : mechanism. Interoperability with other devices in the market is achieved by
             : conformance to very strict requirements of DLNA and on the fly conversion of
             : media to format that client devices are capable of handling.
```

</details>

