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
