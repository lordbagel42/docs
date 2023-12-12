---
author: Raygen Rupe
order: 100000
---

I run as much as possible in docker. There are many things that couldn't be dockerized so I abandoned them for months (eg, Pterodactyl Panel).

Currently, I manage everything through [Portainer](/overview/portainer), a GUI for docker.

I have a total of three devices I run software on often:
   - 1x Raspberry Pi 3, used for [Home Assistant](/)
   - 1x Raspberry Pi 2, used for [my 3d printer](/printer)
   - 1x Dell Inspiron 20 Model 3048 01 All-In-One desktop, hereby known as `inspiron-server`.

Raspberry Pi 2
:   > Runs Klipper with Mainsail on my Ender 3 3d printer.
    > Used only for this

Raspberry Pi 3
:   > I run Home Assistant on this along with a few add-ons:
    > - MariaDB as a database
    > - Mosquitto Broker for MQTT
    > - a [Matter](https://en.wikipedia.org/wiki/Matter_(standard)) server, currently inactive.

Dell Inspiron All-In-One 3048 01
:   > I use this for the bulk of my hosting.
    > **Referred to as `inspiron-server`.**

!!!
It should be noted I do also host some things using Oracle Cloud, described more in [Cloud Computing](/cloud-computing)