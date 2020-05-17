# Matthew Nagy - IMGD 4000 - Team JAMMIN: Cartograbird Documentation


## My Role


My name is Matthew Nagy and my role for team JAMMIN was making a few particle effects, implementing all the sounds, how they interact with the world,
and the state machines that power the animations and their transitions. All of this was done using Unreal Engine's blueprints and particle engine.


## Challenges I Faced and Overcoming Them


Some challenges I encountered often times finding the right sounds that felt like they would fit into the game. Not every sound is made to loop and finding ways
to edit the sounds and manipulate them using other audio resources like Reaper to edit them was something I did often to try to make the sounds sound as good as possible.
A large bulk of my time was spent learning how animation state machines worked in Unreal and figuring out some issues with the artists and communicating how they should
export rigs and the animations, and for me to learn how to properly import them to ensure that Unreal recognizes what animations belong to what skeleton.
I ended up having to learn how to retarget an animation to use a different skeleton, even if it was literally the same skeleton with a different name.
Most notably, I had very little engine experience with Unreal prior to this class. I had used Unity a handfull of times but this was the deepest dive into
a game engine that I have really experienced in my WPI career, and career in general. I would say that to any students who are ever unfamiliar with something,
don't be afraid to ask questions from your peers, but first, google your question, word it a bunch of different ways, and look to see tutorials of someone
else that may have done it, research and then communication will help you solve most of your problems.


![Image of FireParticleEX](https://github.com/AstroSeer/JamminMattDoc/blob/master/FireParticleEX.PNG)


Up here is an example screenshot of the fire particle system, I created a spherical space for it to put out the particles, firstly making a bright material and a material 
instance, chose the colors, added in a transition and adjusted how I wanted that color to transition into, adjusted the range of sizes and what shapes the particles make 
as well, which was really intersting and I feel that the simple low poly style of particles I chose fit the game world, I did the same procedure with the clouds.


![Image of BlendspaceEX](https://github.com/AstroSeer/JamminMattDoc/blob/master/BlendspaceEX.PNG)


This is an image of a blendspace I used for how the strafing movement is implemented with how the character moves, I did this for the Deer as well.


![Image of CarmenStateLogic](https://github.com/AstroSeer/JamminMattDoc/blob/master/CarmenStateLogic.PNG)


This is an image the state machine logic for how carmen updates and transitions between his animations, using blueprints.


![Image of CarmenStateMachine](https://github.com/AstroSeer/JamminMattDoc/blob/master/CarmenStateMachine.PNG)


This is an example showing how the animation graph looks and the links between the different states that played the animations.


![Image of Sounds](https://github.com/AstroSeer/JamminMattDoc/blob/master/Sounds.PNG)


Small image showing the sounds and their sound cues.


![Image of WaterEX](https://github.com/AstroSeer/JamminMattDoc/blob/master/WaterEX.PNG)


This is an image showing how the sound cues look and the randomization and attentuation added to most sounds to add variation and avoid repitition.


## Game Project Architecture


![Image of graph](https://github.com/AstroSeer/JamminMattDoc/blob/master/graph.png)


This shows how the work was planned out and distributed and is mostly accurate to how the final project panned out, although I did dip my toes into particle effects.


## Version Control


We used git for our version control and my experience was as chaotic as my first experience with Git during CS-3733, Software Engineering. Although the chaos
that stemmed from Soft. Eng. was because that was my very first experience using it, using it with Unreal would often times create frustrating moments for myself
and other group members. Often times files would corrupt and the game world could only have one person working on it at a time, since you cannot merge together
two different worlds. Aside from those examples, in general, it did tend to work, but I am VERY open to trying different forms of version control for Unreal
on my future group projects.


## Credits


Lastly, almost all of my sounds were obtained from https://freesound.org/ but here is the list of all sounds I used and edited, with the addition of one sound
that I ended up making myself.
https://freesound.org/people/Ali_6868/sounds/384865/       -Grass Step
https://freesound.org/people/AgentDD/sounds/246225/        -Flap
https://freesound.org/people/RensvdMeijs/sounds/377068/    -Wind
https://freesound.org/people/straget/sounds/415053/        -Water
https://freesound.org/people/DDmyzik/sounds/468212/        -Music
https://freesound.org/people/AmberdeMeillon/sounds/443065/ -Leaf Rustle
https://freesound.org/people/Splatez07/sounds/413690/      -UI Click
https://freesound.org/people/Anthousai/sounds/398897/      -Map Rustle
https://freesound.org/people/Anthousai/sounds/398897/      -Dialogue Popup
https://freesound.org/people/TriqyStudio/sounds/467604/    -Inventory
https://freesound.org/people/Greencouch/sounds/124899/     -Pause Menu
https://freesound.org/people/Alexbuk/sounds/391754/        -Plane
https://freesound.org/people/onehugeeye/sounds/511318/     -Landing on Grass
https://freesound.org/people/DeepPurple5/sounds/448975/    -Wing Rustle
Grunt- Matthew Nagy
https://freesound.org/people/PhreaKsAccount/sounds/46272/  -Fire
https://freesound.org/people/_nuel/sounds/54973/           -Crow
https://freesound.org/people/msantoro11/sounds/351113/     -Deer
