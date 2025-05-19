#     csoc-25-GameDev-Godot-week-1
# Getting Started with Godot + 2D Movement

Welcome to Week 1 of your Godot game dev journey!  
This week, we’ll learn how to create a Godot project, build your first scene, and make a player move around using the keyboard. Let’s keep it simple and fun!

---

## 🚀 What You'll Learn

- How to set up and navigate the Godot 4.4 interface
- Creating and saving your first scene
- Using nodes like CharacterBody2D, Sprite2D, and CollisionShape2D
- Writing simple movement logic with GDScript

---

## 📝 How to Submit

1. Fork this repository to your GitHub account.
2. Creat a zip for the game folder
3. Name the zip file like this: `YourName_RollNo`
4. Go to the `Your Games/` folder. Add your zip file to this folder
5. Push your changes and open a Pull Request.

---


## 🎯 Your Main Goal

You’ll build a simple scene where:

- A player character can move around using arrow keys or WASD.
- Create a tilemap for design a small new level using tilemap, to know more about TileMap refer to [this article](https://docs.godotengine.org/en/latest/tutorials/2d/using_tilemaps.html) or [this video](https://www.youtube.com/watch?v=sbv35boXqac)
- create a script for player naming it `Player_rollnumber.gd`
- ready function executes one time at the start of the scene, process function executes every frame.
- write basic player movement code with jump implementaion(allow double jump and not more than that)
- The movement should feel smooth and responsive.

Try making it funny, stylish, or totally weird — this is your playground!


---

## ✅ Week 1 Tasks

### 1. 🌀 Teleport Pads

- Add two **Area2D** nodes on the map (some sprite attached to it or your choice).
- When the player enters one, they should be instantly teleported to the second.


---

### 2. 🎨 Sprite Color Changer

- Make it so that when you press the **C** key, your player changes color.
- Add a few different colors(more than two) that change every time you press C,(change should be in cyclic order)
  

---

## 📚 Docs

- [🎮 Your First 2D Game Tutorial](https://docs.godotengine.org/en/latest/getting_started/first_2d_game/)
- [🧍 CharacterBody2D Docs](https://docs.godotengine.org/en/latest/classes/class_characterbody2d.html)
- [📜 GDScript Basics](https://docs.godotengine.org/en/latest/tutorials/scripting/gdscript/gdscript_basics.html)

---

## 💡 Tips

- Save your scene often (`Ctrl + S`) and test frequently.
- Keep your player sprite and collision aligned properly.
- And most importantly — experiment and have fun!

---

Once you're done, don’t forget to submit your Pull Request so we can see your awesome work!

Happy coding and game dev'ing! 🎉
