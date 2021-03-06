# For first letter r, information about installation packages

<details>
<summary>radeon-profile</summary>

```
From repo    : fedora
Short desc   : Application to read current clocks of ATi Radeon cards
URL          : https://github.com/marazmista/radeon-profile
License      : GPLv2+
Descript     : Simple application to read current clocks of ATi Radeon cards (xf86-video-ati,
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
From repo    : fedora
Short desc   : Daemon for radeon-profile GUI
URL          : https://github.com/marazmista/radeon-profile-daemon
License      : GPLv2+
Descript     : System daemon for reading info about Radeon GPU clocks and volts as well as
             : control card power profiles so the GUI radeon-profile application can be run
             : as normal user.
             : 
             : Supports opensource xf86-video-ati and xf86-video-amdgpu drivers.
```

</details>

<details>
<summary>radeontool</summary>

```
From repo    : fedora
Short desc   : Backlight and video output configuration tool for radeon cards
URL          : http://people.freedesktop.org/~airlied/radeontool/
License      : zlib
Descript     : radeontool is used for debugging radeon related issues. In the past it has
             : been used for backlight control, but this should no longer be required.
```

</details>

<details>
<summary>radeontop</summary>

```
From repo    : fedora
Short desc   : AMD Radeon video cards monitoring utility
URL          : https://github.com/clbr/radeontop
License      : GPLv3
Descript     : RadeonTop is a monitoring utility for AMD Radeon cards from R600 and up.
```

</details>

<details>
<summary>radvd</summary>

```
From repo    : anaconda
Short desc   : A Router Advertisement daemon
URL          : http://www.litech.org/radvd/
License      : BSD with advertising
Descript     : radvd is the router advertisement daemon for IPv6.  It listens to router
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
From repo    : anaconda
Short desc   : RDF Parser Toolkit for Redland
URL          : http://librdf.org/raptor/
License      : GPLv2+ or LGPLv2+ or ASL 2.0
Descript     : Raptor is the RDF Parser Toolkit for Redland that provides
             : a set of standalone RDF parsers, generating triples from RDF/XML
             : or N-Triples.
```

</details>

<details>
<summary>rasqal</summary>

```
From repo    : anaconda
Short desc   : RDF Query Library
URL          : http://librdf.org/rasqal/
License      : LGPLv2+ or ASL 2.0
Descript     : Rasqal is a library providing full support for querying Resource
             : Description Framework (RDF) including parsing query syntaxes, constructing
             : the queries, executing them and returning result formats.  It currently
             : handles the RDF Data Query Language (RDQL) and SPARQL Query language.
```

</details>

<details>
<summary>rav1e-libs</summary>

```
From repo    : updates
Short desc   : Library files for rav1e
URL          : https://crates.io/crates/rav1e
License      : BSD and ASL 2.0 and ISC and MIT and zlib
Descript     : Library files for rav1e, the fastest and safest AV1 encoder.
```

</details>

<details>
<summary>rav1e-libs</summary>

```
From repo    : updates-testing
Short desc   : Library files for rav1e
URL          : https://crates.io/crates/rav1e
License      : BSD and ASL 2.0 and ISC and MIT and zlib
Descript     : Library files for rav1e, the fastest and safest AV1 encoder.
```

</details>

<details>
<summary>rb_libtorrent</summary>

```
From repo    : updates-testing
Short desc   : A C++ BitTorrent library aiming to be the best alternative
URL          : https://www.libtorrent.org
License      : BSD
Descript     : rb_libtorrent is a C++ library that aims to be a good alternative to all
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
From repo    : fedora
Short desc   : Convenient and transparent local/remote incremental mirror/backup
URL          : https://rdiff-backup.net/
License      : GPLv2+
Descript     : rdiff-backup is a script, written in Python, that backs up one
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
From repo    : updates-testing
Short desc   : C++ fast alternative to backtracking RE engines
URL          : http://github.com/google/re2/
License      : BSD
Descript     : RE2 is a C++ library providing a fast, safe, thread-friendly alternative to
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
From repo    : fedora
Short desc   : A library for editing typed command lines
URL          : https://tiswww.case.edu/php/chet/readline/rltop.html
License      : GPLv3+
Descript     : The Readline library provides a set of functions that allow users to
             : edit command lines. Both Emacs and vi editing modes are available. The
             : Readline library includes additional functions for maintaining a list
             : of previously-entered command lines for recalling or editing those
             : lines, and for performing csh-like history expansion on previous
             : commands.
```

</details>

<details>
<summary>readline</summary>

```
From repo    : anaconda
Short desc   : A library for editing typed command lines
URL          : https://tiswww.case.edu/php/chet/readline/rltop.html
License      : GPLv3+
Descript     : The Readline library provides a set of functions that allow users to
             : edit command lines. Both Emacs and vi editing modes are available. The
             : Readline library includes additional functions for maintaining a list
             : of previously-entered command lines for recalling or editing those
             : lines, and for performing csh-like history expansion on previous
             : commands.
```

</details>

<details>
<summary>readline-devel</summary>

```
From repo    : fedora
Short desc   : Files needed to develop programs which use the readline library
URL          : https://tiswww.case.edu/php/chet/readline/rltop.html
License      : GPLv3+
Descript     : The Readline library provides a set of functions that allow users to
             : edit typed command lines. If you want to develop programs that will
             : use the readline library, you need to have the readline-devel package
             : installed. You also need to have the readline package installed.
```

</details>

<details>
<summary>realmd</summary>

