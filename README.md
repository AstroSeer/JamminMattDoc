# Matthew Nagy - IMGD 4000 - Team JAMMIN: Cartograbird Documentation


##My Role


My name is Matthew Nagy and my role for team JAMMIN was making a few particle effects, implementing all the sounds, how they interact with the world,
and the state machines that power the animations and their transitions. All of this was done using Unreal Engine's blueprints and particle engine.


##Challenges I Faced and Overcoming Them


Some challenges I encountered often times finding the right sounds that felt like they would fit into the game. Not every sound is made to loop and finding ways
to edit the sounds and manipulate them using other audio resources like Reaper to edit them was something I did often to try to make the sounds sound as good as possible.
A large bulk of my time was spent learning how animation state machines worked in Unreal and figuring out some issues with the artists and communicating how they should
export rigs and the animations, and for me to learn how to properly import them to ensure that Unreal recognizes what animations belong to what skeleton.
I ended up having to learn how to retarget an animation to use a different skeleton, even if it was literally the same skeleton with a different name.
Most notably, I had very little engine experience with Unreal prior to this class. I had used Unity a handfull of times but this was the deepest dive into
a game engine that I have really experienced in my WPI career, and career in general. I would say that to any students who are ever unfamiliar with something,
don't be afraid to ask questions from your peers, but first, google your question, word it a bunch of different ways, and look to see tutorials of someone
else that may have done it, research and then communication will help you solve most of your problems.


![Image of fire](https://github.com/AstroSeer/JamminMattDoc/blob/master/FireParticleEX.PNG)


Up here is an example screenshot of the fire particle system, I created a spherical space for it to put out the particles, firstly making a bright material and a material 
instance, chose the colors, added in a transition and adjusted how I wanted that color to transition into, adjusted the range of sizes and what shapes the particles make 
as well, which was really intersting and I feel that the simple low poly style of particles I chose fit the game world, I did the same procedure with the clouds.