#  RetroFPS-GPJ
On this repo I will be going through the **[Retro FPS in Unity ](https://youtu.be/Kgjth3nRsFc)** by **[GamesPlusJames](https://www.youtube.com/channel/UCyBsvsU7uiurMiBZIYXvnyg)**. 

**Please Note** :
GamesPlusJames has loads of great content on his channel, including but not restricted to beginner oriented tutorials. So **please** check out his channel and tutorial.




## Contents

1. [ Description ](#description)
2. [ Changelog ](#changelog)

## 1. Description
#### What is this project and why does it exist?

I loved the tutorial and I would like to do it again. Hopefully improve on it and add more content on top. 
After each video of the tutorial, the repo is going to be updated, with the progress. Details of the updates will be found under the [ Changelog ](#changelog) category.
- Given that it is a short tutorial (9 videos, about 10 to 25 mins each), there are some bugs and issues here and there that I'd  like to address and fix. 
- Given that the editor version used in the videos is older, we might encounter issues and errors along the way, which I want to address.

**Please Note**:
- I'm using Unity version 2021.2.18f1;
- You can download the assets used in this tutorial [here](https://www.dropbox.com/s/juihs7yq93x1aon/GPJ_FPS_Assets.zip?dl=0);
- You can find the tutorial on how to add a Unity project to Git here: [Brackeys](https://www.youtube.com/watch?v=qpXxcvS-g3g);

## 2. Changelog




>## 0.0.0
>03/23/2022 • 03:31AM GMT+2
>
> Episode 0 - Preparations
>
>Created a 2D project and placed it in the git folder. Edited the engine settings and the gitignore file.
>Details on how to configure the Unity editor and the gitignore file can be found [here](https://www.youtube.com/watch?v=qpXxcvS-g3g).
>
<br/><br/>

>## 0.0.1
>03/23/2022 • 08:06pm GMT+2
>
>  Episode 1 - [Retro FPS in Unity #1 - First Person movement](https://youtu.be/Kgjth3nRsFc)
>
>Created a Player game object and a PlayerMovement script. 
>Attached the camera, the script and a Rigidbody2D to the Player. 
>
<br/><br/>

>## 0.0.2
>03/24/2022 • 08:06pm GMT+2
>
>  Episode 2 - [Retro FPS in Unity #2 - Shooting ](https://youtu.be/4H6-obIxnjg)
>
>Created a Wall and Bullet Impact prefabs. 
>Implemented a shooting system with ammo check. 
>
<br/><br/>

>## 0.0.3
>04/01/1000 • 06:50pm GMT+2
>
>  Episode 3 - [Retro FPS in Unity #3 - Billboarding & Ammo ](https://youtu.be/oY0p3QqpkBg)
>
>Created an Ammo Pickup game object and a Bill Board script. 
>Added a gun to the UI with a shoot animation. 
>
<br/><br/>

>## 0.0.4
>04/01/1000 • 08:38pm GMT+2
>
>  Episode 4 - [Retro FPS in Unity #4 - Making Enemies ](https://youtu.be/ntDhEmd8kCQ)
>
>Created Enemy game object, script for it to take dmg, to die, to move towards the Player. 
>Added an Explosion animation for the Enemy death. 
>
<br/><br/>

>## 0.0.5
>04/01/1000 • 09:32pm GMT+2
>
>  Episode 5 - [Retro FPS in Unity #5 - Health ](https://youtu.be/ohLbQb2iTpk)
>
>Created the Health system. Now the Player can take dmg and die, upon death being greeted with a death screen and a restart button that resets the scene. 
>The Enemy now shoots bullets (that deal dmg) towards the player. 
>
<br/><br/>

>## 0.0.6
>04/02/1000 • 03:55pm GMT+2
>
>  Episode 6 - [Retro FPS in Unity #6 - Adding UI ](https://youtu.be/qcjPANvdIwg)
>
>Created Health Pickup prefab. Added basic Health and Ammo UI and Camera animation simulating movement.
>Created a script that hides the mouse cursor upon starting the game.
>
>**Please Note** : Using the 2021 version of the editor, only TextMeshPro is available (for the text on the hud).
>For things to work properly, in the PlayerController scripy, you must insert `using  TMPro;` in the beginning of the script, and use this code when creating the variables `public  TextMeshProUGUI  healthText, ammoText;` .
>
<br/><br/>
>## 0.0.7
>04/03/1000 • 11:55pm GMT+2
>
>  Episode 7 - [Retro FPS in Unity #7 - Designing 3D levels with Tilemaps](https://youtu.be/MCRgJIU54pc)
>
>Created Level Editor with the Tilemap system and created a small level for testing.
>
>**Please Note** : Using the 2021 version of the editor, there is no need to import and install the 2D tilemap extras for the Rule Tile. It is already included. 
>What you have to do is right click in the desired folder `Create > 2D > Tiles > Rue Tile`.
>
<br/><br/>

