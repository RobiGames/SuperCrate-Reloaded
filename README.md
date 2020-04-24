# SuperCrate Reloaded
A rich crate plugin, which acts as a colorful prize lottery. Perfect for vote keys.

'SuperCrate Reloaded plugin is just updated by me and I will try to keep it updated. **Original plugin:** [SuperCrate 1.9](https://www.spigotmc.org/resources/supercrate.20377/)

SuperCrate is a unique and lightweight plugin - made in my spare time. Altough you probaly see alot of Crate/Keys plugins, this one is different, fully customizable, and great for both tiny servers and huge networks.
The installing and setup process is quick and easy, and the whole process is smooth. The plugin also supports money as rewards, see Features Section.

# Features
- Light and effecient, developed to handle enormous amounts of players, while using the lowest amount of CPU and RAM. If you need a plugin that could handle thousends and hundred thousends of players, this plugin is for you.
- The plugin is 100% customisable, meaning you can change the prefix, ALL the messages (lang file included) and the config is fully supporting color codes.
- Completely premission based giving you full control over the usage of the plugin. There is even "sc.help" to control the ability to view the help menu.
- Defaults to OP, meaning the plugin is usable even without a premissions plugin.
- Easy and simple crates setup. No need to bother in complex configs, or try to understand how to achieve enchants, lores, and other unqiue identifires, becuase the whole process is in-game, and goes smoothly.
- Reward players with money, by renaming a paper to "[AMOUNT]$" and placing it in the prizes GUI.
- GUI based, meaning there are not much commands, and the whole editing process happens by dragging items around.
- Colorful, Sounds, And beatiful opening animation. The best you can find for free.
- Using vault, you can choose whatever permissions & economy plugin suits you the best.
- The config doesn't have to be edited/opened at all. You can drop the plugin inside the folder, jump on into the server and start playing. It's simple as that.
- Left clicking the crate chest would open a GUI which allow you to see what are the possible rewards.

# Permissions
- /supercrate OR /sc - sc.help - Shows the help menu.
- /sc list - sc.list - List all current crates.
- /sc create [name] - sc.create - Open the crate GUI to setup a new crate.
- /sc remove [name] - sc.remove - Remove an existing crate.
- /sc edit [name] - sc.edit - Edit an existing crate.
- /sc get [name] - sc.get - Recieve a placeable crate(chest).
- /sc give [player] [name] - sc.give - Give the specified player a crate key. Use this command in vote plugins and buycraft perks.

# Images
![IMG1](https://proxy.spigotmc.org/6eb7b0937e398546bce5a51037ce6dc839132e73?url=http%3A%2F%2Fi.imgur.com%2F2RCj1Ly.png)
![IMG2](https://proxy.spigotmc.org/0c16602ce9992722eb8dc4808dd0d74e686375d4?url=http%3A%2F%2Fi.imgur.com%2FjEYAXou.png)

# Code (text)
```#SuperCrate by DrPiggy
#DO NOT REDISTRIBUTE OR TAKE CREDIT OF!
#Use '&' char for format/color codes!

#Plugin Prefix
prefix: "&3[&6&lSuperCrate&r&3]"

#     ----MESSAGES----
#     ================
#Available formats: NONE
receive_key: "&rYou received a crate key!"
#Available formats: %p = Player
give_key: "&rKey sent to %p successfully!"
#Available formats: NONE
open_crate: "&rOpening crate..."
#Available formats: %i = Amount + Item
prize_item: "&rYou won &6%i&r!"
#Available formats: %a = Money Amount
prize_money: "&rYou won &6%a cash&r!"
#Available formats: NONE
no_perm: "&r&4YOU DONT HAVE PERMISSIONS TO USE THIS COMMAND/CRATE!"


# I'm publishing this plugin free of charge and, allowing you to fully-100% customize it.
# I have only one little credit, in the help list, And still, you have the option to remove it.
# Please consider supporting me, by leaving it there, Thank you, -DrPiggy :)
Credit: true```
