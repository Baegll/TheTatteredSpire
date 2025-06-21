---
tags:
  - mechanics
---
A more stable version of Exploding Dice
> credit to [u/choco_pi on r/RPGdesign](https://www.reddit.com/r/RPGdesign/comments/ne975k/cascading_dice_a_more_stable_version_of_exploding/)

"Exploding dice" refers to rolling a particular value on a die (generally the highest--like 6 on a d6) and rolling it again, adding the value to the new roll. Under most uses of this mechanic, the die can potentially explode again, repeating to no limit.

Exploding dice are so intrinsically fun (and popular!) that I'm not going to spend any time elaborating on their merits. Suffice to say that they do a great job at "keeping the high moments high" and provide a slow-motion freeze at the game's most intense moments, full of anticipation.
# Commonly Cited Issues with Exploding Dice

- **Unbounded rolls have no ceiling** and can be difficult for the GM to work around. (Assuming resolution isn't entirely binary, which would defeat the point!) A lucky enough mook might be able to one-shot a player. While it's usually correct GM behavior to only ask for a roll if success is possible, exploding dice imposes that all rolls _also_ allow for super-mega-quadruple success. (Or as many as the system supports) Keeping this in mind can make simple moment-to-moment GM calls harder to balance.

- **Because explosions are more likely on smaller dice, they compress the difference between dice.** A normal 1d6 rolls an average of 3.50, 40% more than the average 1d4. (2.50) But an exploding 1d6 rolls an average of 4.20, only 26% more than an exploding 1d4. (3.33) This pattern extends to all die sizes and can be a stumbling block for systems like Savage that rely a lot on dice distinction.

- For the same reason, **certain target numbers are not monotonic across dice size--you're more likely to hit an 8 with 1d6 than 1d8!** While these cases only occur in 1-2% rolls and only on the affected target numbers (evens), the fact that a higher stat or "bonus" to your roll could actively _hurt_ you is just really funky. Savage unfortunately has 8--one of the targets most affected by this--as one of its most common/important targets.

- **Problematic scaling with other dice-rolling mechanics** limits their compatibility with exploding dice. For example, a bonus that lets players reroll all 1s would normally be pretty benign. But applied to exploding dice it would exacerbate the previous problems. Just to emphasize the example: If you could reroll 1s and 2s, an exploding d4 rolls higher averages than an exploding d6. And if could reroll 1s, 2s, and 3s an exploding d4 rolls infinity!

- Excessive exploding dice can **slow the game down**. A player excitedly rerolling their big crit isn't "slow." But the resolution time for 15 dogs attacking the party for 1d4 each--getting extended _33%_ by rerolls--is. (In a system like Savage, 15 extras could actually have been a reasonable scenario, but dice explosions push back a bit.)

- **Players can forget how many dice they have (re)rolled**. This is a tertiary issue that rarely comes up, but worth mentioning.

Some of the mathematical issues can be hacked out by subtracting one from exploded dice, such that an exploding d6 is adding 0-5 rather than 1-6. This does satisfying _those_ issues a bit, but feels weird+slow to introduce discreptancies between the numbers you are adding and the numbers you are seeing on the dice. It's never _hard_ to do this, but it's awkward; I've never seen players like this.
# Introducing Cascading Dice

> When you roll the biggest number on a die, also roll _**the next-smallest die**_ and add that to your roll.
> 
> This can keep going all the way down to a d4. Rolling 4 on a d4 has nowhere left to go, but good job on your massive roll!

This addresses every single one of the listed issues.

- **Ceilings are still super high, but not infinite**. A cascading d12 can roll a 40--over 3 times its base max. But a d4 can only roll a 4! Even medium dice can have huge multi-rolls that get people excited, but tiny attacks no longer have a risk of one-shoting. As GM, this grants a lot more freedom.

- **Dice average improves by roughly 1.00 per size, just like normal dice: [3.92/4.99/6.00/7.00]** None of this weird regressive-curve stuff. The one exception is that d4s, which are still the usual 2.50 given that they do not cascade at all. (In other words, the difference between d4 and other dice is _bigger_ than average here.)

- **Non-monotonic behaviors are eliminated or cut in half**. A cascading d6 hits 8 the same amount as a cascading d8 (12.50%), no longer more. d8/d10 still have a non-monotonic advantage at hitting 10/12 respectively, but this occurance is reduced to a mere 0.4% of rolls.

- **Compatible with other dice rolling alterations**. Stuff like "reroll 1s" is perfectly reasonable now. Bonuses that enable cascading on additional numbers tend to also be safe, and reasonable to balance.

- **Capped rerolls speed the game up**. We no longer have to worry about those 15 dogs rerolling their d4s. Even if they are rolling d6s, that's still a meaningful aggregate reduction in rerolling.

- **Players can't lose track in the middle of rerolling**, since each "stage" is unique. They even still have their previous die/dice sitting on the table, highest side face up, waiting to be added.
#### Table: Dice Values

| Dice Size |     |
| --------- | --- |
| d4        |     |
| d6        |     |
| d8        |     |
| D10       |     |
| D12       |     |
| D20       |     |
| D100      |     |
