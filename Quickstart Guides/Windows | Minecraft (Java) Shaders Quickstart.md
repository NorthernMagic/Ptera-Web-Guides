---
Title: Shaders Quickstart Guide
Description: A guide designed to get you started with Minecraft shaders!
Last Edit: 2/19/2023
---

## 📖 Table Of Contents

* [Setting Up Iris (Recommended)](#setting-up-iris-recommended)
  * [Iris Install Method 1](#iris-install-method-1)
  * [Allocating RAM To Iris](#allocating-ram-to-iris)
* [Iris Install Method 2](#iris-install-method-2)
  * [(Recommended) Download Java JDK](#recommended-download-java-jdk)
  * [Installing Fabric](#installing-fabric)
  * [Installing Fabric API And Mods](#installing-fabric-api-and-mods)
  * [Allocating RAM To Fabric](#allocating-ram-to-fabric)
* [Setting Up Optifine](#setting-up-optifine)
  * [Allocating RAM To Optifine](#allocating-ram-to-optifine)
* [Installing Shaders](#installing-shaders)
  * [Amazing Shaders To Try Out](#amazing-shaders-to-try-out)
  * [Amazing Resourcepacks To Try Out](#amazing-resourcepacks-to-try-out)

## SETTING UP IRIS (RECOMMENDED)

Here at the Fluffy Wing Fam HQ we recommend using Iris, as it's highly configurable and very performant.
If you followed the Windows Quickstart Guide, you likely already installed Iris onto your PC.
But if you didn't, don't worry as installing Iris is easy and effortless.

### IRIS INSTALL METHOD 1

This method is super easy for beginners, just a few clicks and Iris is installed onto your PC, no fuss!
But a drawback of this method is less performance. Thus is the cost of ease of use.

⬇️You can download Iris [here](https://irisshaders.net/download)

1a) Go to the download page above to download Iris. Click `Download Universal Jar` to download the Iris installer.

1b) In the installer make sure `Select Game Version:` is set to `1.19.3`, `Installation Type:` to `Iris Install`, and `Installation Directory` to `.minecraft`.

1c) Click `Install`, Iris will create a profile inside the Minecraft Launcher.

#### ALLOCATING RAM TO IRIS

We recommend allocating more RAM to your Sodium + Iris installation to maximize performance.

2a) In the main page of the launcher, click the `Installations` tab at the top. While here make sure `Modded` and `Snapshots` are checkmarked alongside `Latest Version` if they aren't.

2b) Click on the version you want to allocate RAM to. In this case click the `Iris & Sodium for 1.19.3` version and click `Edit`.

2c) In the installation editor, click `More Options`. In the `JVM Arguments` box, you will see a `-Xmx2G -XX` followed by a chain of text. 

⚠️ Make sure you know how much RAM you have on your PC! You can look it up in the Windows Settings by typing `About PC` and looking it up.

Allocating more than half of it is generally a bad idea. So for example if you have a PC with 8GB, allocate up to 4GB. If you have a higher RAM count, such as 16GB or 32GB, allocating more than 8GB to Minecraft usually yields diminishing returns.

2d) Once comfortable with allocating the amount of RAM you want, change the number between the x and the G to it. Click `Save` and Go to the `Play` tab. 

✅ Iris is now installed! Skip to [Installing Shaders](#installing-shaders) to install your shaders!

### IRIS INSTALL METHOD 2

We recommend this method over the first one because it grants the best performance and configurability. 

#### (RECOMMENDED) DOWNLOAD JAVA JDK

Minecraft comes with its own standalone version of Java pre-installed. But I recommend installing it anyway as it doesn't hurt and some mod loaders need Java installed. Installing Java takes little time to do.

⬇️You can download Java 17.0.6 [here](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)

3a) To begin the installation process, go to the Java download page. This will take you to Oracle's website, where you can download Java from the official source. Oracle is the company that develops and maintains Java.

3b) To download the latest version of Java, go to the Java download page and look for the section labeled `Java SE 17.0.6`. Click the link labeled `Windows x64 Installer` to download the appropriate version for your PC.

3c) To install Java, simply follow the instructions in the installer by clicking `Next` a few times. Java will then install. Once the installation is complete, you can close the installer. Java is ready.

#### INSTALLING FABRIC

Fabric is lightweight and is blossoming with new mods everyday. This section uses Fabric for Iris and actually most of us here actually use Fabric as our primary loader too! Before you install Fabric, make sure to close the Minecraft Launcher. Fabric won't install if it's still open.

⬇️You can download Fabric [here](https://fabricmc.net/use/installer/)

4a) On the Fabric download page, you'll see two options: `Download for Windows` or `Download Universal Jar`. Click `Download For Windows`.

⚠️ The Windows download doesn't need Java to be installed on your system as it uses the version the launcher has. If you are experiencing issues with the Windows installer, choose the `Download Universal Jar` option and install Java if you haven't.

4b) To install Fabric, double click the installer file in your downloads folder. The Fabric installer will open and display the latest version of the loader `(0.14.14)` and Minecraft (1.19.3) by default. Make sure the option on the top left is set to `Client`, then click the 'Install' button to begin the process.

4c) After you click `Install`, Fabric will begin the installation process and create a profile in the Minecraft launcher. This will allow you to easily access and launch the Fabric version of Minecraft from within the launcher.

4d) Go back to the allocating RAM section and allocate RAM for the Fabric install instead of the Latest Version install. 

4e) After allocating RAM, launch Fabric and go if you are in the title screen, Fabric is now installed correctly.

#### INSTALLING FABRIC API AND MODS

Fabric API is a library that provides essential hooks and interoperability tools for Fabric mods. It helps ensure that different mods can work together seamlessly and without issues. It's highly recommended to install this to use many mods. To begin, make sure the Minecraft Launcher is closed.

You can download Fabric API [here](https://modrinth.com/mod/fabric-api)

⚠️ We are using modrinth as our mod download site. Its clean and easy to use. In the picture below, make sure the Minecraft version matches 1.19.3. The featured versions usually have the latest builds for each version.

![image](https://user-images.githubusercontent.com/116324840/219203266-344f8658-c7f0-4f48-a61e-dcb60388c857.png)


5a) Once you've downloaded the Fabric API `(0.73.4)` for 1.19.3 .jar file, move it to your desktop for easy access.

5b) Then, open File Explorer and navigate to the `mods` folder located at `C:\Users\<user>\AppData\Roaming\.minecraft\mods.` This is where you'll install the Fabric API and any other mods you want to use. If there is no `mods` folder, create one.

5c) To install the Fabric API, simply drag the .jar file from your desktop and drop it into the `mods` folder. Once the file has been transferred, you can close File Explorer. The Fabric API is now installed! This drag and drop process works with most mods.

