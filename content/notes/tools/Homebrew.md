---
title: "Homebrew"
tags: 
  - package manager
  - tools
---

https://brew.sh/

Apparently either beloved or hated, depending on.. things I haven't quite looked into and probably would rather avoid.

Works for me.

On [[notes/OS/macOS]] and [[notes/OS/Ubuntu]], where on the latter it's a nice supplement to out of date or not (yet?) available `apt` packages, while not having to do the `git clone`s and the `sudo make install`s for some common tools, like the [[notes/tools/Modern Unix]] stack

## Installation

The classic "pipe `curl` into `sh` lol"

```shell {title=""}
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```