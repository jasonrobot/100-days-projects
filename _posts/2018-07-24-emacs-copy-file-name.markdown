---
layout: post
title:  "Emacs Plugin: Copy file name.
date:   2018-07-24 18:00:00 -0700
categories: post
---

# Emacs Copy File Name

You know, I thought I had a gist of the function I wrote up somewhere, but I guess not.
It is in my configs repo here though https://github.com/jasonrobot/configs/blob/master/emacs.d/init.el#L152

The idea would be to broaden this out, package it, and put it in melpa or something.

### What I'd implement
copy-file-name: copies just the name of the file
copy-file-path: copies the full path of the file
(probably would want something to get just the dir-part too)
projectile-copy-file-name: copy the filename relative to the root of the current projectile project

Might want to find a better name for those functions too, since it doesnt really imply string -> clipboard right off the top of the head.