5d) Download the mods listed below. There are compatible with our server and improve Minecraft's performance drastically. Drag them into the `mods` folder like you did with the Fabric API.

* [Sodium](https://modrinth.com/mod/sodium)
* [Lithium](https://modrinth.com/mod/lithium)
* [Phosphor](https://modrinth.com/mod/phosphor)
* [Iris Shaders](https://modrinth.com/mod/iris)
* [FerriteCore](https://modrinth.com/mod/ferrite-core)
* [LazyDFU](https://modrinth.com/mod/lazydfu)

These mods listed above help with gameplay performance. The base game of Minecraft isn't that optimized, so these mods will help increase performance. 
These mods especially give a boost to those on 'Low-End' hardware.

#### ALLOCATING RAM TO FABRIC

We recommend allocating more RAM to your custom Iris installation to maximize performance.

6a) In the main page of the launcher, click the `Installations` tab at the top. While here make sure `Modded` and `Snapshots` are checkmarked alongside `Latest Version` if they aren't.

6b) Click on the version you want to allocate RAM to. In this case click the `Fabric` version and click `Edit`.

6c) In the installation editor, click `More Options`. In the `JVM Arguments` box, you will see a `-Xmx2G -XX` followed by a chain of text. 

⚠️ Make sure you know how much RAM you have on your PC! You can look it up in the Windows Settings by typing `About PC` and looking it up.

Allocating more than half of it is generally a bad idea. So for example if you have a PC with 8GB, allocate up to 4GB. If you have a higher RAM count, such as 16GB or 32GB, allocating more than 8GB to Minecraft usually yields diminishing returns.

6d) Once comfortable with allocating the amount of RAM you want, change the number between the x and the G to it. Click `Save` and Go to the `Play` tab.

✅ Iris and the mods are now installed! Skip to [Installing Shaders](#installing-shaders) to install your shaders!


## SETTING UP OPTIFINE

Optifine has the best shader compatibility out of the 2 shader mods, though Iris is improving quite rapidly in that regard. If you just want a shader mod with the whole kitchen sink, then Optifine is your best bet!

### INSTALLING OPTIFINE

⬇️You can download Optifine [here](https://optifine.net/downloads)

1a) Go to the Optifine download link posted above. 

⚠️ Depending on how recent the latest version of Minecraft is, there might be a preview version of Optifine. If there is now Optifine version, mainline or preview, just install Iris for now.

1b) Once you found the Optifine download for `1.19.3`, click `Mirror` to download it without ads. 

1c) In the Optifine Installer, make sure it matches `1.19.3` and if it does, click `Install`. Optifine will now install onto your PC and create a profile in the Minecraft Launcher.

#### ALLOCATING RAM TO OPTIFINE

We recommend allocating more RAM to your Optifine installation to maximize performance.

2a) In the main page of the launcher, click the `Installations` tab at the top. While here make sure `Modded` and `Snapshots` are checkmarked alongside `Latest Version` if they aren't.

