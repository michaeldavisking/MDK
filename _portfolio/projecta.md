---
title: "Vauquois"
excerpt: "Applied Research in Immersive Experiences and Simulations project, ongoing"

header:
  image: images/AV_Cover.png
  teaser: images/AV_Cover.png
  
gallery1:
  - url: images/AV_Junction_Blender.png
    image_path: images/AV_Junction_Blender.png
gallery2:
  - url: images/AV_Junction_Scene.png
    image_path: images/AV_Junction_Scene.png
gallery3:
  - url: /images/AV_Junction_remesh_Unreal.png
    image_path: /images/AV_Junction_remesh_Unreal.png
gallery4:
  - url: /images/AV_Tunnel_Junction_unreal_with_lighting.png
    image_path: /images/AV_Tunnel_Junction_unreal_with_lighting.png
gallery5:
  - url: /images/Boids.gif
    image_path: /images/Boids.gif
---
**Introduction**

Vauquois is a long term ARIES project dedicated to the creation of an authentic representation of the tunnels of Vauquois. These tunnels were the site of German and French confrontations beneath a hilltop village in an attempt to prevent German forces from maintaining control of a critical viewing and gun platform during the battle of Verdun. 

**Development**

I was assigned to take previously captured Faro Scan and GeoSLAM point clouds from Scene to Maya and/or Blender to build a 3D mesh before polishing and retopologizing them to be compatible with Unreal Engine 5.6.

The polished and game ready meshes were textured in Adobe Substance Painter and carefully labeled and stored in the event of any necessary adjustments or additions to the meshes or textures. I designed all assets to work with Nantie and Lumen to allow efficient and volumetric lighting that remained compatible with Virtual Reality Viewing from the Meta Quest 3.

{% include gallery id="gallery2" caption="Tunnel Junction in scene Project. Junction is made from a combination of Faro and GeoSLAM point clouds" %}
{% include gallery id="gallery1" caption="Tunnel Junction in Blender, point coulds are converted to highpoly tri-meshes" %}
{% include gallery id="gallery3" caption="Tunnel Junction in Unreal Engine after remeshing and touch up in Zbrush" %}
{% include gallery id="gallery4" caption="Tunnel Junction in Unreal Engine with inital lighting pass" %}


In addition to texturing and modeling I coordinated with the assigned programmer to optimize levels in Unreal to allow higher polygon count meshes in order to balance the desire for an authentic representation of the tunnels and the needs of a VR experience. 
  
I had control over the project file organization and version control managed through Perforce. I managed files across multiple cloud storages and also documented my workflow to benefit the future development of the project.
{% include video id="1Y_kw4uwHOM8srErhW_dJy-6TWU4LyhR9" provider="google-drive" %}


