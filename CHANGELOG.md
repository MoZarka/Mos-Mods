# [4.0.0-beta4] - 2021-12-02

Note: Antique Atlas' are now colorized! New textured for modded biomes now too. The origins collection mods have been replaced with a custom datapack (the same origins, but bug-fixed/enhanced/nerfed). Upon death, you can update your origin once after updating. Backpacks are being changed into a different mod. Backpacks are going to be removed, so please empty all of their contents before updating. Elytra will also no longer be able to be equipped as a curio.

### ADDED:
- 'AI Improvements'
- 'Buried Knight Origin'
- 'Chunky Pregenerator'
- 'CobbleGenRandomizer'
- 'Demagnetize'
- 'DrawerFPS'
- 'Drippy Loading Screen'
- 'Enhanced Celestials'
    - Crash fixed, now re-added
- 'FancyMenu'
- 'Konkrete'
- 'ModernWorldCreation'
- 'More Mounted Storages'
- 'More Overlays Updated'
    - JEI Item Searching implemented! (And pressing F7 and F9 shows mobspawn/chunk overlays)
- 'RandomPatches'
    - Fixes multiple server-side issues
- 'Stylish Effects'
    - Replaced InventoryHUD
- 'Visual Workbench'
- 'AntiqueAtlasEMS' resourcepack
- 'LootrChestRetexture for Create!' - resourcepack
- New fancy Knightmetal textures
- New application icon & name
- Custom menu and loading screens
- Smooth Basalt, rarely generating in Deepslate blocks

### UPDATED:
- 'Curios API'
- 'CodeChicken Lib'
- 'Controlling'
- 'Easy Discord Rich Presence'
- 'FastWorkbench'
- 'GeckoLib'
- 'Architectury API'
- 'Chunk Pregenerator'
- 'Cosmetic Armor'
- 'Create'
- 'Diet'
- 'Flywheel'
- 'Hats'
- 'iChunUtil'
- 'JustEnoughItems'
- 'Just Enough Resources'
- 'Kiwi'
- 'Kobolds!'
- 'KubeJS'
- 'Lootr'
- 'Meet Your Fight'
- 'Outvoted'
- 'Pehkui'
- 'Placebo'
- 'Polymorph'
- 'Repurposed Structures'
- 'Quark'
- 'Supplementaries'

### REMOVED:
- 'Backpacked'
- 'Backpacker'
- 'Chunk-Pregenerator'
- 'Chisels & Bits'
    - Will be re-added once several issues have been resolved
- 'Create Deco'
- 'Create Gears'
    - Will likely not update for future versions of Create
- 'Curious Elytra'
- 'Mutant Creatures'
- 'Mutant More'
- 'Darker Loading Screen'
- 'Enchant With Mob'
- 'InventoryHUD'
- 'Origins Collection 1'
- 'Origins Reservoir 2'
- 'ReAuth'
- 'Scuba Gear'
- Disabled Emblem of Monster Slayer
- Disabled Gift of the Heaven
- Disabled Iron, Exquisite, Ender, Magnetic and Dislocation rings
- Removed custom Pirat Hat from loot tables

### ORIGINS REWORK:
- Removed Minotaur Origin
- Removed Demon Origin
- Removed Shadekin Origin
- Removed Beetle Origin
- Added Inchling Origin
- Added custom-made Buried Knight origin that spawns in the twilight forest
- Water Vulnerabilty can be entirely negated by a conduit block within 20 blocks
- Origin-related items are now tagged for easy searching with JEI. The following searches will allow you to find all items correlated to their origin:
    - $piglin_all
    - $penguin
    - $moth
    - $deer_berry
- Elytrian:
    - New 'Rideable' ability
    - Can now use any armor, but can't use chestplates
    - Gift of the Winds now launches you forwards, as opposed to straight into the air. Recommended for use in the air, or during takeoff
    - New sounds and effects added to Gift of the Winds
- Blazeborn:
    - Blazeborns always spawn in a Crimson Forest
    - Blazeborns can swim through Lava
    - Hotblooded now also gives Nausea immunity, in addition to immunity to Hunger and Poison.
