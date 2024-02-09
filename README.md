![VasaCraft](banner.png)

## Table of Contents

- [About the Modpack](#about-the-modpack)
- [Requirements](#requirements)
  - [Minimum](#minimum)
  - [Recommended](#recommended)
- [Installation](#installation)
  - [Java](#java)
  - [CurseForge App](#curseforge-app)
    - [Create a new profile](#create-a-new-profile)
    - [Import the modpack](#import-the-modpack)
    - [Set memory options](#set-memory-options)
  - [Modrinth App](#modrinth-app)
    - [Create a new profile](#create-a-new-profile-1)
    - [Import the modpack](#import-the-modpack-1)
    - [Set memory options](#set-memory-options-1)
  - [Minecraft Launcher](#minecraft-launcher)
    - [Installing Forge](#installing-forge)
    - [Import the modpack](#import-the-modpack-2)
    - [Set memory options](#set-memory-options-2)
- [Included Resource Packs](#included-resource-packs)
- [Optional Client Mods](#optional-client-mods)
- [Modlist](#modlist)
  - [Libraries](#libraries)
  - [Client](#client)
  - [Technology](#technology)
  - [Magic](#magic)
  - [Weapons, Tools \& Armors](#weapons-tools--armors)
  - [Decoration](#decoration)
  - [Food](#food)
  - [Structures \& Generation](#structures--generation)
  - [Other](#other)

# About the Modpack

Mix of Exploration, Technology, and Magic, this Modpack was made for the **VasaCraft** server and provides experiences of all flavors.

# Requirements

## Minimum

- 4GB Memory
- 2GB Storage

## Recommended

- 6GB+ memory
  
# Installation

Download the [latest release](https://github.com/TomasTobrman/VasaCraft/releases/latest) of the modpack

## Java

Make sure to have **Java 17** installed on your system

Check your Java version by running this command in a command prompt or a terminal

```
$ java --version
```

## CurseForge App

### Create a new profile

- click `Create Custom Profile` in the top right corner
- give a name to the profile
- choose the `1.20.1` version of minecraft
- choose `Forge` as your modloader
- choose modloader version `forge-47.2.17` in the list
- create the profile

### Import the modpack

- open your created profile
- click on the three dots next to the `Play` button
- select `Open Folder` from the menu
- extract contents of the modpack archive into this folder

### Set memory options

- open your created profile
- click on the three dots nex to the `Play` button
- select `Profile Options` from the menu
- under the `Memory Settings`
    - uncheck `Use System Memory Settings`
    - set your desired amount of memory

## Modrinth App

### Create a new profile

- click the `+` _(plus)_ icon in the left panel
- give a name to the profile
- select `Forge` as your loader
- choose `1.20.1` as the game version
- click on `Show advanced`
- select `Other` under the loader version
- choose `1.20.1-47.2.17` as the version
- create the profile

### Import the modpack

- open your created profile
- click on `Folder` under the profile icon
- extract contents of the modpack archive into this folder

### Set memory options

- open your created profile
- select `Options` in the left menu
- scroll to `Java memory` section
  - check `Override` global memory settings
  - set your desired amount of memory

## Minecraft Launcher

### Installing Forge

- select `Installations` tab at the top of the launcher
- click on `New installation`
- select the version `1.20.1` and click `Create`
- click `Play` on the created installation
- close Minecraft and the Launcher after loading
- extract `forge-1.20.1-47.2.17-installer.jar` from the modpack archive
- launch `forge-1.20.1-47.2.17-installer.jar` and install it
- make sure to let the installer create a new profile
- open the Launcher and select the new profile

### Import the modpack

- select `Installations` tab at the top of the launcher
- select the created `Forge` profile
- choose a folder under `GAME DIRECTORY` where the profile will be stored
- find the folder in a file explorer
- extract contents of the modpack archive into this folder

### Set memory options

- select `Installations` tab at the top of the launcher
- select the created `Forge` profile
- click on `MORE OPTIONS`
- choose the desired amount of memory in the `-Xmx` option under `JVM ARGUMENTS`
  - example of 4GB of memory: `-Xmx4G` or `-Xmx4096M`
  - example of 8GB of memory: `-Xmx8G` or `-Xmx8192M`

# Included Resource Packs

You are free to add more resource packs, but these will always be active for everyone on the server.

- [Adventurer's Chest (Lootr)](https://www.curseforge.com/minecraft/texture-packs/adventurers-chest-lootr)
- [Lopy's Create Style Sophisticated Backpacks](https://www.curseforge.com/minecraft/texture-packs/create-sophisticated-backpacks)
- [VanillaTweaks](https://vanillatweaks.net/picker/resource-packs/)

# Optional Client Mods

The modpack archive contains an `optional` folder, from which you can move any of these mods into the `mods` folder. If you would like to install any other client mods, you are free to do so.

- [BoccHUD](https://modrinth.com/mod/bocchud)
- [Distant Horizons](https://modrinth.com/mod/distanthorizons)
- [Forgematica](https://modrinth.com/mod/forgematica)
- [Mica](https://modrinth.com/mod/mica)
- [Oculus](https://modrinth.com/mod/oculus)
- [Tweakerge](https://modrinth.com/mod/tweakerge)

# Modlist

## Libraries

- [AeroBlender](https://modrinth.com/mod/aeroblender)
- [Architectury API](https://modrinth.com/mod/architectury-api)
- [Athena](https://modrinth.com/mod/athena-ctm)
- [AzureLib](https://modrinth.com/mod/azurelib)
- [Balm](https://modrinth.com/mod/balm)
- [BlockUI](https://www.curseforge.com/minecraft/mc-mods/blockui)
- [Bookshelf](https://modrinth.com/mod/bookshelf-lib)
- [Botarium](https://modrinth.com/mod/botarium)
- [Caelus API](https://modrinth.com/mod/caelus)
- [Citadel](https://modrinth.com/mod/citadel)
- [Cloth Config API](https://modrinth.com/mod/cloth-config)
- [Collective](https://modrinth.com/mod/collective)
- [Cristel Lib](https://modrinth.com/mod/cristel-lib)
- [Domum Ornamentum](https://www.curseforge.com/minecraft/mc-mods/domum-ornamentum)
- [FerriteCore](https://modrinth.com/mod/ferrite-core)
- [FLIB](https://www.curseforge.com/minecraft/mc-mods/flib)
- [Geckolib](https://modrinth.com/mod/geckolib)
- [Konkrete](https://modrinth.com/mod/konkrete)
- [Kotlin for Forge](https://modrinth.com/mod/kotlin-for-forge)
- [libIPN](https://modrinth.com/mod/libipn)
- [Library Ferret - Forge](https://www.curseforge.com/minecraft/mc-mods/library-ferret-forge)
- [Melody](https://modrinth.com/mod/melody)
- [Moonlight Lib](https://modrinth.com/mod/moonlight)
- [Multi-Piston](https://www.curseforge.com/minecraft/mc-mods/multi-piston)
- [mutil](https://modrinth.com/mod/mutil)
- [ObsidianUI](https://modrinth.com/mod/obsidianui)
- [OctoLib](https://modrinth.com/mod/octo-lib)
- [Patchouli](https://modrinth.com/mod/patchouli)
- [Placebo](https://www.curseforge.com/minecraft/mc-mods/placebo)
- [playerAnimator](https://modrinth.com/mod/playeranimator)
- [Potacore](https://modrinth.com/mod/potacore)
- [Puzzles Lib](https://modrinth.com/mod/puzzles-lib)
- [Resourceful Config](https://modrinth.com/mod/resourceful-config)
- [Resourceful Lib](https://modrinth.com/mod/resourceful-lib)
- [Rhino](https://modrinth.com/mod/rhino)
- [Searchables](https://modrinth.com/mod/searchables)
- [ShetiPhianCore](https://modrinth.com/mod/shetiphiancore)
- [Sophisticated Core](https://www.curseforge.com/minecraft/mc-mods/sophisticated-core)
- [Structure Gel API](https://modrinth.com/mod/structure-gel-api)
- [Structurize](https://www.curseforge.com/minecraft/mc-mods/structurize)
- [TerraBlender](https://modrinth.com/mod/terrablender)
- [Titanium](https://modrinth.com/mod/titanium)
- [YUNG's API](https://modrinth.com/mod/yungs-api)

## Client

- [AppleSkin](https://modrinth.com/mod/appleskin)
- [[EMF] Entity Model Features](https://modrinth.com/mod/entity-model-features)
- [[ETF] Entity Texture Features](https://modrinth.com/mod/entitytexturefeatures)
- [3D Skin Layers](https://modrinth.com/mod/3dskinlayers)
- [AnimaticaReforged](https://modrinth.com/mod/animaticareforged)
- [Better Advancements](https://modrinth.com/mod/better-advancements)
- [BetterF3](https://modrinth.com/mod/betterf3)
- [Builtin Servers](https://modrinth.com/mod/builtin-servers)
- [Controlling](https://modrinth.com/mod/controlling)
- [Crafting Tweaks](https://modrinth.com/mod/crafting-tweaks)
- [Crawl on Demand](https://modrinth.com/mod/crawl-on-demand)
- [Embeddium (Rubidium) Extra](https://modrinth.com/mod/rubidium-extra)
- [Embeddium](https://modrinth.com/mod/embeddium)
- [Enchantment Descriptions](https://modrinth.com/mod/enchantment-descriptions)
- [Entity Culling](https://modrinth.com/mod/entityculling)
- [Experimental Settings Disabler](https://modrinth.com/mod/experimental-settings-disabler)
- [Extreme sound muffler](https://modrinth.com/mod/extreme_sound_muffler)
- [Fast Paintings](https://modrinth.com/mod/fast-paintings)
- [fast-ip-ping](https://modrinth.com/mod/fast-ip-ping)
- [Fastload](https://modrinth.com/mod/fastload)
- [Forge Config Screens](https://modrinth.com/mod/forge-config-screens)
- [Game Menu Mod Option](https://modrinth.com/mod/gamemenumodoption)
- [Game Menu Remove GFARB](https://modrinth.com/mod/gamemenuremovegfarb)
- [Global Packs](https://modrinth.com/mod/globalpacks)
- [Highlight](https://modrinth.com/mod/highlight)
- [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast)
- [Inventory Profiles Next](https://modrinth.com/mod/inventory-profiles-next)
- [Jade 🔍](https://modrinth.com/mod/jade)
- [Jade Addons (Forge)](https://modrinth.com/mod/jade-addons-forge)
- [JadeColonies](https://www.curseforge.com/minecraft/mc-mods/jadecolonies)
- [Just Enough Items](https://modrinth.com/mod/jei)
- [Just Enough Mekanism Multiblocks](https://modrinth.com/mod/just-enough-mekanism-multiblocks)
- [Leave My Bars Alone](https://modrinth.com/mod/leave-my-bars-alone)
- [Lighty](https://modrinth.com/mod/lighty)
- [Memory Leak Fix](https://modrinth.com/mod/memoryleakfix)
- [Mini Effects](https://modrinth.com/mod/mini-effects)
- [ModernFix](https://modrinth.com/mod/modernfix)
- [No Chat Reports](https://modrinth.com/mod/no-chat-reports)
- [No Telemetry](https://modrinth.com/mod/no-telemetry)
- [Not Enough Animations](https://modrinth.com/mod/not-enough-animations)
- [Not Enough Recipe Book [NERB]](https://modrinth.com/mod/nerb)
- [Mouse Tweaks](https://modrinth.com/mod/mouse-tweaks)
- [Mysterious Mountain Lib](https://modrinth.com/mod/mmlib)
- [Panorama Screens](https://modrinth.com/mod/panorama-screens)
- [Remove Reloading Screen](https://modrinth.com/mod/rrls)
- [Saturn](https://modrinth.com/mod/saturn)
- [Screenshot Viewer](https://modrinth.com/mod/screenshot-viewer)
- [Seamless](https://modrinth.com/mod/seamless)
- [Sound Physics Remastered](https://modrinth.com/mod/sound-physics-remastered)
- [TexTrue's Embeddium Options](https://modrinth.com/mod/textrues-embeddium-options)
- [Toast Control](https://www.curseforge.com/minecraft/mc-mods/toast-control)
- [YUNG's Menu Tweaks](https://modrinth.com/mod/yungs-menu-tweaks)

## Technology
- [Ad Astra](https://modrinth.com/mod/ad-astra)
- [Advanced Peripherals](https://modrinth.com/mod/advancedperipherals)
- [Applied Botanics](https://modrinth.com/mod/applied-botanics)
- [Applied Energistics 2](https://modrinth.com/mod/ae2)
- [Applied Mekanistics](https://modrinth.com/mod/applied-mekanistics)
- [CC: Tweaked](https://modrinth.com/mod/cc-tweaked)
- [CC:C Bridge](https://modrinth.com/mod/cccbridge)
- [Create Big Cannons](https://modrinth.com/mod/create-big-cannons)
- [Create Central Kitchen](https://modrinth.com/mod/create-central-kitchen)
- [Create Crafts & Additions](https://modrinth.com/mod/createaddition)
- [Create Deco](https://modrinth.com/mod/create-deco)
- [Create Enchantment Industry](https://modrinth.com/mod/create-enchantment-industry)
- [Create Goggles](https://modrinth.com/mod/create-goggles)
- [Create Jetpack](https://modrinth.com/mod/create-jetpack)
- [Create Slice & Dice](https://modrinth.com/mod/slice-and-dice)
- [Create: Bells & Whistles](https://modrinth.com/mod/bellsandwhistles)
- [Create: Connected](https://modrinth.com/mod/create-connected)
- [Create: Framed](https://modrinth.com/mod/create-framed)
- [Create: Interiors](https://modrinth.com/mod/interiors)
- [Create: Liquid Fuel](https://modrinth.com/mod/create-liquid-fuel)
- [Create: Misc and Things](https://modrinth.com/mod/create-misc-and-things)
- [Create: Netherless](https://www.curseforge.com/minecraft/mc-mods/create-netherless)
- [Create: Oppenheimered](https://modrinth.com/mod/create-oppenheimered)
- [Create: Oxidized](https://modrinth.com/mod/create_oxidized)
- [Create: Power Loader](https://modrinth.com/mod/create-power-loader)
- [Create: Steam 'n' Rails](https://modrinth.com/mod/create-steam-n-rails)
- [Create: The Factory Must Grow](https://modrinth.com/mod/create-tfmg)
- [Create: Trimmed](https://modrinth.com/mod/create-trimmed)
- [Create: Tweaked Controllers](https://modrinth.com/mod/create-tweaked-controllers)
- [Create: Unbreakable Tools](https://modrinth.com/mod/create_unbreakable)
- [Create: Vintage Improvements](https://modrinth.com/mod/create-vintage-improvements)
- [Create](https://modrinth.com/mod/create)
- [Embers Rekindled](https://modrinth.com/mod/embers)
- [EnderChests](https://modrinth.com/mod/enderchests)
- [EnderTanks](https://modrinth.com/mod/endertanks)
- [Functional Storage](https://modrinth.com/mod/functional-storage)
- [Industrial Foregoing: Souls](https://modrinth.com/mod/industrial-foregoing-souls)
- [Industrial Foregoing](https://modrinth.com/mod/industrial-foregoing)
- [Iron Chests: Restocked](https://modrinth.com/mod/ironchests)
- [Mekanism Generators](https://modrinth.com/mod/mekanism-generators)
- [Mekanism Tools](https://modrinth.com/mod/mekanism-tools)
- [Mekanism: Ad Astra Ores](https://modrinth.com/mod/mekanism-ad-astra-ores)
- [Mekanism](https://modrinth.com/mod/mekanism)
- [Mob Grinding Utils](https://www.curseforge.com/minecraft/mc-mods/mob-grinding-utils)
- [More Peripherals](https://modrinth.com/mod/more-peripherals)
- [More Red](https://modrinth.com/mod/more-red)
- [Refined Storage](https://modrinth.com/mod/refined-storage)
- [Tom's Peripherals](https://modrinth.com/mod/toms-peripherals)
- [Tom's Simple Storage Mod](https://modrinth.com/mod/toms-storage)
- [Turtle Charging Station](https://modrinth.com/mod/turtle-charging-station)

## Magic

- [Aether: Lost Content Addon](https://modrinth.com/mod/aether-lost-content)
- [Botania](https://modrinth.com/mod/botania)
- [Deep Aether](https://modrinth.com/mod/deep-aether)
- [Ice and Fire](https://modrinth.com/mod/ice-and-fire-dragons)
- [Iron's Spells 'n Spellbooks](https://modrinth.com/mod/irons-spells-n-spellbooks)
- [The Aether: Redux](https://modrinth.com/mod/the-aether-redux)
- [The Aether](https://modrinth.com/mod/aether)
- [The Twilight Forest](https://www.curseforge.com/minecraft/mc-mods/the-twilight-forest)
- [Twilight Forest: The Lost Blocks](https://modrinth.com/mod/twilight-forest-the-lost-blocks)
- [Twilight's Flavor & Delight](https://modrinth.com/mod/twilight-delight)

## Weapons, Tools & Armors

- [Artifacts](https://modrinth.com/mod/artifacts)
- [Curios API](https://modrinth.com/mod/curios)
- [Epic Samurai's - Forge](https://modrinth.com/mod/epic-samurais)
- [Explorer's Compass](https://modrinth.com/mod/explorers-compass)
- [Exposure](https://modrinth.com/mod/exposure)
- [Immersive Armors](https://modrinth.com/mod/immersive-armors)
- [Nature's Compass](https://modrinth.com/mod/natures-compass)
- [Relics](https://modrinth.com/mod/relics-mod)
- [Responsive Shields](https://modrinth.com/mod/responsiveshields)
- [Sophisticated Backpacks](https://www.curseforge.com/minecraft/mc-mods/sophisticated-backpacks)
- [Spyglass of Curios](https://modrinth.com/mod/spyglass-of-curios)
- [Tempad](https://modrinth.com/mod/tempad)
- [tetra](https://modrinth.com/mod/tetra)
- [Walkie-Talkie](https://modrinth.com/mod/walkie-talkie)
- [Waystones](https://modrinth.com/mod/waystones)

## Decoration

- [Chipped](https://modrinth.com/mod/chipped)
- [Even Better Amethyst](https://modrinth.com/mod/even-better-amethyst)
- [Handcrafted](https://modrinth.com/mod/handcrafted)
- [Re:Deco](https://modrinth.com/mod/redeco)
- [Sooty Chimneys](https://modrinth.com/mod/sooty-chimneys)
- [Stoneworks](https://modrinth.com/mod/stoneworks)
- [Storage Labels](https://modrinth.com/mod/labels)
- [Supplementaries Squared](https://modrinth.com/mod/supplementaries-squared)
- [Supplementaries](https://modrinth.com/mod/supplementaries)
- [Thaumon](https://modrinth.com/mod/thaumon)
- [Wallpapers](https://modrinth.com/mod/wallpapers)

## Food

- [Corn Delight](https://modrinth.com/mod/corn-delight)
- [Crabber's Delight](https://modrinth.com/mod/crabbers-delight)
- [Crate Delight](https://modrinth.com/mod/crate-delight)
- [End's Delight](https://modrinth.com/mod/ends-delight)
- [Farmer's Delight](https://modrinth.com/mod/farmers-delight)
- [Nether's Delight Aether Compac](https://modrinth.com/mod/nethers-delight-aether-compac)
- [Nether's Delight](https://modrinth.com/mod/nethers-delight)
- [Sushi Go Crafting](https://modrinth.com/mod/sushigocrafting)
- [Tetra's Delight](https://modrinth.com/mod/tetras-delight)

## Structures & Generation
- [Alex's Caves](https://modrinth.com/mod/alexs-caves)
- [Better Villages - Forge](https://www.curseforge.com/minecraft/mc-mods/better-village-forge)
- [Dungeon Crawl](https://www.curseforge.com/minecraft/mc-mods/dungeon-crawl)
- [MineColonies](https://www.curseforge.com/minecraft/mc-mods/minecolonies)
- [Repurposed Structures - Neoforge/Forge](https://modrinth.com/mod/repurposed-structures-forge)
- [Towns and Towers](https://modrinth.com/mod/towns-and-towers)
- [William Wythers' Expanded Ecosphere](https://modrinth.com/mod/expanded-ecosphere)
- [William Wythers' Overhauled Overworld](https://modrinth.com/mod/wwoo)
- [YUNG's Better Desert Temples](https://modrinth.com/mod/yungs-better-desert-temples)
- [YUNG's Better Dungeons](https://modrinth.com/mod/yungs-better-dungeons)
- [YUNG's Better End Island](https://modrinth.com/mod/yungs-better-end-island)
- [YUNG's Better Jungle Temples](https://modrinth.com/mod/yungs-better-jungle-temples)
- [YUNG's Better Mineshafts](https://modrinth.com/mod/yungs-better-mineshafts)
- [YUNG's Better Nether Fortresses](https://modrinth.com/mod/yungs-better-nether-fortresses)
- [YUNG's Better Ocean Monuments](https://modrinth.com/mod/yungs-better-ocean-monuments)
- [YUNG's Better Strongholds](https://modrinth.com/mod/yungs-better-strongholds)
- [YUNG's Better Witch Huts](https://modrinth.com/mod/yungs-better-witch-huts)
- [YUNG's Bridges](https://modrinth.com/mod/yungs-bridges)
- [YUNG's Extras](https://modrinth.com/mod/yungs-extras)

## Other

- [Alex's Mobs](https://modrinth.com/mod/alexs-mobs)
- [Clumps](https://modrinth.com/mod/clumps)
- [Conduits Prevent Drowned](https://modrinth.com/mod/conduits-prevent-drowned)
- [Corpse](https://modrinth.com/mod/corpse)
- [Disable Ad Astra Meteors](https://modrinth.com/mod/disable-ad-astra-meteors)
- [Disable Ad Astra Oil Wells](https://modrinth.com/mod/disable-ad-astra-oil-wells)
- [Easy Anvils](https://modrinth.com/mod/easy-anvils)
- [Easy Magic](https://modrinth.com/mod/easy-magic)
- [Emotecraft](https://modrinth.com/mod/emotecraft)
- [Heracles](https://modrinth.com/mod/heracles)
- [HT's TreeChop](https://modrinth.com/mod/treechop)
- [I don't want portal yet](https://modrinth.com/mod/i-dont-want-portal-yet)
- [Lootr](https://modrinth.com/mod/lootr)
- [Minecards [Forge]](https://modrinth.com/mod/minecards-forge)
- [More Red x CC:Tweaked Compat](https://modrinth.com/mod/more-red-x-cc-tweaked-compat)
- [Polymorph](https://modrinth.com/mod/polymorph)
- [Polymorphic Energistics](https://modrinth.com/mod/polymorphic-energistics)
- [Refined Polymorphism](https://modrinth.com/mod/refined-polymorphism)
- [Relics: Alex's Mobs Compat](https://modrinth.com/mod/ram-compat)
- [Scaffolding Drops Nearby](https://modrinth.com/mod/scaffolding-drops-nearby)
- [Simple Voice Chat](https://modrinth.com/mod/simple-voice-chat)
- [Stylecolonies](https://www.curseforge.com/minecraft/mc-mods/stylecolonies)
- [tetracelium](https://modrinth.com/mod/tetracelium)
- [Visual Workbench](https://modrinth.com/mod/visual-workbench)
- [Xaero's Minimap](https://modrinth.com/mod/xaeros-minimap)
- [Xaero's World Map](https://modrinth.com/mod/xaeros-world-map)
