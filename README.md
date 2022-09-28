# MCSpigot-WoolSelector
One of my first every Minecraft Spigot plugins!


# Purpose
This plugin automatically changes the wool color when placed to one selected by a player. 

This is my first project that included: 
    - Connecting to and using an online database
    - Using Spigot to create a plugin
        - Creating a responsive GUI
    - Commiting and pushing to GitHub
    - Creating and hosting a local Minecraft server
    - Troubleshooting problems
    


# Features
1. Connects with MongoDB to create, store and update wool selections for a player.

2. Custom responsive GUI.

3. Selection automatically saves to a database and is remembered when a user rejoins the server.
    - Does not use server resources to store data while plugin is active.

4. Replaces block based on database data and user selection.

# Commands
**/wool [x]**
- Opens GUI where players can click and choose the color of their wool.
