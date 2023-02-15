---
Title: Windows 10/11 Quickstart Guide
Description: A guide designed to get Minecraft set up and optimized for our server.
---

## 📖TABLE OF CONTENTS

* [Buying and Installing Minecraft](#buying-and-installing-minecraft)
* [Allocating Memory/RAM](#allocating-memory-to-minecraft)
* [Joining The Server](#joining-the-server)
* [(Recommended) Installing Java JDK](#recommended-download-java-jdk)
* [Installing Fabric](#installing-fabric)
* [Installing Fabric API and Mods](#installing-fabric-api-and-mods)
* [(Optional) Installing Ferium](#optional-installing-ferium)


## BUYING AND INSTALLING MINECRAFT

If you don't have Minecraft at all, you need to install it. Before, you had to choose between Java (Recommended) and Bedrock Edition. Thankfully you can buy both versions for $30 USD. But we still recommend using the Java Edition when logging into the server, as it's natively supported.

1a) To buy Minecraft for Windows click this [link](https://www.minecraft.net/en-us/store/minecraft-java-bedrock-edition-pc).

1b) Register your payment information (credit card). Once filled out, and bought, click 'Download for Windows'. The Minecraft Launcher will download onto your Windows PC.

1c) Sign into the launcher with your Microsoft account. Make sure the version drop-down to the left is selected to 'Latest Version'. 

1d) Click 'Play', the launcher will download the game files to your device and launch into the title screen. Once launched into the title screen, close the game by pressing 'Quit'. 

## ALLOCATING MEMORY TO MINECRAFT 

This section will be referenced multiple times. If you are seeing this section for the first time, we will be increasing the amount of RAM or memory to increase Minecraft's performance.  

2a) In the main page of the launcher, click the 'Installations' tab at the top. While here make sure 'Modded' and 'Snapshots' are checkmarked if they aren't.

2b) Click on the version you want to allocate RAM to. If this is the first time, select the 3 little vertical dots on the 'Latest Release' version and click 'Edit'.

2c) In the installation editor, click 'More Options'. In the 'JVM Arguments' box, you will see a -Xmx2G -XX followed by a chain of text. 

⚠️ Make sure you know how much RAM you have on your PC! You can look it up in the Windows Settings by typing 'About PC' and looking it up.

Allocating more than half of it is generally a bad idea. So for example if you have a PC with 8GB, allocate up to 4GB. If you have a higher RAM count, such as 16GB or 32GB, allocating more than 8GB to Minecraft usually yields diminishing returns.

2d) Once comfortable with allocating the amount of RAM you want, change the number between the x and the G to it. Click 'Save' and Go to the 'Play' tab. 

## JOINING THE SERVER

Time to join the server! This is pretty easy and seamless

3a) Launch Minecraft and go to the 'Multiplayer' Tab in the title screen.

3b) Click 'Add Server' and in the 'Server Name' field, type in 'Ptera's Forest'. 

3c) In the 'Server Address' field, type in the IP address of our server. **play.ptera.tv**

3d) Click done and the server should be saved to your server list. Fill out this Google form and DM Ptera or a moderator about you filling it out to ensure you get added.

3e) Once you are added to the server join it in the server list by hovering over the server picture and clicking the gray 'Play Button'. You should be able to join and will be at spawn. 

⚠️ If you get an error saying you aren't on the whitelist, DM a moderator and they will get things sorted out. Try to rejoin after that.

### ✅ You have everything needed to join our server. We highly recommend installing some mods to improve Minecraft's performance. You can end here, but follow sections 4+ to install mods if you'd like.



## (RECOMMENDED) DOWNLOAD JAVA JDK

Minecraft comes with its own standalone version of Java pre-installed. But I recommend installing it anyway as it doesn't hurt and some mod loaders need Java installed. Installing Java takes little time to do.

⬇️You can download Java 17.0.6 [here](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)

4a) To begin the installation process, go to the Java download page. This will take you to Oracle's website, where you can download Java from the official source. Oracle is the company that develops and maintains Java.

4b) To download the latest version of Java, go to the Java download page and look for the section labeled 'Java SE 17.0.6'. Click the link labeled 'Windows x64 Installer' to download the appropriate version for your PC.

4c) To install Java, simply follow the instructions in the installer by clicking "Next" a few times. Java will then install. Once the installation is complete, you can close the installer. Java is ready.

## INSTALLING FABRIC

Fabric is lightweight and is blossoming with new mods everyday. Most of us here actually use Fabric as our primary loader. Before you install Fabric, make sure to close the Minecraft Launcher. Fabric won't install if it's still open.

⬇️You can download Fabric [here](https://fabricmc.net/use/installer/)

5a) On the Fabric download page, you'll see two options: 'Download for Windows' or ' Download Universal Jar'. Click 'Download For Windows'.

⚠️ The Windows download doesn't need Java to be installed on your system as it uses the version the launcher has. If you are experiencing issues with the Windows installer, choose the 'Download Universal Jar' option and install Java if you haven't.

5b) To install Fabric, double click the installer file in your downloads folder. The Fabric installer will open and display the latest version of the loader (0.14.14) and Minecraft (1.19.3) by default. Make sure the option on the top left is set to 'Client', then click the 'Install' button to begin the process.

5c) After you click 'Install', Fabric will begin the installation process and create a profile in the Minecraft launcher. This will allow you to easily access and launch the Fabric version of Minecraft from within the launcher.

5d) Go back to the allocating RAM section and allocate RAM for the Fabric install instead of the Latest Version install. 

5e) After allocating RAM, launch Fabric and go if you are in the title screen, Fabric is now installed correctly.

## INSTALLING FABRIC API AND MODS

Fabric API is a library that provides essential hooks and interoperability tools for Fabric mods. It helps ensure that different mods can work together seamlessly and without issues. It's highly recommended to install this to use many mods. To begin, make sure the Minecraft Launcher is closed.

You can download Fabric API [here](https://modrinth.com/mod/fabric-api)

⚠️ We are using modrinth as our mod download site. Its clean and easy to use. In the picture below, make sure the Minecraft version matches 1.19.3. The featured versions usually have the latest builds for each version.

![image](https://user-images.githubusercontent.com/116324840/219203266-344f8658-c7f0-4f48-a61e-dcb60388c857.png)


6a) Once you've downloaded the Fabric API **(0.73.4)** for 1.19.3 .jar file, move it to your desktop for easy access.

6b) Then, open File Explorer and navigate to the 'mods' folder located at **C:\Users\<user>\AppData\Roaming\.minecraft\mods.** This is where you'll install the Fabric API and any other mods you want to use. If there is no 'mods' folder, create one.

6c) To install the Fabric API, simply drag the .jar file from your desktop and drop it into the 'mods' folder. Once the file has been transferred, you can close File Explorer. The Fabric API is now installed! This drag and drop process works with most mods.

6d) Download the mods listed below. There are compatible with our server and improve Minecraft's performance drastically. Drag them into the 'mods' folder like you did with the Fabric API.

* [Sodium](https://modrinth.com/mod/sodium)
* [Lithium](https://modrinth.com/mod/lithium)
* [Phosphor](https://modrinth.com/mod/phosphor)
* [Iris Shaders](https://modrinth.com/mod/iris)
* [FerriteCore](https://modrinth.com/mod/ferrite-core)
* [LazyDFU](https://modrinth.com/mod/lazydfu)

These mods listed above help with gameplay performance. The base game of Minecraft isn't that optimized, so these mods will help increase performance. 
These mods especially give a boost to those on 'Low-End' hardware.

## (OPTIONAL) INSTALLING FERIUM


