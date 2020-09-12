# Bash

## Find total size of files found with find

```bash
find -print0 | xargs -0 du -hc
```

# Videos

## Convert file to UTF-8 encoding
`enconv -L ru -x UTF-8`

# Working with archives

## Unzip file without saving

```bash
wget -qO- link | bsdtar -xvf -
```

# Date and time

## Print current unix timestamp

```bash
date +%s
```

## List files

# Git

## Find branches that contain given commit

```bash
git branch --contains $commit
```

# Vim