```
From repo    : anaconda
Short desc   : Kerberos realm enrollment service
URL          : https://gitlab.freedesktop.org/realmd/realmd
License      : LGPLv2+
Descript     : realmd is a DBus system service which manages discovery and enrollment in realms
             : and domains like Active Directory or IPA. The control center uses realmd as the
             : back end to 'join' a domain simply and automatically configure things correctly.
```

</details>

<details>
<summary>realmd</summary>

```
From repo    : updates-testing
Short desc   : Kerberos realm enrollment service
URL          : https://gitlab.freedesktop.org/realmd/realmd
License      : LGPLv2+
Descript     : realmd is a DBus system service which manages discovery and enrollment in realms
             : and domains like Active Directory or IPA. The control center uses realmd as the
             : back end to 'join' a domain simply and automatically configure things correctly.
```

</details>

<details>
<summary>rear</summary>

```
From repo    : fedora
Short desc   : Relax-and-Recover is a Linux disaster recovery and system migration tool
URL          : http://relax-and-recover.org/
License      : GPLv3
Descript     : Relax-and-Recover is the leading Open Source disaster recovery and system
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
From repo    : anaconda
Short desc   : Configuration and data files for the desktop menus
URL          : http://www.redhat.com
License      : GPL+
Descript     : This package contains the XML files that describe the menu layout for
             : GNOME and KDE, and the .desktop files that define the names and icons
             : of "subdirectories" in the menus.
```

</details>

<details>
<summary>redhat-rpm-config</summary>

```
From repo    : updates-testing
Short desc   : Red Hat specific rpm configuration files
URL          : https://src.fedoraproject.org/rpms/redhat-rpm-config
License      : GPL+
Descript     : Red Hat specific rpm configuration files.
```

</details>

<details>
<summary>redland</summary>

```
From repo    : anaconda
Short desc   : RDF Application Framework
URL          : http://librdf.org/
License      : LGPLv2+ or ASL 2.0
Descript     : Redland is a library that provides a high-level interface for RDF
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
From repo    : updates-testing
Short desc   : RDF Application Framework
URL          : http://librdf.org/
License      : LGPLv2+ or ASL 2.0
Descript     : Redland is a library that provides a high-level interface for RDF
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
From repo    : updates
Short desc   : Remote Desktop Client
URL          : http://remmina.org
License      : GPLv2+ and MIT
Descript     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
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
From repo    : updates
Short desc   : External execution plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
License      : GPLv2+ and MIT
Descript     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
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
From repo    : updates
Short desc   : NX plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
License      : GPLv2+ and MIT
Descript     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
             : system administrators and travelers, who need to work with lots of remote
             : computers in front of either large monitors or tiny net-books.
             : 
             : This package contains the NX plugin for the Remmina remote desktop client.
```

</details>

<details>
<summary>remmina-plugins-rdp</summary>

```
From repo    : updates
Short desc   : RDP plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
License      : GPLv2+ and MIT
Descript     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
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
From repo    : updates
Short desc   : Keyring integration for Remmina Remote Desktop Client
URL          : http://remmina.org
License      : GPLv2+ and MIT
Descript     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
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
From repo    : updates
Short desc   : Simple Terminal plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
License      : GPLv2+ and MIT
Descript     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
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
From repo    : updates
Short desc   : VNC plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
License      : GPLv2+ and MIT
Descript     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
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
From repo    : updates
Short desc   : XDMCP plugin for Remmina Remote Desktop Client
URL          : http://remmina.org
License      : GPLv2+ and MIT
Descript     : Remmina is a remote desktop client written in GTK+, aiming to be useful for
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
From repo    : fedora
Short desc   : Attach a running process to a new terminal
URL          : http://github.com/nelhage/reptyr
License      : MIT
Descript     : reptyr is a utility for taking an existing running program and
             : attaching it to a new terminal.  Started a long-running process over
             : ssh, but have to leave and don't want to interrupt it?  Just start a
             : screen, use reptyr to grab it, and then kill the ssh session and head
             : on home.
```

</details>

<details>
<summary>rest</summary>

```
From repo    : anaconda
Short desc   : A library for access to RESTful web services
URL          : http://www.gnome.org
License      : LGPLv2
Descript     : This library was designed to make it easier to access web services that
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
From repo    : fedora
Short desc   : X color name database
URL          : https://www.x.org
License      : MIT
Descript     : This package includes both the list mapping X color names to RGB values
             : (rgb.txt) and, if configured to use a database for color lookup, the
             : rgb program to convert the text file into the binary database format.
```

</details>

<details>
<summary>rhash</summary>

```
From repo    : fedora
Short desc   : Great utility for computing hash sums
URL          : https://github.com/rhash/RHash
License      : MIT
Descript     : RHash is a console utility for calculation  and verification of magnet links
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
From repo    : anaconda
Short desc   : Music Management Application
URL          : https://wiki.gnome.org/Apps/Rhythmbox
License      : GPLv2+ with exceptions and GFDL
Descript     : Rhythmbox is an integrated music management application based on the powerful
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
From repo    : fedora
Short desc   : Wrapper for GNU readline
URL          : https://github.com/hanslub42/rlwrap
License      : GPLv2+
Descript     : rlwrap is a 'readline wrapper' that uses the GNU readline library to
             : allow the editing of keyboard input for any other command. Input
             : history is remembered across invocations, separately for each command;
             : history completion and search work as in bash and completion word
             : lists can be specified on the command line.
```

</details>

<details>
<summary>rocm-opencl</summary>

