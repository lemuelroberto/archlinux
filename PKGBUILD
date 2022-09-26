# Maintainer: Lemuel Roberto Bonifácio
pkgbase=lemuel
pkgname=(lemuel-base lemuel-vm-host lemuel-vm-guest)
pkgver=1
pkgrel=1
pkgdesc="Meta packages for my Arch Linux machines"
arch=(any)
url="https://github.com/lemuelroberto/archlinux"
license=(MIT)
groups=(lemuel)

rootdir=$PWD

package_lemuel-base() {
    install=lemuel-base.install

    depends=(
        base # Minimal package set to define a basic Arch Linux installation
    )

    depends+=(
        alacritty # A cross-platform, GPU-accelerated terminal emulator
        alsa-utils # Advanced Linux Sound Architecture - Utilities
        arandr # Provide a simple visual front end for XRandR 1.2.
        autoconf # A GNU tool for automatically configuring source code
        automake # A GNU tool for automatically creating Makefiles
        baobab # A graphical directory tree analyzer
        bc # An arbitrary precision calculator language
        bind # A complete, highly portable implementation of the DNS protocol
        binutils # A set of programs to assemble and manipulate binary and object files
        bison # The GNU general-purpose parser generator
        brightnessctl # Lightweight brightness control tool
        calc # Arbitrary precision console calculator
        chromium # A web browser built for speed, simplicity, and security
        code # The Open Source build of Visual Studio Code (vscode) editor
        composer # Dependency Manager for PHP
        cryptsetup # Userspace setup tool for transparent encryption of block devices using dm-crypt
        device-mapper # Device mapper userspace library and tools
        dhcpcd # RFC2131 compliant DHCP client daemon
        diffutils # Utility programs used for creating patch files
        dmenu # Generic menu for X
        docker # Pack, ship and run any application as a lightweight container
        docker-compose # Fast, isolated development environments using Docker
        e2fsprogs # Ext2/3/4 filesystem utilities
        efibootmgr # Linux user-space application to modify the EFI Boot Manager
        eog # Eye of Gnome: An image viewing and cataloging program
        evince # Document viewer (PDF, PostScript, XPS, djvu, dvi, tiff, cbr, cbz, cb7, cbt)
        f2fs-tools # Tools for Flash-Friendly File System (F2FS)
        fakeroot # Tool for simulating superuser privileges
        feh # Fast and light imlib2-based image viewer
        firefox # Standalone web browser from mozilla.org
        flex # A tool for generating text-scanning programs
        fwupd # Simple daemon to allow session software to update firmware
        gcc # The GNU Compiler Collection - C and C++ frontends
        git # the fast distributed version control system
        github-cli # The GitHub CLI
        go # Core compiler tools for the Go programming language
        go-tools # Developer tools for the Go programming language
        gparted # A Partition Magic clone, frontend to GNU Parted
        graphviz # Graph visualization software
        groff # GNU troff text-formatting system
        htop # Interactive process viewer
        hwdata # hardware identification databases
        i3-wm # Improved dynamic tiling window manager
        i3lock # Improved screenlocker based upon XCB and PAM
        i3status # Generates status bar to use with i3bar, dzen2 or xmobar
        inetutils # A collection of common network programs
        intel-ucode # Microcode update files for Intel CPUs
        jfsutils # JFS filesystem utilities
        jq # Command-line JSON processor
        kubectl # A command line tool for communicating with a Kubernetes API server
        less # A terminal based program for viewing text files
        libmnl # Minimalistic user-space library oriented to Netlink developers.
        libreoffice-fresh # LibreOffice branch which contains new features and program enhancements
        libtool # A generic library support script
        linux # The Linux kernel and modules
        linux-firmware # Firmware files for Linux
        logrotate # Rotates system logs automatically
        lsof # Lists open files for running Unix processes
        lvm2 # Logical Volume Manager 2 utilities
        m4 # The GNU macro processor
        make # GNU make utility to maintain groups of programs
        man-db # A utility for reading man pages
        man-pages # Linux man pages
        mdadm # A tool for managing/monitoring Linux md device arrays, also known as Software RAID
        meld # Compare files, directories and working copies
        mesa # An open-source implementation of the OpenGL specification
        mtr # Combines the functionality of traceroute and ping into one tool (CLI version)
        ncdu # Disk usage analyzer with an ncurses interface
        netctl # Profile based systemd network management
        network-manager-applet # Applet for managing network connections
        networkmanager # Network connection manager and user applications
        networkmanager-openconnect # NetworkManager VPN plugin for OpenConnect
        networkmanager-pptp # NetworkManager VPN plugin for PPTP
        nm-connection-editor # NetworkManager GUI connection editor and widgets
        nmap # Utility for network discovery and security auditing
        npm # A package manager for javascript
        ntfs-3g # NTFS filesystem driver and utilities
        obs-studio # Free, open source software for live streaming and recording
        openconnect # Open client for Cisco AnyConnect VPN
        openssh # Premier connectivity tool for remote login with the SSH protocol
        pacman-contrib # Contributed scripts and tools for pacman systems
        pam # PAM (Pluggable Authentication Modules) library
        parallel # A shell tool for executing jobs in parallel
        patch # A utility to apply patch files to original sources
        pavucontrol # PulseAudio Volume Control
        pdftk # Command-line tool for working with PDFs
        perl # A highly capable, feature-rich programming language
        php # A general-purpose scripting language that is especially suited to web development
        pkgconf # Package compiler and linker metadata toolkit
        pkgfile # a pacman .files metadata explorer
        polkit # Application development toolkit for controlling system-wide privileges
        polkit-gnome # Legacy polkit authentication agent for GNOME
        protobuf # Protocol Buffers - Google's data interchange format
        pulseaudio # A featureful, general-purpose sound server
        pulseaudio-alsa # ALSA Configuration for PulseAudio
        python-pip # The PyPA recommended tool for installing Python packages
        python-pyqt5 # A set of Python bindings for the Qt5 toolkit
        qt5-quickcontrols # Reusable Qt Quick based UI controls to create classic desktop-style user interfaces
        qt5-sensors # Provides access to sensor hardware and motion gesture recognition
        qt5-webkit # Classes for a WebKit2 based implementation and a new QML API
        reiserfsprogs # Reiserfs utilities
        rsync # A fast and versatile file copying tool for remote and local files
        s-nail # Environment for sending and receiving mail
        sbcl # Steel Bank Common Lisp
        shadow # Password and account management tool suite with support for shadow files and PAM
        shellcheck # Shell script analysis tool
        shfmt # Format shell programs
        sof-firmware # Sound Open Firmware
        staticcheck # The advanced Go linter
        sudo # Give certain users the ability to run some commands as root
        sysfsutils # System Utilities Based on Sysfs
        terraform # HashiCorp tool for building and updating infrastructure as code idempotently
        texinfo # GNU documentation system for on-line information and printed output
        thunar # Modern file manager for Xfce
        totem # Movie player for the GNOME desktop based on GStreamer
        traceroute # Tracks the route taken by packets over an IP network
        transmission-gtk # Fast, easy, and free BitTorrent client (GTK+ GUI)
        tree # A directory listing program displaying a depth indented list of files
        unrar # The RAR uncompression program
        unzip # For extracting and viewing files in .zip archives
        upx # Extendable, high-performance executable packer for several executable formats
        usbutils # A collection of USB tools to query connected USB devices
        util-linux # Miscellaneous system utilities for Linux
        vi # The original ex/vi text editor
        vim # Vi Improved, a highly configurable, improved version of the vi text editor
        vlc # Multi-platform MPEG, VCD/DVD, and DivX player
        vulkan-intel # Intel's Vulkan mesa driver
        wget # Network utility to retrieve files from the Web
        which # A utility to show the full path of commands
        woff2 # Web Open Font Format 2 reference implementation
        xclip # Command line interface to the X11 clipboard
        xf86-video-intel # X.org Intel i810/i830/i915/945G/G965+ video drivers
        xfce4-screenshooter # An application to take screenshots
        xorg-server # Xorg X server
        xorg-xbacklight # RandR-based backlight control application
        xorg-xhost # Server access control program for X
        xorg-xinit # X.Org initialisation program
        xorg-xkill # Kill a client by its X resource
        xorg-xrandr # Primitive command line interface to RandR extension
        xorg-xset # User preference utility for X
        xsel # XSel is a command-line program for getting and setting the contents of the X selection
        yarn # Fast, reliable, and secure dependency management
        yq # Command-line YAML, XML, TOML processor - jq wrapper for YAML/XML/TOML documents
        zip # Compressor/archiver for creating and modifying zipfiles
    )

    cp -a "$rootdir/files-base/"* "$pkgdir"
    chmod -R 0750 "$pkgdir/etc/sudoers.d"
}

package_lemuel-vm-host() {
    depends=(
        virtualbox # Powerful x86 virtualization for enterprise as well as home use
        virtualbox-host-modules-arch # Virtualbox host kernel modules for Arch Kernel
    )
}

package_lemuel-vm-guest() {
    depends=(
        virtualbox-guest-utils # VirtualBox Guest userspace utilities
    )
}
