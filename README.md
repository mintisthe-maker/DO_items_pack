# DO Items, Artifacts & Cards - Resource Pack (Minecraft Java 26.3)

Namespace: `do`. Each item uses the `item_model` component, so any base item can wear any model.

## Server setup (server.properties)

1. The zip is hosted in this repo; the link below is already the direct download.
2. In server.properties:

```
resource-pack=https://raw.githubusercontent.com/mintisthe-maker/do_items_pack/main/DO_Items_Pack.zip
resource-pack-sha1=95f1bfd2b2bdaa4327ef28f74aaaa38b3f692461
require-resource-pack=true
```

3. Restart the server. If you edit the pack later, re-upload and update the sha1.

## Give commands - items

Base item is iron nugget here; swap for anything (e.g. a sword so the blade actually deals damage).

```
give @p minecraft:iron_nugget[item_model="do:amulet",item_name="Amulet"]
give @p minecraft:iron_nugget[item_model="do:armor",item_name="Armor"]
give @p minecraft:iron_nugget[item_model="do:blade",item_name="Blade"]
give @p minecraft:iron_nugget[item_model="do:bow",item_name="Bow"]
give @p minecraft:iron_nugget[item_model="do:cloak",item_name="Cloak"]
give @p minecraft:iron_nugget[item_model="do:coin",item_name="Coin"]
give @p minecraft:iron_nugget[item_model="do:crown",item_name="Crown"]
give @p minecraft:iron_nugget[item_model="do:deathloop",item_name="Deathloop"]
give @p minecraft:iron_nugget[item_model="do:ember",item_name="Ember"]
give @p minecraft:iron_nugget[item_model="do:goldeneye",item_name="GoldenEye"]
give @p minecraft:iron_nugget[item_model="do:hammer",item_name="Hammer"]
give @p minecraft:iron_nugget[item_model="do:helm",item_name="Helm"]
give @p minecraft:iron_nugget[item_model="do:key",item_name="Key"]
give @p minecraft:iron_nugget[item_model="do:mcburger",item_name="McBurger"]
give @p minecraft:iron_nugget[item_model="do:potion",item_name="Potion"]
give @p minecraft:iron_nugget[item_model="do:ring",item_name="Ring"]
give @p minecraft:iron_nugget[item_model="do:robe",item_name="Robe"]
give @p minecraft:iron_nugget[item_model="do:scroll",item_name="Scroll"]
give @p minecraft:iron_nugget[item_model="do:shard",item_name="Shard"]
give @p minecraft:iron_nugget[item_model="do:shield",item_name="Shield"]
give @p minecraft:iron_nugget[item_model="do:staff",item_name="Staff"]
give @p minecraft:iron_nugget[item_model="do:staff_of_kelpish_lag",item_name="Staff of Kelpish Lag"]
give @p minecraft:iron_nugget[item_model="do:victorytome",item_name="VictoryTome"]
give @p minecraft:iron_nugget[item_model="do:wizardhat",item_name="WizardHat"]
give @p minecraft:iron_nugget[item_model="do:damoosesblastingcaps",item_name="DaMoosesBlastingCaps"]
give @p minecraft:iron_nugget[item_model="do:tygrrnade",item_name="Tygrrnade"]
give @p minecraft:iron_nugget[item_model="do:3d_glasses",item_name="3D Glasses"]
give @p minecraft:iron_nugget[item_model="do:sushi_s_darling_ribbon_wand",item_name="Sushi's Darling Ribbon Wand"]
give @p minecraft:iron_nugget[item_model="do:golden_vinyl_of_truth",item_name="Golden Vinyl of Truth"]
give @p minecraft:iron_nugget[item_model="do:the_enthusiast_s_refusal",item_name="The Enthusiast's Refusal"]
give @p minecraft:iron_nugget[item_model="do:windmill",item_name="Windmill"]
give @p minecraft:iron_nugget[item_model="do:cadens_ring",item_name="Caden's Ring of the Helping Hand"]
give @p minecraft:iron_nugget[item_model="do:saettas_shroud_of_helping",item_name="Saetta's Shroud of Helping"]
give @p minecraft:iron_nugget[item_model="do:mintis_headband",item_name="The Mintis's Headband"]
give @p minecraft:iron_nugget[item_model="do:lucians_stained_glass_carrot",item_name="Lucian's Stained-Glass Carrot"]
```

## Wearable 3D Glasses

