---
title: "Fixing file associations on macOS"
tags: 
  - tools
  - macOS
---

When you try to open a small [[YAML]] file and nothing happens, only to realize that the behemoth that is Xcode has been starting up for what feels like minutes --- that's when it's time to recheck file type associations on your machine.

[[notes/tools/duti]] is a neat and ancient little tool for that. It's _unsupported_ and I wouldn't rely on it in the long run, but as long as it still works, it works.

## Checking associations

```shell
❯ duti -x yaml
Zed.app
/Applications/Zed.app
dev.zed.Zed

❯ duti -x sh
Xcode.app
/Applications/Xcode.app
com.apple.dt.Xcode
```

## Fixing associations

```
duti -s com.microsoft.VSCode sh all
duti -s com.microsoft.VSCode bash all
duti -s com.microsoft.VSCode zsh all
duti -s com.microsoft.VSCode yml all
```

Useful identifiers:
- `dev.zed.Zed`
- `com.rstudio.desktop`
- `com.microsoft.VSCode`
- `org.videolan.vlc`
- `com.apple.TextEdit`
- `com.apple.Finder`