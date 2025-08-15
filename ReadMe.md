# Slime Survival Game - README

Welcome to **Slime Survival**, a game where you survive in a world of slimes! Craft tools, chop trees, and navigate the wilderness while avoiding or fighting off slimes. Don't forget to manage your health, water, and hunger to stay alive!

![SlimeSurvivalCover](https://github.com/user-attachments/assets/891b7d8e-5d93-40c6-943e-cfac727165ce)

## Table of Contents
1. [How to Play](#how-to-play)
2. [Building and Running in Unity](#building-and-running-in-unity)
3. [Features Implemented](#features-implemented)
4. [Resources](#resources)
5. [Videos and Screenshots](#videos-and-screenshots)

---

## How to Play

- **Movement:**
  - Use the **W**, **A**, **S**, **D** keys to move around.
  - Press **Spacebar** to jump.

- **Items and Inventory:**
  - Click on **I** key to open Inventory
  - **Left-click** to pick up items.
  - **Equip weapons** by **middle-clicking** on them or dragging them into one of the quick slots.
  - **Eat item** by **right-clicking** on them.
  - To use an equipped weapon, press the number corresponding to its quick slot (1, 2, 3, etc.).
  - To **remove an item**, drag it to the **Trash Slot**.

- **Crafting:**
  - Click on **c** key to open Craft panel
  - Combine materials in the **Crafting System** to create new tools and weapons.

- **Health, Water, and Hunger:**
  - Monitor your **health**, **water**, and **food** levels. Eat food items to heal and restore your energy.

- **Combat:**
  - Slimes will chase and attack you! Use your equipped weapons to defend yourself.

---

## Building and Running in Unity

### Opening the Project:
1. Open **Unity**.
2. Import all necessary assets (scripts, models, etc.).
3. Open the scene **Game** Scene.

### Building the Game:
1. Go to **File > Build Settings**.
2. Add the open scene to the build if it's not already there by clicking **Add Open Scenes**.
3. Choose your target platform (PC, Mac, Linux, etc.).
4. Click **Build** to generate the executable for your platform.

### Running the Game in Unity:
1. In the Unity editor, click the **Play** button to run the game.
2. You can interact with the world, manage resources, and fight slimes.

---

## Features Implemented

1. **Player Movement:**
   - **Script:** `PlayerMovement.cs`
   - Allows movement using **WASD** and jumping with the **spacebar**.

2. **Inventory System:**
   - **Scripts:** `InventorySystem.cs`, `InventoryItem.cs`, `ItemSlot.cs`
   - Manages item collection, inventory organization, eat item and item selection.

3. **Crafting System:**
   - **Scripts:** `CraftingSystem.cs`, `Blueprint.cs`
   - Enables the player to craft tools and weapons by combining resources.

4. **Equip System:**
   - **Scripts:** `EquipSystem.cs`, `EquipableItem.cs`
   - Allows the player to equip weapons and tools via quick slots or middle-click.

5. **Health, Water, and Hunger Bars:**
   - **Scripts:** `HealthBar.cs`, `WaterBar.cs`, `HungryBar.cs`, `ResourcesHealthBar.cs`
   - Tracks health, water, and food levels; players must manage these to survive.

6. **Slime AI (Chase and Attack States):**
   - **Scripts:** `SlimeAttackState.cs`, `SlimeChaseState.cs`, `SlimeWalkState.cs`, `SlimeIdleState.cs`
   - Controls slime behavior, including movement, chasing the player, and attacking.

7. **Interactive Objects:**
   - **Scripts:** `InteractableObject.cs`, `ChoppableTree.cs`
   - Allows players to interact with the environment, like chopping trees and gathering resources.

8. **Trash Slot (Item Removal):**
   - **Script:** `TrashSlot.cs`
   - Enables players to remove unwanted items from their inventory.

9. **Mouse Movement:**
   - **Script:** `MouseMovement.cs`
   - Manages mouse cursor movement and interaction with objects.

10. **Sound Manager:**
    - **Script:** `SoundManager.cs`
    - Manages sound effects and background music.

11. **Selection Manager:**
    - **Script:** `SelectionManager.cs`
    - Handles object selection for interaction.

12. **Global State:**
    - **Script:** `GlobalState.cs`
    - Tracks the overall game state (e.g., whether the player is alive or dead).

---

**Enjoy your survival adventure in the world of slimes!** Stay safe, craft wisely, and don't let the slimes get you!

---

# Resources:
- Free Terrain Sample Asset Pack:
   https://assetstore.unity.com/packages... 
- Free Fantasy Landscape Assets Pack:
   https://assetstore.unity.com/packages... 
- Free Fantasy Skybox:
   https://assetstore.unity.com/packages... 
- Free Rocks Package:
   https://assetstore.unity.com/packages/3d/environments/lowpoly-rocks-137970
- Inventory:
   https://assetstore.unity.com/packages/2d/gui/icons/gui-parts-159068
    https://assetstore.unity.com/packages/2d/gui/fantasy-wooden-gui-free-103811
    https://assetstore.unity.com/packages/tools/gui/simple-and-powerful-inventory-system-265015
  
- Nature:
   https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153
- Weapons:
   https://assetstore.unity.com/packages/3d/props/weapons/lowpoly-weapon-pack-216486

--- 

# Videos and ScreenShots:
![image](https://github.com/user-attachments/assets/3cac7c1f-6fb3-4778-91a0-e6c890ba9f7d)
![image](https://github.com/user-attachments/assets/47889c69-f1d1-4027-b5ad-0862795255f5)
![image](https://github.com/user-attachments/assets/fc65123f-e92e-4578-9445-0c4f9f6eca13)
![image](https://github.com/user-attachments/assets/d82d8930-9362-41ac-8d89-c6740906435a)
![image](https://github.com/user-attachments/assets/98c857fb-f683-4c58-8d37-dccff5fa525c)
![image](https://github.com/user-attachments/assets/db85e15b-b9dc-4fe7-b9d3-702f28cc3952)


## Video:


https://github.com/user-attachments/assets/95c75d65-9706-45c3-890c-c13034767c41