```
From repo    : ROCm
Short desc   : OpenCL: Open Computing Language on ROCclr
License      : unknown
Descript     : DESCRIPTION
             : ===========
             : 
             : This is an installer created using CPack (https://cmake.org). No additional installation instructions provided.
```

</details>

<details>
<summary>rocminfo</summary>

```
Short desc   : ROCm system info utility
URL          : https://github.com/RadeonOpenCompute/rocminfo
License      : NCSA
Descript     : ROCm system info utility
```

</details>

<details>
<summary>rofi</summary>

```
From repo    : fedora
Short desc   : A window switcher, application launcher and dmenu replacement
URL          : https://github.com/DaveDavenport/rofi
License      : MIT
Descript     : Rofi is a dmenu replacement. Rofi, like dmenu, will provide the user with a
             : textual list of options where one or more can be selected. This can either be,
             : running an application, selecting a window or options provided by an external
             : script.
```

</details>

<details>
<summary>rofi-themes</summary>

```
From repo    : fedora
Short desc   : Themes for rofi
URL          : https://github.com/DaveDavenport/rofi
License      : MIT
Descript     : The rofi-themes package contains themes for rofi.
```

</details>

<details>
<summary>rootfiles</summary>

```
From repo    : anaconda
Short desc   : The basic required files for the root user's directory
License      : Public Domain
Descript     : The rootfiles package contains basic required files that are placed
             : in the root user's account.  These files are basically the same
             : as those in /etc/skel, which are placed in regular
             : users' home directories.
```

</details>

<details>
<summary>rootsh</summary>

```
From repo    : fedora
Short desc   : Shell wrapper for auditing
URL          : http://sourceforge.net/projects/rootsh
License      : GPLv3+
Descript     : Rootsh is a wrapper for shells which logs all echoed keystrokes and
             : terminal output to a file and/or to syslog. Its main purpose is the
             : auditing of users who need a shell with root privileges. They start
             : rootsh through the sudo mechanism.
```

</details>

<details>
<summary>rpcbind</summary>

```
From repo    : anaconda
Short desc   : Universal Addresses to RPC Program Number Mapper
URL          : http://nfsv4.bullopensource.org
License      : BSD
Descript     : The rpcbind utility is a server that converts RPC program numbers into
             : universal addresses.  It must be running on the host to be able to make
             : RPC calls on a server on that machine.
```

</details>

<details>
<summary>rpkg-common</summary>

```
From repo    : updates
Short desc   : Common files for rpkg
URL          : https://pagure.io/rpkg
License      : GPLv2+ and LGPLv2
Descript     : Common files for python2-rpkg and python3-rpkg.
```

</details>

<details>
<summary>rpm</summary>

```
From repo    : anaconda
Short desc   : The RPM package management system
URL          : http://www.rpm.org/
License      : GPLv2+
Descript     : The RPM Package Manager (RPM) is a powerful command line driven
             : package management system capable of installing, uninstalling,
             : verifying, querying, and updating software packages. Each software
             : package consists of an archive of files along with information about
             : the package like its version, a description, etc.
```

</details>

<details>
<summary>rpm</summary>

```
From repo    : updates-testing
Short desc   : The RPM package management system
URL          : http://www.rpm.org/
License      : GPLv2+
Descript     : The RPM Package Manager (RPM) is a powerful command line driven
             : package management system capable of installing, uninstalling,
             : verifying, querying, and updating software packages. Each software
             : package consists of an archive of files along with information about
             : the package like its version, a description, etc.
```

</details>

<details>
<summary>rpm-build</summary>

```
From repo    : updates-testing
Short desc   : Scripts and executable programs used to build packages
URL          : http://www.rpm.org/
License      : GPLv2+
Descript     : The rpm-build package contains the scripts and executable programs
             : that are used to build packages using the RPM Package Manager.
```

</details>

<details>
<summary>rpm-build-libs</summary>

```
From repo    : anaconda
Short desc   : Libraries for building RPM packages
URL          : http://www.rpm.org/
License      : GPLv2+ and LGPLv2+ with exceptions
Descript     : This package contains the RPM shared libraries for building packages.
```

</details>

<details>
<summary>rpm-build-libs</summary>

```
From repo    : updates-testing
Short desc   : Libraries for building RPM packages
URL          : http://www.rpm.org/
License      : GPLv2+ and LGPLv2+ with exceptions
Descript     : This package contains the RPM shared libraries for building packages.
```

</details>

<details>
<summary>rpm-devel</summary>

```
From repo    : fedora
Short desc   : Development files for manipulating RPM packages
URL          : http://www.rpm.org/
License      : GPLv2+ and LGPLv2+ with exceptions
Descript     : This package contains the RPM C library and header files. These
             : development files will simplify the process of writing programs that
             : manipulate RPM packages and databases. These files are intended to
             : simplify the process of creating graphical package managers or any
             : other tools that need an intimate knowledge of RPM packages in order
             : to function.
             : 
             : This package should be installed if you want to develop programs that
             : will manipulate RPM packages and databases.
```

</details>

<details>
<summary>rpm-libs</summary>

```
From repo    : anaconda
Short desc   : Libraries for manipulating RPM packages
URL          : http://www.rpm.org/
License      : GPLv2+ and LGPLv2+ with exceptions
Descript     : This package contains the RPM shared libraries.
```

</details>

<details>
<summary>rpm-libs</summary>

```
From repo    : updates-testing
Short desc   : Libraries for manipulating RPM packages
URL          : http://www.rpm.org/
License      : GPLv2+ and LGPLv2+ with exceptions
Descript     : This package contains the RPM shared libraries.
```

