---
title: Writing LaTex on Ubuntu using VSCode
date: 2017-09-28 16:21:51
tags: LaTex
---

__LaTex__ is one of the best thing I've learned ever (another is markdown). It's really a ease for me to concentrate myself to contents rather than styles.

[OverLeaf](www.overleaf.com) is a pretty good tool for LaTex writing and there are plenty of templates there for beginners or professionals. The tricky things is, the speed of its live rendering highly relies on network, which is quite annoying.

It would be a good choice to have a local writing environment (so that I can use my favorite editor). I use VSCode in general.

### Install LaTex Dependencies on Ubuntu

```shell
sudo apt-get update
sudo apt-get install texlive latexmk texlive-latex-extra
```

This is enough for me. You can install other textlive packages if you need.

### Install VSCode LaTex Addons

There is a great addons called [LaTex Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop). Simply install it and then you can having your latex project work.

---

__Happy Writing LaTex!__