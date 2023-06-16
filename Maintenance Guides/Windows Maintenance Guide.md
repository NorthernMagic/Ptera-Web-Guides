---
Title: Minecraft Maintenance Windows
Description: A guide to teach you how to maintain Minecraft.
Last Edit: 6/16/2023
---

Minecraft needs to be maintained regularly.
This ensures you have an amazing experience without issues. 
We also recommend you keep Windows and all your other software such as drivers, up to date.

⚠ This guide is based off the Windows Quickstart guide. Same process with forge or quilt mod loaders.

## 📖 TABLE OF CONTENTS 
* [Updating Minecraft](#updating-minecraft)
  * [Updating Minecraft (Java Edition)](#updating-minecraft-java-edition)
  * [Updating Minecraft (Bedrock Edition)](#updating-minecraft-bedrock-edition)
* [Updating Fabric](#updating-fabric)
* [Updating Mods](updating-mods)
  * [Updating Mods With Ferium](#updating-mods-with-ferium)
  * [Updating Mods Manually](#updating-mods-manually)

## UPDATING MINECRAFT

### UPDATING MINECRAFT (JAVA EDITION)

Our server usually does a good job keeping up to date. 
But you also need to update too. Here's how to update the base Minecraft game

1a) Open the Minecraft Launcher. The launcher auto-checks for updates.
You might see it download a new version of itself. If it doesn't update itself
you are likely up to date with the launcher.

1b) Select the `Latest Version` in the drop-down menu left of the play button.

1c) The game will download the latest game files to your PC.

1d) Minecraft will launch! You are now up to date.

⚠️ For those who have the base game only or have only
followed sections 1-3 in the quickstart guide, you are done here.

### UPDATING MINECRAFT (BEDROCK EDITION)

Bedrock Players have a similar process. But this involves the Microsoft store.

1a) Open the Microsoft Store app on your PC. Navigate to library, and 
click `Check for Updates`. Minecraft Bedrock (and other apps) will download 
updates. If an update doesn't download, you are up to date with the game.

1b) Open the Minecraft Launcher. The launcher auto-checks for updates.
You might see it download a new version of itself. If it doesn't update itself
you are likely up to date with the launcher.

1c) Launch Minecraft Bedrock and you are done! Be sure to do this every so often.

⚠️ The next sections are intended for Java Edition players only.

## UPDATING FABRIC

The Fabric loader gets updates every so often. Unfortunately Ferium can't download the newest loader versions,
so we need to do things manually.

2a) Go [here](https://fabricmc.net/use/installer/) and download the Fabric installer. Or if you already have it installed, open that.

2b) Once in the installer, make sure the loader version to download matches the current one you have installed. An easy way to check is to open the launcher and
analyze the version info below your Fabric installation.

2c) If they match, then you are up to date. If they don't then download the latest version from the installer.

2d) The new version will overwrite the old one and keep your configs, mods, and memory allocation.

## UPDATING MODS
Mods recieve updates every so often too. Ferium can download these mods in a jiffy. You can also update them manually too.

#### Updating Mods With Ferium
3a) We need to sync your Ferium profile with the newest Minecraft version first. Open a terminal. We are using 1.20.1 as an example, as its the latest version of Minecraft available.

3b) In the terminal type or copy in `ferium profile configure --game-version 1.20.1`.

3c) Open a terminal and type or copy in `ferium upgrade`. Then press enter. Ferium will then update your mods instantly for 1.20.1.

3d) Close the terminal. You can hit X or type in `exit` and press enter.

#### Updating Mods Manually

While we recommend using Ferium, you can download mods manually too if you don't want Ferium installed on your system

3c) Go to the website where you downloaded the mod(s) from and compare the name of the file to the .jar files in your `mods` folder.

3d) If they match, they are likely up to date. If they don't replace the old mod .jar file with the new one.

3e) Close File Explorer. The mod(s) are now updated and ready to use.



