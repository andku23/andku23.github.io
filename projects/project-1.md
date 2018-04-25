---
layout: project
type: project
image: images/holosage.jpg
title: HoloSage
permalink: projects/hale
# All dates must be YYYY-MM-DD format!
date: 2017-08-01
labels:
  - Unity
  - AR/VR/Mixed Reality
  - Microsoft Hololens
summary: Create a Mixed Reality learning environment for the Microsoft Hololens to assist the navy in training new recruits.
---

<div class="ui small rounded images">
 
</div>

## Introduction

HoloSage was a project that I started while working in the Laboratory for Advanced Visualizations and Applications (LAVA).  This project was actually contracted by one of the navy departments, because they wanted to see if they could use Augmented Reality (AR) to teach new users how to operate and maintain large vehicles such as submarines.  The original idea was that they wanted to use the Microsoft Hololens, and have a senior engineer walk around a room and create different notes in different locations.  For example they could leave text notes by certain dials that specified what each dial did and why they were important.  They could also get different colored pens and draw notes into the 3D space to mark things like designated paths and dangerous areas.

## Starting the Project

When I first started working on HoloSage, I had absolutely no idea how to do AR development.  I did have prior experience in developing for Unity as well as some VR development, but AR was a completely new field for me.  In addition to this, AR is still a relatively new field at least when developing for the Hololens.  There wasn't a lot of good descriptive documentation online, which made learning it even more difficult.  It took me a really long time before I even had something resembling the project.  I remembered the first feature I implemented was the ability to draw using the AirTap gesture on the hololens.  You could get your hand, pinch and move it around, and a line would draw where you were looking.  I was really happy to get this working because up until this point I was having next to no results and no way to see if what I was doing was working.  After this I then added in saving and loading the points of the line to the Hololens, so now there was a way to persistently store the lines you drew.

## Restructuring

Around this time I was getting pretty comfortable with writing for AR.  

         The Holographic Accelerated Learning Environment (HALE) is a 
    Mixed Reality program that will use a series of holograms to train 
    a user to use any device within a room.  This use of Mixed Reality 
    as a teaching tool will allow the user to be able to see an 
    interactive set of instructions projected into the real world, 
    allowing them to learn in an augmented version of the working 
    environment.
    
        The HALE will be able to be used in two main steps.  First, an instructor 
    will put on the hololens and proceed to use the program to document a room or 
    object.  Documenting a room will consist of creating holograms within the 
    world that will display things such as drawings and annotations, written 
    instructions, usage tips for devices, points of interest, audio recordings 
    and warning markers.  The instructor will be able to create as many or as 
    little notes as they would like within the 3D environment.  Once the 
    instructor feels that they have an adequate amount of notes to teach a new 
    user, they can save all of the holograms they created in their overlay to a 
    file.  This file can either be stored locally within the hololens, or 
    uploaded to a server.  
    
        When a student or new user  would like to learn how to use the documented 
    material, they will be able to use the file saved by the instructor.  The user 
    can either put on the same hololens as the instructor, or their own hololens 
    containing the HALE program and download the hologram file from a server.  
    Once the file is downloaded the user will be able to see all of the notes that 
    the instructor created.  The user will be able to learn more efficiently by 
    being able to see all of the annotations within the actual work environment.
