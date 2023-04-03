---
title: "fzf"
date: "2023-04-03 22:11"
alias: 
tags:
  - tools
  - shell
---

https://github.com/junegunn/fzf

A fuzzy-finding-thing from the [[notes/tools/Modern Unix]] stack.

Neat use-case is live-updating `jq` filters ([via](https://social.jvns.ca/@b0rk/110135929111161568)):

```shell {title=""}
echo '' | fzf --preview 'jq {q} < filename.json'
```