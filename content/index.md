---
title: Welcome to The Tattered Spire
---

This is a campaign setting created by @Baegll and friends!

---
## [[Diveneu]]
It is a city of turmoil.

[[The Palestone Bloodline]] has had an iron grip on the council of the city for so long, but their power is waning. After years of prosperity, their recent scraping victory in [[The Stone War]] has the Crested and Crestative families eyes glistening with potential power and wealth. With so many factions vying for control, which will you ally yourself with? The city itself is not the only danger, with recent extraplanar threats displacing the local wildlife, there are plenty of reasons to die in the wilderness, whether for your own profit or a nobles whim.

You are one of many 3rd-level adventurers. You may know some familiar faces. You have seen The Board with lots of jobs available at [[The Sanron Company]] or specifically been requested with a task by some Noble who lives in town.

Adventuring is a diverse job with many races using it as a dangerous quick cash grab, their only way of making a living, or a way to pursue nobility and honor.

You might be a [[Human]], while this city is not yours, your people have always existed in [[Aurelin]] and many variations of your culture have existed in the city.

You might be a [[Dwarf]], your people built this city, and many nobles and commoners thrive in the city in all aspects of trade, industry, and politics.

You might be an [[Elf]], while a recent addition to the city, your people have known these mountains long before civilaztion took roots here.

You could be a [[Dragonborn]], created by the terrible [[Furzhold M Groust]] your kind are outlawed in many cities, however not this one. This does not stop the bounty hunters from attempting to claim your head as the local city [[]] has a hefty gold reward on the heads of your kind.

You might be a [[Gnome]], a people determined to create the future, and attempt to control its direction.

You might be a [[Halfling]], often a friendly race, your people are welcome everywhere.

You might be an [[Orc]], a new addition to the city, your people are warily eyed at first for your strong tusks and large stature.

You could be a [[Tiefling]], your people are uncommon, but often highly specialized in a vital trade or craft for where you live.

You could be an [[Aasimar]], often mistaken for whichever race you look most like, your uncommon lineage ties you directly to [[The Panath]].

You might be a [[Goliath]], your people ruled these mountains for many years before [[The Palestone Bloodline]] became rulers here. Or you might be from a non-local tribe adventuring away from home for a multitude of reasons.

---

## Contribution Guide

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
