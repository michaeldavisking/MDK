---
title: "Transmutation"
excerpt: "Game development graduate class project. Made in Unreal Engine, December, 2024"
header:
  image: /images/part_running.gif
  teaser: /images/part_running.gif
  
gallery1:
  - url: /images/part1.png
    image_path: /images/part1.png
gallery2:
  - url: /images/partdoc1.png
    image_path: /images/partdoc1.png
gallery3:
  - url: /images/partdoc2.png
    image_path: /images/partdoc2.png
gallery4:
  - url: /images/partdoc2.png
    image_path: /images/part_space.jpg
gallery5:
  - url: /images/Boids.gif
    image_path: /images/Boids.gif
---

**Introduction**

Transmutation was a 2024 Game Development Class Project. It is a five to seven minute horror experience where the player has been called by a research colleague to recover their documents after an experiment gone wrong. They have to collect keys to unlock doors leading to the documents and are killed by a monster before they have recover anything or escape from the mansion.

**Development**

Development for this project was done by Myself and my cohort member Stella Park. I designed the game environment in blender and imported the assets in groups to Unreal Engine. The textures for the objects are made from free textures or simple handmade textures in the engine.

<img src="images/partdoc1.png" alt="A screenshot of Particles in Unreal Engine" width="720" height="500">

I also designed the lighting and sound for the environment. I wanted a balance of lighting so the scene was navigable and warm while still providing a layer of unease. The sounds in the scene help to establish a more immersive environment and keep the game from being too silent. This is mainly accomplished through the ambient storm which has lighting added through a rect light that increases in intensity.

<video width="480" height="320" controls="controls">
  <source src="images/Transmutation_Sound_Examples.mov" type="video/mov">
</video>

The sounds were sourced from sound libraries and recorded by me. There is a blend of spatial noise and non spatial sound volumes. This ensures that sounds are heard properly in the spaces they should play.

My other area of focus was on the AI monster that attacks the player at the end of the game. The monster is sourced from sketch fab and came with animations that I blended in Unreal Engine.

The AI functions off a behaviour tree which controls its ability to chase the player or randomly roam around the level. This ensures that if the monster loses the player or is unable to reach them, it can fall back on a random roaming behaviour and still looks natural in the game.

 **Learned**

This project allowed me to gain further experience in the Unreal Game Engine. I was able to make complex blueprints to control in-game events, design cinematic moments with sound and camera shake, and animation blend with a character sourced from sketchfab. I was able to use this experience to work more inside of Github to practice version control and game building with a team.