2b) Click on the version you want to allocate RAM to. In this case click the `Optifine` version and click `Edit`.

2c) In the installation editor, click `More Options`. In the `JVM Arguments` box, you will see a `-Xmx2G -XX` followed by a chain of text. 

⚠️ Make sure you know how much RAM you have on your PC! You can look it up in the Windows Settings by typing `About PC` and looking it up.

Allocating more than half of it is generally a bad idea. So for example if you have a PC with 8GB, allocate up to 4GB. If you have a higher RAM count, such as 16GB or 32GB, allocating more than 8GB to Minecraft usually yields diminishing returns.

2d) Once comfortable with allocating the amount of RAM you want, change the number between the x and the G to it. Click `Save` and Go to the `Play` tab.

✅ Optifine is now installed! Skip to [Installing Shaders](#installing-shaders) to install your shaders!

## INSTALLING SHADERS 

Time to install the glorious stuff we want. The eye candy shaders! Installing shaders are easy to do and only take a few minutes to set up!

1a) Regardless of however you installed Iris or Optifine, launch the installation. This is to create a `shaderpacks` folder.

1b) Close the game and Launcher. Head on over to `C:\Users\<user>\AppData\Roaming\.minecraft` and locate the folder called `shaderpacks`. 
If there is no `shaderpacks` folder, then create one.

1c) Minimize the file explorer window.

1d) Lets practice installing shaders.

⬇️ Download Complementary Shaders v4 [here](https://www.complementary.dev/shaders-v4/)

1e) Click the download for Complementary Shaders v4, an amazing all around shader many of us use. Download the zip file and put it into the `shaderpacks` folder.
The shader is now installed! Then close file explorer.

⚠️ Some shaders may require you to extract certain contents from the zip folders they are downloaded in. But for most, just drag and drop the freshly download zip folder into the `shaderpacks` folder.

✅ You are done installing shaders! Good Job! 

#### AMAZING SHADERS TO TRY OUT

[SEUS Renewed](https://www.sonicether.com/seus/)

[SEUS HRR 2.1](https://www.patreon.com/posts/45141775)

[Sildurs Vibrant Shaders](https://www.curseforge.com/minecraft/customization/sildurs-vibrant-shaders)

[Sildurs Enhanced Default](https://www.curseforge.com/minecraft/customization/sildurs-enhanced-default)

[Make Up UltraFast](https://www.curseforge.com/minecraft/customization/makeup-ultra-fast-shader)

[SDV Shaders](https://www.curseforge.com/minecraft/customization/super-duper-vanilla-shaders)

[BSL](https://www.curseforge.com/minecraft/customization/bsl-shaders)

#### AMAZING RESOURCEPACKS TO TRY OUT

These resourcepacks will quite literally make your world POP! Use shaders with these for a more immersive experience!

[Vanilla PBR](https://www.curseforge.com/minecraft/texture-packs/vanilla-pbr)

[Another Vanilla PBR](https://www.curseforge.com/minecraft/texture-packs/avpbr)