</details>

<details>
<summary>rpm-plugin-selinux</summary>

```
From repo    : anaconda
Short desc   : Rpm plugin for SELinux functionality
URL          : http://www.rpm.org/
License      : GPLv2+
Descript     : Rpm plugin for SELinux functionality.
```

</details>

<details>
<summary>rpm-plugin-selinux</summary>

```
From repo    : updates-testing
Short desc   : Rpm plugin for SELinux functionality
URL          : http://www.rpm.org/
License      : GPLv2+
Descript     : Rpm plugin for SELinux functionality.
```

</details>

<details>
<summary>rpm-plugin-systemd-inhibit</summary>

```
From repo    : anaconda
Short desc   : Rpm plugin for systemd inhibit functionality
URL          : http://www.rpm.org/
License      : GPLv2+
Descript     : This plugin blocks systemd from entering idle, sleep or shutdown while an rpm
             : transaction is running using the systemd-inhibit mechanism.
```

</details>

<details>
<summary>rpm-plugin-systemd-inhibit</summary>

```
From repo    : updates-testing
Short desc   : Rpm plugin for systemd inhibit functionality
URL          : http://www.rpm.org/
License      : GPLv2+
Descript     : This plugin blocks systemd from entering idle, sleep or shutdown while an rpm
             : transaction is running using the systemd-inhibit mechanism.
```

</details>

<details>
<summary>rpm-sign-libs</summary>

```
From repo    : anaconda
Short desc   : Libraries for signing RPM packages
URL          : http://www.rpm.org/
License      : GPLv2+ and LGPLv2+ with exceptions
Descript     : This package contains the RPM shared libraries for signing packages.
```

</details>

<details>
<summary>rpm-sign-libs</summary>

```
From repo    : updates-testing
Short desc   : Libraries for signing RPM packages
URL          : http://www.rpm.org/
License      : GPLv2+ and LGPLv2+ with exceptions
Descript     : This package contains the RPM shared libraries for signing packages.
```

</details>

<details>
<summary>rpmdevtools</summary>

```
From repo    : fedora
Short desc   : RPM Development Tools
URL          : https://pagure.io/rpmdevtools
License      : GPLv2+ and GPLv2
Descript     : This package contains scripts and (X)Emacs support files to aid in
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
From repo    : rpmfusion-free
Short desc   : Appstream metadata for the RPM Fusion free repository
URL          : http://rpmfusion.org
License      : CC0
Descript     : Appstream metadata for packages in the RPM Fusion free repository
```

</details>

<details>
<summary>rpmfusion-free-obsolete-packages</summary>

```
From repo    : rpmfusion-free
Short desc   : A package to obsolete retired packages from rpmfusion-free
URL          : http://rpmfusion.org
License      : MIT
Descript     : This package exists only to obsolete other packages which need to be removed
             : from the RPM Fusion free for some reason.
```

</details>

<details>
<summary>rpmfusion-free-release</summary>

```
From repo    : rpmfusion-free-updates-testing
Short desc   : RPM Fusion (free) Repository Configuration
URL          : http://rpmfusion.org
License      : BSD
Descript     : RPM Fusion free package repository files for yum and dnf
             : along with gpg public keys
```

</details>

<details>
<summary>rpmfusion-nonfree-appstream-data</summary>

```
From repo    : rpmfusion-nonfree
Short desc   : Appstream metadata for the RPM Fusion nonfree repository
URL          : http://rpmfusion.org
License      : CC0
Descript     : Appstream metadata for packages in the RPM Fusion nonfree repository
```

</details>

<details>
<summary>rpmfusion-nonfree-release</summary>

```
From repo    : rpmfusion-nonfree-updates-testing
Short desc   : RPM Fusion (nonfree) Repository Configuration
URL          : http://rpmfusion.org
License      : BSD
Descript     : RPM Fusion nonfree package repository files for yum and dnf
             : along with gpg public keys
```

</details>

<details>
<summary>rpmlint</summary>

```
From repo    : updates
Short desc   : Tool for checking common errors in RPM packages
URL          : https://github.com/rpm-software-management/rpmlint
License      : GPLv2
Descript     : rpmlint is a tool for checking common errors in RPM packages. Binary
             : and source packages as well as spec files can be checked.
```

</details>

<details>
<summary>rrdtool</summary>

```
From repo    : fedora
Short desc   : Round Robin Database Tool to store and display time-series data
URL          : https://oss.oetiker.ch/rrdtool/
License      : GPLv2+ with exceptions
Descript     : RRD is the Acronym for Round Robin Database. RRD is a system to store and
             : display time-series data (i.e. network bandwidth, machine-room temperature,
             : server load average). It stores the data in a very compact way that will not
             : expand over time, and it presents useful graphs by processing the data to
             : enforce a certain data density. It can be used either via simple wrapper
             : scripts (from shell or Perl) or via frontends that poll network devices and
             : put a friendly user interface on it.
```

</details>

<details>
<summary>rsnapshot</summary>

```
From repo    : fedora
Short desc   : Local and remote filesystem snapshot utility
URL          : https://rsnapshot.org/
License      : GPLv2+
Descript     : This is a remote backup program that uses rsync to take backup snapshots of
             : filesystems.  It uses hard links to save space on disk.
```

</details>

<details>
<summary>rsync</summary>

