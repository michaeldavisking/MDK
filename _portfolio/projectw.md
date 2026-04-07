---
title: "Vauquois"
excerpt: "Applied Research in Immersive Experiences and Simulations project, ongoing"

header:
  image: images/AV_Cover.png
  teaser: images/AV_Cover.png
  
gallery1:
  - url: images/AV_meshprereduce.png
    image_path: images/AV_meshprereduce.png
gallery2:
  - url: images/AV_Junction_Scene.png
    image_path: images/AV_Junction_Scene.png
gallery3:
  - url: /images/AV_meshreduced.png
    image_path: /images/AV_meshreduced.png
gallery4:
  - url: /images/AV_Unrealdetail.png
    image_path: /images/AV_Unrealdetail.png
gallery5:
  - url: /images/Boids.gif
    image_path: /images/Boids.gif
---
**Introduction**

Vauquois is a long term ARIES project dedicated to the creation of an authentic representation of the tunnels of Vauquois. These tunnels were the site of German and French confrontations beneath a hilltop village in an attempt to prevent German forces from maintaining control of a critical viewing and gun platform during the battle of Verdun. 

**Development**

I was tasked with taking data from 2016 Faro Scans and using cloudcompare to clean, reduce, and mesh them into 3D assets that could be used in the Unreal engine for rendering, traditional serious game and serious VR games. 

The polished and game ready meshes were textured in Adobe Substance Painter and carefully labeled and stored in the event of any necessary adjustments or additions to the meshes or textures. I designed all assets to work with Nantie and Lumen to allow efficient and volumetric lighting that remained compatible with Virtual Reality Viewing from the Meta Quest 3.

{% include gallery id="gallery2" caption="Tunnel Junction in scene Project. Junction is made from a combination of Faro and GeoSLAM point clouds" %}
{% include gallery id="gallery1" caption="The Tunnel Meshes start as a high density point cloud incompatible with mesh making for game engines in real time. These higher density clouds could have value as renderable mesh assets in the future." %}
{% include gallery id="gallery3" caption="The tunnel segment is reduced in cloud compare, then the normals are calculated before poisson reconstruction is used to build a mesh" %}
{% include gallery id="gallery4" caption="detailed lighting view in unreal engine on cloud compare mesh with light decimation in Blender" %}


In addition to texturing and modeling I coordinated with the assigned programmer to optimize levels in Unreal to allow higher polygon count meshes in order to balance the desire for an authentic representation of the tunnels and the needs of a VR experience. 
  
I had control over the project file organization and version control managed through Perforce. I managed files across multiple cloud storages and also documented my workflow to benefit the future development of the project.


