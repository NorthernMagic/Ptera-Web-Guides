---
Title: Windows 10/11 Quickstart Guide
Description: A guide designed for Windows users to get Minecraft set up and optimized for our server.
Last Edit: 6/16/2023
---

## 📖TABLE OF CONTENTS

* [System Requirements 2023](#system-requirements-2023)
  * [Minimum Requirements (Java Edition)](#minimum-requirements-java-edition)
  * [Recommended Requirements (Java Edition)](#recommended-requirements-java-edition)
  * [PC Minimum Requirements (Bedrock Edition)](#pc-minimum-requirements-bedrock-edition)
* [Buying and Installing Minecraft](#buying-and-installing-minecraft)
* [Allocating Memory/RAM](#allocating-memory-to-minecraft)
* [Joining The Server](#joining-the-server)
* [(Recommended) Installing Java JDK](#recommended-download-java-jdk)
* [Installing Fabric](#installing-fabric)
* [Installing Fabric API and Mods](#installing-fabric-api-and-mods)
* [(Optional) Installing Ferium](#optional-installing-ferium)
  * [Installing Scoop and Ferium for Windows](#installing-scoop-and-ferium-for-windows)
  * [Configuring Ferium](#configuring-ferium)

## SYSTEM REQUIREMENTS 2023

#### MINIMUM REQUIREMENTS (JAVA EDITION)
* **CPU:** Intel Core i3-3210 3.2 GHz / AMD A8-7600 APU 3.1 GHz or equivalent
* **RAM:** 4GB
* **GPU** (Integrated): Intel HD Graphics 4000 (Ivy Bridge) or AMD Radeon R5 series (Kaveri line) with OpenGL 4.4*
* **GPU** (Discrete): Nvidia GeForce 400 Series or AMD Radeon HD 7000 series with OpenGL 4.4
* **HDD:** At least 1GB for game core, maps, and other files
* **OS:** Windows: 64-Bit Windows 10 and up
* Internet connectivity is required for downloading Minecraft files, afterwards offline play is possible.

#### RECOMMENDED REQUIREMENTS (JAVA EDITION)
* **CPU:** Intel Core i5-4690 3.5GHz / AMD A10-7800 APU 3.5 GHz or equivalent
* **RAM:** 8GB
* **GPU:** GeForce 700 Series or AMD Radeon Rx 200 Series (excluding integrated chipsets) with OpenGL 4.5
* **HDD:** 4GB (SSD is strongly recommended)
* **OS:** Windows: 64-Bit Windows 10 and up
* Internet connectivity is required for downloading Minecraft files, afterwards offline play is possible.

#### PC MINIMUM REQUIREMENTS (BEDROCK EDITION)
* **CPU:** Intel Core i3 3210 | AMD A8 7600 APU or equivalent
* **RAM:** 4 GB RAM
* **HDD:** 180 MB to 1 GB available space
* **GPU:** Intel HD Graphics 4000 or AMD Radeon R5 series | NVIDIA GeForce 400 Series or AMD Radeon HD 7000 series
* **OS:** 64-bit Windows 10 and up
* **Screen Resolution:** 1024 x 768 or better
* Internet connectivity is required for downloading Minecraft files, afterwards offline play is possible. 

## BUYING AND INSTALLING MINECRAFT

If you don't have Minecraft at all, you need to install it. Before, you had to choose between Java (Recommended) and Bedrock Edition. Thankfully, you can buy both versions for $30 USD. But we still recommend using the Java Edition when logging into the server, as it's natively supported and has less issues.

1a) To buy Minecraft for Windows click this [link](https://www.minecraft.net/en-us/store/minecraft-java-bedrock-edition-pc).

1b) Register your payment information (credit card). Once filled out, and bought, click `Download for Windows`. The Minecraft Launcher will download onto your Windows PC.

1c) Sign into the launcher with your Microsoft account. Make sure the version drop-down to the left is selected to `Latest Version`. 

1d) Click `Play`, the launcher will download the game files to your device and launch into the title screen. Once launched into the title screen, close the game by pressing `Quit`. 

## ALLOCATING MEMORY TO MINECRAFT 

This section will be referenced multiple times. If you are seeing this section for the first time, we will be increasing the amount of RAM or memory to increase Minecraft's performance.  

2a) In the main page of the launcher, click the `Installations` tab at the top. While here make sure `Modded` and `Snapshots` are checkmarked alongside `Latest Version` if they aren't.

2b) Click on the version you want to allocate RAM to. If this is the first time, select the 3 little vertical dots on the `Latest Release` version and click `Edit`.

2c) In the installation editor, click `More Options`. In the `JVM Arguments` box, you will see a `-Xmx2G -XX` followed by a chain of text. 

⚠️ Make sure you know how much RAM you have on your PC! You can look it up in the Windows Settings by typing `About PC` and looking it up.

Allocating more than half of it is generally a bad idea. So for example if you have a PC with 8GB, allocate up to 4GB. If you have a higher RAM count, such as 16GB or 32GB, allocating more than 8GB to Minecraft usually yields diminishing returns.

2d) Once comfortable with allocating the amount of RAM you want, change the number between the x and the G to it. Click `Save` and Go to the `Play` tab. 

## JOINING THE SERVER

Time to join the server! This is pretty easy and seamless

3a) Launch Minecraft and go to the `Multiplayer` Tab in the title screen.

3b) Click `Add Server` and in the 'Server Name' field, type in `Ptera's Forest`. 

3c) In the `Server Address` field, type in the IP address of our server. `play.ptera.tv`

3d) Click done and the server should be saved to your server list. Fill out this Google [form](https://docs.google.com/forms/d/e/1FAIpQLSeEBVKIESOidbwOyYXCdaG4JxFVVfZEXefyW7vQQQHF83sEYQ/viewform?usp=send_form) if you haven't, and DM Ptera or a moderator about you filling it out to ensure you get added.

3e) Once you are added to the server join it in the server list by hovering over the server picture and clicking the gray `Play Button`. You should be able to join and will be at spawn. 

⚠️ If you get an error saying you aren't on the whitelist, DM a moderator and they will get things sorted out. Try to rejoin after that.

### ✅ You have everything needed to join our server. We highly recommend installing some mods to improve Minecraft's performance. You can end here, but follow sections 4+ to install mods if you'd like.



## (RECOMMENDED) DOWNLOAD JAVA JDK

Minecraft comes with its own standalone version of Java pre-installed. But I recommend installing it anyway as it doesn't hurt and some mod loaders need Java installed. Installing Java takes little time to do.

⬇️You can download Java 17.0.7 [here](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)

4a) To begin the installation process, go to the Java download page. This will take you to Oracle's website, where you can download Java from the official source. Oracle is the company that develops and maintains Java.

4b) To download the latest version of Java, go to the Java download page and look for the section labeled `Java SE 17.0.7`. Click the link labeled `Windows x64 Installer` to download the appropriate version for your PC.

