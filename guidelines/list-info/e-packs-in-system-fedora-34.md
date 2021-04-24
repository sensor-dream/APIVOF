# For first letter e, information about installation packages

<details>
<summary>e2fsprogs</summary>

```
From repo     : anaconda
Short desc    : Utilities for managing ext2, ext3, and ext4 file systems
URL          : http://e2fsprogs.sourceforge.net/
License      : GPLv2
Descript     : The e2fsprogs package contains a number of utilities for creating,
             : checking, modifying, and correcting any inconsistencies in second,
             : third and fourth extended (ext2/ext3/ext4) file systems. E2fsprogs
             : contains e2fsck (used to repair file system inconsistencies after an
             : unclean shutdown), mke2fs (used to initialize a partition to contain
             : an empty ext2 file system), debugfs (used to examine the internal
             : structure of a file system, to manually repair a corrupted
             : file system, or to create test cases for e2fsck), tune2fs (used to
             : modify file system parameters), and most of the other core ext2fs
             : file system utilities.
             : 
             : You should install the e2fsprogs package if you need to manage the
             : performance of an ext2, ext3, or ext4 file system.
```

</details>

<details>
<summary>e2fsprogs-libs</summary>

```
From repo     : anaconda
Short desc    : Ext2/3/4 file system specific shared libraries
URL          : http://e2fsprogs.sourceforge.net/
License      : GPLv2 and LGPLv2
Descript     : E2fsprogs-libs contains libe2p and libext2fs, the libraries of the
             : e2fsprogs package.
             : 
             : These libraries are used to directly access ext2/3/4 file systems
             : from user space.
```

</details>

<details>
<summary>ed</summary>

```
From repo     : fedora
Short desc    : The GNU line editor
URL          : http://www.gnu.org/software/ed/
License      : GPLv3+ and GFDL
Descript     : Ed is a line-oriented text editor, used to create, display, and modify
             : text files (both interactively and via shell scripts).  For most
             : purposes, ed has been replaced in normal usage by full-screen editors
             : (emacs and vi, for example).
             : 
             : Ed was the original UNIX editor, and may be used by some programs.  In
             : general, however, you probably don't need to install it and you probably
             : won't use it.
```

</details>

<details>
<summary>edk2-ovmf</summary>

```
From repo     : anaconda
Short desc    : Open Virtual Machine Firmware
URL          : http://www.tianocore.org/edk2/
License      : BSD-2-Clause-Patent and OpenSSL
Descript     : EFI Development Kit II
             : Open Virtual Machine Firmware (x64)
```

</details>

<details>
<summary>efi-filesystem</summary>

```
From repo     : anaconda
Short desc    : The basic directory layout for EFI machines
URL          : https://github.com/rhboot/efi-rpm-macros/
License      : GPLv3+
Descript     : The efi-filesystem package contains the basic directory layout for EFI
             : machine bootloaders and tools.
```

</details>

<details>
<summary>efi-filesystem</summary>

```
From repo     : updates-testing
Short desc    : The basic directory layout for EFI machines
URL          : https://github.com/rhboot/efi-rpm-macros/
License      : GPLv3+
Descript     : The efi-filesystem package contains the basic directory layout for EFI
             : machine bootloaders and tools.
```

</details>

<details>
<summary>efi-srpm-macros</summary>

```
From repo     : updates-testing
Short desc    : Common SRPM Macros for building EFI-related packages
URL          : https://github.com/rhboot/efi-rpm-macros/
License      : GPLv3+
Descript     : efi-srpm-macros provides a set of SRPM macros for use in EFI-related packages.
```

</details>

<details>
<summary>efibootmgr</summary>

```
From repo     : anaconda
Short desc    : EFI Boot Manager
URL          : https://github.com/rhboot/efibootmgr/
License      : GPLv2+
Descript     : efibootmgr displays and allows the user to edit the Intel Extensible
             : Firmware Interface (EFI) Boot Manager variables.  Additional
             : information about EFI can be found at https://uefi.org/.
```

</details>

<details>
<summary>efivar-libs</summary>

```
From repo     : anaconda
Short desc    : Library to manage UEFI variables
URL          : https://github.com/rhboot/efivar
License      : LGPL-2.1
Descript     : Library to allow for the simple manipulation of UEFI variables.
```

