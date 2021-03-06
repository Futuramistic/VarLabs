# VarLabs

As GithHub cannot store large files and stopped cooperating mid project, here you can find the ZIP of: 
* exercises 1-6: <a href="https://drive.google.com/drive/folders/1lt5Xv7QdjEpAdOxGfysoCn7mmhtgoW93?usp=sharing">Link</a>
* exercise 7: <a href="https://drive.google.com/drive/folders/1dZeXNUAvP11S_suSMFb1g6xOCdqBEBKF?usp=sharing">Link</a>

A set of weekly exercises and assignments to familiarize with the Unreal Engine for CS3247 class at NUS
Content:
1. Introduction to Unreal
2. Blueprinting
3. Blueprint Communication
4. Locomotion and Perspective
5. Physics
6. Materials
7. AI

## Introduction to Unreal
Familiarity with some of the foundational components of Unreal Engine 4 and experience in virtual reality.

Content:
* Navigate through a game world in the Viewport
* Place an actor in the world using the Content Browser or Place Mode
* Change an actor’s position, scale, and rotation as well as edit other attributes in the Details panel
* Use lights to better illuminate game world
* Change a Static Mesh’s material
* Create Material Instances

Levels:
* Scale (HW_Scale)
  * The relative size of objects in a VR scene can have a powerful effect on the viewer. 
  When immersed in a stereoscopic environment, 
  the viewer is able to infer more about scale because the environment is rendered for each eye at slightly different positions.
    This level uses scale in a meaningful way, by making the viewer feeling small.
* Rotational Degrees of Freedom (HW_Rotation)
  * The headset tracks three rotational degrees of freedom: pitch, yaw, and roll. 
    With this information, the headset can provide a more immersive environment as the viewer rotates.
    This level inspires the viewer to rotate.
* Translational Degrees of Freedom (HW_Translation)
  * The headset also tracks three translational degrees of freedom: up/down, left/right, and forward/backward. 
    With this information, the headset can provide a more immersive environment as the viewer moves in position.
    This level inspires the viewer to move their head.
* Dark forest (HW_MyVR)

|Scale|Rotation|Translation|Forest|
|------|------|------|------|
|![](https://github.com/Futuramistic/VarLabs/blob/master/Promo/Images/scale.PNG)|![](https://github.com/Futuramistic/VarLabs/blob/master/Promo/Images/rotation.PNG)|![](https://github.com/Futuramistic/VarLabs/blob/master/Promo/Images/translation.PNG)|![](https://github.com/Futuramistic/VarLabs/blob/master/Promo/Images/forest.PNG)|

Overall grade:

## Blueprinting
Building actors with defined behaviour.

Content:
* Using Blueprints as a way to define the look and behavior of a type of actor.
* Scripting using UE4’s visual scripting language.
* Enriching experience with audio and particle emitters
* Using vector math to manipulate actors in 3D space.
* Reacting to actor collision.
* Using Timers to repeatedly do things.
* Using Functions to encapsulate a bunch of reusable code.
* Using public variables and the construction script to alter blueprints from the Level Editor.

Levels:

* Lean (HW_Lean)
  * Inspire the viewer to lean in for better perspective.
* Dip (HW_Dip)
  * Inspire the viewer to dip, dodge, duck, dive, and/or dodge.
* Left (HW_Left)
  * Inspire the user to look left/right or up/down repeatedly.
  
  |Lean|Dip|Left|
  |------|------|------|
  |![](https://github.com/Futuramistic/VarLabs/blob/master/Promo/Images/Lean.PNG)|![](https://github.com/Futuramistic/VarLabs/blob/master/Promo/Images/Dip.PNG)|![](https://github.com/Futuramistic/VarLabs/blob/master/Promo/Images/Left.PNG)|
  
## Blueprint Communication 

<i align="right">Photo: Link to youtube level showcase</i>
<a href="https://youtu.be/4Z7t-nAWpAM" align ="right">
 <img src="http://i3.ytimg.com/vi/4Z7t-nAWpAM/hqdefault.jpg" align="right">
</a>

Blueprint communication paradigms

Link to built level: <a href="https://drive.google.com/drive/folders/1hjqCbw3l_kT4a0p6vmYejOT6ms9zY1-n?usp=sharing">Link</a>

Content:
* Blueprint Communication
  * Creating Custom Events.
  * Using Cast To nodes to fire events on other actors.
  * Using Blueprint Interfaces when you find a common interaction between multiple blueprints.
* Creating custom curves with Timeline
* Animating actor properties with Sequencer

## Locomotion and Perspective

<i align="right">Photo: Link to youtube level showcase</i>
<a href="https://youtu.be/xsC9kT13r_4" align ="right">
 <img src="http://i3.ytimg.com/vi/xsC9kT13r_4/hqdefault.jpg" align="right">
</a>

Character movement. Avoiding motion sickness in virtual reality.

Link to built levels: <a href="https://drive.google.com/drive/folders/1hSY6sMxvO4tZsYtzGH6PMhrwk0RGzNek?usp=sharing"> Link </a>

Types of games concerned:
* First Person
* 2.5D
* Point and Click
* Stationary Cameras

Content:
* Create a character that moves using the CharacterMovement component
* Use your mouse in game to interact with a 3D world
* Possess external cameras for Third Person experiences
* Experiment with different types of locomotion and perspective
* Use collision components to define overlap triggers
* Change levels
* Fade the camera in and out


## Physics

<i align="right">Photo: Link to youtube level showcase</i>
<a href="https://youtu.be/aF1eCuQIXIs" align ="right">
 <img src="http://i3.ytimg.com/vi/aF1eCuQIXIs/hqdefault.jpg" align="right">
</a>

Physics simulations. 

Link to built levels: <a href="https://drive.google.com/drive/folders/1J5DQf9-e2ehc1bJpOJKkrCrt6OllKhVf?usp=sharing">Link</a>

Content:
* Moving objects
* Gravity
* Radial forces
* Time dilation 
* Picking objects

Levels:

## Materials

<img src="https://github.com/Futuramistic/VarLabs/blob/master/Promo/GIFs/Lava.gif" align="right">

Basics of materials

Content:
* Textures
* Texture Coordinates
* Masking with textures
* Emissive colours
* Normal maps
* Material Instances
* Dynamic materials

## AI

<i align="right">Photo: Link to youtube level showcase</i>
<a href="https://youtu.be/5GnqzFIDwWI" align ="right">
 <img src="http://i3.ytimg.com/vi/5GnqzFIDwWI/hqdefault.jpg" align="right">
</a>

Writing classes which used for making blueprints for AI. 

Link to built levels: <a href="https://drive.google.com/open?id=1x-q2dchdYKG1Tj9VuTAhVqENQaBkVE9o">Link</a>

Content:
* Setting up a Nav Mesh Bounds Volume.
* Creating and coding out C++ Classes
* Using Blackboards and Behavior Tree.



