<!--
  Title: EaglercraftX-1.19-Server
  Description: A 1.19 Eaglercraft / EaglercraftX server project!
  Author: CaenJones
  -->
<meta name='eaglercraft, eaglercraftx, eagler, eaglercraftx server, eaglercraft server' content='HTML, JavaScript, Shell, Batchfile'>

# EaglercraftX 1.19 Server (Reborn)



[Demo Video](https://github.com/CaenJones/EaglercraftX-1.19-Server/assets/131218155/0ee532ab-46d3-4959-ac9a-860931ffd649)

<p align="center">
 <a href="https://github.com/iddu0/EaglercraftX-1.19-Server-Reborn/blob/main/install.sh">
    <img src="https://github.com/iddu0/iddu0.github.io/blob/3be29f9189f50ee0bd5d7f4e89fc36c3d575ff5f/files/Photos/Misc/EaglerCraft-Server_Download_for_Linux-removebg-preview.png" alt="Description here" width="200" height="59">
 </a>
 <a href="https://github.com/iddu0/EaglercraftX-1.19-Server-Reborn/blob/main/install.sh">
    <img src="https://github.com/iddu0/iddu0.github.io/blob/3be29f9189f50ee0bd5d7f4e89fc36c3d575ff5f/files/Photos/Misc/EaglerCraft-Server_Download_for_macOS-removebg-preview.png" alt="Description here" width="200" height="59">
 </a>
 <a href="https://github.com/iddu0/EaglercraftX-1.19-Server-Reborn/blob/main/install.bat">
    <img src="https://github.com/iddu0/iddu0.github.io/blob/3be29f9189f50ee0bd5d7f4e89fc36c3d575ff5f/files/Photos/Misc/EaglerCraft-Server_Download_for_Windows-removebg-preview.png" alt="Description here" width="200" height="59">
 </a>
</p>

## Overview
Hello! The EaglercraftX 1.19 server project is an enhanced version of CaenJones's Eaglercraft server which incorporates items, mobs, structures, and other properties from Minecraft 1.19. Please note that some mobs and textures may be missing (eg: Drowned texture).
<br><br>
This new version of CaenJones's server is maintained, has a discussions tab, and has a wiki!
<br><br>
If you like this project and want to support it, please consider making a fork or giving it a :star:!

## Requirements 
- **Minimum:** 2 Core CPU, 2GB RAM, and 5GB storage space.
- **Recommended:** 8GB DDR4 RAM, 4-core x64 CPU, over 20GB free storage, and network speeds of 750 MBPS - 1 GBPS or higher for optimal performance.

## Updating Existing Servers
1. Clone the server repository: `git clone https://github.com/iddu0/EaglercraftX-1.19-Server-Reborn`
2. Use cURL for Windows: `curl -O https://github.com/iddu0/EaglercraftX-1.19-Server-Reborn/archive/refs/heads/main.zip`
3. Copy the `world` folder from the old server to the new one.
4. Run `server.jar` and `bungee.jar` to update chunks automatically.

## Running the Server
Please download the [installer script](https://github.com/iddu0/EaglercraftX-1.19-Server-Reborn/tree/main#eaglercraftx-119-server) for your appropriate operating system before procedding to this step.

### Linux & MacOS
- Start server: `./server/server.sh` (use `chmod +x /server/server.sh` first)
- Start bungeecord: `./bungee/bungee.sh` (use `chmod +x /bungee/bungee.sh` first)

### Windows
- Run `/server/server.bat` (in Eaglercraft server directory)
- Run `/bungee/bungee.bat` (in Eaglercraft server directory) 

Now forward ports 8081 and 25565, then access your server at `[server-ip:8081]`.

## What to do if Your Server Crashes
If your server is not starting after a crash, try deleting the `server/world/session.lock` file and restart it.

## Plugin Installation
- Navigate to `server/plugins` and `bungee/plugins`.
- Paste the plugin `.jar` file and create a separate directory for additional data.
- Restart the server to activate the plugin.

## FAQ
- **Can I find and craft 1.19 items?** Yes, with normal item behaviour but potentially different textures.
- **Will mobs behave normally?** Most mobs are matched to their closest pre-existing characters or models, with standard drops and stats.
- **Can I find new structures?** Yes, though they may not match the blocks or layouts of 1.19.
