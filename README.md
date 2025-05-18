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
2. Go to the `Your Games/` folder.
3. Create your scene and name it like this: `YourName_YourRollNo.tscn`
4. Do the tasks given below.
5. Push your changes and open a Pull Request.

---

## 🎮 Creating Your Godot Project

1. Open Godot and click on the **+ New Project** option.
2. Name your project like this: `YourName_RollNo`
3. Choose a folder to save your project.
4. Hit **Create & Edit** to launch the editor.

![Create project](https://github.com/user-attachments/assets/853a09f2-55e0-4ba9-b007-b5379e72e055)

---

## 🧱 Creating Your Main Scene

Now let’s make your game world!

1. Click the **+** icon in the scene panel and add a **Node2D** as the root node.
2. Rename it to something like `YourName_RollNo` (you can right-click to rename or use shortcut F2).
3. Press `Ctrl + S` to save the scene.
4. Save it with the name: `YourName_RollNo.tscn`

![Create scene](https://github.com/user-attachments/assets/457f1e03-1a12-430c-af34-08c7e6471f6a)

---

## 🧍‍♂️ Adding Your Player Character

1. Add a **CharacterBody2D** node to your scene and name it `Player_rollnumber`.
2. Add a **Sprite2D**(you can use the default godot icon for this) and **CollisionShape2D** as children of the Player.
3. Load a simple sprite image to your Sprite2D (you can use any character image you like or godot logo is also fine).
4. Set up the CollisionShape2D (use a rectangle shape or capsule shape and resize it around the sprite).

This is the basic structure for a 2D player in Godot!

---

## 🎯 Your Main Goal

You’ll build a simple scene where:

- A player character can move around using arrow keys or WASD.
- Create timemap for level and develop any map you like, to know more about TileMap refer to ![this article](https://docs.godotengine.org/en/latest/tutorials/2d/using_tilemaps.html) or ![this video](https://www.youtube.com/watch?v=sbv35boXqac)
- The movement should feel smooth and responsive.

Try making it funny, stylish, or totally weird — this is your playground!

---

## ✅ Week 1 Tasks

### 1. 🌀 Teleport Pads

- Add two **Area2D** nodes on the map (some sprite attached to it or your choice).
- When the player enters one, they should be instantly teleported to the second.
- This will help you learn signals and position changing!

---

### 2. 🎨 Sprite Color Changer

- Make it so that when you press the **C** key, your player changes color.
- Use the `modulate` property of the sprite to do this.
- Bonus: Add a few different colors(more than two) that change every time you press C,(change should be in cyclic order)

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