- Penguin:
    - No longer spawns in a tundra biome due to a nasty bug
    - Snowy & Icy biomes now give Resistance II. Warm biomes give Weakness I. Very warm biomes (including the nether) give Weakness II & Slowness II
    - Nether biomes burn you, unless Fire Protection armor is equipped
    - Can only consume seafood (but gains more out of consumption)
    - Size is half of a human
    - Increased attack speed
    - Slightly increased Snowball cooldown
    - Snowballs play the correct sound now
    - Penguins now have a much higher Oxygen storage
    - Added Aquatic Lunge ability
    - Removed Fins ability
    - Better ability bars
    - Decreased fall damage
- Crab:
    - Overhauled ability names and descriptions
    - No longer spawns in beach biome due to a nasty bug
    - Crab is now 20% smaller than a human and W I D E
    - Made Crab Walk ability toggle-able
    - Increased armor from Shell ability from 4 to 6
    - Reworked "Land Breathe" to "Crustacean Gills", an increased oxygen capacity ability.
    - Fire Protection now protects crabs from high temperature biomes
    - Reduced speed bonus from being wet
    - Halved beach biome regeneration
    - Removed Strong Arms ability
- Deer:
    - Combined the Forrest Gump ability into the Forest Native ability
    - Overhauled ability descriptions and names
    - Un-hid multiple hidden abilities
    - Increased food gained from eating berries and Deers can now consume every berry-related item
    - Immune to berry bush damage
    - Decreased fall damage negation
    - "Oh Deer God!" only activates when below 4 health now
    - Modded forests now supported
