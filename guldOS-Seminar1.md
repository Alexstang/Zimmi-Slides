# guldOS Seminar Day 1

### *Author: Ira Miller*

## Seminar Goal

Each student will build their own trusted computing environment.

Install and understand the guldOS encryption toolset featuring PGP.

Leave confident in ability to secure private data, be it an email or a bitcoin private key.

![BitcoinLogo](https://github.com/Alexstang/Zimmi-Slides/blob/master/Bitcoin.jpg) <![PurpleguldLogo](https://github.com/Alexstang/Zimmi-Slides/blob/master/purpleguld.jpg)

## Sources

[guldOS Specification](http://guld.io/)

[Gentoo Handbook](https://wiki.gentoo.org/wiki/Handbook:AMD64/Full/Installation)

[Ubuntu LiveCD](https://help.ubuntu.com/community/LiveCD)

[![OpenSourceLego](https://github.com/Alexstang/Zimmi-Slides/blob/master/OpenSourceLego.jpg)](https://www.youtube.com/watch?v=a8fHgx9mE5U)

## Background

* GuldOS is a security and privacy focused Operating System (OS) for the network of the future.
* GuldFS is a decentralized, immutable FileSystem (FS) and file sharing network.
* The Blocktree is the hashed merkle polytree that guldFS reads and writes to.
* Directed Acyclic Graphs are a subset of trees that does not allow loops, but does allow branches.

![Dag](https://github.com/Alexstang/Zimmi-Slides/blob/master/DagDiagram.jpg)

## Your Background?

* What is your relationship with open source?
* Do you own or use digital currencies? If so, do you control your private keys?
* Do you encrypt or digitally sign your messages, such as email?
* What are your main security and privacy concerns?

![CartoonQuestion](https://github.com/Alexstang/Zimmi-Slides/blob/master/CartoonQuestion.jpg)

## Gentoo

Gentoo is a well maintained source distribution of GNU/Linux.

This means Gentoo users each compile their system from source code, instead of running someone else's binary.

Binaries may differ from the source, i.e a MITM attack.

Binaries compiled for general packaging have all options turned on, creating maximum surface area for attacks.

![Gentoo](https://github.com/Alexstang/Zimmi-Slides/blob/master/gentoo.jpg)

## Bios

### *Put USB first in boot order.*

![Bios](https://github.com/Alexstang/Zimmi-Slides/blob/master/Bios.jpg)

## LiveCD (USB)

![LiveCD](https://github.com/Alexstang/Zimmi-Slides/blob/master/LiveCD.jpg)

1. Boot into Ubuntu? LiveCD
2. Choose "Try" not "Install"
3. Upon login, check the internet.

## Terminal

### *Try to open a terminal. Can you become root? Root is god, in a computer.*

![Terminal](https://github.com/Alexstang/Zimmi-Slides/blob/master/Terminal.jpg)

## Gentoo Stage 3

Look for the Gentoo Stage 3 tarball.

It should be called <br> stage3-amd64-hardened-20171005.tar.bz2

It has a sha1sum of <br> 4fa1e6421df308257a2e25cbd64e5e70aa99c48f

This is a fresh, clean slate Gentoo installation, ready to write directly to disk. Accomplishing this from our liveCD environment is the first goal.
