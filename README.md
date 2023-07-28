# How to Install a Vanilla World on Your PocketMine Server

In this tutorial, we will guide you through the process of installing a Vanilla World on your Minecraft server. By following these steps, you can easily load and set up a pre-generated world without the need for lengthy in-game exploration and terrain generation.

## Prerequisites

Before you begin, ensure you have the following:

- SpigotMC installed on your server: SpigotMC is a modified version of the Minecraft server that allows for plugins and provides enhanced performance.
- Chunky installed on your computer: Chunky is a world-rendering tool that helps you pre-generate chunks and create the Vanilla World you want to use on your server.

## Step 1: Download SpigotMC and Install Chunky

First, make sure you have downloaded and installed SpigotMC on your server. SpigotMC will serve as the base for running your Minecraft server with custom configurations and plugins.

Next, install Chunky on your computer. Chunky is a standalone application that allows you to render and pre-generate chunks for your Vanilla World.

## Step 2: Pre-generate Chunks in a Radius

After installing Chunky, open the application and set the desired world size for your Vanilla World. You can choose the radius of the world you want to generate, such as 500, 1000, or any other suitable value.

Using Chunky, pre-generate all the chunks within the specified radius. This step will create the terrain and landscape of your Vanilla World.

## Step 3: Stop the Server

Before moving forward, make sure to stop your Minecraft server using the appropriate command. Stopping the server is essential to prevent any potential issues that might arise when installing a pre-generated world.

## Step 4: Open Chunker.app and Configure World Dimensions

Now, open Chunker.app and select the Minecraft version 1.19.80. In case you need to handle Nether or End Worlds, go to Advanced Mode.

In Advanced Mode, navigate to Dimensions and configure the worlds as "Overworld." This step ensures that both PocketMine (PM) and Minecraft recognize the world correctly and do not attempt to generate a new Overworld.

## Step 5: Handle Potential "NetworkVersion" Error

If you encounter the "NetworkVersion" error while using Chunker.app, follow these steps:

1. Launch Minecraft with version 1.18.x using tools like mcpelinuxlauncher.
2. Play on the world and generate some chunks to resolve the error.

## Step 6: Transfer the World to Your Server

Now that you have successfully pre-generated the Vanilla World using Chunky, transfer the world's files to your Minecraft server's directory.

## Step 7: Start Your Server

With the pre-generated Vanilla World now on your server, start your Minecraft server. Your players can now join and explore the custom terrain without experiencing lengthy world generation on first entry.

Congratulations! You have successfully installed a Vanilla World on your Minecraft server, allowing your players to dive into the action immediately. Enjoy the vast landscapes and unique terrains you've prepared for your community!
