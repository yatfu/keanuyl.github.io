---
layout: project
type: project
image: images/HeAuHou.PNG
title: He Au Hou
permalink: projects/HeAuHou
# All dates must be YYYY-MM-DD format!
date: 2017-07-23
labels:
  - Blender
  - Unity
  - C++
  - Game Development
summary: My group created a point-and-click adventure game in Unity that focuses on telling the ancient stories of Hawaiian akua, with a sci-fi twist.
---

<div class="ui large rounded images">
  <img class="ui image" src="../images/HeAuHou2.jpg">
  <img class="ui image" src="../images/HeAuHou1.png">
  <img class="ui image" src="../images/HeAuHou4.PNG">
</div>
He Au Hou is a project of the Initiative for Indigenous Futures (IIF) Na 'Anae Mahiki, a collaboration of Kamehameha Schools, Concordia University of Montreal, and chosen participants from all across Hawai'i. Within a three-week period, our team were responsible for coming up with and creating a game with a focus on Hawaiian culture/storytelling. Along with brainstorming ideas, finalizing a theme/story, and creating the game, we also had to learn the software required, which included a 3D creation suite (Blender), game engine (Unity), audio editor (Audacity), and image editor (Photoshop).

Our final product, He Au Hou, is aenture game that focuses on storytelling and star navigation, two fundamental aspects of Hawaiian culture. In the game, you play as a space pilot trying to find your sister, lost in space. Along the way, you encounter Hawaiian gods and dieties and have to solve their puzzles. 

Micromouse is an event where small robot “mice” solve a 16 x 16 maze.  Events are held worldwide.  The maze is made up of a 16 by 16 gird of cells, each 180 mm square with walls 50 mm high.  The mice are completely autonomous robots that must find their way from a predetermined starting position to the central area of the maze unaided.  The mouse will need to keep track of where it is, discover walls as it explores, map out the maze and detect when it has reached the center.  having reached the center, the mouse will typically perform additional searches of the maze until it has found the most optimal route from the start to the center.  Once the most optimal route has been determined, the mouse will run that route in the shortest possible time.

For this project, I was the lead programmer who was responsible for programming the various capabilities of the mouse.  I started by programming the basics, such as sensor polling and motor actuation using interrupts.  From there, I then programmed the basic PD controls for the motors of the mouse.  The PD control the drive so that the mouse would stay centered while traversing the maze and keep the mouse driving straight.  I also programmed basic algorithms used to solve the maze such as a right wall hugger and a left wall hugger algorithm.  From there I worked on a flood-fill algorithm to help the mouse track where it is in the maze, and to map the route it takes.  We finished with the fastest mouse who finished the maze within our college.

Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [Skins 5.0 Website](http://skins.abtec.org/skins5.0/).



