# ball_game_vr
Unity Adventure Game
Overview
A 3D adventure game developed in Unity and C# as part of a game development course. The game features a player navigating through four levels, collecting pickups, interacting with the environment, and achieving objectives. The project fulfills lab requirements, including player mechanics, animations, UI, and level design, with bonus features like audio and an enhanced environment.
Features

Player (4 pts): A controllable character with movement (WASD/arrow keys) and interaction capabilities.
Pickups (9 pts): Collectible items scattered across levels, triggering score updates.
Animations (15 pts): Player and pickup animations (e.g., walking, idle, collect) using Unity’s Animator.
Colliders (9 pts): Physics-based interactions for player, pickups, walls, and obstacles.
Material (5 pts): Custom materials applied to objects for enhanced visuals.
Skybox (5 pts): A dynamic skybox for an immersive environment.
4 Levels (10 pts): Four distinct levels with increasing complexity and unique layouts.
UI (10 pts): Displays score, win/lose text, and game status.
Scripts (3 pts): Custom C# scripts for game mechanics and logic.
Executable (30 pts): A Windows .exe file for running the game.
Bonus Features:
Audio (15 pts): Sound effects for pickups, background music, and win/lose events.
Enhanced Environment (up to 50 pts): 3D models for players, pickups, and walls; vibrant colors; and a game menu with Start/Exit buttons in a separate scene.



Project Structure

Scripts:
PlayerController.cs: Manages player movement and interactions.
PickupController.cs: Handles pickup collection and scoring.
GameManager.cs: Controls game state, UI updates, and level progression.
MenuController.cs: Manages the main menu (bonus).


Assets:
3D models for player, pickups, and environment.
Materials and textures for visual enhancement.
Audio files for sound effects and music.


Scenes:
MainMenu: Game menu with Start/Exit buttons (bonus).
Level1 to Level4: Four playable levels.


Build:
Game.exe: Windows executable for the game.



Requirements

Unity Version: 2021.3 or later.
Install dependencies:# Uses Unity’s built-in features; no external packages required.



Usage

Clone the repository:git clone https://github.com/your-username/unity-adventure-game.git


Open in Unity:
Launch Unity Hub, click "Add," and select the project folder.


Play the game:
Open the MainMenu scene and click "Play" in the Unity Editor.
Use WASD/arrow keys to move, Space to interact/collect pickups.


Run the executable:
Navigate to the Build folder and run Game.exe (Windows).


Build for other platforms (optional):
Go to File > Build Settings to build for Windows or Android (APK, bonus).



How It Works

Player Mechanics: The player navigates using Rigidbody-based movement, with animations triggered by input.
Pickups: Colliders detect pickup collection, incrementing the score and playing sound effects.
Levels: Each level has unique obstacles and pickup placements, with win/lose conditions.
UI: Updates score and displays win/lose messages based on game state.
Audio: Background music loops during gameplay, with sound effects for key events.
Menu: A separate scene provides Start/Exit options for a polished user experience.

Future Improvements

Add multiplayer support using Photon or Mirror.
Implement additional levels or difficulty settings.
Optimize for mobile platforms with touch controls.
Enhance visuals with particle effects and dynamic lighting.

Acknowledgments

Unity: For the game engine and learning resources.
Course Instructors: For guidance and lab requirements.

Author

Abdallah Soliman Alzoghby (Reg: 211003603)

