Okay, here is an English version of the README.md for a simplified Minecraft world generator:

# Simple PocketMine World Generator

This is a simple Minecraft world generator that creates a randomly generated world with all available blocks and items.

## Features

- Randomly generated world using all Minecraft blocks 
- Includes all regular and special blocks
- All items spawned randomly in chests
- Simple biome and terrain generation using noise

## Usage

The generator can be integrated as a plugin into a Minecraft server.

## How it works

The generator first creates a simple landscape as a base using noise.

Then in each chunk column, random blocks are placed from the list of all available blocks.

On the surface, a random biome is chosen from a list and the top blocks are set accordingly. 

At random intervals, chests are spawned containing all possible items.

## Credits

- [poggit-orphanage](https://github.com/poggit-orphanage) for the initial generator code
- [MinecraftForge](https://github.com/MinecraftForge/MinecraftForge) for parts of the biome code
- [PocketMine](https://github.com/pmmp/PocketMine-MP) for the API and docs

## Contributors

Pull requests are welcome!
