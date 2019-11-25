# mb_trains
Replaces minecarts in Minecraft with rideable trains. I've only tested it in the Windows 10 Edition, but it should work on other devices running Bedrock Edition as well.

![Minecart replacement](https://github.com/FreekBes/mb_trains/blob/master/imgs/better_minecarts.png "Minecart replacement")

The default minecart gets replaced with a train based on the [NS Kameel](https://nl.wikipedia.org/wiki/Kameel_(spoorwegmaterieel)), which can be ridden on by 4 people at the same time.

When the default minecarts goes over a powered activator rail, it starts running in hyperspeed mode: its max speed will double (16 blocks per second). As soon as the cart runs over an activator rail again, the mode will end and the cart will return to its default speed (which is 8 blocks per second). On turns, this hyperspeed should be disabled (in time), otherwise the train might derail!

![Minecart with Chest replacement](https://github.com/FreekBes/mb_trains/blob/master/imgs/better_minecarts_freight.png "Minecart with Chest replacement")

The chest minecart gets replaced with a custom freight train. The inventory slots don't change. This train can be ridden on by 2 people at the same time.

*Update 22-11-2019: the chest minecart doesn't seem to be working, due to Minecraft assigning the default minecart texture+model to all minecart types.*

## Downloading & activating the add-on
To activate the packs, get the latest version from the [releases](https://github.com/FreekBes/mb_trains/releases/) page and open the downloaded `.mcaddon` file using Minecraft. The packs should now be imported, and you can now activate them in your world's settings!

If the above does not work, you can also activate the packs manually, by downloading [this](https://github.com/FreekBes/mb_trains/archive/master.zip) full repository. Press <kbd>Windows</kbd> + <kbd>R</kbd>, write `%APPDATA%` and press <kbd>Enter</kbd>. Go up one directory, then open the `Local` folder, navigate to `Packages`, then `Microsoft.MinecraftUWP_8wekyb3d8bbwe`, `LocalState`, `games`, and finally `com.mojang`. put the `NS_Kameel_Behavior` folder in the `behavior_packs` folder, and the `NS_Kameel_Resources` folder in the `resource_packs` folder.

You need to activate both the behavior and the resource pack in order for everything to work smoothly. If somehow you are unable to use a behavior pack, the pack will still work with just the resource pack - but it will only be for the eyes, as the extra features (such as 4 people on the same train) will not work.
