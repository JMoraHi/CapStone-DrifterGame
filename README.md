2D Adventure Game

Project Overview

This is a 2D side-scrolling adventure game developed using the Unity
engine. Players can control the character to explore the map, fight
enemies, use skills, avoid traps, and ultimately defeat the Boss to
complete the game. This game was independently developed by our team.
The art assets are from South China University of Technology, and the
audio assets are sourced from open-source materials available online.

Game Features

-   Smooth Character Control：Supports basic operations such as
    movement, jumping, and rolling
-   Combat System：The character can attack enemies and use skills such
    as magic bullets
-   Health System：The character has a health bar and can use health
    potions to restore health
-   Map Exploration：Multiple level scenes including various terrains
    and obstacles
-   Trap Mechanism：Dangerous traps such as ground spikes will deal
    damage to the character
-   Boss Battle：Challenge powerful Boss enemies
-   Respawn System：After death, the character can restart at a respawn
    point
-   Beautiful UI Interface：Includes main menu, health bar, skill
    cooldown interface, etc.

Technical Implementation

Development Tools

-   Game Engine：Unity 2022.3 LTS
-   Programming Language：C#
-   Render Pipeline：Universal Render Pipeline (URP)
-   Version Control：Git

Main Systems

1.  Character Control System

    Player input handling

    Character movement and animation

    Collision detection

2.  Combat System

    Player attack mechanism

    Enemy AI behavior

    Damage calculation

3.  UI System

    Health display

    Skill cooldown interface

    Game menu

4.  Level System

    Scene management

    Map tile system

    Parallax background scrolling

Project Structure
```
Assets/
├── Scenes/ # Game scene files 
├── Scripts/ # C# script files
├── Prefabs/ # Prefab assets
├── Audio/ # Audio files
├── UI_set/ # UI interface assets
├── Map/ # Map-related assets
├── Enemy/ #Enemy-related assets
├── Boss/ # Boss-related assets
└── Trap/ #Trap-related assets
```

How to Run the Game

Environment Requirements

-   Unity 2022.3 LTS or higher
-   Windows 10/11 operating system

Running Steps

1.  Download or clone the project locally
2.  Open the project using Unity Hub
3.  Wait for Unity to finish importing and compiling
4.  In the Project window, locate Assets/Scenes/MainMenuScene.unity
5.  Double-click to open the main menu scene
6.  Click the Play button at the top of the Unity editor to start the
    game

Game Controls

-   WAD ：Character movement
-   Spacebar：Jump
-   Left Mouse Button：Attack
-   Right Mouse Button：Roll
-   Specific Keys：Use skills (Q、R、X)

Main Feature Description

Character System

-   The character has a health value that decreases when taking damage
-   Health can be restored using health potion items
-   After death, the character will respawn at the nearest respawn point

Combat System

-   Players can use melee attacks, rolling (invincibility frames), and
    various skills (magic bullets, attribute enhancement, energy wave
    punch)
-   Different enemies have different behavior patterns
-   The Boss has more complex attack methods and higher health

Map System

-   Supports destructible tile-based terrain
-   Includes various traps such as ground spikes
-   The background supports parallax scrolling effects

⭐ Core Responsibilities & Contributions (My Role & Contributions)

As the project leader and lead programmer of this project, I was honored
to collaborate with a talented and passionate team to turn “Drifter
Game” from an idea into reality. I was responsible for the overall
project planning, technical architecture selection, and led the
development of multiple core systems. My main contributions focused on
the following aspects： - System Architecture & Integration (System
Architecture & Integration): Led the selection and integration of the
project’s technical framework, ensuring that various modules (such as
combat, UI, and quest systems) could work together efficiently with low
coupling. Built the game’s core event manager to handle complex
interaction logic, significantly improving code maintainability and
scalability. - Level Design & World Building (Level Design & World
Building): Responsible for the overall layout of the game world and map
assembly, using the Unity Tilemap system to build all major scenes.
Implemented seamless loading and transition mechanisms between scenes,
optimizing the player’s exploration experience. - Core Gameplay &
Interaction Logic (Core Gameplay & Interaction Logic): Developed complex
interaction systems between the player character, enemies, and the map
environment, including mechanism triggers, damage areas, destructible
objects, etc. This provided rich dynamic elements to the game, making
combat and exploration more engaging. - Enemy AI System (Enemy AI
Systems)

💖 Development Team (Our Team) - The success of a project depends on the
efforts of every member. This game is the crystallization of our wisdom
and hard work:
