2D Adventure Game
Project Overview

This is a 2D side-scrolling adventure game developed using the Unity engine. Players control a character to explore maps, fight enemies, use skills, avoid traps, and ultimately defeat the Boss to complete the game.

This game was independently developed by our team. All art assets from South China University of Technology and audio assets are sourced from open-source materials available online.

Game Features

Smooth Character Control: Supports basic actions such as movement, jumping, and rolling

Combat System: The character can attack enemies and use skills such as magic projectiles

Health System: The character has a health bar and can use health potions to restore HP

Map Exploration: Multiple levels with diverse terrain and obstacles

Trap Mechanism: Dangerous traps such as ground spikes deal damage to the character

Boss Battles: Challenge powerful Boss enemies

Respawn System: The character respawns at a checkpoint after death

Polished UI Interface: Includes main menu, health bar, skill cooldown interface, etc.

Technical Implementation
Development Tools

Game Engine: Unity 2022.3 LTS

Programming Language: C#

Render Pipeline: Universal Render Pipeline (URP)

Version Control: Git

Core Systems

Character Control System

Player input handling

Character movement and animation

Collision detection

Combat System

Player attack mechanics

Enemy AI behavior

Damage calculation

UI System

Health display

Skill cooldown interface

Game menu

Level System

Scene management

Tilemap system

Parallax background scrolling

Project Structure
Assets/
├── Scenes/           # Game scene files
├── Scripts/          # C# script files
├── Prefabs/          # Prefab assets
├── Audio/            # Audio files
├── UI_set/           # UI assets
├── Map/              # Map-related assets
├── Enemy/            # Enemy-related assets
├── Boss/             # Boss-related assets
└── Trap/             # Trap-related assets
How to Run the Game
System Requirements

Unity 2022.3 LTS or higher

Windows 10/11 operating system

Steps to Run

Download or clone the project locally

Open the project using Unity Hub

Wait for Unity to finish importing and compiling

In the Project window, locate Assets/Scenes/MainMenuScene.unity

Double-click to open the main menu scene

Click the Play button at the top of the Unity editor to start the game

Controls

W, A, D: Move character

Spacebar: Jump

Left Mouse Button: Attack

Right Mouse Button: Roll

Specific Keys: Use skills (Q, R, X)

Main Features Description
Character System

The character has a health value that decreases when taking damage

Health can be restored using health potion items

After death, the character respawns at the nearest checkpoint

Combat System

Players can use melee attacks, rolling (with invincibility frames), and various skills (magic bullets, attribute enhancement, energy wave punch)

Different enemies have different behavior patterns

Bosses have more complex attack patterns and higher health

Map System

Supports destructible tile-based terrain

Includes various traps such as ground spikes

Background supports parallax scrolling effects

⭐ Core Responsibilities & Contributions (My Role & Contributions)

As the project leader and lead programmer, I was honored to collaborate with a talented and passionate team to bring Drifter Game from concept to reality. I was responsible for overall project planning, technical architecture selection, and led the development of multiple core systems.

My main contributions include:

System Architecture & Integration

Led the selection and integration of the project’s technical framework, ensuring efficient and low-coupling collaboration between modules (such as combat, UI, and quest systems).

Built the game’s core event manager to handle complex interaction logic, significantly improving code maintainability and scalability.

Level Design & World Building

Designed the overall layout of the game world and map assembly using Unity’s Tilemap system to build all major scenes.

Implemented seamless scene loading and transition mechanisms to optimize the player’s exploration experience.

Core Gameplay & Interaction Logic

Developed complex interaction systems between the player, enemies, and the environment, including mechanism triggers, damage zones, and destructible objects.

Added dynamic gameplay elements to enhance both combat and exploration.

Enemy AI Systems

💖 Development Team (Our Team)

The success of this project would not have been possible without the efforts of every team member. This game is the result of our collective wisdom and hard work.