4c) To install Java, simply follow the instructions in the installer by clicking `Next` a few times. Java will then install. Once the installation is complete, you can close the installer. Java is ready.

## INSTALLING FABRIC

Fabric is lightweight and is blossoming with new mods everyday. Most of us here actually use Fabric as our primary loader. Before you install Fabric, make sure to close the Minecraft Launcher. Fabric won't install if it's still open.

⬇️You can download Fabric [here](https://fabricmc.net/use/installer/)

5a) On the Fabric download page, you'll see two options: `Download for Windows` or `Download Universal Jar`. Click `Download For Windows`.

⚠️ The Windows download doesn't need Java to be installed on your system as it uses the version the launcher has. If you are experiencing issues with the Windows installer, choose the `Download Universal Jar` option and install Java if you haven't.

5b) To install Fabric, double click the installer file in your downloads folder. The Fabric installer will open and display the latest version of the loader `(0.14.21)` and Minecraft (1.20.1) by default. Make sure the option on the top left is set to `Client`, then click the 'Install' button to begin the process.

5c) After you click `Install`, Fabric will begin the installation process and create a profile in the Minecraft launcher. This will allow you to easily access and launch the Fabric version of Minecraft from within the launcher.

5d) Go back to the allocating RAM section and allocate RAM for the Fabric install instead of the Latest Version install. 

5e) After allocating RAM, launch Fabric and go if you are in the title screen, Fabric is now installed correctly.

## INSTALLING FABRIC API AND MODS

Fabric API is a library that provides essential hooks and interoperability tools for Fabric mods. It helps ensure that different mods can work together seamlessly and without issues. It's highly recommended to install this to use many mods. To begin, make sure the Minecraft Launcher is closed.

