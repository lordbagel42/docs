---
author: Raygen Rupe
---

[Portainer](https://portainer.io/) is the GUI I use to manage docker environments. 

!!!danger
***I wish I had not used portainer.***

Portainer can cause instability and due to where files end up stored recovery of broken states can be near impossible, especially remotely.
!!!

I initially decided to use Portainer mostly because I had heard of it and wanted to get into having a large amount of apps, and at the time did not understand `docker` nor `docker-compose`. I warn against using Portainer as once you reach a certain point, you develop a reliance on it. I have almost 50 stacks in it, with no easy way to export or leave portainer other than copy and pasting them into `docker-compose.yml` files one by one and praying everything migrates correctly.

That being said, Portainer was definitely a very useful tool when I began getting into selfhosting. It allowed me to 