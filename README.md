If you've somehow stumbled into this, you should probably check out [the original implementation](https://github.com/Seldom-SE/archipelago_terraria_client) as well

My plan here is to add a good bit more to the Terraria implementation to make it a lot more expansive. Here's everything I want to do at some point (key word: want):
- Substantial logic reworking
  - A lot more needs to be added to account for everything else I want to do. I'll very much need to figure out a way to *not* do this manually; would need to look into making a script that makes a DSV or JSON from the vanilla and Calamity item recipes.
  - Enemies will be pain
- Townsanity
  - Shuffling of town NPC flags. Also includes Princess and Wall of Flesh as goals.
- Misc Flag Shuffling
  - Stuff like breaking Altars, Advanced Combat Techniques, and other things not dependent on boss flags.
- Bestiarysanity
  - Kill enemies to send checks, receive the item to be able to get loot from them (and probably also a few bonus items corresponding to the loot you would've got)
  - I'm pretty sure someone else is working on this?
  - Most enemies' rewards are filler, look into more specifics.
- Boostersanity
  - Shuffles things like Life Crystals and other player-improving items.
- Researchsanity
  - Journey-exclusive - research check forms of items to send out a check, received items are instantly unlocked in research.
  - All items created from the world or in an NPC's shop must be check items, at least until the item is both sent and received.
  - Most items are filler. Non-filler items are only equipment (weapons, tools, armor, accessories, mounts, hooks) or items used to craft equipment (Souls, etc.). Filler items are basically everything else.
  - Definitely will break with Upgraded Research lol
 
First to-do is learning how to mod this game, though. That'll happen soon™

## License

Archipelago Terraria Client is licensed under MIT. The Archipelago logo, by Krista Corkos and
Chistopher Wilson, is licensed under CC BY-NC 4.0. The icon and collection button image used by this
mod are modified versions of the Archipelago logo, made to fit Terraria's style.
