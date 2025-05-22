Installation
------------

This mod requires Bepinex5 to be installed, please download the latest one for your OS here:
https://github.com/BepInEx/BepInEx/releases

﻿Then in Steam\steamapps\common\Ratopia, extract it and make sure the BepInEx folder is alongside MonoBleedingEdge and Ratopia_Data.

To install my mod, simply extract the zipped folder to your ﻿Steam\steamapps\common\Ratopia folder. It should just work if you did all this correctly.

Usage
-----

Inside BepInEx/plugins/ConstructionManager, you will find 3 files. ConstructionManager.dll is the main plugin file, ResourceList.txt is a list of valid resource names for use in recipes (they may differ from what you expect, so experiment or try to find the closest name to what you want), and Buildings.json is the main configuration for the mod.

Inside Buildings.json is a list of every single enabled building in the game, which automatically populates if the file is missing somehow. Here you can change the recipe to construct anything by changing the 'recipe' field. If the recipe is Sandrock(1), it will cost 1 sandrock to build. If the recipe is empty (just "" quotes), it will be completely free to build.
