---
title: "Git Submodule Theme"
date: 2023-06-09T23:50:47+06:00
draft: false
---

### Initializing git repository
Before executing any of the other commands below, make sure you have initialized your git repository by issuing the following command:

```bash
 git init
``` 

### Adding a theme
Once you have initialized your git repository, you can go ahead and add one or more themes to your website.
In this case, I’ve added the Toha theme as a git submodule using the following command:

```bash
git submodule add https://github.com/zzossig/hugo-theme-zzo themes/zzo
```

### Updating a theme
When it is time to update your theme, it is as simple as updating the git submodule.

```bash
 git submodule update --remote --merge
```
