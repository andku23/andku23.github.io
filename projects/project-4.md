---
layout: project
type: project
image: images/kirukata.PNG
title: Kirukata VR
permalink: kirukata/gsss
# All dates must be YYYY-MM-DD format!
date: 2017-06-01
labels:
  - Technical Art
  - VR
  - Game Design
summary: I wanted to make a VR Game where you cut things with a sword
---

<div class="ui small rounded images">
 
</div>
<div style = "width: 100%; background-color:blue">
  <iframe style = "background-color:black;overflow: hidden; width:100%;height:500px"   src="https://www.youtube.com/embed/T2_TL2cCOo4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>


## Introduction

Kirukata VR was the first game that I created for VR.  I really wanted to make a game that utilized VR to do something that I've always wanted.  In this case it was cutting flying cubes with a katana, which has always been a dream of mine.  Before I made this game, I already had a samurai sword 3D model that I made from a while ago, so I decided that it would finally be time to put it to use.

## Programming 

It turned out that programming in VR was actually ridiculously easy so long as you already knew how to program in Unity.  SteamVR made a Unity package that you could just drag in and use as a default prefab.  For the actual code I did it in two parts.  I had no idea how to cut a mesh in Unity since I had never done mesh deformation.  I looked online and found some examples of people cutting code on a plane.  What I did was I got the entrance and exit points of the sword into the object, like a cube.  Then I used those points to draw a plane through the object.  I then cut the object using the mesh cutting script examples I saw earlier.  This was a nice way to do it because the object would split into two parts, but those parts would also be cuttable by the sword.

## Conclusion

Kirukata was a fun little project to start off working in VR.  Every now and then I like to do projects that aren't directly related to work and are just for my own fun.  I feel like it stops me from going crazy.  I think if you just code for work and never do it for fun it will become harder and harder to enjoy what you're doing.