</details>

<details>
<summary>egl-utils</summary>

```
From repo     : fedora
Short desc    : EGL utilities
URL          : http://www.mesa3d.org
License      : MIT
Descript     : The egl-utils package provides the eglinfo and es2_info utilities.
```

</details>

<details>
<summary>egl-wayland</summary>

```
From repo     : fedora
Short desc    : Wayland EGL External Platform library
URL          : https://github.com/NVIDIA/egl-wayland
License      : MIT
Descript     : Wayland EGL External Platform library
```

</details>

<details>
<summary>elementary-print</summary>

```
From repo     : fedora
Short desc    : Simple shim for printing support via Contractor
URL          : https://github.com/elementary/print
License      : GPLv3+
Descript     : Simple shim for printing support via Contractor.
```

</details>

<details>
<summary>elfutils</summary>

```
From repo     : anaconda
Short desc    : A collection of utilities and DSOs to handle ELF files and DWARF data
URL          : http://elfutils.org/
License      : GPLv3+ and (GPLv2+ or LGPLv3+) and GFDL
Descript     : Elfutils is a collection of utilities, including stack (to show
             : backtraces), nm (for listing symbols from object files), size
             : (for listing the section sizes of an object or archive file),
             : strip (for discarding symbols), readelf (to see the raw ELF file
             : structures), elflint (to check for well-formed ELF files) and
             : elfcompress (to compress or decompress ELF sections).
```

</details>

<details>
<summary>elfutils-debuginfod-client</summary>

```
From repo     : anaconda
Short desc    : Library and command line client for build-id HTTP ELF/DWARF server
URL          : http://elfutils.org/
License      : GPLv3+ and (GPLv2+ or LGPLv3+)
Descript     : The elfutils-debuginfod-client package contains shared libraries
             : dynamically loaded from -ldw, which use a debuginfod service
             : to look up debuginfo and associated data. Also includes a
             : command-line frontend.
```

</details>

<details>
<summary>elfutils-default-yama-scope</summary>

```
From repo     : anaconda
Short desc    : Default yama attach scope sysctl setting
URL          : http://elfutils.org/
License      : GPLv2+ or LGPLv3+
Descript     : Yama sysctl setting to enable default attach scope settings
             : enabling programs to use ptrace attach, access to
             : /proc/PID/{mem,personality,stack,syscall}, and the syscalls
             : process_vm_readv and process_vm_writev which are used for
             : interprocess services, communication and introspection
             : (like synchronisation, signaling, debugging, tracing and
             : profiling) of processes.
```

</details>

<details>
<summary>elfutils-libelf</summary>

```
From repo     : anaconda
Short desc    : Library to read and write ELF files
URL          : http://elfutils.org/
License      : GPLv2+ or LGPLv3+
Descript     : The elfutils-libelf package provides a DSO which allows reading and
             : writing ELF files on a high level.  Third party programs depend on
             : this package to read internals of ELF files.  The programs of the
             : elfutils package use it also to generate new ELF files.
```

</details>

<details>
<summary>elfutils-libelf-devel</summary>

```
From repo     : fedora
Short desc    : Development support for libelf
URL          : http://elfutils.org/
License      : GPLv2+ or LGPLv3+
Descript     : The elfutils-libelf-devel package contains the libraries to create
             : applications for handling compiled objects.  libelf allows you to
             : access the internals of the ELF object file format, so you can see the
             : different sections of an ELF file.
```

</details>

<details>
<summary>elfutils-libs</summary>

```
From repo     : anaconda
Short desc    : Libraries to handle compiled objects
URL          : http://elfutils.org/
License      : GPLv2+ or LGPLv3+
Descript     : The elfutils-libs package contains libraries which implement DWARF, ELF,
             : and machine-specific ELF handling and process introspection.  These
             : libraries are used by the programs in the elfutils package.  The
             : elfutils-devel package enables building other programs using these
             : libraries.
```

</details>

<details>
<summary>emacs-filesystem</summary>

```
Эпоха        : 1
From repo     : updates-testing
Short desc    : Emacs filesystem layout
URL          : http://www.gnu.org/software/emacs/
License      : GPLv3+ and CC0-1.0
Descript     : This package provides some directories which are required by other
             : packages that add functionality to Emacs.
```

