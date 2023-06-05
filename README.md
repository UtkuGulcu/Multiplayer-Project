# Multiplayer-Project-Prototype
This was a basic multiplayer game prototype heavily inspired from Gun Mayhem, made in Unity. Unfortunately I had lost the project files, all I have about this project is this build. Because of that I can no longer make any updates to the game. Nevertheless I wanted to share it because it is kind of fun when you gather friends and try it.
  
I had been using Photon for networking while I was developing the project. Visuals are very basic since this was only a prototype.  

By the way you should have at least two instances of the game running when playing, otherwise game ends on the first death of the player since it checks the player count whenever a player dies. If the alive player count is 1 the game state is set to win state.

# Controls:   
Arrow keys: Move sideways, you can double jump with up arrow. You can drop off the platform with down arrow.  
Z: Shoot

# Gameplay
In this game you must push your enemies off the map with your guns to win. All players spawn with a pistol which has infinite ammo. Over the course of the game some pickups will be dropped. White pickup gives you shield which makes you invulnerable for a limited time. Blue pickup gives you automatic rifle that can shoot 30 bullets and its knockback is stronger than pistol. Finally we have black pickup that gives you a sniper. Sniper only holds 5 ammo but is knockback is the strongest in the game. Each player has 10 lives, only one of them can win.
