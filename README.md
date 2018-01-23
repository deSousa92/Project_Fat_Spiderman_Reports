# Project_Fat_Spiderman_Report

#### **INITIAL IDEA / CONCEPT OF THE PROJECT**

The initial concept for this project was based on puzzle and physics gameplay. Early brainstorming had been influenced by puzzle games such as Portal and Inside. Our idea started focusing on the games physics and its possibilities for puzzle making and solving. 
Relying mostly on the physical interactions between assets the idea grew around the players ability to utilise certain objects to his advantage or disadvantage to complete the levels.

We were initially trying to achieve this by adding some special abilities to the playable character such as a grappling hook. The grapple would allow the player to reach for the required prop that would help him solve the puzzle or allow him to overcome an obstacle by swinging around specific parts in the level.

Our unique selling point was well-defined by the grappling hook and we soon began developing the game design around that feature. Following a group merge, the game started having more elaborate ideas being stirred into the pot and the team agreed in keeping the abilities simple and with a unique purpose. Eventually we decided to scrap the idea of being apple to pull objects towards you and instead came up with a weight-based system that would blend into the puzzle system by working in favour or against the players in the game.

The concept became known as the Fat Spiderman project, a first-person puzzle game where the players objective is to solve platformer puzzles to go from an area to the other. The puzzles are based on the swinging and on the weight of the player, who will have to exhibit good control of the characters abilities and movement to make it through the challenges.
The character’s main abilities were narrowed down to a set of two; a grappling hook that serves as a movement enhancer, allowing the player to swing over greater distances, and an ability to absorb and/or release items that would affect the character’s weight and consequently its movement abilities but also his strength. 


#### **TEAMWORK**

Having two programmers with previous game making experience, Sam and Mike took responsibility for creating the core game mechanics that we would be using for the game. This allowed our team to subdivide into two. We scheduled weekly meetings up so that we could assign our weekly tasks and discuss any ideas or problems that may have arisen. 

The teams kept each other updated with what they were doing at all times to avoid people overwritting eachother's work. Luckily for our team, Sam and Mike were always available to sort any problems that we may have encountered, or issues with the merging platform. In the end our team leaders found a good way to manage our resources and a good chemistry was evident in those that were most involved.

#### **ART & MODELLING**

While our programmers sorted the core mechanics of the game I began working on the level design as well as sketching out and modelling the most important assets for the game. 

#### **WEAPON MODEL**

The Fat Spiderman character was visualised owning a sort of ‘fat gun’ that would allow him to suck fat from nearby fat sources. The gun itself was inspired in vacuum cleaners, from old to contemporary, and the character would have to use both of his hands to carry it.
It would feature a grapple launcher under the main barrel from where it would shoot the grapple that would allow him to swing away. 


