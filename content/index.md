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
set up quartz prerequisites:
Node v20 and npm v9.3.1

run `npm i`


### Render your changes locally!
```
npx quartz build --serve
```
This will start a local web server to run the vault from your computer. Open a browser and visit `http://localhost:8080/` to view it.

### Commit your changes!
If you've set up your github account properly and created an ssh key, you should be able to publish to your fork of the site, and then submit a pull request to the main notes!

To do so, you'll run a sync against your fork with npx quartz sync
