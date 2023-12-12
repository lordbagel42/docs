---
author: Raygen Rupe
order: 100000
---

I run <ins>**as much as possible**</ins> in docker. There are many things that couldn't be dockerized so I abandoned them for months (eg, Pterodactyl Panel).

Currently, I manage everything through [Portainer](/overview/portainer), a GUI for docker.

## Devices Used:

**1x Raspberry Pi 2**
:   > Runs Klipper with Mainsail on my Ender 3 3d printer.
    > Used only for this

**1x Raspberry Pi 3**
:   > I run Home Assistant on this along with a few add-ons:
    > - MariaDB as a database
    > - Mosquitto Broker for MQTT
    > - a [Matter](https://en.wikipedia.org/wiki/Matter_(standard)) server, currently inactive.

**1x Dell Inspiron All-In-One 3048 01**
:   > I use this for the bulk of my hosting.
    > **Referred to as `inspiron-server`.**

    > Operating system is Ubuntu Server 22.04, running:
    > - Nextcloud
    > - Authentik
    > - Nginx Proxy Manager
    > - The [Emulation](/emulation/) Stack
    > - Plex (and all of that stack)
    > - Wyoming-Whisper and Wyoming-Piper

!!!info
It should be noted I do also host some things using Oracle Cloud, described more in [Cloud Computing](/cloud-computing).

This entire documentation site is also hosted in [Github Pages](https://pages.github.com/) for high availability and reduced load.
!!!