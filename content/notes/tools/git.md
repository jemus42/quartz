---
title: "git"
tags:
  - tools
---

Should this be its own tag?

At some place I'd need to collect useful commands, like adding the following to `.gitconfig`:

```
[alias]
	adog = log --all --decorate --oneline --graph
```

Because it's useful to `git adog` sometimes.

Or setting up [[notes/tools/delta]] for nicer diffs:

```
[pager]
    diff = delta
    log = delta
    reflog = delta
    show = delta

[delta]
    plus-style = "syntax #012800"
    minus-style = "syntax #340001"
    syntax-theme = Monokai Extended
    navigate = true

[interactive]
    diffFilter = delta --color-only
```

## GPG signing commits



## GitHub Credentials

Currently relying on [[gh]] on Linux:

```
[credential "https://github.com"]
	helper =
	helper = !/opt/homebrew/bin/gh auth git-credential
[credential "https://gist.github.com"]
	helper = !/opt/homebrew/bin/gh auth git-credential
```

On [[notes/OS/macOS]] (and presumably Windows), we can use system keychains without any headaches.