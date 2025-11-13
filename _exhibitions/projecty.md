---
title: "Put Me On"
excerpt: "Voice activated particles in Virtual Reality. Made in Unreal Engine. Displayed at Birdblock Ceramics Studio, 2025"
header:
  image: /images/putmo_running.gif
  teaser: /images/putmo_running.gif
  
gallery1:
  - url: /images/putmo1.png
    image_path: /images/putmo1.png
gallery2:
  - url: /images/putmo2.png
    image_path: /images/putmo2.png
gallery3:
  - url: /images/putmo3.jpg
    image_path: /images/putmo3.jpg
gallery4:
  - url: /images/partdoc2.png
    image_path: /images/part_space.jpg
gallery5:
  - url: /images/Boids.gif
    image_path: /images/Boids.gif
---

## Particles

**Introduction**

Put Me On builds on Particles to introduce a sound activated interactable particle. Guests at the Bird Block exhibition were asked to explore the range of colors that are created through changes in pitch which will change the rgb values of the particle texture in real time. 


{% include gallery id="gallery1" caption="A screen shot of Particles in Unreal Engine" %}

**Development**

Put Me On uses Particles as a template project, changing the spline to a single point of attraction that will slowly pull in all the particles. Guests are able to move the particles with their hands using an expanded physics interaction that places point forces on each xr hand joint allowing for high fidelity interaction. The volume of the person in the headset will also control the rate at which the particles move on their own through randomized physics forces.

**Display**
Put Me On was displayed in the Bird Block gallery where it ran independantly for 4 hours. It was displayed on a Oculus Quest 3 headset connected to a standard Gaming Laptop.

{% include gallery id="gallery2" caption="Put Me On display" %}



{% include gallery id="gallery3" caption="" %}
