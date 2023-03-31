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

Or how to set up GPG signing commits.

Or how to store credentials securely on Linux (sigh), which I currently do with [[gh]]:

```
[credential "https://github.com"]
	helper =
	helper = !/opt/homebrew/bin/gh auth git-credential
[credential "https://gist.github.com"]
	helper = !/opt/homebrew/bin/gh auth git-credential
```