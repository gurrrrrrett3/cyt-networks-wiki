## Networks

### Networks is an addon for Slimefun that aims to be a complete replacement for the slow and laggy Cargo system. This Tutorial will teach you how to use Networks, convert your existing Cargo system to Networks, some tips, and some advanced concepts. 

# Blocks

<img src="https://media.discordapp.net/attachments/965295564721897554/1019460528864755783/unknown.png" alt="Block header image">

<br>

## Network Controller

<img src="https://media.discordapp.net/attachments/965295564721897554/1019457108527296602/unknown.png">

The **Network Manager** does simply that, Manage your network! It is the core of your entire network, and you only need one per network. All other blocks will connect to this block.

## Network Bridge

<img src="https://media.discordapp.net/attachments/965295564721897554/1019457261711654912/unknown.png">

The **Network Bridge** is an extremely simple block that's used to connect your network components together, and to your [Network Controller](#network-controller).

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

The **Network Importer** is a small storage container (9 slots) that will put items inside it into it into the network. This is very useful while you're transitioning from Cargo to Networks, as Cargo can interact with it.

## Network Exporter

<img src="https://cdn.discordapp.com/attachments/965295564721897554/1019457505228763248/unknown.png">

The **Network Exporter** will make a single item type from your network available to  the block it's connected to. This block can also interact with Cargo.

## Network Vanilla Pusher

<img src="https://cdn.discordapp.com/attachments/965295564721897554/1019457535465508914/unknown.png">

The **Network Vanilla Pusher** will push items from the network into a vanilla stoage block (Chest, Barrel, etc.) that it's connected to. This block is very useful for **Chest Shops**

## Network Vanilla Grabber

<img src="https://cdn.discordapp.com/attachments/965295564721897554/1019457581032427550/unknown.png">

The **Network Vanilla Grabber** will grab items from a vanilla storage block (Chest, Barrel, etc.) that it's connected to and put them into the network. This block is very useful for **Chest Shops**

<br>
<br>

# Switching from Cargo

<img src="https://media.discordapp.net/attachments/965295564721897554/1019651754826149968/unknown.png">

<br>
Switching from Cargo to Networks is a pretty easy process, however there are some difficulties that you may encounter. This guide will teach you how to convert your existing Cargo system to Networks, and some tips to make the process easier.

<br>

## Warning

**If your network is larger than `2000` nodes, you need to subnetwork. Use the [Subnetworking Guide](#subnetworking) below.  I highly reccomend doing subnetworking anyway as it will allow you to expand your network if your network goes above the `2000` node limit.**

# Single Network

This guide is to build a single network (under `2000` nodes). This network will be more difficult to expand, but it will be easier to build at the start.
## Step 1: Build your Network Hub

<img src="https://media.discordapp.net/attachments/965295564721897554/1019673045507506266/unknown.png?width=863&height=666">

<br>
Your Network Hub is the main place that you will be interacting with your network. I like to include workbenches and other utilities that I often use nearby to speed up crafting, close to my [Network Controller](#network-controller).

<br>

<img src="https://media.discordapp.net/attachments/965295564721897554/1019672926473162854/unknown.png?width=863&height=666">

## Step 2: Connect your machines

<br>
<img src="https://media.discordapp.net/attachments/965295564721897554/1019674354277154866/unknown.png?width=863&height=666">

Use 



<br>
<br>

# Subnetworking