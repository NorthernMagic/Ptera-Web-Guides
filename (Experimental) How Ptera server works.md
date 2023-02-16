---
Title: How the Ptera server works
Description: A guide explaining how our server works.
Last Edit: 2/16/2022
---

## 📖 Table Of Contents

* [Minecraft Version](#minecraft-version)
* [Server "Base"](#server-base)
* [Mods We Use]()
  * [Fabric API](#fabric-api)
  * [Fabric Language Kotlin](#fabric-language-kotlin)
  * [Lithium](#lithium)
  * [Geyser](#geyser)
  * [Floodgate](#floodgate) 
  * [FerriteCore](#ferritecore)
  * [Ledger](#ledger)
  * [No Chat Reports](#no-chat-reports)
  * [World Edit](#world-edit)
  * [Falling Tree](#falling-tree)
  * [Terralith](#terralith)

## Minecraft Version
Our server is always based off the latest version of Minecraft.
Right now it's currently `1.19.3`. Historically it takes around 2
weeks to for everything to be updated.

## Server "Base"

The server is currently using Fabric as the "base" of it.
This is different than Paper or Spigot. As we use mods instead of plugins.

## Mods We Use

#### Fabric API

Fabric API is the library for essential hooks 
and interoperability mechanisms for Fabric mods. 

* [Fabric API Download & Documentation](https://modrinth.com/mod/fabric-api)

#### Fabric Language Kotlin

This is a mod that enables usage of the Kotlin programming language for Fabric mods.

[Fabric Language kotlin Download & Documentation](https://modrinth.com/mod/fabric-language-kotlin)

#### Lithium

Lithium is a modern, general-purpose optimization mod 
for Minecraft which works to improve a 
number of systems (game physics, mob AI, block ticking, etc) 
with the goal of not changing any vanilla mechanics.

* [Lithium Download & Documentation](https://modrinth.com/mod/lithium)

#### Geyser

Geyser is a middleware, 
which translates all the incoming and
outgoing packets (pieces of data your client and server
send between each other to maintain good networking).

* [Geyser Download & Documentation](https://wiki.geysermc.org/geyser/using-geyser-with-consoles/)

#### Floodgate

Floodgate is a hybrid mode plugin that allows Minecraft: Bedrock Accounts to join Minecraft: Java Edition servers without needing a 
Minecraft: Java Edition account. 
This is something you install in addition to Geyser.

* [Floodgate Download & Documentation](https://github.com/GeyserMC/Floodgate)

#### FerriteCore

This mod reduces the memory usage of Minecraft 
in a few different ways.

* [FerriteCore Download & Documentation](https://modrinth.com/mod/ferrite-core)

#### Ledger

Ledger is a server-side logging mod for Minecraft 1.19.x. 
Ledger has been written from scratch to solve the main issues of 
DeltaLogger and other logging mods. 
This allows it to log much more and 
it's much easier to add new, easy to use features.

* [Ledger Download & Documentation](https://modrinth.com/mod/ledger)



#### No Chat Reports

This mod strips cryptographic signatures that since 1.19 are 
attached to every message sent in the chat. Removing them 
makes it impossible to track and associate your chat 
messages with your Minecraft and, 
by extension, Microsoft account.

* [No Chat Reports Download & Documentation](https://modrinth.com/mod/no-chat-reports)

#### World Edit

A Minecraft Map Editor... that runs in-game!
With selections, schematics, copy and paste, 
brushes, and scripting.

* [World Edit Download & Documentation](https://www.curseforge.com/minecraft/mc-mods/worldedit)

#### Falling Tree 

Break down your 
trees by only cutting one piece of it.
All works on the server side!

* [Falling Tree Download & Documentation](https://modrinth.com/mod/fallingtree)

#### Terralith

Terralith adds over 95 brand new biomes, 
as well as updating almost every vanilla 
biome with new and improved features.

* [Terralith Download & Documentation](https://modrinth.com/mod/terralith)





