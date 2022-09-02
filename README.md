ACCRETION
=========
**NOTE: If you are updating the modpack, you will need to delete your profile in your mod manager and download the modpack again. This is a limitation of the way Thunderstore handles modpacks and there is nothing I can do about it.**

**Join the community** over at itch.io for discussion, bug reports, or feedback! https://pollychan.itch.io/accretion-modpack/community

***ACCRETION*** is an expansion and overhaul modpack for Risk of Rain 2. The aim of the modpack is to add highly polished new content to the game, while improving the vanilla experience to a significant degree. Careful attention has been paid to the balance between individual mods and to providing an out of the box high quality experience for all players.

This modpack is intended to be played from either an existing save or a brand new save. New players to the game should ideally have an experience that is at least as stable as vanilla, while still being able to unlock everything they would normally be able to unlock. Veteran players will find a significant amount of new content and changes to play around with.

Currently adds:
- 5 Survivors.
- 75+ Items.
- 22 Artifacts.
- 3 Enemies.
- 2 Bosses.
- 45+ Skins.
- 6 Difficulties.
- Offline Prismatic Trials.

Many of the changes come from the excellent RiskyMod by Moffein. The changes have been mirrored in the full changelog below, but you are encouraged to check out the mod on the Thunderstore, which also links to a full changelog that goes into further detail about the design philosophy of the overhaul.

<https://thunderstore.io/package/Risky_Lives/RiskyMod/>

Additionally, many other tweaks are not listed for one reason or another. Be sure to check out the full list of mods and their individual pages for more information. A huge thank you to all of the mod creators who have contributed to making this expansion what it is.

DISABLING INDIVIDUAL MODS
------
To disable individual mods, first disable Accretion (the main Modpack). You should then be able to disable any individual mods as you wish.

CHANGELIST
----------

Due to the extensive number of changes, the full changelog is kept in a separate document.

[Full Changelog](https://docs.google.com/document/d/1GXYCsytmH1DupGy7YKiLaJOb5AGFLu3Hhd8o8UL8JU4/edit?usp=sharing)

CONTACT
----
If you would like to report bugs, make suggestions, or have any other feedback, please let me know at the itch.io community. Although I have tested the pack extensively myself, there are likely to be many bugs and balancing issues I overlooked. I will attempt to fix any bugs I can as soon as possible. I don’t play multiplayer a whole lot, so I have some difficulty testing multiplayer. If you encounter any bugs or oddities, please let me know.

You can post on the [itch.io community](https://pollychan.itch.io/accretion-modpack/community) if you have any feedback or bug reports, or find others to play with. There is also a [github](https://github.com/PollyEdaline/Accretion-Modpack) if you would prefer to post issues there.

I am also interested in working with an experienced mod creator on adding some additional content and tweaks to the pack. If you are willing to work with me, please let me know.

CHANGELOG
----
**4.0.0**
- **Generate a new profile** for this release.
- Updated all applicable mods.
- **NEW SURVIVOR**: Pathfinder. The Pathfinder is an interplanetary hunter who fights alongside his falcon, Squall. An already highly polished survivor from Bog. Still in early access, so needs balance testing. Currently, I have implemented the following changes already.
  - Squall: Battery recharge rate while in Follow Mode increased from 1% up to 2%.
  - Squall: Battery drain rate while in Attack Mode increased from 8% up to 10%.
    - These changes are focused on allowing you to utilize Squall's Attack Mode more frequently in the early game, as well as scaling back a bit of its late game power.
- **PALADIN**:
  - Cruel Sun Rework
  - No longer placed at an aim point. Now is held consistently above you.
  - Ally damage and burn stacks reduced heavily, allowing for controlled use against enemies.
  - Can be canceled by pressing R, Utilities, or Sprinting.
  - Scepter: Pride Flare: Become aimed and thrown to detonate for 9001% to all characters.
- **ENFORCER**:
  - Riot Shotgun
    - Damage increased to 75%, up from 60%.
    - Pellets reduced to 6, down from 8.
    - Range increased to 64, up from 48.
  - Tear Gas
    - Stun radius increased to 8m, up from 6m.
    - Uptime reduced to 12s, down from 18s.
    - Cooldown reduced to 16s, down from 24s.
- **TINKER'S SATCHEL ITEMS**:
  - **NEW:** Fudge Dice (Uncommon) - Every 20 seconds, automatically succeed on a random roll.
  - **NEW:** Celestial Gambit (Lunar) - Gain an extra item from the teleporter... BUT the teleporter zone weakens you (50% reduced healing per stack, no jumping).
  - **NEW:** Lemurian's Claw (Lunar Equipment) - Give a target item drop to ALL characters. Enemies receive multiple, 1 per ally.
  - **NEW:** Scavenger's Rucksack (Boss) - Hold one extra equipment. Stand still to cycle through equipment slots. Rarely replaces Scavenger backpack drops.
  - **Mostly-Tame Mimic** (the following is a direct paste from ThinkInvisible's patch notes!)
    - *Minor rework to Mostly-Tame Mimic. MTM was always meant to provide unpredictable power boosts, but the execution was unclear and the item's moment-to-moment effects were sometimes hard to notice. The following changes are meant to focus on this role more strongly; providing a much spikier item distribution with more clearly defined points of change over time, as well as giving the player more time to identify and take advantage of boosted items.*
      - Now scrambles all-at-once instead of gradually over time (15% --> 100% chance per mimic), using a much longer interval (3s --> 15s).
      - Now only selects a small fraction of all available items per tier (100% --> 20% of item types per tier, rounded up).
      - No longer redistributes mimics as soon as the last stack of a mimicked item is lost, in order to avoid abuse of by-tier selection alongside e.g. a conveniently-placed scrapper/printer or an item drop mod. Will instead remove those mimics and wait for the next scramble.*
  - **Bulwark Drone** (another copy from the patch notes!)
    - Was severely overperforming in an attempt to justify its high cost and lack of attacks, especially when multiple were obtained. Its taunt mechanic was also unintentionally inconsistent.
      - Now spawns with one stack of Razorwire. Those shields are pointy!
      - Reduced taunt chance per enemy (50% --> 25%).
      - Now selects a consistent fraction of valid targets to taunt, instead of rolling a chance for each target.
      - Reduced base stats (health 400 --> 275, shield 60 --> 25, health regen 5 --> 2, armor 20 --> 0, move speed 20 --> 15).
      - Increased hitbox size.
      - Reduced base cost ($80 --> $60).
- **NEW ARTIFACTS**
-- *Artifact of Reconfiguration*: (by ThinkInvisible) Start with 3 Equipment slots. Equipment is more common, and is consumed instead of going on cooldown.
- Added *StageAesthetic* by HIFU, adding randomly-selected additional color schemes to stages.
- Added *FasterPickupText* by DestroyedClone, changing the duration of pickup notifications.
-- Changed values:
- Added *Aetherium* by KomradeSpectre (and the rest of the contributors!). Adds a great deal of content including items, artifacts, and even a new Elite type.
- Removed *Melting Pot* by Shasocais. Never received the polish I hoped it would, hopefully will be able to add back later!

- Added a new skin for Paladin.

**3.0.2**
- Added a [community](https://pollychan.itch.io/accretion-modpack/community) on itch.io where people can post feedback and report bugs.