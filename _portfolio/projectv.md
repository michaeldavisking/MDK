---
title: "Truck Simulation"
excerpt: "Applied Research in Immersive Experiences and Simulations project, ongoing"

header:
  image: images/AT_Cover.png
  teaser: images/AT_Cover.png
  
gallery1:
  - url: images/AT_Levels.png
    image_path: images/AT_Levels.png
gallery2:
  - url: images/AT_Level_Sequences.png
    image_path: images/AT_Level_Sequences.png
gallery3:
  - url: /images/AT_Audio_In_Level_Sequence.png
    image_path: /images/AT_Audio_In_Level_Sequence.png
gallery4:
  - url: /images/AT_Truck_UI.png
    image_path: /images/AT_Truck_UI.png
---
**Introduction**

The Virginia Tech Transportation Institute Truck simulation is an ARIES project designed for a web based and VR conference based experience. The aim of the project is to demonstrate the safety features found in the Detroit Assurance and Bendix Wingman Fusion systems. 

**Development**

The entire demonstration of these features is done through an on rails method with all audio and UIchanges happening through custom made level sequences for each scenario.  

{% include gallery id="gallery1" caption="Levels for the Detroit Assurance Demonstrations" %}
{% include gallery id="gallery2" caption="Corresponding Level Sequences for the Demonstrations" %}

Audio is controlled through several sound sources on the Truck which are triggered via the level sequencer to deliver audio in authentic locations to where the user would hear them in the truck.

{% include gallery id="gallery3" caption="Example of an Audio Queue in the Level Sequencer" %}


The Ui is integrated directly into the dashboard and is similarly triggered by the level sequencer to display warning messages in a way authentic to the Detroit Assurance and Bendix Wingman Fusion Systems. 

{% include gallery id="gallery4" caption="Truck UI in Unreal UI editor" %}
