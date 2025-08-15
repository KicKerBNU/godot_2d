# 🎮 Godot 2D Game Project

A 2D platformer game built with Godot 4.4, featuring a knight character that can jump, move around platforms, and collect coins.

## 📋 Project Overview

This is a 2D game development project created in Godot Engine. The game features a simple platformer setup with a playable character, interactive elements, and a tile-based world system.

## 🚀 Features

- **Player Character**: A knight character with basic movement and jumping mechanics
- **Platform System**: Tile-based platforms with physics collision
- **Collectibles**: Coins that can be collected by the player
- **World Design**: Custom tilemap using a world tileset
- **Audio**: Background music and sound effects for various actions

## 🎯 Game Mechanics

### Player Controls
- **Movement**: Use `A/D` or `Left/Right` arrow keys to move
- **Jump**: Press `Space` or `Up` arrow key to jump
- **Physics**: Realistic gravity and collision detection

### Game Elements
- **Coins**: Collectible items that disappear when touched
- **Platforms**: Solid surfaces for the player to walk and jump on
- **World Boundaries**: Invisible walls to keep the player in the game area

## 🏗️ Project Structure

```
godot_2d_01/
├── assets/                 # Game assets
│   ├── fonts/             # Pixel art fonts
│   ├── music/             # Background music
│   ├── sounds/            # Sound effects
│   └── sprites/           # Game sprites and textures
├── scenes/                 # Godot scene files
│   ├── coin.tscn          # Coin collectible scene
│   ├── game.tscn          # Main game scene
│   ├── platform.tscn      # Platform scene
│   └── player.tscn        # Player character scene
├── scripts/                # GDScript files
│   ├── coin.gd            # Coin behavior script
│   └── player.gd          # Player movement and physics
├── project.godot          # Godot project configuration
└── icon.svg               # Project icon
```

## 🎨 Assets

### Sprites
- **Knight**: Main player character
- **Coins**: Collectible items
- **Platforms**: Various platform designs
- **Enemies**: Green and purple slime creatures
- **World Tileset**: Comprehensive tile collection for level design

### Audio
- **Background Music**: "Time for Adventure" - atmospheric game music
- **Sound Effects**: 
  - Coin collection
  - Jump sounds
  - Hurt sounds
  - Explosion effects
  - Power-up sounds
  - Tap/click sounds

### Fonts
- **PixelOperator**: Pixel art font family (regular and bold variants)

## 🛠️ Technical Details

- **Engine**: Godot 4.4
- **Rendering**: Forward Plus pipeline
- **Scripting**: GDScript
- **Physics**: Built-in 2D physics engine
- **Audio**: Built-in audio system

## 🚀 Getting Started

### Prerequisites
- [Godot Engine 4.4](https://godotengine.org/download) or later

### Installation
1. Clone or download this repository
2. Open Godot Engine
3. Click "Import" and select the `project.godot` file
4. Click "Import & Edit" to open the project

### Running the Game
1. In the Godot editor, press `F5` or click the "Play" button
2. The main game scene will load automatically
3. Use the controls to play the game

## 🎮 How to Play

1. **Start**: The game begins with your knight character on a platform
2. **Move**: Use `A/D` or arrow keys to move left and right
3. **Jump**: Press `Space` to jump onto platforms
4. **Collect**: Touch coins to collect them
5. **Explore**: Navigate through the platform-based world

## 🔧 Development

### Adding New Features
- **New Scenes**: Create `.tscn` files in the `scenes/` folder
- **Scripts**: Add `.gd` files in the `scripts/` folder
- **Assets**: Place new assets in the appropriate `assets/` subfolder

### Script Structure
- **Player Script** (`player.gd`): Handles character movement, jumping, and physics
- **Coin Script** (`coin.gd`): Manages collectible behavior and collision detection

## 📝 License

This project is open source. Feel free to use, modify, and distribute as needed.



**Happy Gaming! 🎮✨**