You can download Fabric API [here](https://modrinth.com/mod/fabric-api)

⚠️ We are using modrinth as our mod download site. Its clean and easy to use. In the picture below, make sure the Minecraft version matches 1.19.4. The featured versions usually have the latest builds for each version. The picture may not be up to date sometimes and the newest Fabric API will likely be a higher version. 

![image](https://github.com/NorthernMagic/Ptera-Web-Guides/assets/116324840/6e736ec4-84d4-485d-a860-a203db925167)

6a) Once you've downloaded the Fabric API for 1.20.1 .jar file, move it to your desktop for easy access.

6b) Then, open File Explorer and navigate to the `mods` folder located at `C:\Users\<user>\AppData\Roaming\.minecraft\mods.` This is where you'll install the Fabric API and any other mods you want to use. If there is no `mods` folder, create one.

6c) To install the Fabric API, simply drag the .jar file from your desktop and drop it into the `mods` folder. Once the file has been transferred, you can close File Explorer. The Fabric API is now installed! This drag and drop process works with most mods.

6d) Download the mods listed below. There are compatible with our server and improve Minecraft's performance drastically. Drag them into the `mods` folder like you did with the Fabric API.

* [Sodium](https://modrinth.com/mod/sodium)
* [Lithium](https://modrinth.com/mod/lithium)
* [Phosphor](https://modrinth.com/mod/phosphor)
* [Iris Shaders](https://modrinth.com/mod/iris)
* [FerriteCore](https://modrinth.com/mod/ferrite-core)
* [Krypton](https://modrinth.com/mod/krypton)
* [EntityCulling](https://modrinth.com/mod/entityculling)

These mods listed above help with gameplay performance. The base game of Minecraft isn't that optimized, so these mods will help increase performance. 
These mods especially give a boost to those on 'Low-End' hardware.

## (OPTIONAL) INSTALLING FERIUM 
Ferium is a simple and easy to use command line based tool to manage mods for Minecraft. Namely, keeping them up to date instantly. If you have a similar tool, feel free to ignore this section.

#### INSTALLING SCOOP AND FERIUM FOR WINDOWS
7a) Open a Windows Powershell (v5.1+) window. And run `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser`. This is to make Windows run a remote script for the first time. Feel free to copy and paste the commands in.

7b) Then run `irm get.scoop.sh | iex` to download and install Scoop.

7c) Run `scoop bucket add games` to create a games bucket for ferium. It may bring up a prompt to install git and a command to do so. Enter the git install command and try the games bucket command again.

7d) Then run `scoop install ferium` to install ferium on your device. Ferium is now installed!

#### CONFIGURING FERIUM

7e) Create a new profile by running `ferium profile create` in the powershell terminal. 

7f) Configure as follow
*  >Would you like to specify a custom mods directory? (n)
*  >What should this profile be called? `1.20.x Minecraft Mods`
*  >1.20.1
*(Use arrow keys to choose if not highlighted in blue, then press enter)*
* >Which mod loader do you use? Fabric 
*(Use arrow keys to choose if not highlighted in blue, then press enter)*


⚠️ To find a project id on Modrinth, scroll down on the left-hand sidebar containing the featured versions and technical info. Scroll until you find  `project id` below the technical info. Clicking on the id will copy and paste it to your clipboard, for easy copying into the terminal.

7g) Add mods using `ferium add <project id>`. For example, if you wanted to add Sodium to your mods profile, do `ferium add AANobbMI`.

⬇️If you are following the mods listed on this guide, here are the ids.

Fabric API - `gvQqBUqZ`
Sodium - `AANobbMI`
Lithium - `gvQqBUqZ`
Phosphor - `hEOCdOgW`
Iris Shaders - `YL57xq9U`
FerriteCore - `uXXizFIs`
LazyDFU - `hvFnDODi`
Krypton - `fQEb0iXm`
EntityCulling - `NNAgCjsB`

7h) Once finished adding the project ids into Ferium, put in `ferium upgrade` to download your mods into the mods folder. You also use this command to update your mods too. So do it every so often. It only takes a few seconds, by opening the terminal and typing this in, compared to manually looking on the mod pages themselves.

### ✅ You are done with installing mods and making updates easier! Feel free to join our server now! 

