# Introduction 

### Networks is an addon for Slimefun that aims to be a complete replacement for the slow and laggy Cargo system. This Tutorial will teach you how to use Networks, convert your existing Cargo system to Networks, some tips, and some advanced concepts.  <!-- omit in toc -->

# Table of Contents <!-- omit in toc -->

- [Introduction](#introduction)
- [Notes](#notes)
- [Blocks](#blocks)
  - [Network Controller](#network-controller)
  - [Network Bridge](#network-bridge)
  - [Network Monitor](#network-monitor)
  - [Network Pusher](#network-pusher)
  - [Network Grabber](#network-grabber)
  - [Network Importer](#network-importer)
  - [Network Exporter](#network-exporter)
  - [Network Vanilla Pusher](#network-vanilla-pusher)
  - [Network Vanilla Grabber](#network-vanilla-grabber)
  - [Network Grid](#network-grid)
  - [Network Crafting Grid](#network-crafting-grid)
  - [Quantum Storage Units](#quantum-storage-units)
- [Tools](#tools)
  - [Network Configurator](#network-configurator)
  - [Network Probe](#network-probe)
  - [Network Rakes](#network-rakes)
- [Switching from Cargo](#switching-from-cargo)
- [Single Network](#single-network)
  - [Step 1: Build your Network Hub](#step-1-build-your-network-hub)
  - [Step 2: Connect your machines](#step-2-connect-your-machines)
  - [Step 3: Connect your storage](#step-3-connect-your-storage)
- [Subnetworking](#subnetworking)

# Notes

Resource Packs used in this tutorial:
- [Slimefun Beutified](https://github.com/54M44R/Slimefun-Beautified/releases) by [54M44R](https://github.com/54M44R)
- [Vanilla Tweaks](https://vanillatweaks.net/picker/resource-packs/)

# Blocks

<img src="https://media.discordapp.net/attachments/965295564721897554/1019460528864755783/unknown.png" alt="Block header image">

<br>

## Network Controller

<img src="https://media.discordapp.net/attachments/965295564721897554/1019457108527296602/unknown.png">

The **Network Controller** does simply that, control your network! It is the core of your entire network, and you only need one per network. All other blocks will connect to this block.

## Network Bridge

<img src="https://media.discordapp.net/attachments/965295564721897554/1019457261711654912/unknown.png">

The **Network Bridge** is an extremely simple block that's used to connect your network components to your [Network Controller](#network-controller).

## Network Monitor

<img src="https://media.discordapp.net/attachments/965295564721897554/1019457332574429244/unknown.png">

The **Network Monitor** "monitors" certain storage blocks connected to it. It will allow your network to view and interact with the contents of the storage blocks.

## Network Pusher

<img src="https://media.discordapp.net/attachments/965295564721897554/1019457368813215764/unknown.png">

The **Network Pusher** will "push" items from the network into the block it's connected to. 

## Network Grabber

<img src="https://media.discordapp.net/attachments/965295564721897554/1019457416317906944/unknown.png">

The **Network Grabber** will "grab" items from the block it's connected to and put them into the network.

## Network Importer

<img src="https://media.discordapp.net/attachments/965295564721897554/1019457463453483058/unknown.png">

The **Network Importer** is a small storage container (9 slots) that will put items inside it into the network. This is very useful while you're transitioning from Cargo to Networks, as Cargo can interact with it.

## Network Exporter

<img src="https://cdn.discordapp.com/attachments/965295564721897554/1019457505228763248/unknown.png">

The **Network Exporter** will make a single item type from your network available to  the block it's connected to. This block can also interact with Cargo.

## Network Vanilla Pusher

<img src="https://cdn.discordapp.com/attachments/965295564721897554/1019457535465508914/unknown.png">

The **Network Vanilla Pusher** will push items from the network into a vanilla storage block (Chest, Barrel, etc.) that it's connected to. This block is very useful for **Chest Shops**

## Network Vanilla Grabber

<img src="https://cdn.discordapp.com/attachments/965295564721897554/1019457581032427550/unknown.png">

The **Network Vanilla Grabber** will grab items from a vanilla storage block (Chest, Barrel, etc.) that it's connected to and put them into the network. This block is very useful for **Chest Shops**

## Network Grid

@TODO

## Network Crafting Grid

@TODO

## Quantum Storage Units

<img src=https://media.discordapp.net/attachments/965295564721897554/1019685548283150387/unknown.png>

**Quantum Storage Units** are a storage block that stores a single type of item. They can be used to store items for your network, and need to be connected to a [Network Monitor](#network-monitor) to allow your network to interact with them.

Each Quantum Storage Unit is a different size, and you can use it's color to tell them apart. The colors are as follows:

- **White** - Stores `4,096` items
- **Light Gray** - Stores `32,768` items
- **Gray** - Stores `262,144` items
- **Brown** - Stores `2,097,152` items
- **Black** - Stores `16,777,216` items
- **Purple** - Stores `134,217,728` items
- **Magenta** - Stores `1,073,741,824` items
- **Red** - Stores infinite items... almost. (`2,147,483,647`)

<br>
<br>

# Tools

## Network Configurator

<img src="https://media.discordapp.net/attachments/965295564721897554/1019678675198808084/unknown.png">

The **Network Configurator** will be the most useful tool you'll use while using Networks. Crouch right click on a Node to copy it's settings, then right click on another Node to paste the settings.

## Network Probe

<img src="https://media.discordapp.net/attachments/965295564721897554/1019679295762870413/unknown.png">

The **Network Probe** will show you the size of your Network, and the amount of items in it. This is very important to have, as it will tell you if your network is over the node limit. Right click on your [Network Controller](#network-controller) to use it. It's recommended to keep it in your [Hub](#step-1-build-your-network-hub).

## Network Rakes

<img src="https://media.discordapp.net/attachments/965295564721897554/1019681355891753012/unknown.png">

**Network Rakes** are simple tools that allow you to break Nodes instantly. There are three different types of Rakes, each with different durability.

- **Network Rake (1)** - 250 uses
- **Network Rake (2)** - 1000 uses
- **Network Rake (3)** - 9999 uses
  
# Switching from Cargo

<img src="https://media.discordapp.net/attachments/965295564721897554/1019651754826149968/unknown.png">

<br>
Switching from Cargo to Networks is a pretty easy process, however there are some difficulties that you may encounter. This guide will teach you how to convert your existing Cargo system to Networks, and some tips to make the process easier.

<br>

## Warning <!-- omit in toc -->

**If your network is larger than `2000` nodes, you need to subnetwork. Use the [Subnetworking Guide](#subnetworking) below.  It is highly recommended to do subnetworking anyway as it will allow you to expand your network if your network goes above the `2000` node limit.**

# Single Network

This guide is to build a single network (under `2000` nodes). This network will be more difficult to expand, but it will be easier to build at the start.
## Step 1: Build your Network Hub

<img src="https://media.discordapp.net/attachments/965295564721897554/1019673045507506266/unknown.png">

<br>

Your Network Hub is the main place that you will be interacting with your network. Include workbenches and other utilities that you use often nearby to speed up crafting, close to your [Network Controller](#network-controller). Also, keep a chest nearby to store your network tools, like a [Network Probe](#network-probe), [Network Configurator](#network-configurator), and [Network Rake](#network-rakes).

<br>

<img src="https://media.discordapp.net/attachments/965295564721897554/1019672926473162854/unknown.png">
<br>

## Step 2: Connect your machines

<br>
<img src="https://media.discordapp.net/attachments/965295564721897554/1019674354277154866/unknown.png">
<br>

Use [Network Bridges](#network-bridge) to conect groups of machines to your [Network Hub](#step-1-build-your-network-hub). Keep in mind that each [Network Bridge](#network-bridge) counts as a node, so don't make your connections too long or complex.

## Step 3: Connect your storage

<img src="https://media.discordapp.net/attachments/965295564721897554/1019700875771510926/unknown.png?width=879&height=666">



<br>
<br>

# Subnetworking