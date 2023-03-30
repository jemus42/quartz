---
title: "Shell Scripting"
tags:
  - programming
---

I always look up the same things again and again and/or refer to old scripts where I've done the looking up. Might as well start dumping some things here.

## Arrays

I _think_ this is compatible with [[bash]]/[[notes/tools/zsh]], but not sure. I tend to stick to bash for scripts for portability, just in case.

```shell
packages=( ctop lazydocker )

for i in "${packages[@]}"
do
  echo "Checking if $i is available..."
  if [ -x "$(command -v $i)" ]; then
    echo "Found $i"
  else
    brew install $i
  fi
done
```

## Case

```shell
case expression in
    pattern1 )
        statements 
    ;;
    pattern2 )
        statements
    ;;
    ...
esac
```