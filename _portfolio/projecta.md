---
title: "Particles"
excerpt: "Interactable particles in Virtual Reality. Made in Unreal Engine, November, 2024"
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

## Particles

**Introduction**

Particles is an interactive Virtual Reality experience where the guest is able to push around small orbs using their hands.

This project was displayed in the 2024 pop-up exhibition at Bird Block Gallery and Ceramics Studio “Bird Bonk”. It was made to be a simple interaction so that all ages and experience levels would be able to put on the headset and understand what to do.


{% include gallery id="gallery1" caption="A screen shot of Particles in Unreal Engine" %}

**Development**

Particles uses a Niagara Particle that is bound to a spline path by several simulated physics forces. A spline in this case is a 3D closed loop which gives the piece a general shape. All the forces are adjustable and can affect the form the particle stream takes as each of the 15000 particles make their way around the spline. In the image below the force pushing the particles around the spline is the first variable followed by values controlling the rate at which the forces push and the direction that it pushes particles. In this instance the particles are allowed to be pushed forward or backward along the spline. At the end are magnetic forces that are keeping them within a certain distance from the spline.

{% include gallery id="gallery2" caption="" %}


Guests are able to push the particles out of the way using their hands which have point forces that are updated to the hand locations every frame. This was accomplished by creating an unreal vector parameter for each hand. The parameters are then updated in the VR pawn using the Blueprint below. Lastly the Niagara Particle effect has two point forces whose origins are the positions of the parameters. This creates a seamless push effect around the hands.

{% include gallery id="gallery3" caption="" %}

**Display**

Particles was displayed in a small back room of Bird Block Gallery and Ceramics Studio in Blacksburg Virginia. It was viewed by more than 30 individuals during the exhibition who put on a Quest 3 Vr headset. This headset was connected to a computer which had a build of Particles perpetually running. The cable was able to keep the headset charged during the 4 hour exhibition and did not have any connection interuption.

{% include gallery id="gallery4" caption="Particles during setup" %}

 **Inspiration**
 
This work was born out of my experimentation with Boids in both Unity and Unreal Engine 5. Boids, developed by Craig Renolds in 1987, are small objects that use a small set of rules to create flock-like behaviors. For me they were an introduction to emergent behaviors in games.

{% include gallery id="gallery5" caption="Boids in the Unity Game Engine" %}

 **Learned**

Through this work I learned how to set up Unreal Engine 5 particles and create simple interactions with them in the gamespace. This has laid a foundation that allows me to create additional particles in games, animations, or VR experiences that are able to be influenced by objects in the scene.

When displaying the piece I found that I had to help some people understand how the headset and controllers work. This created room for changes in Particles where I would use handtracking instead of controllers so that guests only need to put the headset on to engage with the piece.
