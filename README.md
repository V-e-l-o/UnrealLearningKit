# UnrealLearningKit

Level objective is for player to get to the top of a mountain from a small, ransacked village. The player runs on guarded rooftops with enemies that have knock attacks, making the journey risky.

All requirements met. The Special enemy is a combination of mortar and pursuer name shooter, but with a little more ambitious AI by attempting to space away from the player if the player is in “comfort zone.” The shooter only throws bombs at the player if they are in this comfort zone,

Health System is very similar to infinite matrix.

 Pursuer has a “pursuer area” actor in which they stay inside of. They have a patrol path of a square inside the pursuer area, and patrol points relative to the middle of the pursuer area sphere. Pursuers only chase players if they are seen inside the pursuer area.

Mortar fires constantly in random locations every 2 seconds. Stationary enemy can be destroyed when jumping toward cannon.

Shooter is like a pursuer with a mortar that always aims at the player, along with a comfort zone mechanic. Shooter roams without a patrol path, but does have a shooter area where they guard. Shooters are generally placed near collectables.

Health packs guide players up the mountain. Heal 1/20th of health.

There are 10 collectables, with a progress bar in the bottom right corner of the UI. They are in hidden areas, but a few in the main areas to remind the player that collectibles exist. A collectible slightly increases movement speed, making the level slightly easier.

There is one Fly powerup somewhere in the level guarded by a shooter, but the ability only glides and does not increase verticality. Only useful for touring level or saving self from high falls.
