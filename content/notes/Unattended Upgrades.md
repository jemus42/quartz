---
title: "Unattended Upgrades"
tags:
  - ubuntu
  - sysadmin
---

Config for apt on [[notes/OS/Ubuntu]]:

```
/etc/apt/apt.conf.d/50unattended-upgrades
```

To disable auto-updating nvidia / [[cuda]] packages:

```
// Python regular expressions, matching packages to exclude from upgrading
Unattended-Upgrade::Package-Blacklist {
     // Do not upgrade nvidia stuff
     "nvidia*";
     "libnvidia*";
     "cuda*";
     // ...
```

At leats I think that should work.