</details>

<details>
<summary>enchant</summary>

```
Эпоха        : 1
From repo     : anaconda
Short desc    : An Enchanting Spell Checking Library
URL          : http://www.abisource.com/
License      : LGPLv2+
Descript     : A library that wraps other spell checking backends.
```

</details>

<details>
<summary>enchant2</summary>

```
From repo     : anaconda
Short desc    : An Enchanting Spell Checking Library
URL          : https://github.com/AbiWord/enchant
License      : LGPLv2+
Descript     : A library that wraps other spell checking backends.
```

</details>

<details>
<summary>environment-modules</summary>

```
From repo     : fedora
Short desc    : Provides dynamic modification of a user's environment
URL          : http://modules.sourceforge.net/
License      : GPLv2+
Descript     : The Environment Modules package provides for the dynamic modification of
             : a user's environment via modulefiles.
             : 
             : Each modulefile contains the information needed to configure the shell
             : for an application. Once the Modules package is initialized, the
             : environment can be modified on a per-module basis using the module
             : command which interprets modulefiles. Typically modulefiles instruct
             : the module command to alter or set shell environment variables such as
             : PATH, MANPATH, etc. modulefiles may be shared by many users on a system
             : and users may have their own collection to supplement or replace the
             : shared modulefiles.
             : 
             : Modules can be loaded and unloaded dynamically and atomically, in an
             : clean fashion. All popular shells are supported, including bash, ksh,
             : zsh, sh, csh, tcsh, as well as some scripting languages such as perl.
             : 
             : Modules are useful in managing different versions of applications.
             : Modules can also be bundled into metamodules that will load an entire
             : suite of different applications.
             : 
             : NOTE: You will need to get a new shell after installing this package to
             : have access to the module alias.
```

</details>

<details>
<summary>eog</summary>

```
From repo     : updates-testing
Short desc    : Eye of GNOME image viewer
URL          : https://wiki.gnome.org/Apps/EyeOfGnome
License      : GPLv2+ and GFDL
Descript     : The Eye of GNOME image viewer (eog) is the official image viewer for the
             : GNOME desktop. It can view single image files in a variety of formats, as
             : well as large image collections.
             : 
             : eog is extensible through a plugin system.
```

</details>

<details>
<summary>esmtp</summary>

```
From repo     : fedora
Short desc    : User configurable send-only Mail Transfer Agent
URL          : http://esmtp.sourceforge.net/
License      : GPL+ and GPLv2+
Descript     : ESMTP is a user configurable relay-only Mail Transfer Agent (MTA) with a
             : sendmail-compatible syntax. It's based on libESMTP supporting the AUTH
             : (including the CRAM-MD5 and NTLM SASL mechanisms) and the StartTLS SMTP
             : extensions.
```

</details>

<details>
<summary>espeak-ng</summary>

```
From repo     : anaconda
Short desc    : eSpeak NG Text-to-Speech
URL          : https://github.com/espeak-ng/espeak-ng
License      : GPLv3+
Descript     : The eSpeak NG (Next Generation) Text-to-Speech program is an open source speech
             : synthesizer that supports over 70 languages. It is based on the eSpeak engine
             : created by Jonathan Duddington. It uses spectral formant synthesis by default
             : which sounds robotic, but can be configured to use Klatt formant synthesis
             : or MBROLA to give it a more natural sound.
```

</details>

<details>
<summary>ethtool</summary>

```
Эпоха        : 2
From repo     : anaconda
Short desc    : Settings tool for Ethernet NICs
URL          : https://www.kernel.org/pub/software/network/ethtool/
License      : GPLv2
Descript     : This utility allows querying and changing settings such as speed,
             : port, auto-negotiation, PCI locations and checksum offload on many
             : network devices, especially of Ethernet devices.
```

</details>

<details>
<summary>ettercap</summary>

```
From repo     : fedora
Short desc    : Network traffic sniffer/analyser, NCURSES interface version
URL          : http://ettercap.sourceforge.net
License      : GPLv2+
Descript     : Ettercap is a suite for man in the middle attacks on LAN. It features
             : sniffing of live connections, content filtering on the fly and many other
             : interesting tricks. It supports active and passive dissection of many
             : protocols (even ciphered ones) and includes many feature for network and host
             : analysis.
```

