# Entry 2: Winter Break FP Goal
##### 12/15/25

### Tool Learning
#### Tinker
After checking out some of the content on [***Godot***](https://godotengine.org/), I decided to work on the [2D-tutorial](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html) they have. 
* First, we created a `Player` parent node and added two child nodes: `AnimatedSprite2D` and `CollisionShape2D`.
  * We imported folders with files of images for the player and enemies and used the `player` images to display the `player` and show animation effects.
  * I also learned a lot of new things like how to [add animations](../tool/Adding_animations.png) based on user/keyboard-input and write code in the [GDScript](../tool/GDScript_code.png) to make the scene more interactive.
* Then we moved on to adding the `enemies` which was a pretty similar structure to how we made the `Player`.
  * I forgot how to add some things like animations and grouping nodes so I went back to the [player doc](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/02.player_scene.html) and the `player` scene we made which made it easier.
  * A takeaway I had in this part is that to get an element from an array in GDScript, we use `array_name.pick_random()`.
  * Something new I did was [connect a signal](../tool/Node_signal_connection.png) of a child node called `VisibleOnScreenNotifier2D` to the main/parent `Mob` node and use this in the `Script`.
* After the `enemies`, I was able to get the [`Main`](../tool/tutorial_main_scene.png) scene to work where the game is functioning as needed with basic features.
  * I had forgotten how to add a scene. I thought it would be the `+` in the scene dock but that adds a child node. I went back to earlier in the tutorial and remembered that we need to click that `Scene` at the top left above the Scene dock to add a new scene.
  * The [`Main` scene](../tool/main-scene_dock.png) doesn't have to be a `Node2D` because we are mainly just putting the other nodes like `Player` into it which are already `2D` so they have the physics characteristics.
  * In this part, the main thing we did was add [`timer`s](../tool/tutorial_timer_code.png) as child nodes of the `Main` scene to control when the game/mob starts.
* Lastly, I added the user-interface part of the [game](../tool/UI-tutorial.png) and also learned a lot while going through this section.
  * The `CanvasLayer` node, a type of `Control` node, lets us draw our UI elements on a layer above the rest of the game, so that the information it displays isn't covered up by any game elements.
  * `Control` nodes have a position and size, but they also have [anchors](../tool/Adding-Anchors.png). Anchors define the reference point for the edges of the node.

#### FP Winter Break Goal
My goal for the winter break is to have fun, spend time with my family and get some rest. However, I also aim to continue learning and practicing my tool. My partner and I plan on making the `Sprites` for the racers which potentially includes 1 player and 3 or more bots. I plan on doing this in the first couple of days of the break.


### Engineering Design Process
I am currently on stage 2 of the engineering designing process. I am learning about the concepts in ***Godot*** and documenting what I find. To fully get a sense of how ***Godot*** works I have tried tutorials and watched videos. Now I am moving on to step 3 which is where we brainstorm possible solutions.


### Skills
The skills I have improved on are **Collaboration** and **Communication**. For SEP, I joined the *INFY App Design Challenge* where we have to work in a group to compete with other groups and schools. In this, I was put in a group with students I didn't know and were in lower grades. Since I had always been shy, I thought it would be really hard for me to work with them. However, I realized that it was easy to talk to them, get their ideas, and we worked really well together. Not only this, but in my *Participation in Government* I have to work with a partner. We have to do research, write paragraphs, and more. We are in constant communication so that we can get all the work done on time and make sure our paragraphs transition smoothly.

[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)