The model has a head position, so the glasses show over the eyes when worn. The `equippable={slot:"head"}` part puts them in the helmet slot.

Iron nugget base (can't be placed as a block, recommended):
```
give @p minecraft:iron_nugget[item_model="do:3d_glasses",item_name="3D Glasses",equippable={slot:"head"}]
```

Carved pumpkin base (the pumpkin trick). Overriding `equippable` removes the orange pumpkin blur. Note: right-clicking a block with it places a normal carved pumpkin.
```
give @p minecraft:carved_pumpkin[item_model="do:3d_glasses",item_name="3D Glasses",equippable={slot:"head"}]
```

Red/blue screen tint while worn (works with either base item):
```
give @p minecraft:iron_nugget[item_model="do:3d_glasses",item_name="3D Glasses",equippable={slot:"head",camera_overlay:"do:misc/3d_glasses_overlay"}]
```

## Wearable 3D Wizard Hat

A purple 3D version of the wizard hat (brim, band, tiered cone, floppy tip; ombré from dark tip to light brim) that sits on top of the head like a hat and leaves the face clear. The original flat `do:wizardhat` sprite is unchanged.

Carved pumpkin base (the pumpkin trick). Overriding `equippable` removes the orange pumpkin blur:
```
give @p minecraft:carved_pumpkin[item_model="do:wizardhat_3d",item_name="Wizard Hat",equippable={slot:"head"}]
```

Iron nugget base (can't be placed as a block):
```
give @p minecraft:iron_nugget[item_model="do:wizardhat_3d",item_name="Wizard Hat",equippable={slot:"head"}]
```

## Wearable Headband (The Mintis)

The red headband from TheMintis skin as a 3D model: a band one skin-pixel tall that wraps the head just below the hairline, with a knot at the back and two tails hanging in a V. It sits on the head and leaves the face clear.

Iron nugget base (can't be placed as a block):
```
give @p minecraft:iron_nugget[item_model="do:mintis_headband",item_name="The Mintis's Headband",equippable={slot:"head"}]
```

Carved pumpkin base (the pumpkin trick). Overriding `equippable` removes the orange pumpkin blur:
```
give @p minecraft:carved_pumpkin[item_model="do:mintis_headband",item_name="The Mintis's Headband",equippable={slot:"head"}]
```

## Give commands - cards

Cards use iron nuggets as the base item.

```
give @p minecraft:iron_nugget[item_model="do:cards/adrenaline_rush",item_name="Adrenaline Rush"]
give @p minecraft:iron_nugget[item_model="do:cards/beast_sense",item_name="Beast Sense"]
give @p minecraft:iron_nugget[item_model="do:cards/bounding_strides",item_name="Bounding Strides"]
give @p minecraft:iron_nugget[item_model="do:cards/brilliance",item_name="Brilliance"]
give @p minecraft:iron_nugget[item_model="do:cards/chill_step",item_name="Chill Step"]
give @p minecraft:iron_nugget[item_model="do:cards/cold_snap",item_name="Cold Snap"]
give @p minecraft:iron_nugget[item_model="do:cards/dark_depths",item_name="Dark Depths"]
give @p minecraft:iron_nugget[item_model="do:cards/deepfrost",item_name="Deepfrost"]
give @p minecraft:iron_nugget[item_model="do:cards/dungeon_lackey",item_name="Dungeon Lackey"]
give @p minecraft:iron_nugget[item_model="do:cards/dungeon_repairs",item_name="Dungeon Repairs"]
give @p minecraft:iron_nugget[item_model="do:cards/eerie_silence",item_name="Eerie Silence"]
give @p minecraft:iron_nugget[item_model="do:cards/ember_focus",item_name="Ember Focus"]
give @p minecraft:iron_nugget[item_model="do:cards/ember_seeker",item_name="Ember Seeker"]
give @p minecraft:iron_nugget[item_model="do:cards/evasion",item_name="Evasion"]
give @p minecraft:iron_nugget[item_model="do:cards/eyes_on_the_prize",item_name="Eyes On The Prize"]
give @p minecraft:iron_nugget[item_model="do:cards/frost_focus",item_name="Frost Focus"]
give @p minecraft:iron_nugget[item_model="do:cards/fuzzy_bunny_slippers",item_name="Fuzzy Bunny Slippers"]
give @p minecraft:iron_nugget[item_model="do:cards/hazerdus_embers",item_name="Hazerdus Embers"]
give @p minecraft:iron_nugget[item_model="do:cards/loot_and_scoot",item_name="Loot And Scoot"]
give @p minecraft:iron_nugget[item_model="do:cards/moment_of_clarity",item_name="Moment Of Clarity"]
give @p minecraft:iron_nugget[item_model="do:cards/nimble_looting",item_name="Nimble Looting"]
give @p minecraft:iron_nugget[item_model="do:cards/pay_to_win",item_name="Pay To Win"]
give @p minecraft:iron_nugget[item_model="do:cards/pirate_booty",item_name="Pirate Booty"]
give @p minecraft:iron_nugget[item_model="do:cards/pork_chop_power",item_name="Pork Chop Power"]
give @p minecraft:iron_nugget[item_model="do:cards/quickstep",item_name="Quickstep"]
give @p minecraft:iron_nugget[item_model="do:cards/reckless_charge",item_name="Reckless Charge"]
give @p minecraft:iron_nugget[item_model="do:cards/second_wind",item_name="Second Wind"]
give @p minecraft:iron_nugget[item_model="do:cards/silent_runner",item_name="Silent Runner"]
give @p minecraft:iron_nugget[item_model="do:cards/smash_and_grab",item_name="Smash And Grab"]
give @p minecraft:iron_nugget[item_model="do:cards/sneak",item_name="Sneak"]
give @p minecraft:iron_nugget[item_model="do:cards/sneeky_ember_step",item_name="Sneeky Ember Step"]
give @p minecraft:iron_nugget[item_model="do:cards/speed_run",item_name="Speed Run"]
give @p minecraft:iron_nugget[item_model="do:cards/sprint",item_name="Sprint"]
give @p minecraft:iron_nugget[item_model="do:cards/stability",item_name="Stability"]
give @p minecraft:iron_nugget[item_model="do:cards/stumble",item_name="Stumble"]
give @p minecraft:iron_nugget[item_model="do:cards/suit_up",item_name="Suit Up"]
give @p minecraft:iron_nugget[item_model="do:cards/swagger",item_name="Swagger"]
give @p minecraft:iron_nugget[item_model="do:cards/tactical_approach",item_name="Tactical Approach"]
give @p minecraft:iron_nugget[item_model="do:cards/tread_lightly",item_name="Tread Lightly"]
give @p minecraft:iron_nugget[item_model="do:cards/treasure_hunter",item_name="Treasure Hunter"]
```

## Notes

- pack.mcmeta declares min_format 84 / max_format 200, so it loads on 26.1 and later without an 'incompatible' warning.
- Tygrrnade is a 3D model (body/head/handle); everything else is a flat sprite like vanilla items.
- Staff and Staff of Kelpish Lag had the same texture name in Blockbench but different art; they're kept as separate textures.
- Cards live under `do:cards/...` (models in `models/item/cards`, textures in `textures/item/cards`), merged in from the separate DO Cards pack and moved from the `custom` namespace to `do`.
- Windmill is a 3D model (thatched tower, cap, gallery, orange/white sails), based on a photo of the Het Jonge Schaap mill at Zaanse Schans.
- Caden's Ring of the Helping Hand (`do:cadens_ring`) is the Ring sprite with a blue stone instead of red; the plain `do:ring` stays red.
- Saetta's Shroud of Helping (`do:saettas_shroud_of_helping`) is the Robe sprite recolored pink with white trim and a small heart on the chest; the plain `do:robe` keeps its original colors.
- Lucian's Stained-Glass Carrot (`do:lucians_stained_glass_carrot`) is a flat 16x16 sprite: a carrot of orange glass panes and green glass leaves set in a stone gothic window arch with blue/purple panes; Blockbench project is DO_LuciansStainedGlassCarrot.bbmodel.
- The Mintis's Headband (`do:mintis_headband`) is a 3D model with a 16x16 texture taken from the band pixels of TheMintis skin; Blockbench project is DO_MintisHeadband.bbmodel.
- Wizard Hat 3D (`do:wizardhat_3d`) is a 3D model with a 32x32 texture; Blockbench project is DO_WizardHat_3D.bbmodel.
- 3D Glasses is a 3D model (frame, see-through red/blue lenses, temples). See "Wearable 3D Glasses" above. Shape based on "3D Glasses" by James.Pham (https://sketchfab.com/3d-models/3d-glasses-3088cc62775140e7b567b597b5bd378e), CC-BY-4.0.