</details>

<details>
<summary>evince</summary>

```
From repo     : anaconda
Short desc    : Document viewer
URL          : https://wiki.gnome.org/Apps/Evince
License      : GPLv2+ and GPLv3+ and LGPLv2+ and MIT and Afmparse
Descript     : Evince is simple multi-page document viewer. It can display and print
             : Portable Document Format (PDF), PostScript (PS) and Encapsulated PostScript
             : (EPS) files. When supported by the document format, evince allows searching
             : for text, copying text to the clipboard, hypertext navigation,
             : table-of-contents bookmarks and editing of forms.
             : 
             :  Support for other document formats such as DVI and DJVU can be added by
             : installing additional backends.
```

</details>

<details>
<summary>evince</summary>

```
From repo     : updates-testing
Short desc    : Document viewer
URL          : https://wiki.gnome.org/Apps/Evince
License      : GPLv2+ and GPLv3+ and LGPLv2+ and MIT and Afmparse
Descript     : Evince is simple multi-page document viewer. It can display and print
             : Portable Document Format (PDF), PostScript (PS) and Encapsulated PostScript
             : (EPS) files. When supported by the document format, evince allows searching
             : for text, copying text to the clipboard, hypertext navigation,
             : table-of-contents bookmarks and editing of forms.
             : 
             :  Support for other document formats such as DVI and DJVU can be added by
             : installing additional backends.
```

</details>

<details>
<summary>evince-djvu</summary>

```
From repo     : anaconda
Short desc    : Evince backend for djvu files
URL          : https://wiki.gnome.org/Apps/Evince
License      : GPLv2+ and GPLv3+ and LGPLv2+ and MIT and Afmparse
Descript     : This package contains a backend to let evince display djvu files.
```

</details>

<details>
<summary>evince-djvu</summary>

```
From repo     : updates-testing
Short desc    : Evince backend for djvu files
URL          : https://wiki.gnome.org/Apps/Evince
License      : GPLv2+ and GPLv3+ and LGPLv2+ and MIT and Afmparse
Descript     : This package contains a backend to let evince display djvu files.
```

</details>

<details>
<summary>evince-libs</summary>

```
From repo     : anaconda
Short desc    : Libraries for the evince document viewer
URL          : https://wiki.gnome.org/Apps/Evince
License      : GPLv2+ and GPLv3+ and LGPLv2+ and MIT and Afmparse
Descript     : This package contains shared libraries needed for evince
```

</details>

<details>
<summary>evince-libs</summary>

```
From repo     : updates-testing
Short desc    : Libraries for the evince document viewer
URL          : https://wiki.gnome.org/Apps/Evince
License      : GPLv2+ and GPLv3+ and LGPLv2+ and MIT and Afmparse
Descript     : This package contains shared libraries needed for evince
```

</details>

<details>
<summary>evince-nautilus</summary>

```
From repo     : updates-testing
Short desc    : Evince extension for nautilus
URL          : https://wiki.gnome.org/Apps/Evince
License      : GPLv2+ and GPLv3+ and LGPLv2+ and MIT and Afmparse
Descript     : This package contains the evince extension for the nautilus file manager.
             : It adds an additional tab called "Document" to the file properties dialog.
```

</details>

<details>
<summary>evince-thumbnailer</summary>

```
From repo     : anaconda
Short desc    : Evince thumbnailer
URL          : https://wiki.gnome.org/Apps/Evince
License      : GPLv2+ and GPLv3+ and LGPLv2+ and MIT and Afmparse
Descript     : This package brings the Evince thumbnailer independently from Evince.
```

</details>

<details>
<summary>evince-thumbnailer</summary>

```
From repo     : updates-testing
Short desc    : Evince thumbnailer
URL          : https://wiki.gnome.org/Apps/Evince
License      : GPLv2+ and GPLv3+ and LGPLv2+ and MIT and Afmparse
Descript     : This package brings the Evince thumbnailer independently from Evince.
```

</details>

<details>
<summary>evolution-data-server</summary>

