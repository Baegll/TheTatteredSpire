---
title: Welcome to The Tattered Spire
---

This is a campaign setting created by @Baegll and friends!

The most likely starting location to read about the world would most likely be the central city [[Diveneu]] or [[The Tattered Spire]]

If youre interested in adding your notes to the world or adding your character sheet to the PCs folder by filling out your own [[Player Character Info Template]] you can learn how I'm using Quartz to render this [Obsidian](https://obsidian.md) vault by checking out the documentation at [Quartz](https://quartz.jzhao.xyz/), or following the guide below.

### Set up Github
create a github account.
create a ssh key
git check out [The Tattered Spire repository](https://github.com/Baegll/TheTatteredSpire)
ensure your remote is set correctly by running:

```
git remote add upstream https://github.com/jackyzha0/quartz.git
```

and

```
git remote set-url origin git@github.com:Baegll/TheTatteredSpire.git
```

set up quartz prerequisites, the docs are at: https://quartz.jzhao.xyz/

Specifically, you'll need to install Node v20 and npm v9.3.1

then run `npm i` to set up your package-lock, which lets you build


### Render your changes locally!
Quarts has an explanation here: https://quartz.jzhao.xyz/build

```
npx quartz build --serve
```

This will start a local web server to run the vault from your computer. Open a browser and visit `http://localhost:8080/` to view it.

### Commit your changes!
So, Quartz explanation is here: https://quartz.jzhao.xyz/setting-up-your-GitHub-repository

However, since we have a single repository and youre not creating a new quartz vault, you'll be creating a fork of the main repo. Then you should be able to pull down your fork, make changes, `npx quartz sync` with your fork, and then commit a Pull Request (PR) to bring your changes from your fork into the main 'v4' repo!
