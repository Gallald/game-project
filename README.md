## CISC 4900 encryption game module.
**This is a first [prototype](https://vladglad.itch.io/phaser-rpg?secret=6ltnySNslGpibAeh8dyZCC8PotI) of my module made using [Phaser.io](https://phaser.io) HTML5 game framework.**

### Update:
Encryption/decryption educational module is outsourced to Gallal. 
My main focus now is development of the game world.

**Considering things to be done in the near future:**
- [ ] Title screen.
- [X] Pause menu (Resume, Options, Quit).
- [X] UI that runs in parallel with WorldScene (HP bar, items, currency/score).
- [ ] Player control with WASD.
- [ ] Transition between worlds/biomes.
- [ ] World map; contamination/decontamination.
- [ ] New Enemies.
- [ ] Basic enemy AI.
- [ ] Character invincibility frames.
- [X] Update tiled map layout (added roads).

**(Week 3-4) What has been done:**
* Bug fixed when exiting Scenes: could not exit a Scene due to overlap of game objects.
* Configured "smooth" transitioning between Scenes -> no more Scene restart (on exiting).
* Configured a cycalable dialog Scene with an NPC.
* Tested audio capabilities of Phaser3 and logic to turn on/pause/reume music. (Things don't have to be 8-bit "Retro", you can go as epic as you would like; the only limit is resources and time).
* Explored possibility of loading and using HTML DOM elements into Phaser3.
* Introduced new Scene BookInteraction: where players solve a decryption puzzle. Input check and evaluated (only rudiments so far; the full logic is to be implemented in the future).

**Alternative idea for the game:**
* As we disussed during the 2nd meeting: we could have a world map completely contaminated and it is a player's task to decontaminate the world from this cybersecurity threat. 
* As players travel through this world they learn things from NPCs and need to solve problems introduced in our modules upon encountering enemies.
* Upon succesful progress, world gets gradually cleansed from this threat.

**Potential problems and concerns:**
* **Heavily** time consuming (complexity).
* We are limited on time: when to integrate and polish.

**__________________________________________________________________________________________________________________________________**

**(Week 1-2) Things that had been done:**
* Learned the basics of Phaser3: Loading resources - images spritesheets, creating animation, using "Arcade" physics, scene managemnet, update logic.
* Created two layers of a top-down 2D styled RPG environment to explore using [Tiled](https://www.mapeditor.org "map editor").
* Loaded this environment as a JSON format.
* There are currently 3 scenes: world exploration, turn-based battle, dialog with NPC.
* Hosted the module on [itch.io](https://vladglad.itch.io/phaser-rpg?secret=6ltnySNslGpibAeh8dyZCC8PotI)
* Actual teaching process is to be implemented.

**Things to consider during our next meeting (Still relevant):**
* Team communication: should consider setting up a group chat.
* How should modules be integrated? Is my module standalone or other consepts could be included within my module? (What role does my module play in the final product?)
* Too ambitious? Follow through with this module or abandon it due to a possible complexity and instead create something simpler - like a visual novel.
