---
layout: ../../layouts/MarkdownPostLayout.astro
title: "Click the Squares"
pubDate: 22-11-2024
description: "This blog post will be updated with content about my game, Click the Squares."
author: "Jakob Frederikson"
image:
  url: "/src/assets/blog/icons/robot-antennas.png"
  alt: "Robot Antennas Icon"
tags: ["game-dev"]
---

### Update from 06-04-2025
Not sure if this project will continue due to lack of 'flame' for this project. Possibly, I'll continue with this game later in life! I ended making some really cool tools with this game, like having an 'auto clicker' upgrade and a randomizer for spawning the squares around the level (as well as others). If you would like to take a look at the code, you can check it out [here](https://github.com/jakobfrederikson/squaresgame). I've left some screenshots of what the game looks like in its current state below.
<div class="post-2-images">
<img src="/src/assets/blog/post-2/SquaresGame_01.png" alt="Screenshot 1, showing the main menu of Click the Squares." />
<img src="/src/assets/blog/post-2/SquaresGame_02.png" alt="Screenshot 2, showing the level select screen." />
<img src="/src/assets/blog/post-2/SquaresGame_03.png" alt="Screenshot 3, showing what playing a level looked like." />
<img src="/src/assets/blog/post-2/SquaresGame_04.png" alt="Screenshot 4, showing the upgrades menu." />
<img src="/src/assets/blog/post-2/SquaresGame_05.png" alt="Screenshot 5, showing the stats screen." />
<img src="/src/assets/blog/post-2/SquaresGame_06.png" alt="Screenshot 6, showing the Round Over screen." />
</div>


*Original blog below*
# Click the Squares

To GDScript, or not to GDScript?

This was a question I constantly asked myself while making this game. I still don't know if there is a right answer, but I did try out both GDScript and C# for this project.

Started using Godot with GD-Script, quickly found that a scripting language just doesn't work with my way of thinking.

I needed objects, I needed to segregate certain parts of the project how I wanted to... but GDscript didn't allow that.

So, I spent a morning merging from GDScript to C#. And boy, was it worth it.

I took this opportunity to work from the ground up - instead of just seeing if I can click on squares, I made sure that all of my data was able to be recorded and saved.
