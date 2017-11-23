# Awesome UNIX® 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# FAQ

###  What was UNIX?

The greatest operating system ever invented you have probably never heard about whose genius design ideas now enable everything great you love. [More...](https://en.wikipedia.org/wiki/History_of_Unix)

### Why is UNIX relevant today?

The ideas behind UNIX, a research operating system from AT&T in the 1960s, have evolved to form a set of core [computer science principles](https://en.wikipedia.org/wiki/Unix_philosophy) around which dozens of operating systems are built. These operating systems and applications built on them underpin most of modern computing, from the mobile devices in your pocket to mainframes that perform climate change analysis. [More...](https://en.wikipedia.org/wiki/Unix#Impact)

### Disambiguation: UNIX, UNIX-Like, and Linux

#### Commercial UNIX

UNIX was originally a research operating system developed at AT&T's Bell Labs.® It has evolved today into a set of operating systems standards, called [POSIX](https://en.wikipedia.org/wiki/POSIX)® overseen by the (IEEE®)[https://en.wikipedia.org/wiki/POSIX], and an official certification that can be obtained by companies for their commercial operating systems, this through a process administrated by (The Open Group®)[https://www.opengroup.org/openbrand/register/]. Among the commercial are massive mainframe operating systems like IBM®'s AIX® as well Apple®'s macOS® desktop operating for their MacBook® and iMac® lineup.

#### UNIX Philosophy

UNIX philosophy is a core set of computer science principles, first implemented in UNIX, now codified in standards set forth by IEEE and The Open Group, and duplicated in dozens of UNIX-like operating systems that emphasize building simple, short, clear, modular, and extensible software on a common set of programming standards and libraries that allow that software to be easily maintained and repurposed by developers other than its creators, across operating systems and platforms. This enables the rapid spread and development of new and better software. It goes hand in hand with [open source philosophy](https://opensource.org/osd-annotated).

> "This is the Unix philosophy: Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface." - *Douglas McIlroy, former head of Bell Labs Computing Sciences Research Center*

#### AT&T UNIX-Derived Descendants, e.g FreeBSD®

The term UNIX also debatedbly encompasses operating systems that are direct descendants of the original AT&T UNIX codebase but have since [re-implemented the AT&T code with code under open source licenses](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution). The most prominent of which the family of BSDs: FreeBSD, OpenBSD, and NetBSD, and their derivatives. These are not UNIX certified, they are technically UNIX-like, but share a unique direct link back to AT&T UNIX and newcomers like RedoxOS do not.

#### UNIX-Like Operating Systems, e.g. Linux®

For a variety of historical and legal reasons, there has also been a massive explosion of *UNIX-like* operating systems. MINIX, for example, was created as a UNIX-like teaching operating system by Prof. Andrew S. Tanenbaum. Linux was created because Linus Torvalds, a college student, [wanted to run a UNIX-like operating system](https://www.cs.cmu.edu/~awb/linux.history.html) on his own hardware. Linux has since gone on to be come the most popular Unix-like operating system. Twenty years later, when Android, Inc. needed a kernel for their new namesake mobile operating system they borrowed one from Linux. Unix-like operating systems implement some degree of the POSIX standards and UNIX principles but do not seek official UNIX certification.

----------

# Real UNIX

## Certified UNIX Operating Systems💰

* [macOS](https://www.apple.com/macos/)® - macOS is the current series of Unix-based graphical operating systems developed and marketed by Apple Inc. designed to run on Apple's personal computers.
* [AIX](https://www.ibm.com/power/operating-systems/aix)® - AIX is a series of proprietary Unix operating systems developed and sold by IBM for several of its computer platforms. 
* [HP-UX](https://www.hpe.com/us/en/servers/hp-ux.html)® - HP-UX is  Hewlett Packard Enterprise's proprietary implementation of the Unix operating system, based on UNIX System V.
* [UnixWare](https://www.xinuos.com)® - UnixWare is a Unix operating system made by Xinuos from the assets of SCO Group.
* [Solaris](https://www.oracle.com/solaris/solaris11/index.html)® - Solaris is a Unix operating system originally developed by Sun Microsystems, acquired by Oracle in 2010.

#### [Get More macOS](#more-macos)
#### [Get More Solaris](#more-solaris)

## AT&T UNIX-Derived Operating Systems ![Open Source][OSS Icon]

* [FreeBSD](https://www.freebsd.org)® - FreeBSD is a free and open-source Unix-like operating system descended from Research Unix via the Berkeley Software Distribution (BSD) known for it's package availability.
	* [GhostBSD](http://www.ghostbsd.org) - GhostBSD is a Unix-like operating system based on FreeBSD with MATE as its default desktop environment.
	* [TrueOS](https://www.trueos.org)® - TrueOS (formerly PC-BSD or PCBSD) is a Unix-like, desktop-oriented operating system built upon the most recent releases of FreeBSD. Features Lumina desktop environment.
	* [FreeNAS](http://www.freenas.org)® - FreeNAS is a free and open-source network-attached storage (NAS) software based on FreeBSD and the OpenZFS file system.
	* [pfSense](https://www.pfsense.org)® - pfSense is an open source firewall/router computer software distribution based on FreeBSD
	* [RaspBSD](http://www.raspbsd.org) - RaspBSD is a image of FreeBSD  that is preconfigured for Raspberry Pi Computers.
	* [MidnightBSD](http://www.midnightbsd.org) - MidnightBSD is a free Unix-like, desktop-oriented operating system based on FreeBSD 6.1 and borrowing heavily from the NeXTSTEP graphical user interface.
	* [Open Server 10](https://www.xinuos.com/menu-products/openserver-10®) - Xinuos® OpenServer 10® is a 64-bit operating system based on the popular FreeBSD and designed to support business applications. 💰
	* [NAS4Free](https://www.nas4free.org) - NAS4Free is an embedded Open Source NAS (Network-Attached Storage) distribution based on the latest FreeBSD releases.
* [NetBSD](https://www.netbsd.org)® - NetBSD is a free and open source Unix-like operating system that descends from Berkeley Software Distribution (BSD), a Research Unix derivative developed at the University of California, Berkeley known for it's wideranging platform support.
* [OpenBSD](http://www.openbsd.org) - OpenBSD is a free and open-source Unix-like computer operating system descended from Berkeley Software Distribution (BSD), a Research Unix derivative developed at the University of California, Berkeley known for it's security and development discipline.
	* [FuguIta](http://fuguita.org/?FuguIta) - FuguIta is an OpenBSD live CD featuring portable workplace, low hardware requirements, additional software, and partial support for Japanese. 
	* [MirBSD](http://www.mirbsd.org) - Fork of OpenBSD that tracks OpenBSD base with a number of enhancements and modifications.  
* [DragonflyBSD](https://www.dragonflybsd.org) - DragonFly BSD is a free and open source Unix-like operating system created as a fork of FreeBSD 4.8.
* [PureDarwin](http://www.puredarwin.org) - PureDarwin is a operating system based on the open-source components of Apple's macOS operating system, principally code derived from NeXTSTEP, BSD, Mach, and other software projects released under free software licenses.

#### [Get More BSD](#more-bsd)

## UNIX-Certified Linux-Based Operating Systems

* [K-UX](http://www.inspursystems.com/product/32-way-system/)® - K-UX is a Linux distribution based on CentOS produced by Inspur®, a Chinese multinational company specializing in information technology. 💰
* [EulerOS](http://developer.huawei.com/ict/en/site-euleros)® -  EulerOS is a Linux distribution based on CentOS produced by Huawei®, a Chinese networking and telecommunications equipment and services company. 💰

#### [Get More UNIX](#more-unix)

# Linux (The Most Popular *UNIX-Like* Operating System)

## Most [UNIX-Like](https://en.wikipedia.org/wiki/Unix_philosophy) Linux [Distributions](https://en.wikipedia.org/wiki/Linux_distribution) ![Open Source][OSS Icon]

* [Devuan](https://devuan.org) - Devuan Linux is a fork of Debian without systemd from UNIX veterans with the goal of becoming the new go-to base distribution for Linux. XFCE is default desktop environment.
	* [heads](https://heads.dyne.org/about.html) - heads is a live CD to connect securely over Tor, unlike Tails it does not rely on systemd or non-free software. awesome is default desktop environment.
	* [Gnuinos](http://gnuinos.org/) - Gnuinos is a lightweight Linux libre distro based on Devuan with no non-free software featuring OpenBox desktop.
	* [Dynebolic Linux](https://www.dyne.org/software/dynebolic/) - Dyne:bolic is a Free Software Foundation-approved Linux libre distro for media activists, artists and creatives. 
* [Alpine](https://alpinelinux.org) - Alpine Linux is an independent, non-commercial, general purpose Linux distribution designed for power users who appreciate security, simplicity and resource efficiency.
	* [Adélie](http://adelielinux.org/) - Adélie Linux was created by Gentoo users who combined the power of Alpine with the ease-of-use of a binary package manager. Adélie is notable for supporting x86, PowerPC, MIPS, and ARM platforms.
* [Void](https://www.voidlinux.eu) - Void is a general purpose operating system, based on the monolithic Linux kernel, Features XBPS packaging system.
* [Cucumber](http://cucumberlinux.com) - Cucumber Linux aims to provide a Linux distribution that is usable as an every day, general purpose operating system. It aims to do this in as minimalistic a way as possible and in a way that follows the Unix Philosophy. 
* [Slackware](http://www.slackware.com) - Slackware is a Linux distribution created by Patrick Volkerding in 1993. Slackware aims for design stability and simplicity and to be the most "Unix-like" Linux distribution
* [GuixSD](https://www.gnu.org/software/guix/) - GuixSD is an advanced distribution of the GNU operating system developed by the GNU Project —which respects the freedom of computer users.
* [Gentoo](https://www.gentoo.org)® - Gentoo is a Linux distribution built using the Portage package management system. Unlike a binary software distribution, the source code is compiled locally.
	* [Funtoo](https://www.funtoo.org/Welcome) - Funtoo Linux is a Linux-based operating system that is a variant of Gentoo Linux.
	* [Redcore](https://redcorelinux.org) - Redcore Linux is a distribution based on Gentoo Linux that aims to be a very quick way to install a pure Gentoo Linux system without spending hours or days compiling from source code.
* [Dragora](https://www.dragora.org/) - The Dragora project produces a libre, reliable, UNIX-like GNU/Linux distribution made from scratch!
* [Morpheus](https://morpheus.2f30.org) - Linix distribution built with staticly linked binaries using [musl libc](http://www.musl-libc.org) featuring suckless tools.
* [Stali](https://sta.li) - stali is a static linux distribution based on the original pre-2010 plans of the suckless.org project, but with a couple of revised goals.
* [OviOS](http://www.ovios.org) - OviOS is a distribution designed to easily deploy a Linux unified storage server. Written from scratch it is fully compatible with the Linux Standard Base.
* [KNOPPIX](http://www.knopper.net/) - KNOPPIX is a Debian-based distribution that can be run entirely from a CD or USB on computers with minimal hardware specificiations. Replaces systemd in Debian with sysV and systemd-shim.

## Popular Commercial Linux Distributions ![Open Source][OSS Icon]

* [Red Hat Enterprise Linux](https://www.redhat.com)® - Red Hat Enterprise Linux is a Linux distribution developed by Red Hat® and targeted toward the commercial market. 💰
* [Ubuntu](https://ubuntu.com)® - Ubuntu is a Debian-based Linux distribution published by Canonical® who offer commercial support for enterprise-class Ubuntu Server variant.
* [SUSE Linux Enterprise](https://www.suse.com)® - SUSE Linux Enterprise is a Linux-based operating system developed by SUSE®. It is designed for servers, mainframes, and workstations. 💰
* [elementaryOS](https://elementary.io) - elementary OS is a consumer-oriented Linux distribution based on Ubuntu. It is the flagship distribution to showcase the Pantheon desktop environment.💰
* [Oracle](https://www.oracle.com/linux/)® - Oracle Linux® is compiled from Red Hat Enterprise Linux source code, replacing Red Hat branding with Oracle's, optimized to run Oracle software. 💰
* [Pop!_OS](https://system76.com/pop) - POP!_OS is a developer-focused minimalist Linux distro from Linux hardware manufacturer System 76®.

## Popular Non-Commercial Linux Distributions ![Open Source][OSS Icon]

* [Debian](https://www.debian.org)® - Debian is a Unix-like computer operating system that is composed entirely of free software, most of which is under the GNU General Public License and packaged by a group of individuals participating in the Debian Project.
* [Fedora](https://getfedora.org)® - Fedora is an Unix-like operating system based on the Linux kernel and GNU programs (a Linux distribution), developed by the community-supported Fedora Project and sponsored by the Red Hat company.
* [CentOS](https://centos.org) - CentOS is a Linux distribution that attempts to provide a free, enterprise-class, community-supported computing platform functionally compatible with its upstream source, Red Hat Enterprise Linux.
* [Magiea](https://www.mageia.org) - Mageia is a Linux based operating system, distributed as free and open source software. It is forked from the Mandriva Linux distribution.
* [OpenSUSE](https://www.opensuse.org) - openSUSE formerly SUSE Linux and SuSE Linux Professional, is a Linux-based project and distribution sponsored by SUSE Linux GmbH and other companies.
* [Arch](https://www.archlinux.org) - Arch Linux is a Linux distribution for computers based on x86-64 architectures.
	* [Antergos](https://antergos.com) - Antergos is a Linux distribution based upon Arch Linux.
	* [Manjaro](https://manjaro.org) - Manjaro Linux is an open source operating system for computers. It is a distribution of Linux based on the Arch Linux distribution.
* [Solus](https://solus-project.com) - Solus is an independent desktop operating system based on the Linux kernel. It is offered as a curated rolling release model under the slogan "Install Today. Updates Forever".
* [Mint](https://linuxmint.com) - Linux Mint is a community-driven Linux distribution based on Debian and Ubuntu that strives to be a "modern, elegant and comfortable operating system which is both powerful and easy to use.

## Popular Mobile Linux Distributions ![Open Source][OSS Icon]

* [AOSP](https://source.android.com) - Android® is a mobile operating system developed by Google®, based on the Linux kernel and designed primarily for touchscreen mobile devices such as smartphones and tablets.
* [CopperheadOS](https://copperhead.co/android/)® - CopperheadOS is a source-available operating system for smartphones and tablet computers, based on the Android mobile platform. It is based on the official releases of the Android Open Source Project by Google, with added privacy and security features.💰
* [LineageOS](https://lineageos.org) - LineageOS is a free and open-source operating system for smartphones and tablet computers, based on the Android mobile platform.
* [postmarketOS](https://postmarketos.org) - postmarketOS, is a free and open-source operating system under development primarily for smartphones, based on the lightweight Alpine Linux distribution.

## Interesting Linux Distributions/Related Projects 

* [GoboLinux](https://www.gobolinux.org) - GoboLinux is an alternative Linux distribution which redefines the entire filesystem hierarchy. In GoboLinux you don't need a package database because the filesystem is the database. ![Open Source][OSS Icon]
* [oasis](https://github.com/michaelforney/oasis) - A small statically-linked linux system suitable for a range of uses including server and desktop. The entire system can be compiled in minutes.
* [Tails](https://tails.boum.org) - Tails is a security-focused Debian-based Linux distribution aimed at preserving privacy and anonymity ![Open Source][OSS Icon]
* [Bedrock](https://bedrocklinux.org/) - Bedrock Linux is a Linux distribution created with the aim of making most of the (often seemingly mutually-exclusive) benefits of various other Linux distributions available simultaneously and transparently. ![Open Source][OSS Icon]
* [QubesOS](https://www.qubes-os.org) - Qubes OS is a security-focused desktop operating system that aims to provide security through isolation. Virtualization is performed by Xen®, and user environments can be based on Fedora, Debian, Whonix, and Microsoft Windows, among other operating systems. ![Open Source][OSS Icon]
* [Windows Linux Subsystem](https://msdn.microsoft.com/en-us/commandline/wsl/faq) - Windows® Subsystem for Linux (WSL) is a compatibility layer for running Linux binary executables (in ELF format) natively on Windows 10.® 💰

### [Get more Linux](#more-linux)

# Other UNIX-Like/Related Operating Systems

## Plan 9® Derivatives ![Open Source][OSS Icon]

Plan 9 was developed by Bell Labs as the successor to UNIX and incorporated novel ideas, such as a GUI and [distributed computing](https://en.wikipedia.org/wiki/Distributed_operating_system). Official development by Bell Labs has since halted but the code was re-released under the GPL and projects exist to build on Plan 9. Many Bell Labs employees still volunteer on these projects.

* [9front](http://9front.org) - 9front is a fork of Plan 9 from Bell Labs by the People's Front of Cat-V. It is a next generation mushroom cloud computing platform for the 20th century. 
* [9legacy](http://9legacy.org) - 9legacy is an experimental patch queue for Plan 9 from Bell Labs.
* [Harvey OS](https://harvey-os.org) - Harvey is an effort to provide a modern, distributed, 64 bit operating system. A different environment for researching and finding new lines of work. It can be built with gcc and clang and has an ANSI/POSIX compliant subsystem.
* [Inferno](http://www.vitanuova.com/inferno/)® - Inferno was an effort to commercialize Plan 9 as networking software, however like Plan 9 it remained obscure while it's ideas permeated into current operating systems. 
* [Jehanne](http://jehanne.io) - Jehanne is a new distributed operating system designed for programmers. The core values that lead the development are simplicity and security. Jehanne is a fork of Harvey.

## OpenSolaris/illumos® ![Open Source][OSS Icon]

Solaris® was originally a UNIX operating system developed jointly by Sun Microsystems® and AT&T® as a version of AT&T's UNIX System V Release 4. Sun continued development on Solaris and later obtained UNIX certification for Solaris. In 2004 Sun open-sourced much of the Solaris code base as OpenSolaris. Sun was acquired by Oracle in 2010 who discontinued formal support of the OpenSolaris project. OpenSolaris was forked and lives on as illumos.

* [illumos](https://wiki.illumos.org/display/illumos/illumos+Home) - illumos is a free and open-source Unix operating system. It derives from OpenSolaris, which in turn derives from SVR4 UNIX and Berkeley Software Distribution (BSD). 
	* [OpenIndiana](https://www.openindiana.org) - OpenIndiana is a free and open-source, Unix operating system derived from OpenSolaris and based on illumos. Developers forked OpenSolaris after Oracle Corporation discontinued it.
	* [DilOS](http://www.dilos.org) - DilOS is an illumos-based platform featuring the Debian package manager (dpkg+apt).
	* [SmartOS](https://www.joyent.com/smartos) - SmartOS is a free and open-source SVR4 hypervisor, based on the UNIX operating system that combines OpenSolaris technology with Linux's KVM virtualization. Its core kernel contributed to illumos project.
	* [Tribblix](http://tribblix.org) - Tribblix is an operating system created by Peter Tribble. Derived from OpenSolaris, OpenIndiana, and illumos, it blends a retro style with modern components.
	* [XStreamOS](http://www.sonicle.com/index.jsp?pagename=xstreamos&parent=products) - XStreamOS is an  effort to mantain a distribution of the illumos kernel, featuring a customized text install, the ZFS fileystem, advanced features, and a starting point to contribute and develop the illumos kernel.
	
#### [Get More Solaris](#more-solaris)

## UNIX-Like Real Time Operating Systems ([RTOS](https://en.wikipedia.org/wiki/Real-time_operating_system))

A real-time operating system (RTOS) is an operating system (OS) intended to serve real-time applications that process data as it comes in, typically without buffer delays. An example of this in QNX which is used widely in cars and trucks.

* [QNX](https://blackberry.qnx.com/en)® - QNX is a commercial Unix-like real-time operating system, aimed primarily at the embedded systems market. 💰
* [Integrity](https://www.ghs.com/products/rtos/integrity.html)® - Integrity is a real-time operating systems produced and marketed by Green Hills Software. Integrity-178B has a top National Security Agency rating. 💰
* [Contiki](http://contiki-os.org) - Contiki is an operating system for networked, memory-constrained systems with a focus on low-power wireless Internet of Things devices. ![Open Source][OSS Icon]
* [LynxOS](http://www.lynx.com/products/real-time-operating-systems/lynxos-rtos/)® - The LynxOS RTOS is a Unix-like real-time operating system from Lynx Software Technologies. LynxOS features full POSIX conformance and, more recently, Linux compatibility. 💰
* [nuttX](http://nuttx.org)® - NuttX is a real-time operating system (RTOS) with an emphasis on standards compliance and small footprint. Scalable, the primary focus in NuttX are POSIX and ANSI standards. ![Open Source][OSS Icon]
* [Fuchsia](https://github.com/fuchsia-mirror?utf8=✓&query=Escher) - Fuchsia is a new real-time operating system (RTOS) [currently being developed](https://lwn.net/Articles/718267/) by Google with a degree of POSIX compataibility.

## Other UNIX-Like Operating Systems ![Open Source][OSS Icon]

* [Minoca OS](https://github.com/minoca/os) - Minoca OS is a general purpose operating system written from scratch. It aims to be lean, maintainable, modular, and compatible with existing software.
* [Redox](https://www.redox-os.org) - Redox is a Unix-like microkernel operating system written in the programming language Rust, a language with focus on safety and high performance. Redox aims to be secure, usable, and free.
* [GNUSTEP](http://www.aiei.ch/gnustep/) - GNUSTEP is based on Debian 9. without systemd, and features a free implementation of the OPENSTEP and Cocoa frameworks, a continuation of NeXT OS and a common heritage with macOS.
* [Minix](http://www.minix3.org)® - Minix is a POSIX-compliant Unix-like computer operating system based on a microkernel architecture.
* [Haiku](https://www.haiku-os.org) - Haiku is a free and open-source operating system compatible with the now-discontinued BeOS.® Its development began in 2001, and the operating system became self-hosting in 2008.
* [GNU/Hurd](https://www.gnu.org/software/hurd/hurd.html) - GNU Hurd is the multiserver microkernel written as part of GNU. It has been under development since 1990 by the GNU Project of the Free Software Foundation, designed as a replacement for the Unix kernel, and released as free software under the GNU General Public License.
* [Akaros](https://github.com/brho/akaros) - Akaros is an open source, GPL-licensed operating system for manycore architectures. The goal is to provide support for parallel and high-performance applications and to scale to a large number of cores.
* [Sortix](https://sortix.org) - Sortix is a small self-hosting operating-system aiming to be a clean and modern POSIX implementation, a hobbyist operating system written from scratch with its own base system, including kernel and standard library, as well as ports of third party software.
* [OpenVMS](http://www.vmssoftware.com)™ - OpenVMS is a enterprise operating system known for it's reliability. It is the successor to the VMS Operating System and runs on DEC Alpha systems. POSIX compatibility was added in 1991.

-----

# Additional Resources

## More UNIX

### Disambiguation

* [Differentiating UNIX and Linux](https://www.ibm.com/developerworks/aix/library/au-unix-difflinux.html)
* [What, a real UNIX®?](https://www.freebsd.org/doc/en_US.ISO8859-1/articles/explaining-bsd/what-a-real-unix.html)
* [10 differences between Linux and BSD](https://www.techrepublic.com/blog/10-things/10-differences-between-linux-and-bsd/) 📰
	
### History

* [Unix Heritage Wiki](http://wiki.tuhs.org/doku.php?id=start)
* [Unix History Repository](https://github.com/dspinellis/unix-history-repo)
* [WinWorld Library](https://winworldpc.com/library/operating-systems) - Collection of abandonware operating systems.
* [AT&T 3B1 Emulator](http://www.philpem.me.uk/code/3b1emu/) - Emulate the original AT&T UNIX.
* [[YouTube] AT&T Archives: The UNIX Operating System](https://www.youtube.com/watch?v=tc4ROCJYbm0) 📼

### Philosophy

* [Basics of the Unix Philosophy](http://www.catb.org/~esr/writings/taoup/html/ch01s06.html)
* [Program Design in the UNIX Environment](https://nymity.ch/sybilhunting/pdf/Pike1983a.pdf) [PDF]
* [Do one thing, and do it well: 40 years of UNIX](https://techcrunch.com/2009/08/21/do-one-thing-and-do-it-well-40-years-of-unix/) 📰

### Technical Standards

* [The Open Group](http://www.opengroup.org)®
	* [UNIX Certified Products](https://www.opengroup.org/openbrand/register/)
	* [POSIX Certification Register](http://get.posixcertified.ieee.org/register.html)
* [IEEE Standard 1003.1™-2008](http://pubs.opengroup.org/onlinepubs/9699919799/)

### Community

* [nixCraft](https://www.cyberciti.biz)
* [DistroWatch](http://distrowatch.com)
* IRC [freenode](https://webchat.freenode.net)
	* ##unixlove
	* ##climagic
	* ##kernel
* [Awesome Sysadmin](https://github.com/kahun/awesome-sysadmin) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## More macOS

* [Awesome Mac](https://github.com/jaywcjlove/awesome-mac) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [Awesome macOS Command Line](https://github.com/herrbischoff/awesome-osx-command-line) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## More Solaris

* [What are SunOS and Solaris?](https://kb.iu.edu/d/agjq)
* [Awesome DTrace](https://awesome-dtrace.com) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
	
## More BSD

* [Awesome BSD](https://github.com/DiscoverBSD/awesome-bsd) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [BSD v. Linux](https://www.over-yonder.net/~fullermd/rants/bsd4linux/01)
	
## More Linux

* [Awesome Linux Software](https://github.com/LewisVo/Awesome-Linux-Software) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [Awesome Linux](https://github.com/aleksandar-todorovic/awesome-linux) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
* [Linux Standard Base](https://en.wikipedia.org/wiki/Linux_Standard_Base) - LSB is an effort to develop a unifying set of standards for Linux not unlike the Open Group's standards for UNIX. 

## UNIX and UNIX-Like Hardware Vendors

* [Apple](https://apple.com)® - macOS laptops and desktops, x86
* [System76](https://system76.com)® - Linux laptops and desktops, x86
* [Purism](https://puri.sm)® - Linux laptops, x86
* [Entroware](https://www.entroware.com/store/)® - Linux laptops, desktops, and servers, x86
* HP
	* [Consumer/Business](http://www8.hp.com/us/en/campaigns/ubuntu/index.html)® - Linux laptops, desktops, and servers
	* [HP Enterprise](https://www.hpe.com/us/en/servers/hp-ux.html)® - HP-UX servers, x86 and PA-RISC
* [Oracle](https://www.oracle.com/servers/index.html)® - Linux and Solaris servers, x86 and SPARC
* [Dell](http://www.dell.com/learn/us/en/555/campaigns/xps-linux-laptop_us)® - Linux laptops, desktops, and servers; x86
* [IBM](https://www.ibm.com/linuxone)® - Linux and AIX servers, x86 and RISC
* [Raptor Engineering](https://raptorcs.com/TALOSII/)® - Linux PowerPC® workstation
* [PowerPC Notebook](https://www.powerpc-notebook.org/) - Linux laptop with PowerPC architecture
* [StationX](https://stationx.rocks) - Linux laptops and desktops, x86
* [Fujitsu](http://www.fujitsu.com/global/products/computing/servers/unix/sparc/index.html)® - Linux and Solaris servers, SPARC®
* [Inspur](http://www.inspursystems.com/product/32-way-system/)®
* [Huawei](http://developer.huawei.com/ict/en/site-euleros)®

-----

### Intellectual Property Notices

* UNIX® and UnixWare® are registered trademarks of The Open Group, Inc.
* FreeBSD® is a registered trademark of The FreeBSD Foundation.
* NetBSD® is a registered trademark of The NetBSD Foundation, Inc.
* Apple®, MacBook®, iMac®, and macOS® are registered trademarks of Apple, Inc.
* Debian® is a registered trademark of Software in the Public Interest, Inc.
* IEEE®, IEEE Standard 1003.1, and POSIX® are trademarks or registered trademarks of The Institute of Electrical and Electronics Engineers, Inc.
* Bell Labs® and Plan 9® are registered trademarks of Alcatel-Lucent USA, Inc.
* Linux® is a registered trademark of Linus Torvalds.
* AT&T® is a registered trademark of AT&T Intellectual Property II, LLC.
* AIX®, PowerPC®, and IBM® are trademarks or registered trademarks of IBM Corporation.
* HP® and HP-UX® are trademarks or registered trademarks of HP Hewlett Packard Group, LLC.
* Illumos® is a registered trademark of Garrett D'Amore.
* Xinuos® is a registered trademark of Xinuos, Inc.
* Solaris®, Oracle®, and Sun Microsystems® are trademarks or registered trademarks of Oracle Corporation.
* Slackware is a trademark of Patrick Volkerding.
* Google® and Android® are registered trademarks of Alphabet, Inc.
* TrueOS® and FreeNAS® are registered trademarks of IXsystems, Inc.
* BeOS® is a registered trademark of ACCESS Systems Americas, Inc. 
* Xen® is a registered trademark of the Linux Foundation.
* K-UX® and Inspur® are registered trademarks of Inspur Technologies Co., Ltd.
* EulerOS® and Huwaei® is a registered trademarks of Huawei Technologies Co., Ltd.
* pfSense® is a registered trademark of Electric Sheep Fencing, LLC.
* Inferno® is a registered trademark of Vita Nuova Holdings Ltd.
* Red Hat®, Fedora®, and Red Hat Enterprise Linux® are trademarks or registered trademarks of Red Hat, Inc.
* Ubuntu® and Canonical® are registered trademark of Canonical Limited.
* SUSE® and SUSE Linux Enterprise® are registered trademarks of SUSE.
* System76® is a registered trademark of System76, Inc.
* Windows® and Microsoft® are registered trademarks of Microsoft Corporation.
* QNX® is a registered trademark of Blackberry Limited.
* Huawei is is a trademark or registered trademark of Huawei Technologies Co. Ltd.
* Integrity® and Green Hills Software are registered trademarks of Green Hills Software.
* LynxOS® is a registered trademark of Lynx Software Technologies, Inc.
* CopperheadOS® is a registered trademark of Copperhead Limited.
* MINIX® is a trademark or registered trademark of Pearson Education, Inc. in the United States.
* Gentoo® is a registered trademark of Gentoo Foundation, Inc.
* Dell® is a trademark or registered trademark of Dell, Inc.
* Entroware® is a trademark of Entroware, a UK company.
* Raptor Computing Systems® is a registered trademark of Timothy Pearson.
* OpenVMS is a trademark or registered trademark of VMS Software, Inc.
* Fujistu® is a trademark or registered trademark of Fujitsu Limited.
* SPARC® is a trademark or registered trademarks of SPARC International, Inc.

All other trademarks mentioned herein are the property of their respective owners.

This document is licensed under [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).

Portions of the descriptions above are from Wikipedia and used under [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).

[OSS Icon]: https://cdn.rawgit.com/iCHAIT/awesome-osx/master/media/oss.svg