```
From repo     : anaconda
Short desc    : Backend data server for Evolution
URL          : https://wiki.gnome.org/Apps/Evolution
License      : LGPLv2+
Descript     : The evolution-data-server package provides a unified backend for programs that work
             : with contacts, tasks, and calendar information.
             : 
             : It was originally developed for Evolution (hence the name), but is now used
             : by other packages.
```

</details>

<details>
<summary>evolution-data-server</summary>

```
From repo     : updates-testing
Short desc    : Backend data server for Evolution
URL          : https://wiki.gnome.org/Apps/Evolution
License      : LGPLv2+
Descript     : The evolution-data-server package provides a unified backend for programs that work
             : with contacts, tasks, and calendar information.
             : 
             : It was originally developed for Evolution (hence the name), but is now used
             : by other packages.
```

</details>

<details>
<summary>evolution-data-server-langpacks</summary>

```
From repo     : anaconda
Short desc    : Translations for evolution-data-server
URL          : https://wiki.gnome.org/Apps/Evolution
License      : LGPLv2+
Descript     : This package contains translations for evolution-data-server.
```

</details>

<details>
<summary>evolution-data-server-langpacks</summary>

```
From repo     : updates-testing
Short desc    : Translations for evolution-data-server
URL          : https://wiki.gnome.org/Apps/Evolution
License      : LGPLv2+
Descript     : This package contains translations for evolution-data-server.
```

</details>

<details>
<summary>exempi</summary>

```
From repo     : anaconda
Short desc    : Library for easy parsing of XMP metadata
URL          : http://libopenraw.freedesktop.org/wiki/Exempi
License      : BSD
Descript     : Exempi provides a library for easy parsing of XMP metadata. It is a port of
             : Adobe XMP SDK to work on UNIX and to be build with GNU automake.
             : It includes XMPCore and XMPFiles.
```

</details>

<details>
<summary>exfatprogs</summary>

```
From repo     : updates-testing
Short desc    : Userspace utilities for exFAT filesystems
URL          : https://github.com/exfatprogs/exfatprogs
License      : GPLv2
Descript     : Utilities for formatting and repairing exFAT filesystems.
```

</details>

<details>
<summary>exiv2</summary>

```
From repo     : anaconda
Short desc    : Exif and Iptc metadata manipulation library
URL          : http://www.exiv2.org/
License      : GPLv2+
Descript     : A command line utility to access image metadata, allowing one to:
             : * print the Exif metadata of Jpeg images as summary info, interpreted values,
             :   or the plain data for each tag
             : * print the Iptc metadata of Jpeg images
             : * print the Jpeg comment of Jpeg images
             : * set, add and delete Exif and Iptc metadata of Jpeg images
             : * adjust the Exif timestamp (that's how it all started...)
             : * rename Exif image files according to the Exif timestamp
             : * extract, insert and delete Exif metadata (including thumbnails),
             :   Iptc metadata and Jpeg comments
```

</details>

<details>
<summary>exiv2-libs</summary>

```
From repo     : anaconda
Short desc    : Exif and Iptc metadata manipulation library
URL          : http://www.exiv2.org/
License      : GPLv2+
Descript     : A C++ library to access image metadata, supporting full read and write access
             : to the Exif and Iptc metadata, Exif MakerNote support, extract and delete
             : methods for Exif thumbnails, classes to access Ifd and so on.
```

</details>

<details>
<summary>expat</summary>

```
From repo     : anaconda
Short desc    : An XML parser library
URL          : https://libexpat.github.io/
License      : MIT
Descript     : This is expat, the C library for parsing XML, written by James Clark. Expat
             : is a stream oriented XML parser. This means that you register handlers with
             : the parser prior to starting the parse. These handlers are called when the
             : parser discovers the associated structures in the document being parsed. A
             : start tag is an example of the kind of structures for which you may
             : register handlers.
```

</details>

<details>
<summary>expatpp</summary>

```
From repo     : fedora
Short desc    : C++ layer for expat
URL          : http://sourceforge.net/projects/expatpp/
License      : MPLv1.1
Descript     : Expatpp is a simple C++ layer to make using the open source expat XML parsing
             : library vastly easier for complex schemas. It has been used widely in industry
             : including the Valve Steam project.
```

</details>

