# mb_trains
Replaces minecarts in Minecraft with rideable trains. I've only tested it in the Windows 10 Edition, but it should work on other devices running Bedrock Edition as well.

The default minecart gets replaced with a train based on the [NS Kameel](https://nl.wikipedia.org/wiki/Kameel_(spoorwegmaterieel)), which can be ridden on by 4 people at the same time. It also has an inventory with 5 slots for luggage.

The chest minecart gets replaced with a custom freight train. The inventory slots don't change. This train can be ridden on by 2 people at the same time.

You need to activate both the behavior and the resource pack in order for everything to work smoothly. If somehow you are unable to use a behavior pack, the pack will still work with just the resource pack - but it will only be for the eyes, as the extra features (such as 4 people on the same train) will not work.

To activate the packs in-game, press <kbd>Windows</kbd> + <kbd>R</kbd>, typ `%APPDATA%` and press <kbd>Enter</kbd>. Go up one directory, then open the `Local` folder, navigate to `Packages`, then `Microsoft.MinecraftUWP_8wekyb3d8bbwe`, `LocalState`, `games`, and finally `com.mojang`. put the `NS_Kameel_Behavior` folder in the `behavior_packs` folder, and the `NS_Kameel_Resources` folder in the `resource_packs` folder.

You can also zip both folders into one ZIP-file, change the file extension to `.mcaddon` and open this file.
