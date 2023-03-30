---
title: "exa"
tags: 
  - tools
  - shell
---

`exa` is neat as it shows pretty colors, optional [[notes/tools/git]] status, and icons.
It's part of the [[notes/tools/Modern Unix]] stack, supplementing the venerable `ls`.

I have it aliased to show `git` icons by default, because that's kind of the selling feature in my case:

```shell
alias exa=exa -l --git --icons
```

![[assets/Screenshot 2023-03-29 at 01.11.15.jpg]]

I prefer [[lsd]] though, even though it does not have the same `git` feature, it is also pretty by default _and_ it's arguments are backward compatible with GNU `ls`, so you can keep all your existing aliases and muscle memory.
Also, `lsd` is slighty faster (even without the `git` status), but that may vary on caching and whatnot --- the point is that `lsd` feels snappier in my experience, and since typing `l` is kind of a habitual thing I type many times a day, that counts for something ¯\_(ツ)_/¯.