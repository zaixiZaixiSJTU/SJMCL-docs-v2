# Beginner Guide

This guide is intended for **new players or users who are using a Minecraft launcher for the first time**.
Its goal is to help you quickly get started with the **SJMCL Launcher** and Minecraft in the simplest way possible.

If you want to **start playing as soon as possible**, we recommend reading:

* [How to Log In to an Account](#how-to-log-in-to-an-account)
* [How to Download the Game](#how-to-download-the-game)

If you want to learn more about a specific topic, you can follow the links provided in this document.

## How to Log In to an Account

To play Minecraft, you need a **Microsoft account** that owns the game, or you can use an **offline account / external authentication account**.

You can purchase the game from the [Minecraft Official Website](https://www.minecraft.net/) or the [Xbox Store](https://www.xbox.com/).

After purchasing the game, click **Accounts** at the top of **SJMCL**, then click **Add Profile** in the upper-right corner.
You can create an **Offline Profile**, or log in with a **Microsoft Account** or **Third-party Authentication Account**.

You can also [import accounts]() from other launchers.

## How to Download the Game

Downloading Minecraft with **SJMCL** is very simple and only requires a few steps.

If you **have not installed any game versions yet**, follow these steps:

1. On the launcher interface, click **Instances** at the top to enter the instance management page.
   ![Launcher Interface](/images/beginners-guide-launch.png)

2. Click the **Add & Import** button in the lower-left corner.
   ![Instances Page](/images/beginners-guide-games.png)

3. In the popup window, select the **Install New Instance** tab.
   ![Add & Import Page](/images/beginners-guide-add-and-import.png)

Here you will see a list of all available Minecraft versions (usually **sorted from newest to oldest**).
Choose a version you want to play. We generally recommend installing the **latest stable release**, then click **Next**.

![Select Game Version](/images/beginners-guide-game-client.png)

Next, you will see the **Mod Loader selection page**.
Here you can install mod loaders such as **Forge** or **Fabric**.

![Select Mod Loader](/images/beginners-guide-game-loader.png)

> [!TIP]
> If you only want to play **vanilla Minecraft**, you can simply click **Next** to skip this step.

> [!TIP]
> What is a mod loader? Which one should I choose?
> See: [Installing Mod Loaders]()

After that, you will enter the **Instance Settings page**.

Here you can configure:

* Instance name
* Instance description
* Instance icon
* Game storage location

![Instance Settings](/images/beginners-guide-basic-settings.png)

After finishing the settings, click the **Finish** button in the lower-right corner.
The launcher will automatically switch to the download page and begin downloading the selected game version.

Once the download is complete:

1. Click **Launch** at the top to return to the launch page
2. Click **Launch Game** in the lower-right corner

Now you can enter Minecraft and start your adventure!

## What Is Minecraft Gameplay

While waiting for the game to download, you might want to learn about its core gameplay.

As a sandbox game, the core gameplay of Minecraft is **“breaking” and “building.”**
You can freely explore the world, gather resources, build structures, and fight monsters.

If you are new to the game, the following resources are recommended:

* [Minecraft Wiki Tutorials](https://zh.minecraft.wiki/w/%E6%95%99%E7%A8%8B)
* [Your First Day Guide](https://zh.minecraft.wiki/w/Tutorial:%E7%AC%AC%E4%B8%80%E5%A4%A9)

## What Is a Resource Pack

You may have heard other players talking about good-looking **“texture packs.”**

A **texture pack** usually refers to a **resource pack that modifies game textures**, and it was the name used before Minecraft **1.5 and earlier versions**.

The terms “texture” and “texture pack” were early translations. Today, the more accurate terms are **texture** and **resource pack**. When players mention texture packs, they usually mean the **texture component of a resource pack**.

A **Resource Pack** is a type of file that can modify various game resources.
It can change many aspects of the game, including:

* Textures
* Models
* Music
* Sound effects
* Language files
* User interface

By installing resource packs, you can change the visual and audio experience of Minecraft. A well-designed resource pack can even give the game a completely different style.

### How to Use Resource Packs

See: [Resource Pack Loading Tutorial](https://zh.minecraft.wiki/w/Tutorial:%E5%8A%A0%E8%BD%BD%E8%B5%84%E6%BA%90%E5%8C%85)

### Want to Create Your Own Resource Pack

Learn more:
[Resource Pack Documentation](https://zh.minecraft.wiki/w/%E8%B5%84%E6%BA%90%E5%8C%85)

### Where to Get Resource Packs

You can find resource packs on the following websites:

* [CurseForge](https://www.curseforge.com/minecraft/search?page=1&pageSize=20&sortBy=relevancy&class=texture-packs)
* [Modrinth](https://modrinth.com/discover/resourcepacks)

### Related Tutorial

* [How to Install Resource Packs]()

## What Is a Mod

You may have heard that Minecraft has a rich ecosystem of **mods (modifications)**.

Mods are tools that **modify or expand the game's content**, allowing you to add new blocks, creatures, items, and gameplay mechanics.

By installing mods, you can greatly expand the game's content, improve gameplay convenience, and even transform Minecraft into a completely different experience.

### Where to Get Mods

You can obtain mod information from the following websites and install them using **SJMCL**:

* [MC百科](https://www.mcmod.cn/)
* [CurseForge](https://www.curseforge.com/minecraft)
* [Modrinth](https://modrinth.com/)

### Related Tutorial

* [SJMCL Automatic Mod Installation Guide]()

## What to Do If the Game Crashes After Installing Mods

Game crashes after installing mods are relatively common.

Common causes include:

* Mod version incompatibility
* Missing dependency mods
* Conflicts between mods

Possible solutions include:

1. Check whether the mod version matches the Minecraft version
2. Make sure all required dependency mods are installed
3. Remove recently installed mods

More troubleshooting methods:

* [Mod Crash Troubleshooting Guide]()

## How to Choose the Java Version

**SJMCL** automatically manages Java and selects the appropriate Java version for different Minecraft versions.

When launching the game, if no suitable Java installation is detected, the launcher will prompt you to download the required Java version. Simply click **Download** to install it automatically. For most users, **the default settings are sufficient**.

If you need to manually install or specify a Java version, follow the steps below.

### Installing Java

1. Go to **Settings → Java**, where you will see Java versions installed by the launcher or detected on your system.

2. To download a new Java version, click **Download Java**, select the required version, and click **Confirm**.

3. If Java is already installed on your system but not detected, click **Add Java** and select the Java executable file from the Java installation directory:

   * Windows: `java.exe`
   * Linux / macOS: `java`

After adding it, the Java installation will appear in the Java list.

### Selecting Java

You can either use the same Java for all instances or specify a Java version for a specific instance.

**Set Java for all instances**

Go to **Settings → Global Game Settings**.
By default, the launcher **automatically selects an appropriate Java version**. If necessary, you can disable this option and manually choose one.

This Java version will be used by all instances that use global settings (generally not recommended for beginners).

**Set Java for a single instance**

1. Open the **Instances** page
2. Enter the **Settings** of the instance
3. Enable **Instance-specific settings**
4. Select the desired **Java version**

This Java version will only be used when launching that specific instance.

> [!WARNING]
> If the game crashes or fails to launch after changing the Java version, switch back to the launcher’s automatically selected default Java version immediately.
