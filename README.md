# DO Items, Artifacts & Cards - Resource Pack (Minecraft Java 26.3)

Namespace: `do`. Each item uses the `item_model` component, so any base item can wear any model.

## Server setup (server.properties)

1. The zip is hosted in this repo; the link below is already the direct download.
2. In server.properties:

```
resource-pack=https://raw.githubusercontent.com/mintisthe-maker/do_items_pack/main/DO_Items_Pack.zip
resource-pack-sha1=f1139fde57ccdd59e0063efa29543f569c57e039
require-resource-pack=true
```

3. Restart the server. If you edit the pack later, re-upload and update the sha1.

## Give commands - items

Base item is paper here; swap for anything (e.g. a sword so the blade actually deals damage).

```
give @p minecraft:paper[item_model="do:amulet",item_name="Amulet"]
give @p minecraft:paper[item_model="do:armor",item_name="Armor"]
give @p minecraft:paper[item_model="do:blade",item_name="Blade"]
give @p minecraft:paper[item_model="do:bow",item_name="Bow"]
give @p minecraft:paper[item_model="do:cloak",item_name="Cloak"]
give @p minecraft:paper[item_model="do:coin",item_name="Coin"]
give @p minecraft:paper[item_model="do:crown",item_name="Crown"]
give @p minecraft:paper[item_model="do:deathloop",item_name="Deathloop"]
give @p minecraft:paper[item_model="do:ember",item_name="Ember"]
give @p minecraft:paper[item_model="do:goldeneye",item_name="GoldenEye"]
give @p minecraft:paper[item_model="do:hammer",item_name="Hammer"]
give @p minecraft:paper[item_model="do:helm",item_name="Helm"]
give @p minecraft:paper[item_model="do:key",item_name="Key"]
give @p minecraft:paper[item_model="do:mcburger",item_name="McBurger"]
give @p minecraft:paper[item_model="do:potion",item_name="Potion"]
give @p minecraft:paper[item_model="do:ring",item_name="Ring"]
give @p minecraft:paper[item_model="do:robe",item_name="Robe"]
give @p minecraft:paper[item_model="do:scroll",item_name="Scroll"]
give @p minecraft:paper[item_model="do:shard",item_name="Shard"]
give @p minecraft:paper[item_model="do:shield",item_name="Shield"]
give @p minecraft:paper[item_model="do:staff",item_name="Staff"]
give @p minecraft:paper[item_model="do:staff_of_kelpish_lag",item_name="Staff of Kelpish Lag"]
give @p minecraft:paper[item_model="do:victorytome",item_name="VictoryTome"]
give @p minecraft:paper[item_model="do:wizardhat",item_name="WizardHat"]
give @p minecraft:paper[item_model="do:damoosesblastingcaps",item_name="DaMoosesBlastingCaps"]
give @p minecraft:paper[item_model="do:tygrrnade",item_name="Tygrrnade"]
```

## Give commands - cards

Cards use iron ingots as the base item.

```
give @p minecraft:iron_ingot[item_model="do:cards/adrenaline_rush",item_name="Adrenaline Rush"]
give @p minecraft:iron_ingot[item_model="do:cards/beast_sense",item_name="Beast Sense"]
give @p minecraft:iron_ingot[item_model="do:cards/bounding_strides",item_name="Bounding Strides"]
give @p minecraft:iron_ingot[item_model="do:cards/brilliance",item_name="Brilliance"]
give @p minecraft:iron_ingot[item_model="do:cards/dark_depths",item_name="Dark Depths"]
give @p minecraft:iron_ingot[item_model="do:cards/dungeon_lackey",item_name="Dungeon Lackey"]
give @p minecraft:iron_ingot[item_model="do:cards/dungeon_repairs",item_name="Dungeon Repairs"]
give @p minecraft:iron_ingot[item_model="do:cards/eerie_silence",item_name="Eerie Silence"]
give @p minecraft:iron_ingot[item_model="do:cards/ember_focus",item_name="Ember Focus"]
give @p minecraft:iron_ingot[item_model="do:cards/ember_seeker",item_name="Ember Seeker"]
give @p minecraft:iron_ingot[item_model="do:cards/evasion",item_name="Evasion"]
give @p minecraft:iron_ingot[item_model="do:cards/eyes_on_the_prize",item_name="Eyes On The Prize"]
give @p minecraft:iron_ingot[item_model="do:cards/fuzzy_bunny_slippers",item_name="Fuzzy Bunny Slippers"]
give @p minecraft:iron_ingot[item_model="do:cards/hazerdus_embers",item_name="Hazerdus Embers"]
give @p minecraft:iron_ingot[item_model="do:cards/loot_and_scoot",item_name="Loot And Scoot"]
give @p minecraft:iron_ingot[item_model="do:cards/moment_of_clarity",item_name="Moment Of Clarity"]
give @p minecraft:iron_ingot[item_model="do:cards/nimble_looting",item_name="Nimble Looting"]
give @p minecraft:iron_ingot[item_model="do:cards/pay_to_win",item_name="Pay To Win"]
give @p minecraft:iron_ingot[item_model="do:cards/pirate_booty",item_name="Pirate Booty"]
give @p minecraft:iron_ingot[item_model="do:cards/pork_chop_power",item_name="Pork Chop Power"]
give @p minecraft:iron_ingot[item_model="do:cards/quickstep",item_name="Quickstep"]
give @p minecraft:iron_ingot[item_model="do:cards/reckless_charge",item_name="Reckless Charge"]
give @p minecraft:iron_ingot[item_model="do:cards/second_wind",item_name="Second Wind"]
give @p minecraft:iron_ingot[item_model="do:cards/silent_runner",item_name="Silent Runner"]
give @p minecraft:iron_ingot[item_model="do:cards/smash_and_grab",item_name="Smash And Grab"]
give @p minecraft:iron_ingot[item_model="do:cards/sneak",item_name="Sneak"]
give @p minecraft:iron_ingot[item_model="do:cards/sneeky_ember_step",item_name="Sneeky Ember Step"]
give @p minecraft:iron_ingot[item_model="do:cards/speed_run",item_name="Speed Run"]
give @p minecraft:iron_ingot[item_model="do:cards/sprint",item_name="Sprint"]
give @p minecraft:iron_ingot[item_model="do:cards/stability",item_name="Stability"]
give @p minecraft:iron_ingot[item_model="do:cards/stumble",item_name="Stumble"]
give @p minecraft:iron_ingot[item_model="do:cards/suit_up",item_name="Suit Up"]
give @p minecraft:iron_ingot[item_model="do:cards/swagger",item_name="Swagger"]
give @p minecraft:iron_ingot[item_model="do:cards/tactical_approach",item_name="Tactical Approach"]
give @p minecraft:iron_ingot[item_model="do:cards/tread_lightly",item_name="Tread Lightly"]
give @p minecraft:iron_ingot[item_model="do:cards/treasure_hunter",item_name="Treasure Hunter"]
```

## Notes

- pack.mcmeta declares min_format 84 / max_format 200, so it loads on 26.1 and later without an 'incompatible' warning.
- Tygrrnade is a 3D model (body/head/handle); everything else is a flat sprite like vanilla items.
- Staff and Staff of Kelpish Lag had the same texture name in Blockbench but different art; they're kept as separate textures.
- Cards live under `do:cards/...` (models in `models/item/cards`, textures in `textures/item/cards`), merged in from the separate DO Cards pack and moved from the `custom` namespace to `do`.
