## TENTATIVE TITLE: "DIAGRAM GENERATOR"

### [Play HERE](https://editor.p5js.org/chrismdv00/full/C0xxCQ6c0)

### [Code HERE](https://editor.p5js.org/chrismdv00/sketches/C0xxCQ6c0)

![aFinal1.jpg]({{site.baseurl}}/aFinal1.jpg)

### Concept

_Where did this come from?_

This started out as a diagram generator accompaniment to the thesis installation I did (where I made 8 diagrams). I thought it would be cool if I could have these diagrams "randomly" generated, and since the project involved "cyberzombies" and cyborgs it seemed almost like these diagrams should have been computerized more from the get go. 

![sideBySide.jpg]({{site.baseurl}}/sideBySide.jpg)

![artSideBySide.jpg]({{site.baseurl}}/artSideBySide.jpg)


**Generator on left, original diagrams on right**

_What is this though?_

I'm not entire sure is one answer. This is meant to be a fun way to create diagrams, which I find to be a funny medium to absurdify. For me, I enjoy watching the mushrooms grow and the creatures float around on the screen. The mismatching of quotes and images also is something I like play around with. The real short answer is that I just think its funny, and hopefully others will as well. There is something conceptual here about computers generating labels for these fleshy creatures (who can't speak for themselves, can only use quotes, etc), as well as the battle between the sprawling mushrooms and buildings. There is a lot of clashing of worlds here in my opinion. One of the diagrams questions, "what is art", asking the audience, is this art, can you make art with this? These diagrams came out of a project that was related to critical pedagogy, I think these diagrams were meant to subvert a mode of education, make it more malleable and absurdify the unchangeable quality of standard "diagrams". 

_Goals:_

I wanted something that I found fun and funny, and related to the diagram project I based this off of. I wanted to include all 8 of the diagrams but I ended up only including 3 plus other stuff. I wasnt sure how to do this but I wanted it to have some real world effect, or like a command (i.e. draw your own cyber zombie) or something like that. But couldn't figure out how I wanted to include that? Woudl be cool if player/user/etc could upload their face and swap it out of mine, but there are all the creatures and etc as well...hmmm...

Future/other goals:

- Creatures (done)
- pipe/water filling space
- more backgrounds (like my room? so you an infest more spaces)
- sound?


### Challenges

_Conceptual Worries:_

As I continued working through, I kinda of got bored of the diagram generator? It felt flat and I wanted more, so it started to transform into something a little less diagram generatory than I originally intended, and now I feel like all the features are still not fitting together as tightly as I wanted them to. Wish I figured out a soundscape thing for this. Worried if this doesn't make sense out of context with the installation project

_Coding Challenges:_

I a lot of the aspects I was trying to figure out I had never tried so they took me a while to get right, i.e. having the mushrooms spawn based of off the last one's position, and connecting the arrows to the zombie/cyborg is a way where they weren't in the middle of nowhere or all in the same spot (and could move with the creature).

A big challenge was also reworking everything to fit in this more menu like version, instead of the way you "play" through. Think my code could be much much cleaner, I need a better way to organize, when I can't find a section immediate I get overwhelmed and lost lol, need to label everything better and have like a seperate handwritten list of important functions and variables 

I tried to make the zombie/cyborg creatures able to turn on/off in other rooms, but it just didn't work lol, so I gave up on that for now. feel like i need to restart and really clean up my code and figure out where I want to take this next, think I want more drawing tools, and a way for more things to be diagrammed. 

Just made a bunch of little creatures that you can spawn, pretty happy with that, feel like they should do something more though?

![afinal4.jpg]({{site.baseurl}}/afinal4.jpg)


### Approach

