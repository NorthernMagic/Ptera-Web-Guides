---
Title: Paper Study
Description: To see the alternatives and study PaperMC more.
Last Edit: 2/16/2023
---

PaperMC, which is typically better for servers, 
could be used to replace Fabric as the base for our server. 
I'm exploring whether if this is viable and possible.
Due to the fact that most of our mods 
have Paper plugin versions. I'm currently studying about 
this, to see if it would hypothetically work.

A little over half of all our mods have a direct
plugin version compatible with Paper. 

## Table Of Contents

* [PaperMC Downloads & Documentation](#papermc-downloads--documentation)
* [Plugin Counterparts/Alternatives](#plugin-counterpartsalternatives)
* [How To Switch From Fabric to Paper (WIP)](#how-to-switch-from-fabric-to-paper-wip)
  * [Installing PaperMC](#installing-papermc)
  * [Installing Plugins](#installing-plugins)
  * [Additional Information](#additional-information)
* [Troubleshooting Plugins](#troubleshooting-plugins)
  * [Check Server Logs](#check-server-logs)
  * [Missing Dependencies](#missing-dependencies)
  * [Invalid Plugin.yml](#invalid-pluginyml)
  * [Ambiguous Plugin Name](#ambiguous-plugin-name)
  * [Something Else](#something-else)
  * [If Nothing Is Logged](#if-nothing-is-logged)
* [Sources & Documentation](#sources--documentation)


## PaperMC Downloads & Documentation

Paper Main Page: https://papermc.io/

Paper Server Jar Download: https://papermc.io/downloads

Paper Migration Documentation: https://docs.papermc.io/paper/migration



## Plugin Counterparts/Alternatives

🟩 = Direct Plugin or Datapack Version of Fabric Mod

🟨 = Alternative Plugin with similar and/or higher capabilities

---------

🟩 No Chat Reports (Plugin): https://www.spigotmc.org/resources/no-chat-reports-1-19-1-19-x.102931/

🟩 GeyserMC (Plugin): https://ci.opencollab.dev/job/GeyserMC/job/Geyser/job/master/

🟩 WorldEdit (Plugin): https://dev.bukkit.org/projects/worldedit

🟩 Floodgate (Plugin): https://github.com/GeyserMC/Floodgate/

🟩 Spark (Plugin): https://www.spigotmc.org/resources/spark.57242/

🟩 Terralith (Datapack): https://www.planetminecraft.com/data-pack/terralith-overworld-evolved-100-biomes-caves-and-more/

---------

🟨 EssentialsX Moderation (Plugin) https://essentialsx.net/

🟨 Graves (Grave Mod Alternative): https://www.spigotmc.org/resources/graves.74208/

🟨 Ultimate Tree Faller (FallingTree Mod Alternative): https://www.curseforge.com/minecraft/bukkit-plugins/thizzyz-tree-feller
 
🟨 CoreProtect (Ledger Paper Alternative): https://www.spigotmc.org/resources/coreprotect.8631/

## How to Switch From Fabric to Paper (WIP)

#### Installing PaperMC

Paper does not support Fabric or Forge mods. 
You will need to find plugin replacements. 
Any hybrids that 
attempt to support both mods and plugins are 
fundamentally flawed and not recommended for use.

⚠️ When migrating to Paper from Fabric, the way 
worlds are stored will automatically be changed.

1a) `Stop` your Fabric server 
if it is running, and create a `full backup`.

**CREATE A BACKUP!!!**

1b) Download Paper from the downloads page and 
replace your Fabric server jar with 
your freshly downloaded Paper jar.

1c) Download the Terralith Datapack and
install it into the server Datapack folder.

1d) Run the Paper Server to see if everything works.

#### Installing Plugins

2a) `Stop` your Fabric server.

⚠  Ensure the file(s) you have downloaded ends in `.jar`. Some plugins also distribute as `.zip` files, in which case you will need to **extract** the file and locate the `.jar` for your platform, often labelled `bukkit` or `paper`.

2b) Once you have the plugin downloaded locally, locate the plugins folder from the root directory of your Paper server.
Drag and drop the plugin file (.jar) into the plugins folder. 

⚠ If you are using a shared hosting service, you may need to use their web panel or SFTP to upload the plugin; however, the procedure will be the same.

2c) Restart your server. The plugin(s) should load.

2d) Check your work. Once the server has finished loading, run the `/plugins` command in-game or type `plugins` into the console. You should see your freshly installed plugin listed in `green`. If it is not listed or is colored red, continue to [Troubleshooting Plugins](#troubleshooting-plugins). A plugin listed in red means that it is not currently enabled. For a freshly installed plugin, this often means that the plugin failed to load.

## Additional Information

Here is a chart to show the difference between how Vanilla and Paper store worlds.

| Server Software | Overworld | Nether                | End                   |
| --------------- | --------- | --------------------- | --------------------- |
| Vanilla         | `/world`  | `/world/DIM-1`        | `/world/DIM1`         |
| Paper           | `/world`  | `/world_nether/DIM-1` | `/world_the_end/DIM1` |


## Troubleshooting Plugins

#### Check Server Logs

The first step to troubleshooting installing plugins is to check the log of your server. 
Your server's most recent logs will be stored to the `logs/latest.log` file.

-----

#### Missing Dependencies

If you see something like this:

```log
Could not load 'plugins/MyAwesomePlugin-1.0.0.jar' in folder 'plugins'
org.bukkit.plugin.UnknownDependencyException: Unknown/missing dependency plugins: [Vault]. Please download and install these plugins to run 'MyAwesomePlugin'.
```

This means that the plugin you tried to install is missing a dependency. A dependency, in this case,
is another plugin that you must install for the first to function. While you will get a big scary
error, the important line to look at is

```log
Unknown/missing dependency plugins: [Vault]. Please download and install these plugins to run 'MyAwesomePlugin'.
```

In this example it's telling you that in order to load `MyAwesomePlugin`, you must first install `Vault`.

-----

#### Invalid plugin.yml

If you see something closer to this:

```log
Could not load 'plugins/MyAwesomePlugin-1.0.0.jar' in folder 'plugins'
org.bukkit.plugin.InvalidDescriptionException: Invalid plugin.yml
```

This means that what you have downloaded isn't a valid Paper plugin. This is generally caused by one
of the following:

1. The plugin you downloaded isn't a plugin at all, but instead a mod for Forge, Fabric, or similar.
   These will not run on Paper.
2. The plugin failed to download completely. Especially when using tools such as `curl` or `wget`,
   you can easily download error pages rather than the plugin you intended. This may also be caused
   by a network issue. Attempt to download the plugin again. 
   
   ⚠ If you are using FTP (not SFTP or a web
   panel) to upload your plugin to a shared hosting service, ensure your FTP client is in `binary`
   and not `ASCII` mode. Consult the documentation for your FTP client for details.
   
 -----
   
#### Ambiguous Plugin Name

If you see something like this:

```log
Ambiguous plugin name `Essentials' for files `plugins/EssentialsX-2.19.4.jar' and `plugins/Essentialsx-2.20.0-dev.jar' in `plugins'
```

This means you have two plugins with the same name, which is not supported. In this case, two
versions of EssentialsX are installed. Both the release `2.19.4`, and a development build of
`2.20.0`. Ensure you only have one version of each plugin installed at one time. Delete the older
version of the duplicate plugin, and restart your server.

-----

#### Something Else

If you see an error, but it isn't similar to one of the above, attempt to read it yourself. While
the full error may be large and scary, you likely only have to read the first one or two lines to
understand what is going on. If you're not sure, do not hesitate to reach out for support on the
[Discord](https://discord.gg/papermc) in the `#paper-help` channel.

-----

#### If Nothing is Logged

If nothing is logged, your server is likely not attempting to load any plugins. The conditions
needed for the server to load a plugin are as follows:

1. The file is at the root of the `plugins` folder, relative to its working directory. This is
   usually the same folder as the server JAR file. **Subdirectories of the `plugins` folder will not
   be checked.** All plugins must be in the root folder.
2. The file ends in `.jar`. If your plugin does not end in `.jar`, what you have downloaded may not
   be a plugin. Note that some plugins distribute multiple jars as `.zip` files. If this is the
   case, you have to extract them before installing the plugin.

If both of these are true and you still see no logs please reach out for support on the
[Discord](https://discord.gg/papermc) server in the `#paper-help` channel.

-----

## Sources & Documentation

