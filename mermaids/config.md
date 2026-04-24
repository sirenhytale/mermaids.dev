---
title: Config
description: Mermaids Mod - Config
parent: Mermaids
layout: page
permalink: /mermaids/config/
nav_order: 2
---

#### Mermaids Config.
This is the default config values and descriptions for the Mermaids config version 15,
found in the path `mods/Siren_Mermaids/Config.json`.

| Variable Name:                               | Default Value:                                                              | Description:                                                                                                                                                                          |
|:---------------------------------------------|:----------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| "Config-Information"                         | A long string that tells you to come to this site.                          | Information about how to find stuff related to the config.                                                                                                                            |
| "ConfigVersion"                              | 15                                                                          | Current Version when you have loaded for the plugin.                                                                                                                                  |
| "PluginName"                                 | "Mermaids"                                                                  | Plugin name.                                                                                                                                                                          |
| "Version"                                    | "2.5.1"                                                                     | Version of the last ran mod jar.                                                                                                                                                      |
| "Website"                                    | "https://www.mermaids.dev/mermaids/"                                        | Official website for the Mermaids mod.                                                                                                                                                |
| "Download-Site"                              | "https://www.curseforge.com/hytale/mods/mermaids"                           | Website to download this mod, check for updates, and information.                                                                                                                     |
| "Enable-Generic-Console-Logs"                | false                                                                       | Send console logs for majority of mermaid actions: transforming and modifying settings.                                                                                               |
| "Transformation-Mode"                        | 0                                                                           | TransformationMode = 0 : Transform when entering water, TransformationMode = 1 : Requires user to drink Mermaid Potion to Transform.                                                  |
| "Description-Transformation-Mode"            | A long string that tells you about the description for Transformation-Mode. | A description of the Transformation-Mode config option.                                                                                                                               |
| "Always-A-Mermaid-Even-On-Land"              | false                                                                       | If you have permissions to be a Mermaid, than you'll always be transformed into a Mermaid even on land.                                                                               |
| "Mermaid-On-Land-Speed-Debuff"               | true                                                                        | If the player is transformed as a Mermaid, they will have a speed debuff while on land.                                                                                               |
| "Require-Transformation-Permission"          | false                                                                       | Requires the player to have the permission -- mermaids.transform -- to transform into a Mermaid.                                                                                      |
| "Items-Can-Increase-Swim-Speed"              | true                                                                        | Some items like fishbone harpoon and some modded related items will give you increased swim speed as a mermaid.                                                                       |
| "Blocks-Can-Cause-Transformations"           | true                                                                        | Some blocks like mud and a cauldron will cause you to transform into a mermaid.                                                                                                       |
| "Rain-Can-Cause-Transformations"             | false                                                                       | Walking into the rain will cause you to transform into a mermaid.                                                                                                                     |
| "Mermaid-Have-A-Glow/Light"                  | true                                                                        | The mermaid model will light of a glow allowing the player to see better underwater.                                                                                                  |
| "Mermaid-Glow/Light-Radius"                  | 33                                                                          | The radius of the mermaid glow.                                                                                                                                                       |
| "EasyHunger-By:Haasapenas-Compatibility"     | true                                                                        | Compatibility with the [EasyHunger](https://www.curseforge.com/hytale/mods/easyhunger) Mod, see [Compatibilities](/mermaids/compatibilities/) page for more info.                     |
| "AquaThirst&Hunger-By:Jume-Compatibility"    | true                                                                        | Compatibility with the [Aqua Thirst & Hunger](https://www.curseforge.com/hytale/mods/aqua-thirst-hunger) Mod, see [Compatibilities](/mermaids/compatibilities/) page for more info.   |
| "DivingTale-By:xnrdev-Compatibility"         | true                                                                        | Compatibility with the [[xnrdev] DivingTale](https://www.curseforge.com/hytale/mods/diving-equipment) Mod, see [Compatibilities](/mermaids/compatibilities/) page for more info.      |
| "MoreNPC-By:BlueEyesWhiteMen-Compatibility"  | true                                                                        | Compatibility with the [MoreNPC](https://www.curseforge.com/hytale/mods/morenpc) Mod, see [Compatibilities](/mermaids/compatibilities/) page for more info.                           |
| "KeybladesReimagined-By:TaHie-Compatibility" | true                                                                        | Compatibility with the [Keyblades Reimagined](https://www.curseforge.com/hytale/mods/keyblades-reimagined) Mod, see [Compatibilities](/mermaids/compatibilities/) page for more info. |
| "New-Version-Message"                        | true                                                                        | When Mermaids mod version is outdated, send a message to OPed players when they join.                                                                                                 |
| "Do-Not-Change:Add-mermaids-Perm"            | false, but on startup it will set it to true                                | Ignore this value; however, it will add the permission "mermaids" to the Adventure permission group on startup.                                                                       |
| "DebugMode"                                  | false                                                                       | Run the plugin in debug mode to get alerts about most actions of the plugin.                                                                                                          |

<br/>

* * *

<br/>

#### Mermaids Orbis Origins Config
This is the default config values and descriptions for the Mermaids Orbis Origins config version 1,
found in the path `mods/Siren_Mermaids/Compatibility/OrbisOrigins.json`.

| Variable Name:                                   | Default Value:                                                                                | Description:                                                                                           |
|:-------------------------------------------------|:----------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------|
| "Config-Name"                                    | "Orbis Origins Compatibility"                                                                 | The name given to this config file.                                                                    |
| "Config-Description"                             | "This config file allows the user to modify compatibility issues with the Orbis Origins mod." | Description of what this config can modify.                                                            |
| "Config-Information"                             | A long string that tells you to come to this site.                                            | Information about how to find stuff related to the config.                                             |
| "ConfigVersion"                                  | 1                                                                                             | Current Version when you have loaded for the plugin.                                                   |
| "Enable-Orbis-Origins-Compatibility"             | false                                                                                         | Toggle for the Mermaids mod to add a brand new mermaids species to the Orbis Origins mod.              |
| "Description-Enable-Orbis-Origins-Compatibility" | A description of what the "Enable-Orbis-Origins-Compatibility" does.                          | A description of what another variable does.                                                           |
| "Default-Mermaids-Content"                       | false                                                                                         | Toggle the Mermaids mod content. If false, you can only transform into a Mermaid as a mermaid species. |
| "Description-Default-Mermaids-Content"           | A description of what the "Default-Mermaids-Content" does.                                    | A description of what another variable does.                                                           |
| "Mermaid-Only-In-Water"                          | true                                                                                          | When the player is a mermaid species, they will only have a Mermaid tail while in water.               |

<br/>

* * *

<br/>

#### Mermaids Endless Leveling Config
This is the default config values and descriptions for the Mermaids Endless Leveling config version 1,
found in the path `mods/Siren_Mermaids/Compatibility/EndlessLeveling.json`.

| Variable Name:                                      | Default Value:                                                                                   | Description:                                                                                           |
|:----------------------------------------------------|:-------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------|
| "Config-Name"                                       | "Endless Leveling Compatibility"                                                                 | The name given to this config file.                                                                    |
| "Config-Description"                                | "This config file allows the user to modify compatibility issues with the Endless Leveling mod." | Description of what this config can modify.                                                            |
| "Config-Information"                                | A long string that tells you to come to this site.                                               | Information about how to find stuff related to the config.                                             |
| "ConfigVersion"                                     | 1                                                                                                | Current Version when you have loaded for the plugin.                                                   |
| "Enable-Endless-Leveling-Compatibility"             | false                                                                                            | Toggle for the Mermaids mod will add a brand new mermaid race to Endless Leveling.                     |
| "Description-Enable-Endless-Leveling-Compatibility" | A description of what the "Enable-Endless-Leveling-Compatibility" does.                          | A description of what another variable does.                                                           |
| "Default-Mermaids-Content"                          | false                                                                                            | Toggle the Mermaids mod content. If false, you can only transform into a Mermaid as a mermaid species. |
| "Description-Default-Mermaids-Content"              | A description of what the "Default-Mermaids-Content" does.                                       | A description of what another variable does.                                                           |
| "Mermaid-Only-In-Water"                             | true                                                                                             | When the player is a mermaid race, they will only have a Mermaid tail while in water.                  |