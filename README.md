# DO Items & Artifacts - Resource Pack (Minecraft Java 26.3)

Namespace: `do`. Each item uses the `item_model` component, so any base item can wear any model.

## Server setup (server.properties)

1. The zip is hosted in this repo; the link below is already the direct download.
2. In server.properties:

```
resource-pack=https://raw.githubusercontent.com/mintisthe-maker/do_items_pack/main/DO_Items_Pack.zip
resource-pack-sha1=ca32c49369e7451d6080928d96d95a43560f53bd
require-resource-pack=true
```

3. Restart the server. If you edit the pack later, re-upload and update the sha1.

## Give commands

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

## Notes

- pack.mcmeta declares min_format 84 / max_format 200, so it loads on 26.1 and later without an 'incompatible' warning.
- Tygrrnade is a 3D model (body/head/handle); everything else is a flat sprite like vanilla items.
- Staff and Staff of Kelpish Lag had the same texture name in Blockbench but different art; they're kept as separate textures.