```
From repo    : anaconda
Short desc   : A program for synchronizing files over a network
URL          : https://rsync.samba.org/
License      : GPLv3+
Descript     : Rsync uses a reliable algorithm to bring remote and host files into
             : sync very quickly. Rsync is fast because it just sends the differences
             : in the files over the network instead of sending the complete
             : files. Rsync is often used as a very powerful mirroring process or
             : just as a more capable replacement for the rcp command. A technical
             : report which describes the rsync algorithm is included in this
             : package.
```

</details>

<details>
<summary>rsync-bpc</summary>

```
From repo    : fedora
Short desc   : A customized fork of rsync that is used as part of BackupPC
URL          : https://github.com/backuppc/rsync-bpc
License      : GPLv3+
Descript     : Rsync-bpc is a customized version of rsync that is used as part of
             : BackupPC, an open source backup system.
             : 
             : The main change to rsync is adding a shim layer (in the subdirectory
             : backuppc, and in bpc_sysCalls.c) that emulates the system calls for
             : accessing the file system so that rsync can directly read/write files
             : in BackupPC's format.
             : 
             : Rsync-bpc is fully line-compatible with vanilla rsync, so it can talk
             : to rsync servers and clients.
             : 
             : Rsync-bpc serves no purpose outside of BackupPC.
```

</details>

<details>
<summary>rsyslog</summary>

```
From repo    : fedora
Short desc   : Enhanced system logging and kernel message trapping daemon
URL          : http://www.rsyslog.com/
License      : (GPLv3+ and ASL 2.0)
Descript     : Rsyslog is an enhanced, multi-threaded syslog daemon. It supports MySQL,
             : syslog/TCP, RFC 3195, permitted sender lists, filtering on any message part,
             : and fine grain output format control. It is compatible with stock sysklogd
             : and can be used as a drop-in replacement. Rsyslog is simple to set up, with
             : advanced features suitable for enterprise-class, encryption-protected syslog
             : relay chains.
```

</details>

<details>
<summary>rtkit</summary>

```
From repo    : anaconda
Short desc   : Realtime Policy and Watchdog Daemon
URL          : http://git.0pointer.net/rtkit.git/
License      : GPLv3+ and BSD
Descript     : RealtimeKit is a D-Bus system service that changes the
             : scheduling policy of user processes/threads to SCHED_RR (i.e. realtime
             : scheduling mode) on request. It is intended to be used as a secure
             : mechanism to allow real-time scheduling to be used by normal user
             : processes.
```

</details>

<details>
<summary>ruby</summary>

```
From repo    : updates-testing
Short desc   : An interpreter of object-oriented scripting language
URL          : https://www.ruby-lang.org/
License      : (Ruby or BSD) and Public Domain and MIT and CC0 and zlib and UCD
Descript     : Ruby is the interpreted scripting language for quick and easy
             : object-oriented programming.  It has many features to process text
             : files and to do system management tasks (as in Perl).  It is simple,
             : straight-forward, and extensible.
```

</details>

<details>
<summary>ruby-augeas</summary>

```
From repo    : fedora
Short desc   : Ruby bindings for Augeas
URL          : http://augeas.net
License      : LGPLv2+
Descript     : Ruby bindings for augeas.
```

</details>

<details>
<summary>ruby-default-gems</summary>

```
From repo    : updates-testing
Short desc   : Default gems which are part of Ruby StdLib
URL          : https://www.ruby-lang.org/
License      : (Ruby or BSD) and Public Domain and MIT and CC0 and zlib and UCD
Descript     : The .gemspec files and executables of default gems, which are part of Ruby
             : StdLib.
```

</details>

<details>
<summary>ruby-facter</summary>

```
From repo    : fedora
Short desc   : Ruby bindings for facter
URL          : https://puppetlabs.com/facter
License      : ASL 2.0
Descript     : The ruby bindings for libfacter.
```

</details>

<details>
<summary>ruby-libs</summary>

```
From repo    : updates-testing
Short desc   : Libraries necessary to run Ruby
URL          : https://www.ruby-lang.org/
License      : Ruby or BSD
Descript     : This package includes the libruby, necessary to run Ruby.
```

</details>

<details>
<summary>rubygem-bigdecimal</summary>

```
From repo    : updates-testing
Short desc   : BigDecimal provides arbitrary-precision floating point decimal arithmetic
URL          : https://www.ruby-lang.org/
License      : Ruby or BSD
Descript     : Ruby provides built-in support for arbitrary precision integer arithmetic.
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
<summary>rubygem-builder</summary>

```
From repo    : fedora
Short desc   : Builders for MarkUp
URL          : http://onestepback.org
License      : MIT
Descript     : Builder provides a number of builder objects that make creating structured
             : data simple to do. Currently the following builder objects are supported:
             : * XML Markup
             : * XML Events
```

</details>

<details>
<summary>rubygem-bundler</summary>

```
From repo    : updates-testing
Short desc   : Library and utilities to manage a Ruby application's gem dependencies
URL          : https://www.ruby-lang.org/
License      : MIT
Descript     : Bundler manages an application's dependencies through its entire life, across
             : many machines, systematically and repeatably.
```

</details>

<details>
<summary>rubygem-childprocess</summary>

```
From repo    : fedora
Short desc   : A gem for controlling external programs running in the background
URL          : http://github.com/enkessler/childprocess
License      : MIT
Descript     : This gem aims at being a simple and reliable solution for controlling external
             : programs running in the background on any Ruby / OS combination.
```

</details>

<details>
<summary>rubygem-concurrent-ruby</summary>

```
From repo    : fedora
Short desc   : Modern concurrency tools for Ruby
URL          : http://www.concurrent-ruby.com
License      : MIT
Descript     : Modern concurrency tools including agents, futures, promises, thread pools,
             : actors, supervisors, and more.
             : 
             : Inspired by Erlang, Clojure, Go, JavaScript, actors, and classic concurrency
             : patterns.
