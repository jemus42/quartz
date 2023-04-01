---
title: "cuda"
tags:
 - Sysadmin
---

[Nvidia installation instructions](https://docs.nvidia.com/datacenter/tesla/tesla-installation-notes/index.html#ubuntu-lts).

Can be a pain, usually is.

Note that [[notes/Unattended Upgrades]] can ruin your day by auto-upgrading drivers apprently, which will at best require a reboot before the GPUs can be used again and at worst screw up your whole package situation such that you may have to nuke everything and reinstall drivers/cuda things.