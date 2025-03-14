# Remember
## Useful Search Engines
* [shodan.io](https://shodan.io) (IoT devices)
* censys.io (Servers)
* hunter.io (Email)
* urlscan.io (Websites)
* grep.app (Source Code)
* intelx.io (OSINT)
* wigle.net (WiFi)
* fullhunt.io (Attack Surface)
* vulners.com (Vulnerabilities)
* viz.greynoise.io (Threat Intel) 

## OpenJDK Java crashes on Debian/Kali VM on an M4 MBP
* Try `export JAVA_TOOL_OPTIONS="-XX:UseSVE=0"`
  *  Disables use of the Arm AArch64 [SVE extension]([url](https://developer.arm.com/documentation/102476/0101/Introducing-SVE)) for which there is a [bug in the OpenJDK Java library]([url](https://bugs.openjdk.org/browse/JDK-8345296)).

## Resize VM disk on a live system
* [Use gpartd](https://gparted.org/) as its available many *nix systems.
* [Easy Guide to Resizing Linux Partitions Using GParted](https://medium.com/@itsnibhatt/easy-guide-to-resizing-linux-partitions-using-gparted-3567d60bf660)

## Kali guest VMWare Fusion
* [Kali](https://kali.org/) has Debian 12 flavour

## Conventional Commits
* [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) looks like a good idea...