```

</details>

<details>
<summary>rubygem-domain_name</summary>

```
From repo    : fedora
Short desc   : Domain Name manipulation library for Ruby
URL          : https://github.com/knu/ruby-domain_name
License      : BSD and (MPLv1.1 or GPLv2+ or LGPLv2+)
Descript     : This is a Domain Name manipulation library for Ruby.
             : It can also be used for cookie domain validation based on the Public
             : Suffix List.
```

</details>

<details>
<summary>rubygem-erubi</summary>

```
From repo    : fedora
Short desc   : Small ERB Implementation
URL          : https://github.com/jeremyevans/erubi
License      : MIT
Descript     : Erubi is a ERB template engine for ruby. It is a simplified fork of Erubis.
```

</details>

<details>
<summary>rubygem-excon</summary>

```
From repo    : fedora
Short desc   : Speed, persistence, http(s)
URL          : https://github.com/excon/excon
License      : MIT
Descript     : EXtended http(s) CONnections.
```

</details>

<details>
<summary>rubygem-ffi</summary>

```
From repo    : fedora
Short desc   : FFI Extensions for Ruby
URL          : https://github.com/ffi/ffi/wiki
License      : BSD
Descript     : Ruby-FFI is a ruby extension for programmatically loading dynamic
             : libraries, binding functions within them, and calling those functions
             : from Ruby code. Moreover, a Ruby-FFI extension works without changes
             : on Ruby and JRuby. Discover why should you write your next extension
             : using Ruby-FFI here[http://wiki.github.com/ffi/ffi/why-use-ffi].
```

</details>

<details>
<summary>rubygem-fog-core</summary>

```
From repo    : fedora
Short desc   : Shared classes and tests for fog providers and services
URL          : https://github.com/fog/fog-core
License      : MIT
Descript     : Shared classes and tests for fog providers and services.
```

</details>

<details>
<summary>rubygem-fog-json</summary>

```
From repo    : fedora
Short desc   : JSON parsing for fog providers
URL          : http://github.com/fog/fog-json
License      : MIT
Descript     : Extraction of the JSON parsing tools shared between a
             : number of providers in the 'fog' gem.
```

</details>

<details>
<summary>rubygem-fog-libvirt</summary>

```
From repo    : fedora
Short desc   : Module for the 'fog' gem to support libvirt
URL          : http://github.com/fog/fog-libvirt
License      : MIT
Descript     : This library can be used as a module for 'fog' or as standalone libvirt
             : provider.
```

</details>

<details>
<summary>rubygem-fog-xml</summary>

```
From repo    : fedora
Short desc   : XML parsing for fog providers
URL          : https://github.com/fog/fog-xml
License      : MIT
Descript     : Extraction of the XML parsing tools shared between a
             : number of providers in the 'fog' gem.
```

</details>

<details>
<summary>rubygem-formatador</summary>

```
From repo    : fedora
Short desc   : Ruby STDOUT text formatting
URL          : http://github.com/geemus/formatador
License      : MIT
Descript     : STDOUT text formatting.
```

</details>

<details>
<summary>rubygem-hashicorp-checkpoint</summary>

```
From repo    : fedora
Short desc   : Internal HashiCorp service to check version information
URL          : http://www.hashicorp.com
License      : MPLv2.0
Descript     : Internal HashiCorp service to check version information.
```

</details>

<details>
<summary>rubygem-http-accept</summary>

```
From repo    : fedora
Short desc   : Parse Accept and Accept-Language HTTP headers
URL          : https://github.com/ioquatix/http-accept
License      : MIT
Descript     : Parse Accept and Accept-Language HTTP headers.
```

</details>

<details>
<summary>rubygem-http-cookie</summary>

```
From repo    : fedora
Short desc   : Ruby library to handle HTTP Cookies based on RFC 6265
URL          : https://github.com/sparklemotion/http-cookie
License      : MIT
Descript     : HTTP::Cookie is a Ruby library to handle HTTP Cookies based on RFC 6265.  It
             : has with security, standards compliance and compatibility in mind, to behave
             : just the same as today's major web browsers.  It has builtin support for the
             : legacy cookies.txt and the latest cookies.sqlite formats of Mozilla Firefox,
             : and its modular API makes it easy to add support for a new backend store.
```

</details>

<details>
<summary>rubygem-i18n</summary>

```
From repo    : fedora
Short desc   : New wave Internationalization support for Ruby
URL          : https://github.com/ruby-i18n/i18n
License      : MIT and (BSD or Ruby)
Descript     : Ruby Internationalization and localization solution.
```

</details>

<details>
<summary>rubygem-io-console</summary>

```
From repo    : updates-testing
Short desc   : IO/Console is a simple console utilizing library
URL          : https://www.ruby-lang.org/
License      : (Ruby or BSD) and Public Domain and MIT and CC0 and zlib and UCD
Descript     : IO/Console provides very simple and portable access to console. It doesn't
             : provide higher layer features, such like curses and readline.
```

</details>

<details>
<summary>rubygem-json</summary>

```
From repo    : fedora
Short desc   : A JSON implementation in Ruby
URL          : http://json.rubyforge.org
License      : Ruby or GPLv2
Descript     : This is a implementation of the JSON specification according
             : to RFC 4627 in Ruby.
             : You can think of it as a low fat alternative to XML,
             : if you want to store data to disk or transmit it over
             : a network rather than use a verbose markup language.
```

</details>

<details>
<summary>rubygem-listen</summary>

```
From repo    : fedora
Short desc   : Listen to file modifications
URL          : https://github.com/guard/listen
License      : MIT
Descript     : The Listen gem listens to file modifications and notifies you about the
             : changes. Works everywhere!
```

</details>

<details>
<summary>rubygem-log4r</summary>

```
From repo    : fedora
Short desc   : Log4r, logging framework for ruby
URL          : https://github.com/colbygk/log4r
License      : LGPLv3
Descript     : Log4r is a comprehensive and flexible logging library for use in Ruby programs.
             : It features a heirarchical logging system of any number of levels, custom level
             : names, multiple output destinations per log event, custom formatting, and more.
```

</details>

<details>
<summary>rubygem-mime-types</summary>

```
From repo    : fedora
Short desc   : The mime-types library provides a library
URL          : https://github.com/mime-types/ruby-mime-types/
License      : MIT
Descript     : The mime-types library provides a library and registry for information about
             : MIME content type definitions. It can be used to determine defined filename
             : extensions for MIME types, or to use filename extensions to look up the likely
             : MIME type definitions.
             : Version 3.0 is a major release that requires Ruby 2.0 compatibility and
             : removes deprecated functions. The columnar registry format introduced
             : in 2.6 has been made the primary format; the registry data has been
             : extracted from this library and put into {mime-types-data}[https://github.com/mime-types/mime-types-data].
             : Additionally, mime-types is now licensed exclusively under the MIT licence and
             : there is a code of conduct in effect. There are a number of other smaller
             : changes described in the History file.
```

</details>

<details>
<summary>rubygem-mime-types-data</summary>

```
From repo    : fedora
Short desc   : A registry for information about MIME media type definitions
URL          : https://github.com/mime-types/mime-types-data/
License      : MIT
Descript     : mime-types-data provides a registry for information about MIME media type
             : definitions. It can be used with the Ruby mime-types library or other software
             : to determine defined filename extensions for MIME types, or to use filename
             : extensions to look up the likely MIME type definitions.
```

</details>

<details>
<summary>rubygem-multi_json</summary>

```
From repo    : fedora
Short desc   : A common interface to multiple JSON libraries
URL          : https://github.com/intridea/multi_json
License      : MIT
Descript     : A common interface to multiple JSON libraries, including Oj, Yajl, the JSON
             : gem (with C-extensions), the pure-Ruby JSON gem, NSJSONSerialization, gson.rb,
             : JrJackson, and OkJson.
```

</details>

<details>
<summary>rubygem-net-scp</summary>

```
From repo    : fedora
Short desc   : A pure Ruby implementation of the SCP client protocol
URL          : https://github.com/net-ssh/net-scp
License      : MIT
Descript     : A pure Ruby implementation of the SCP client protocol
```

</details>

<details>
<summary>rubygem-net-sftp</summary>

```
From repo    : fedora
Short desc   : A pure Ruby implementation of the SFTP client protocol
URL          : https://github.com/net-ssh/net-sftp
License      : MIT or LGPLv2
Descript     : A pure Ruby implementation of the SFTP client protocol
```

</details>

<details>
<summary>rubygem-net-ssh</summary>

```
From repo    : fedora
Short desc   : Net::SSH: a pure-Ruby implementation of the SSH2 client protocol
URL          : https://github.com/net-ssh/net-ssh
License      : MIT
Descript     : Net::SSH: a pure-Ruby implementation of the SSH2 client protocol. It allows
             : you to write programs that invoke and interact with processes on remote
             : servers, via SSH2.
```

</details>

<details>
<summary>rubygem-netrc</summary>

```
From repo    : fedora
Short desc   : Library to read and write netrc files
URL          : https://github.com/geemus/netrc
License      : MIT
Descript     : This library can read and update netrc files, preserving formatting including
             : comments and whitespace.
```

</details>

<details>
<summary>rubygem-nokogiri</summary>

```
From repo    : updates
Short desc   : An HTML, XML, SAX, and Reader parser
URL          : http://nokogiri.rubyforge.org/nokogiri/
License      : MIT
Descript     : Nokogiri parses and searches XML/HTML very quickly, and also has
             : correctly implemented CSS3 selector support as well as XPath support.
             : 
             : Nokogiri also features an Hpricot compatibility layer to help ease the change
             : to using correct CSS and XPath.
```

</details>

<details>
<summary>rubygem-pathspec</summary>

```
From repo    : fedora
Short desc   : Use to match path patterns such as gitignore
URL          : https://rubygems.org/gems/pathspec
License      : ASL 2.0
Descript     : Use to match path patterns such as gitignore.
```

</details>

<details>
<summary>rubygem-psych</summary>

```
From repo    : updates-testing
Short desc   : A libyaml wrapper for Ruby
URL          : https://www.ruby-lang.org/
License      : MIT
Descript     : Psych is a YAML parser and emitter. Psych leverages
             : libyaml[http://pyyaml.org/wiki/LibYAML] for its YAML parsing and emitting
             : capabilities. In addition to wrapping libyaml, Psych also knows how to
             : serialize and de-serialize most Ruby objects to and from the YAML format.
```

</details>

<details>
<summary>rubygem-racc</summary>

```
From repo    : fedora
Short desc   : LALR(1) parser generator
URL          : https://github.com/tenderlove/racc
License      : BSD
Descript     : Racc is a LALR(1) parser generator.
             : It is written in Ruby itself, and generates Ruby program.
```

</details>

<details>
<summary>rubygem-rb-inotify</summary>

```
From repo    : fedora
Short desc   : A Ruby wrapper for Linux inotify, using FFI
URL          : https://github.com/guard/rb-inotify
License      : MIT
Descript     : A Ruby wrapper for Linux inotify, using FFI.
```

</details>

<details>
<summary>rubygem-rdoc</summary>

```
From repo    : updates-testing
Short desc   : A tool to generate HTML and command-line documentation for Ruby projects
URL          : https://www.ruby-lang.org/
License      : GPLv2 and Ruby and MIT and OFL
Descript     : RDoc produces HTML and command-line documentation for Ruby projects.  RDoc
             : includes the 'rdoc' and 'ri' tools for generating and displaying online
             : documentation.
```

</details>

<details>
<summary>rubygem-rest-client</summary>

```
From repo    : fedora
Short desc   : Simple HTTP and REST client for Ruby
URL          : https://github.com/rest-client/rest-client
License      : MIT
Descript     : A simple HTTP and REST client for Ruby, inspired by the Sinatra microframework
             : style of specifying actions: get, put, post, delete.
```

</details>

<details>
<summary>rubygem-rgen</summary>

```
From repo    : fedora
Short desc   : Ruby Modelling and Generator Framework
URL          : https://github.com/mthiede/rgen
License      : MIT
Descript     : RGen is a framework for Model Driven Software Development (MDSD) in Ruby. This
             : means that it helps you build Metamodels, instantiate Models, modify and
             : transform Models and finally generate arbitrary textual content from it.
```

</details>

<details>
<summary>rubygem-ruby-libvirt</summary>

```
From repo    : fedora
Short desc   : Ruby bindings for LIBVIRT
URL          : http://libvirt.org/ruby/
License      : LGPLv2+
Descript     : Ruby bindings for libvirt.
```

</details>

<details>
<summary>rubygem-ruby-shadow</summary>

```
From repo    : fedora
Short desc   : Ruby shadow password module
URL          : https://github.com/apalmblad/ruby-shadow
License      : Public Domain
Descript     : This module provides access to shadow passwords on Linux and Solaris.
```

</details>

<details>
<summary>rubygem-rubyzip</summary>

```
From repo    : fedora
Short desc   : A ruby module for reading and writing zip files
URL          : http://github.com/rubyzip/rubyzip
License      : Ruby or BSD
Descript     : A ruby module for reading and writing zip files.
```

</details>

<details>
<summary>rubygem-unf</summary>

```
From repo    : fedora
Short desc   : Wrapper library to bring Unicode Normalization Form support to Ruby/JRuby
URL          : https://github.com/knu/ruby-unf
License      : BSD
Descript     : This is a wrapper library to bring Unicode Normalization Form support
             : to Ruby/JRuby.
```

</details>

<details>
<summary>rubygem-unf_ext</summary>

```
From repo    : fedora
Short desc   : Unicode Normalization Form support library for CRuby
URL          : http://github.com/knu/ruby-unf_ext
License      : MIT
Descript     : Unicode Normalization Form support library for CRuby.
```

</details>

<details>
<summary>rubygems</summary>

```
From repo    : updates-testing
Short desc   : The Ruby standard for packaging ruby libraries
URL          : https://www.ruby-lang.org/
License      : Ruby or MIT
Descript     : RubyGems is the Ruby standard for publishing and managing third party
             : libraries.
```

</details>

<details>
<summary>rubypick</summary>

```
From repo    : fedora
Short desc   : Stub to allow choosing Ruby runtime
URL          : https://github.com/fedora-ruby/rubypick
License      : MIT
Descript     : Fedora /usr/bin/ruby stub to allow choosing Ruby runtime. Similarly to rbenv
             : or RVM, it allows non-privileged user to choose which is preferred Ruby
             : runtime for current task.
```

</details>

<details>
<summary>runc</summary>

```
Эпоха        : 2
From repo    : updates
Short desc   : CLI for running Open Containers
URL          : https://github.com/opencontainers/runc
License      : ASL 2.0
Descript     : The runc command can be used to start containers which are packaged
             : in accordance with the Open Container Initiative's specifications,
             : and to manage containers running under runc.
```

</details>

<details>
<summary>rust-srpm-macros</summary>

```
From repo    : fedora
Short desc   : RPM macros for building Rust source packages
URL          : https://pagure.io/fedora-rust/rust2rpm
License      : MIT
Descript     : RPM macros for building Rust source packages.
```

</details>

<details>
<summary>rxvt-unicode</summary>

```
From repo    : updates
Short desc   : Unicode version of rxvt
URL          : http://software.schmorp.de/
License      : GPLv3
Descript     : rxvt-unicode is a clone of the well known terminal emulator rxvt, modified to
             : store text in Unicode (either UCS-2 or UCS-4) and to use locale-correct input
             : and output. It also supports mixing multiple fonts at the same time, including
             : Xft fonts.
```

</details>

<details>
<summary>rygel</summary>

```
From repo    : anaconda
Short desc   : A collection of UPnP/DLNA services
URL          : https://wiki.gnome.org/Projects/Rygel
License      : LGPLv2+
Descript     : Rygel is a home media solution that allows you to easily share audio, video and
             : pictures, and control of media player on your home network. In technical terms
             : it is both a UPnP AV MediaServer and MediaRenderer implemented through a plug-in
             : mechanism. Interoperability with other devices in the market is achieved by
             : conformance to very strict requirements of DLNA and on the fly conversion of
             : media to format that client devices are capable of handling.
```

</details>

