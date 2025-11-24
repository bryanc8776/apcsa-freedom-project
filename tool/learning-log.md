# Tool Learning Log

## Tool: **Godot**

## Project: **[Racing Game](https://godotengine.org/)**

---

### 10/5/25:
* Watched 10 minutes of [this](https://www.youtube.com/watch?v=LOhfqjmasi0) video on how to make a game with godot
  * Making in game is combining and extending **nodes** to get the result we want.
  * **Scenes** allow us to bundle nodes together into reusable packages
* We have to download Godot to use it


### 10/20/25:
* Watched 10 minutes of [this](https://www.youtube.com/watch?v=8CrFk3tjsSY) tutorial video which is part of a crash course on Godot.
  * Godot uses multiple languages. The simplest one is GDScript which is similar to Python.
  * You always attach a script to a node and that script can change the attributes of the node.
    * You can change the position, size, color, texture, rotation, or anything the node has in its inspector.
  *  The grid(x, y) starts from the top left(0, 0)
*  I also tried to download the Godot Engine but it didn't work so I'll have to check that.

### 11/2/25:
* Watched [this](https://www.youtube.com/watch?v=q7wlSvt0JIc&list=PL4cUxeGkcC9iHCXBpxbdsOByZ55Ez4bgF) full video which is part of the crash course.
  * I figured out how to run Godot on my laptop and got my own project.
  * Followed along with the video explaining some of the concepts in Godot along with how to create and manipulate things for scenes and nodes.
  * Imported some images and audio in the form of folders that contain multiple files. Used some to make the meteors and spaceship for the project in the video.
* I plan on following [this](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html) step-by-step 2D-game tutorial to get a better sense of the different functions and concepts in the project folder.

### 11/16/25:
* I started the [step-by-step 2D-game tutorial](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html)
  * We created a `Player` parent node and added two child nodes, `AnimatedSprite2D` and `CollisionShape2D`
  * Imported folders with files of images for the player and enemies
    * Used the `player` images to display the `player` and show animation effects
  * I also learned a lot of new things like how to [add animations](Adding_animations.png) based on user/keyboard-input and write code in the [GDScript](GDScript_code.png) to make the scene more interactive.
* The next step will be to continue with the tutorial and create the enemies.

### 11/23/25:
* I continued working on the tutorial project by adding the [enemies](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/04.creating_the_enemy.html)
  * This had steps that were similar to the `player` scene but I forgot how to add some things like animations and grouping nodes so I went back to the [player doc](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/02.player_scene.html).
  * To get an element from an array in GDScript, we use `array_name.pick_random()`
  * Something new I did was connect a signal of a child node called `VisibleOnScreenNotifier2D` to the main/parent `Mob` node and use this in the `Script`

<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
