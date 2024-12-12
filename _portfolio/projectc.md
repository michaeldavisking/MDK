---
title: "Transmutation"
excerpt: "A short narrative horror experience. Made in Unreal Engine, December, 2024"
header:
  image: /images/transmutation_cover.png
  teaser: /images/transmutation_cover.png
  
gallery1:
  - url: /images/transmutation_Layout.png
    image_path: /images/transmutation_Layout.png
gallery2:
  - url: /images/transumtationblend.gif
    image_path: /images/transumtationblend.gif
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

Transmutation was a 2024 Game Development Class Project. It is a five to seven minute horror experience where the player has been called by a research colleague to recover their documents after an experiment gone wrong. They have to collect keys to unlock doors leading to the documents and are killed by a monster before they have recovered anything or escape from the mansion.

**Development**

Development for this project was done by Myself and my cohort member Stella Park. I designed the game environment using a combination of Maya and Blender. I would design individual rooms, UV unwrap them, and then import them in groups to Unreal Engine. The textures for the objects are made from free textures or simple handmade textures in the engine.

{% include gallery id="gallery1" caption="Above view of game layout" %}


I also designed the lighting and sound for the environment. I wanted a balance of lighting so the scene was navigable and warm while still providing a layer of unease. The sounds in the scene help to establish a more immersive environment and keep the game from being too silent. This is mainly accomplished through the ambient storm which has lighting added through a rect light that increases in intensity. I put focus into decoration when possible in the time frame of the class in order to establish a time period and make the mansion appear more lived in. gas lamps, minimal electric lighting, and paintings of King Edward establish a year in the early 1900s and a setting somewhere in England.

{% include video id="1Byd3PeZpqOCnC3KpdQ6KG2nI-zo5apTO" provider="google-drive" %}
  
The sounds were sourced from sound libraries and recorded by me. There is a blend of spatial noise and non spatial sound volumes. This ensures that sounds are heard properly in the spaces they should play.

My other area of focus was on the AI monster that attacks the player at the end of the game. The monster is sourced from sketch fab and came with animations that I blended in Unreal Engine.

{% include gallery id="gallery2" caption="Amnesia monster asset found on sketchfab animation blended based on speed" %}

The AI functions off a behaviour tree which controls its ability to chase the player or randomly roam around the level. This ensures that if the monster loses the player or is unable to reach them, it can fall back on a random roaming behaviour and still looks natural in the game.

An inclusion that helps to build suspense in the game is the camera shake that happens at two areas within the game. The first is just after the player unlocks the door to the main body of the level, and the second is after finding the hidden room where the final key is. The camera shake is followed with a monster sound and in the second there is a crackling that can be heard which hints to an increased presence of the monster or some other malevolent force.

{% include video id="1d27oQ0YLGNgcQV9OncAKij8vztbb75o-" provider="google-drive" %}

 **Learned**

This project allowed me to gain further experience in the Unreal Game Engine. I was able to make complex blueprints to control in-game events, design cinematic moments with sound and camera shake, and animation blend with a character sourced from sketchfab. I was able to use this experience to work more inside of Github to practice version control and game building with a team. I was able to further my experience with environmental storytelling and narrative building. Notes written by myself and edited by my partner along with custom environmental queues build suspense and feed the player small pieces of information about the world they inhabit.
