# Game-design-project
A FPS game demo 
The game is designed using UNITY

How to Play：
The winning condition: 
Firstly, reach the gate of the target factory. The appearance of the gate is shown on the starting page. 
Secondly, keep health points above 0. 

The target gate is hidden in the game region. To make the game more challenging, we hid it behind a tree and some bushes. When arrived at the front of the gate while health point is above 0, the game will end with a text shown on the screen telling the player he/she won. 



Operation keys:

The player needs to find the gate by travel around the game region. The player can move around by pressing WSAD (forward/ backward/left/right by the same sequence), and hold shift key to move faster.

The players single left click the mouse to fire the pistol. The change of bullet is triggered automatically when the pistol runs out of bullet.  



Health point deduction and shooting bonus:

There are two kinds of enemies in the game: the mutated spider and mutated monster. The spider is a less harmful enemy. It has a 15 point hurt to health point, and takes 2 pistol hits to kill. The monster is stronger with a 25 points hurt to health point, and takes 3 pistol hits to kill. 

The enemies will be awaken by players at different distance. The spider is more sensitive and awakes earlier, at a distance of 80, and starts attack at a distance of 8. The monster has larger hurt and begins moving later, only when players get within a distance of 70 from it. 
Both types of enemies will start attacking the player and causing harm when the distance between itself and the player is below 5. 



There are also a bonus score system for hitting and killing enemies, though the score is not correlated with winning or losing of the game. As spider is comparatively weak, hitting the spider rewards 1 point bonus, while killing a spider rewards 15. On the other hand, hitting a monster rewards 2 points, and killing it rewards 50 points. 