- Moth:
    - Reduced max hearts from 9 to 8
    - New 'Rideable' ability
    - Reworked eating ability. You can now just hold right-click as you would with normal food (and you can't eat enchanting tables anymore)
    - Moth now properly displays its abilities
    - Proximity buffs no longer display potion particles
    - Fibrous Diet ability is more descriptive
    - Night Vision is now toggle-able with secondary ability key
    - "Overwhelming Light" causes a progressive weakness effect
    - Now recieves damage while in water
    - Slowness applied when under rain
    - Sea lanterns no longer provide Dolphin's Grace
    - Soul Torches provide Speed I instead of Speed II
    - Removed Speed effect from Glowstone
- Piglin Brute:
    - Renamed to Lost Piglin, no longer "brute" themed
    - Total ability overhaul
    - No longer spawns in nether, spawns in overworld due to a pretty nasty bug
    - Reworked to make the player immediately progress towards a nether portal to live in the Nether
    - Fixed descriptions

### CHANGED:
- Overhauled how resources are loaded
- New textures replacing vanilla fire making them lower
- Adjusted Danny's Expansion mob spawnrates
- Potentially fixed craftable deeds being interactable by other players
- Fixed Farmers' Delight rope not being fully replaced
- Fixed Fried Egg recipes being removed
- Warpstone XP multiplier now 0.5x from 1.5x
- Fixed only Stasis and Soulbound enchantment books spawning in End Cities' chests
- Enchanted books added to End City loot table
- Soulbound enchantment can now (very rarely) be obtained from enchanting tools/armor, instead of being exclusive to books
- Fixed Soulbound enchantment voiding items on-death
- Removed Ender Rod recipe
- Added "DISABLED" warning to disabled items
- Changed string output from crushing/milling wool to 4 string per piece of wool
- Added information tab to Crystal Shards and Astral Dust
- Increased Crab spawn weight
- Added Bayou as potential spawn for Crocodiles
- Added Armor Shards to stronghold_room loot table (goblin dungeons in twilight forest should have more armor shards)
- The One Probe has been set to a toggle keybind instead of a hold
- Decreased Copper ingot rates from Drowned
- Chisel's Wool can now be used as a windmill sail
- Removed Flax seeds from loot tables
- Added unique cobble and stone generation if a cobblestone generator is built on bedrock
- More default-y default settings
- Added tags to all armors to make them more searchable ($armor)
- Changed recipe display order
- Candle recipe changes
- Removed Master and Music volume from main options menu
- Player's own particles are now hidden


# [4.0.0-beta3] - 2021-11-17

### ADDED:
- 'Babel'
- 'Better Burning'
- 'Carry On'
- 'Compote'
- 'Death Finder'
- 'Just Enough Effect Descriptions'
- 'Just Enough Piglin Bartering'
- 'Just Enough Professions'
- 'Just Enough Resources'
- 'More Minecarts and Rails'
- 'FramedBlocks'

### REMOVED:
- 'BlockCarpentry'
    - Replaced with FramedBlocks
- 'ChickenChunks'
- 'Configured'
- 'Enhanced Celestials'
    - Will be added again later once Create's ponder crash is resolved
- 'JEI Professions'

### UPDATED:
- 'Just Enough Items'
- 'Kobolds!'
- 'Kotlin For Forge'
- 'KubeJS'
- 'Repurposed Structures'
- 'Supplementaries'

### CHANGED:
- Fixed crash when pondering during a moon cycle event (removed Enhanced Celestials)
- Fixed "s" button crash (removed Configured)
- Disabled Create's config button
- Mutant Blazes spawn 75% less
- Mutant Zombies, Skeletons, and Creepers spawn 50% less
- Waystones take 1 level every 1000 blocks instead of every 500
- Optimized scripts
- Hidden items should now be hidden in multiplayer (finally)
- Disabled redundant Quark features
- Enabled Quark's Improved Tooltips
- Overhauled Create's Gabbro, Dolomite, Limestone, and Weathered Limestone generation
- Added tooltip to the Empty Antique Atlas



# [4.0.0-beta2] - 2021-11-16

Note: Removed a bunch of mods for performance enhancements. I've added Antique Atlas since it's the only good alternative to Xaero's Map at the moment. There will be a resource pack in the future for better mod compatibility and better visuals.

### ADDED:
- 'Antique Atlas'
- 'Antique Waystones'
- 'Chisel'
- 'Create Deco'
- 'Create Plus'
- 'Custom FoV'
    - If you're using an origin that gives a speed boost, this should be pretty great for you. I've disabled the speed-boost FoV
- 'TrashSlot'
- 'WorldStripper'

### REMOVED:
- 'Xaero's World Map'
- 'Xaero's Minimap'
- 'Chunk Animator'
- 'CreativeCore'
- 'ItemPhysic Lite'
- 'Sulfuric'

### UPDATED:
- 'Diet'
- 'GeckoLib'
- 'Infernal Expansion'
- 'Just Enough Items'
- 'Kobolds'
- 'Polymorph'
- 'Rhino'
- 'WindowLogging'

### CHANGED:
- Death totems no longer break on a consecutive death
- An "Empty Antique Atlas" is now given on start-up
- Fixed BetterEnd Crystalite Recipe
- Disabled all of Enigmatic Legacy's Spellstones
- Disabled the Grace of the Creator
- Disabled the Astral Breaker
- Disabled the Essence of Raging Life
- Added warning to the Ring of the Seven Curses
- Replaced gold ingot dropped from Drowned to Copper
- Overhauled Simple Storage Network's recipes to incorporate Create
- Changed a lil secret in Buried Treasure loot tables
- Heavily adjusted OreGen rates
- Changed Craftable Deeds recipes
- Potentially fixed item hiding in multiplayer
- Optimized scripts
- Retextured Palm Wood
- Retextured Baobab Wood
- Chisel's Basalt is entirely replaced as Scoria
- Added the Supplementaries guidebook to the Akashic Tome recipe & starting item
- Changed Scroll of Postmortal Recall recipe
- Added Potion of Recall to dungeon loot tables



# [4.0.0-beta1] - 2021-11-12

Note: Fixed worldgen, but at the cost of Biomes O Plenty. I'm making up for that removal with new biome mods that don't break compatibility, and adding ones that were previously incompatible. If you made a world, it will be completely incompatible with this version. Magnesium was removed, but that also means that a manual OptiFine install is required if you want high FPS :/. On the bright side, a new optional resourcepack has been added that adds in custom animations, because of OptiFines addition! This update also features a bunch of mods and changes that make everything feel more complete.

### ADDED:
- 'Abnormals Delight'
- 'Autumnity'
    - Snail slime has been customized to be a considered a slimeball
- 'Akashic Tome'
- 'Anti-ghost'
- 'Armor Toughness Bar'
- 'BetterEnd Reforked'
    - Heavily modified version
- 'Buzzier Bees'
- 'Camels'
- 'Chunk Animator'
- 'Craftable Deeds'
- 'Dragon Mounts: Legacy'
    - Dragon eggs can only rarely be found in Woodland Mansions, End cities, and Buried Treasure
- 'Enchant With Mob'
- 'Enigmatic Legacy'
    - Heavily modified version
- 'Infernal Expansion'
- 'ItemPhysic Lite'
- 'JEI Professions'
- 'Origins Collection 1'
- 'Origins Resevoir 2'
    - Removed Swede origin
- 'Pehkui'
- 'Savage Ender Dragon'
- 'Scuba Gear'
- 'Simple Shops'
- 'Smooth Boot'
- 'Spawner Bug Fix'
- 'Soulbound!'
- 'Trading Post'
- 'YUNG's Extras'
- 'Repurposed Structures',
- 'Valhesia Structures'
- 'Valhelsia Core'
- Optifine compatibility
    - Magnesium caused too many problems, which led to the addition of OptiFine
    - Not technically in the pack, but highly recommended for manual install!
- A few customized Stronghold rooms! (credits to legitchmas)
    - I can't spoil the surprise ;)

### REMOVED:
- 'Biomes O' Plenty' 
    - Compatibility mess
- 'ItemPhysic Full'
    - Unfixed bug (likely won't get fixed)
- 'CreativeCore'
    - ItemPhysic dependency
- 'Magnesium'
    - Caused awful lag spikes and stutters
    - Messed with worldgen when it shouldn't have
- 'Screenshot to Clipboard'
    - Incompatible with OptiFine
- 'Slimy Stuff'
    - Items added were too powerful
- 'The Outer End'
    - Not a very well-made mod
    - Incompatible with Savage Ender Dragon
- 'Toad Terror'
    - Buggy bossfight and Curios bug

### UPDATED:
- 'Allurement'
- 'Caelus API'
- 'CaveBiomeAPI'
- 'Champions'
- 'Cloth Config API'
- 'Curious Elytra'
- 'Farsight: Spyglasses'
- 'GeckoLib'
- 'KubeJS'
- 'OreTweaker'
- 'Supplementaries'
- 'Upgrade Aquatic'

### CHANGED:
- Adjusted biome weights
- Adjusted Create's stone generation
- Adjusted ore generation
- Adjusted cave generation
- Reduced TheOneProbe HUD size
- Enabled Atmospheric's Rainforest biome (previously overlapped with BoP)
- Removed custom recipes that used BoP items
- More KJS scripts replacing datapack tag stuff
- Removed Quark's gold bars
- Removed Comfortable Nethers' Iron Rich Basalt (overlap)
- Removed Comfortable Nethers' Ancient Netherrack
- Re-enabled the accidentally disabled Origins food restrictions
- Clef instruments should now stop spawning in mid to end-tier loot tables
- Disabled Quark replacing chests with variant chests (conflict with Lootr)
- Removed Ender Eye restriction due to BetterEnd Reforked being fixed
- Adjusted Nature's Compass recipe
- Modified Buried Treasure loot tables with some surprises :)



# [4.0.0-alpha3] - 2021-11-08

### ADDED:
- 'Block Carpentry'
- More modded items in origin tags, meaning that Origins support modded items and blocks a lot better now 

### CHANGED:
- Fixed disabled wooden recipes
- Alexs Mobs' shark teeth can be used in place of other teeth



# [4.0.0-alpha2] - 2021-11-08

### ADDED:
- 'Better Ping Display'

### REMOVED:
- 'Super Faster Minecarts'
- 'Not Enough Animations'
- 'TRansliterationLib'

### UPDATED:
- 'Just Enough Items (JEI)'



# [4.0.0-alpha1] - 2021-11-08

Note: PREVIOUS WORLDS INCOMPATIBLE, AND THE END DIMENSION IS PARTIALLY DISABLED. PLEASE WAIT FOR AN UPDATE THAT RE-INTRODUCES IT!!

- Much more polish
- New custom blocks and items (more to come)
- Totally new worldgen!
- Custom textures, and many of them!
- A LOT more customization in recipes
- So, so, so much more, and more to come!