Probably should've planned more. Or well I did plan a lot (just not that thoroughly i guess), and I  change my mind about things often lol. I tried to start out doing all the easiest stuff first and work from there. Towards the end I kinda wanted to fully restart so I could rework eveyrthing since my goals had changed, but I didn't do that (because of time or stubornness). slow and steady! just added something that was much easier to do because I new exactly how I wanted to turn it off and on and etc... If I were to redo I won't use stages, I would just push and splice everything, stages better for something else I think. better for backgrounds maybe... I want more backgrounds... should really do something (drawing-wise) with the mouse, then again, I kinda like limiting the control away from the mouse... Think I was too overwhelmed in the beginning, feels like I'm just nowish figuring out what I want to do and getting comfortable getting it done with the code.

I started making a bunch of copies at some point, which helped me not get stuck or worried I was going to destroy something.

### Reflecting On Process:

hard lol, fun though, only sort of ended up as a diagram generator, I kind of slipped away into something else. Memes kinda feel like diagrams to me though? I guess I was more interesting in weird ways to "draw" (mushrooms, buildings, faces). I liked the diagrams a lot and I want to keep looking at this and figure out how to better incorporate them in this as a whole, I like having this random drawings(?) that are "randomly" labeled, theres soemthign there that appeals to me. Need some way to label anything/everything. I also have like five other diagrams from my installation that I didn't get to work on. I was trying to slow this down a lot, but it still gets overwhelming sometimes. Need to figure out sound. the mushrooms and the buildings aren't very pretty either, wondering if I should've done something with pixels? would be cool if I could figure out a way to embed glitches into this. wish I had more time to play around with this, was hard to manage time with thesis and all, but that's life lol. 

### Thinking about the future:

want to do much more. as I worked through this, I wanted to use things like this to get inspiration to do other stuff, not sure if that makes sense... When I was doing all this stuff and would see the random outputs I would get excited and be like, I want to make something else with this now. I really like this whole procedurally generated thing, feel like there is something here I can latch onto, but I haven't fully figured it out yet. I'm so used to working in video and things that have one exact same output every time, kinda hard to change that thinking, but I would really like to make some kind of "video-like" experience that is generative (summer project!). 


![afinal5.jpg]({{site.baseurl}}/afinal5.jpg)

## In-Depth Info

1. Bio button takes you to the title screen, there is no background so objects will have trail, the numbers are mostly random (with some parameters i.e. age: random (23-30)). All buttons change into same image but with drawn mouth and red X on forehead while they are pressed
1. art changes the state to the what is art background. The text comes from one array and so anything can be in any of those positions, making everything interchangeable
1. zombie button changes state to the blue background with the pink "zombie" version of me. The screen text is amount random(1,10). And combines two words from two arrays that I made. Most of these words come from the original diagram I made previously. The screen text moves with noise and the red X button marks the position.x and position.y, and if that gets closer to another it will eat that one and grow bigger. The creature can move with the arrow keys. If they go over the severed arm (which spawns on a random timer based off when the last was eaten), they will gain another label. you can remove the labels by clicking the X box. In order to get the labels to attach in a good enough way, I had to break up the rules for each position into quadrents and sometimes this causes them to jump around.
1. Cyborg button is basically the same as the zombie, wish I did more differently with this. The words come from different arrays
1. movies button is like a meme generator. It changes the background to a random image from a movie (movies that I remember watching frequently as a kid) and mismatches quotes to the images. 
1. Faces adds face objects that float around and eat smaller versions of themselves, as well as the mona lisas and money
1. Art buttons make mona lisas and moneys that move around and eat each other. There is a resources consumed stat on the bottom left that keeps track of this (although I think I broke it somehow and forgot about that). The arrows control the first object in the mona lisa/money/faces array. (will break if you conume like 800 resources)
1. mush buttons toggles mushroom generator on/off, they spawn (an array of three mushrooms) based off the last mushroom's position
1. build buttons makes sky scrappers in the same fashion as the mushrooms, except slightly slower (hard to tell)
1. create buttons makes creature objects that float around and are attached to a different array of quotes

[HOME](README.md)
