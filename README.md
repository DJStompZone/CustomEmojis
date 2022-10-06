# Custom Stompzone Emojis

![Discord](https://img.shields.io/discord/599808270655291403?color=blue&label=Discord&logo=discord&logoColor=blue&style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/djstompzone/customemojis?style=flat&logo=github&logoColor=blue)

#### Version 1.0.5
#### By MRBBATES1, DJ Stomp#2525

<br>


## Description

Custom Emojis from the [StompZone Discord server](https://discord.gg/stompzone). 
Based on [CustomEmojis](https://github.com/MRBBATES1/CustomEmojis) by [Bobby Bates](https://github.com/MRBBATES1)

<br>

## Requirements

- Minecraft: Bedrock Edition v1.19.30+
- A server, realm, or world updated to a minimum of 1.19.30, with the gametest experimental feature enabled

<br>

## Installation

To install the prebuilt mcaddon pack, simply open with Minecraft Bedrock to import, and apply the resource and behavior packs to your world, server, or realm.
**Note**: Gametest framework (experimental feature) must be enabled on the world, or this pack will not work as intended.

<br>

## Usage

To use, type one of the supported emojis into the chat in Discord/Slack format (:emoji:) and it will be automagically converted to the corresponding image. 

<br>

## Troubleshooting

- If you notice issues with the emojis overlapping, you may need to increase your line spacing in chat settings.
- If the pack is not working, ensure you have the Gametest experimental feature enabled
- For more help, you can join the [Stompzone Discord](https://discord.gg/stompzone)

<br>

## Development

If you would like to implement your own emojis, you can simply insert them into [glyph_E1.png](https://github.com/DJStompZone/CustomEmojis/blob/main/CustomEmojisRP/font/glyph_E1.png) and then update the corresponding entry in [emojis.js](https://github.com/DJStompZone/CustomEmojis/blob/main/CustomEmojisBP/scripts/emojis.js) to the desired emoji handle.
Once you have done this, the manifest.json file will need to be updated for the RP and BP with a new name and new UUIDs.
**Note**: Do __not__ change the UUIDs for the 'mojang-minecraft' or 'mojang-gametest' modules, or the pack will not function as intended. The values have been updated to comply with the new Gametest versioning, and should work correctly as of game version 1.19.31.

<br>

## Coming Soon™

- Step by step guide for adding custom emojis
- Python script to automatically generate a pack from a set of images
- GIF emojis???