![fat_spiderman vaccuum hooks](https://user-images.githubusercontent.com/32702381/35276286-d12a9338-003a-11e8-8bb7-989a43492a2c.jpg)


As we developed the game we came up with the idea of implementing a visual cue that would further evidence the player getting fatter. To achieve such effect, we changed the weapons design so that the characters right arm would be more visible. 
This change led to a more open style weapon that wrapped up around the characters arm with a frame-like support, with a sort of prosthetic look. This visual cue would display the arm getting fatter and bigger as the player injected fat, or skinnier when shedding weight. 


![final_version_nobevel](https://user-images.githubusercontent.com/32702381/35276502-81ad821a-003b-11e8-9ae8-e4520d206b32.jpg)

![final_version_bevelled](https://user-images.githubusercontent.com/32702381/35276537-9c13d4d8-003b-11e8-93e8-4bc61bb4c26d.jpg)


![final_version_uv](https://user-images.githubusercontent.com/32702381/35276587-c23a3a94-003b-11e8-84e3-01f95fa34338.jpg)

![render final](https://user-images.githubusercontent.com/32702381/35276593-c8654616-003b-11e8-8b20-e10ebcf6876b.jpg)

##### Final Model
![render](https://user-images.githubusercontent.com/32702381/35276643-ec5c8890-003b-11e8-815d-aa2dca68e49b.jpg)

#### **MODULAR SET**

The artistic style of the modular set had been initially defined by the sci-fi, lab-like environment that we were trying to achieve. Using an urban-futuristic suprematist architectural style and mixing it with light sources and pipes we put managed to translate our ideas successfully. One of the reasons for this sort of austere design was to avoid players to get distracted by decorative and non-functional elements and encourage a linearity that would come naturally to the player.
The other reason was that we knew we were not going to have enough time to make a detailed scene with outstanding looks so the whole lab environment suited this purpose very well.
I initially set each piece to be 1x1 meters but as it proved to be too small I settled for a 1.4x1.4 meters. It made quite a difference as the 1x1 modular set just look too narrow and tiny when used in the game world. 

![modular set basic](https://user-images.githubusercontent.com/32702381/35276715-32ce801c-003c-11e8-88a2-53a5a166cc99.jpg)

This was the most basic modular set we used for the early blocked out stages of the game.

![modular set 2](https://user-images.githubusercontent.com/32702381/35276724-3b74b240-003c-11e8-94d6-1e764df05b4d.jpg)


![modular set 3](https://user-images.githubusercontent.com/32702381/35276730-4089efd4-003c-11e8-9e6c-209ffa556ee9.jpg)

![modular set final top view](https://user-images.githubusercontent.com/32702381/35276769-67f946be-003c-11e8-98be-d139c89c9eab.jpg)

![modular set final perspective](https://user-images.githubusercontent.com/32702381/35276774-6f21fb98-003c-11e8-9f61-f4e08e17bd49.jpg)

![side_light](https://user-images.githubusercontent.com/32702381/35276776-719b17e2-003c-11e8-886a-3b3d82caa10d.jpg)

#### Final Platform model with color scheme

![modular set rendered and textured](https://user-images.githubusercontent.com/32702381/35276827-9e3f7568-003c-11e8-826f-a3c3cc64ade5.jpg)

##### Breakable Wall Mesh

For the breakable wall I decided to have a pre-defined impact zone that would become the destructible mesh. This was done to keep the walls integrity once the player would break through it. 

![breakable wall](https://user-images.githubusercontent.com/32702381/35276929-00fe0584-003d-11e8-9b3b-947bfd6893d2.jpg)

![wall](https://user-images.githubusercontent.com/32702381/35276943-085d362e-003d-11e8-9269-12f56e73f96a.jpg)


#### **LEVEL DESIGN**

The game itself would be taking place in a platformer test lab environment. The final MVP would be composed of 5 challenges that aimed at getting the player acquainted with the game mechanics and skills. You can interpret the 5 challenges as a sort of tutorial level to go through before moving on to the actual game itself. These 5 challenges are adjacent to each other and connect at the end of each, forming a square wave layout going from left to right viewed from the top. 

In the first challenge the player immediately faces a situation where he needs to use his swinging ability to overcome the first stage of the challenge. Once it reaches the platform he becomes aware of his weight limitations by failing to bypass the fan power due to its lightweight. He is then forced to utilise the fat sucking ability to increase its weight in order to not get push off again and reach the second check point.

At this point, some of the platforms are purposefully at a specific distance from each other. This is made so that the player keeps track of its weight and cannot just free jump from platform to platform. 

In challenge number two the player faces another puzzle where his dexterity in using the previously acquainted mechanics is tested. How well it can manage swinging and sucking fat from a source at the same time whilst calculating a jump into a breakable wall. 

Challenge 3 would remind the player of its weight deficit and therefore require re-adjustment from his part to be successful. 
Upon arriving at challenge 4 an active puzzle element is functional. A button that turns off the laser beams and allows the player to move on to the next stage. The player will have to match the correct weight to be able to press the button. Once the button is pressed, a timer is triggered and the player needs to rely on his timing and swinging skills to make it through.

Challenge 5 is a culmination of all the elements used throughout the MVP. The player will have to make use of what he has learned in order to conclude the game successfully.

When designing the level, our intention was to make sure the player learned as he progressed through the challenges. In our initial gameplay we wanted the player to learn from his mistakes or simply learn by failing. Checkpoints were added for the demo and would not be a part of the actual game, keeping the edge when playing and punishment for failing. 
We aimed for a linearity that would feel natural to the player without giving him too many distractions. We also used varying heights for the platforms to break up the horizontal flow of the game and explore its vertical space.


![image uploaded from ios](https://user-images.githubusercontent.com/32702381/35277108-7a2ea7ce-003d-11e8-9d58-e247418fa962.jpg)


#### **PROGRAMMING**

One of the biggest challenges I encountered during this project was the blueprint programming. Having never done programming before, blueprints seemed to be simpler and more straight forward than written programming. Nevertheless, I realised that blueprints still require a certain level of code intuition and understanding. 
Luckily for our team we had two members with previous coding backgrounds and during task assignments and development planning we agreed in having them perform the heavy lifting for the core game mechanics. Those with less programming experience like me would come in at a stage where less complex programming would need to be done.
As a result of this most of my programming was dedicated to smaller scale details and aspects of the game such as material creation after importing textures, sound cues for certain events, rope mesh display as well the breakable wall.

##### Material creation after import

There were only a few nods to connect in order to assign the material its normal map and occlusion map, pretty simple and straightforward.

![material](https://user-images.githubusercontent.com/32702381/35277159-afcb0828-003d-11e8-9509-dfc9e9db3e84.jpg)

##### Sound Cues

Some of the sound cues were ready to be thrown into blueprints while others I had to mix in other to get the desired effect such as the wall impact thud combined with the bricks breaking off of it. I also had to cut and loop some of the vacuum cleaner sounds in an external application called Audacity.


![sound_cue](https://user-images.githubusercontent.com/32702381/35277170-b64fda84-003d-11e8-8129-4a2a1c215fc2.jpg)

![sound_cue_mixer for wall and player impact](https://user-images.githubusercontent.com/32702381/35277171-b6751c90-003d-11e8-9943-92c74b76d2f8.jpg)




![gun_sound_cue](https://user-images.githubusercontent.com/32702381/35277190-cfdff718-003d-11e8-94df-1f4c8dfcccd5.jpg)

In the blueprint above I called on the sound cue to be played right after the event that is triggered once the mouse buttons are pressed. In this case, when the right mouse button is pressed the vacuum sound cue starts playing and once it the button is released I tell it to stop playing and fade in the end of the sound cue that I previously cut and edited in Audacity. The fade in helps smoothing in the transition between the sounds.

![fat suction sound cue](https://user-images.githubusercontent.com/32702381/35277313-42428eec-003e-11e8-80ff-64d570aac760.jpg)


A bit further ahead I tell the code to play an additional sound cue when the player is sucking fat directly from a source. I just call a simple function to play the sound at the right moment.


##### Rope Mesh Display

![cable_settings rope display](https://user-images.githubusercontent.com/32702381/35277432-a77054d4-003e-11e8-9e12-142863b0c5c1.jpg)

When I created the rope / cable mesh I had to define some starting parameters to make sure the cable had the right properties and size.

![rope mesh display](https://user-images.githubusercontent.com/32702381/35277442-b21e5d90-003e-11e8-9eff-91acf0c47486.jpg)

I struggled a little bit more on this one but with a few hints and tips from our core programmers I finally got it working properly. 

In this blueprint I was tasked with making the rope mesh visible in game. Mike had already worked out the behaviour of the rope itself, so I had to cast the physical rope to the first-person character. I then call a function AttachtoComponent and AttachEnd to enable the rope mesh to be connected to the target. And then I finally its visibility. 

##### Breakable Wall

![wall_blueprint](https://user-images.githubusercontent.com/32702381/35277448-b7ac6cac-003e-11e8-9449-aa74a5e96938.jpg)

Calling a Boolean variable to let the Firstperson character that the wall is not broken. Then if the condition is still true and the Firstperson character’s weight == heavy then the collision with the box happens. With this collision then I set a damage output for the impact that combines with a previously set damage threshold on the destructible mesh.
Technically in this case the player will not be breaking the wall itself, it will trigger a collision box that will in its turn provoke the impact damage on the destructible mesh with an impact direction. The reason behind this was that more often than not the Firstperson character found itself getting catapulted away if too much contact with the falling debris was made.

#### ISSUES

I would be lying if I said that Sourcetree worked like a charm for our group. It certainly did not fail us but a majority of our group, me included, struggle quite a lot using it at first. As a result, people were afraid of committing and would only do so if they were being overseen by either Mike or Sam. This caused a few delays an unnecessary time waste in the long run.

Nevertheless, we established a good workflow from the beginning with a Master branch, a Developing branch and individual branches for working on specific features. We experienced a few conflicts from time to time but there were never build breaking cases.

Blueprint-wise, most of my learning came from watching tutorials and listening to our core programmers advice. I struggled the most to identify at what point in a blueprint I had to add my own blueprints but that was just due to my inexperience with the platform and dealing with more advanced blueprints made by other people.

The modular set was a little tricky to come up with. It was a little bit hard to get used to using exact measurements but in the long run it all fell into place. Developing the platforms, I learned how tricky it can be to bevel your final mesh properly. Making sure I built the mesh with the correct topology and avoiding ngons was a positive challenge that improved the way I create my models and look at topology. 

#### CONCLUSION

This assignment has showed me that the pipeline for creating games can be a little overwhelming. Coordinating a team where each individual has fair load of work to do and it needs to be in constant communication can be a little bit tricky, especially if there is a possibility of breaking the build. I particularly enjoy a more art & design role since programming is not my forte but unreal engine is quite the powerful tool and learning how to use it is a valuable skill. 

To be honest if we had a bit more time, or just a little less clustered deadlines just as we got back from Christmas break, we could have capitalised on what the games mechanics had to offer. I say this because I believe there are a few improvements to be made to the game. Starting with a more clear and obvious communication of the characters weight. More advanced puzzle challenges could’ve have been implemented if we had more time. Although this was a tutorial / MVP type level where the player gets to know the game I agree that, given the time, exploring the game’s verticality and swing action a little more would have greatly worked in our favour. The wall modularity might have not been the best choice and maybe platforms were not the best way to demonstrate a modular set, so we will be looking out for those in the future. 

As my first game project, it was an overall positive experience. I very much enjoyed working as a part of a team that was always open-minded about everyone’s ideas. This allowed us to not be afraid to throw ideas into the pot consequently receive feedback on it. Management-wise, our group was always reasonable during tasks hand out, giving the members the liberty of choice in what they felt most comfortable doing. At the end of this project I have learned a great deal about the pipeline of making a game and the effort it takes to coordinate a team of individuals to bring out everyone’s best qualities. And finally I had a lot of fun just making the game itself, coming up with ideas and working with good people.




