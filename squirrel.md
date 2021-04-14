## ATTACK OF THE EVIL SQUIRRELS!

![squirrel.png]({{site.baseurl}}/squirrel.png)

## [CODE HERE](https://editor.p5js.org/chrismdv00/sketches/WYFyGV4tx)

## [FULLSCREEN MODE](https://editor.p5js.org/chrismdv00/full/WYFyGV4tx)

## PROCESS

We divided up the things that everyone was doing, but helped each other when we got stuck. I did the enemy squirrels and helped others when I could. After the class I had free time, and honestly I enjoy doing this stuff much more than my writing my thesis paper so I got distracted, so I put everyones stuff together and made a couple minor tweaks, like adding in the image for the player squirrel. We then got together on Sunday to tweak the code together, add some features and plan ahead. There was a lot of great brain storming, everyone showed me some stuff I didn't know about (I was doing fullscreen wrong for example and there were a few obvious bugs that soared over my head), in general there were just a lot of great ideas, like to include an acorn that gave the squirrel health, and someone else had the idea to make all the forest objects have avoid functions, and others. And we had a bunch of crazier ideas that weren't exactly possible in the time frame (one of which involved collecting cyborg parts and turning into a cyborg squirrel and having a boss squirrel appear that you need to shoot lasers at to defeat, and a collectable hat that follows you when you pick it up). Was fun and we are continuing to work on and debug together through discord. 

## CHALLENGES

1. Never quite figured out how to get the forest objects to not overlap, but they still look really nice dispersed on the screen randomly so we left it like that and focused on other things
1. The spritesheet thing we got confused about and just used a GIF instead. 
1. Could not figure out the camera thing for the life of me, idk we tried a bunch of different things but it just didn't work lol. Hopefully next time
1. controls still feel a little stiff to me, not sure how to improve, needs a way to tweak keyReleased acceleration.mult(0) so you can press multiple buttons and not have it interfer
1. sort() only sorts by the the first digit? is there a way to sort by entire number? I worked around by dividing the numbers by like 20, but still kinda wonky so I changed some other variables to make sure it doesn't break anything, seems like there should be a better/easier/smarter way to sort?

## ADVANCED REQUIREMENTS

1. eating sounds
1. worked alot on finding the goldilocks level, hope its there? (a lot of the choices we made we made together for this requirement, i.e. asking the group do the squirrels get too big, do they walk funny, etc... which was very helpful to have a group to do that with)
1. the enemy squirrels walking pattern has a noise force on it
1. we have trees and boulders with avoid functions that the effect the player and the enemy squirrel, along when the player is big enough it breaks, which I kinda like because you just like hop over the trees which is funny
1. we also have decorative flowers and bushes
1. what else, acorn that appears when your health is less than 3 that spawns randomly on the map and gives you one health 

## MADE A ROBOT(?)
He has some issues but he kinda works lol. Can't get him to "properly" avoid enemy squirrels that are larger than him so I tried to bounce the squirrels away from him and had to give him a much larger health. still has issues though. I made it so the robot and the player compete to eat the squirrels, when the robot reachs max size he chases the player, but this game might be getting too difficult now...hmm could make the robot carry the little squirrels to the player? The robot is a pretty stupid robot lol, not sure how I could make him smarter, maybe he needs to measure the distance to all the squirrels, sort them somehow and go after the closest that is smaller than him? Not 100% sure how to do that right now

![Screen Shot 2021-04-14 at 10.38.32 AM.jpg]({{site.baseurl}}/Screen Shot 2021-04-14 at 10.38.32 AM.jpg)

[HYDRA EXPERIMENT 3](https://hydra.ojack.xyz/?code=czAuaW5pdEltYWdlKCUyMmh0dHBzJTNBJTJGJTJGdmlnbmV0dGUud2lraWEubm9jb29raWUubmV0JTJGY29uY29yZCUyRmltYWdlcyUyRmYlMkZmYiUyRkludGVyc3RlbGxhcl9zcGFjZXNoaXAuanBnJTJGcmV2aXNpb24lMkZsYXRlc3QlM0ZjYiUzRDIwMjAwODE1MTUyMjQ5JTIyKSUzQiUwQSUwQXNyYyhzMCkuc2F0dXJhdGUoMTApLnJvdGF0ZSgxMCUyQy0xKS5tb2R1bGF0ZVJlcGVhdChvc2MoMTApJTJDMyUyQzMlMkMxJTJDMSkua2FsZWlkKDIpLmFkZChvc2MoMC45JTJDMSUyQy4yKS5jb2xvcmFtYSgxJTJDMCUyQzEpLnBpeGVsYXRlKDEpLnNjYWxlKDAuMSkucm90YXRlKDEwJTJDMSkpLmJsZW5kKG5vaXNlKDEwJTJDMC4xKSUyQzAuNSkucm90YXRlKDEwJTJDLTAuNSkuc2NhbGUoMC4yKS5hZGQoc2hhcGUoMTAwKS5yb3RhdGUoMSUyQzEpKS5hZGQob3NjKCkucGl4ZWxhdGUoMTAwKSkuc2F0dXJhdGUoMTApLnNjYWxlKDIpLm91dCgpJTBB)

![Screen Shot 2021-04-13 at 5.06.56 PM.jpg]({{site.baseurl}}/Screen Shot 2021-04-13 at 5.06.56 PM.jpg)


[Hydra Exp 4](https://hydra.ojack.xyz/?code=czAuaW5pdFZpZGVvKCUyMmh0dHBzJTNBJTJGJTJGbWVkaWEuZ2lwaHkuY29tJTJGbWVkaWElMkZBUzlMSUZ0dFl6a2MwJTJGZ2lwaHkubXA0JTIyKSUzQiUwQSUwQSUwQW9zYygpLmNvbG9yKDElMkMuMSUyQzIpLnNhdHVyYXRlKDI5KS5waXhlbGF0ZSgxMCkuc2NhbGUoMC4xKS5yb3RhdGUoMzAwJTJDMCklMEElMjAlMjAuYmxlbmQob3NjKCkuY29sb3IoLjElMkMyJTJDNCkpJTBBJTIwJTIwLmFkZChub2lzZSgpKSUwQSUwOS5yZXBlYXQoKSUwQS5sdW1hKDAuMSUyQzAuMSklMEEuYWRkKHNoYXBlKDEwMCkpJTBBLmthbGVpZCgxMCklMEEuc2F0dXJhdGUoMTAwKSUwQS5zY2FsZSg1KSUwQS5yb3RhdGUoMSUyQyUyMC4xKSUwQS5tb2R1bGF0ZVJlcGVhdChvc2MoMTApKSUwQS5yb3RhdGUoMjUwJTJDMCklMEEubW9kdWxhdGUobzApJTBBLmJsZW5kKG9zYygpLm1vZHVsYXRlKG8wKS4lMjBjb2xvcmFtYSgxMCkpJTBBLmFkZChzcmMoczApKSUwQS50aHJlc2goLjUlMkMyKSUwQS5pbnZlcnQoKSUwQS5zY2FsZSgwLjIpJTBBLmthbGVpZCgyMCklMEEuYWRkKHNyYyhzMCklMEElMjAlMjAlMjAlMjAubW9kdWxhdGVSZXBlYXQob3NjKCkpJTBBJTIwJTIwJTIwJTIwJTIwLnJvdGF0ZSgzMDAlMkMwKSUwQSUyMCUyMCUyMCUyMCUyMCklMEElMjAlMjAub3V0KCk=)

![Screen Shot 2021-04-14 at 10.29.29 AM.jpg]({{site.baseurl}}/Screen Shot 2021-04-14 at 10.29.29 AM.jpg)

Idk, not happy with any of these... and none of the gifs I find work, only the one of the hydra github example works :(

went back to [exp 3](https://hydra.ojack.xyz/?code=czAuaW5pdEltYWdlKCUyMmh0dHBzJTNBJTJGJTJGdmlnbmV0dGUud2lraWEubm9jb29raWUubmV0JTJGY29uY29yZCUyRmltYWdlcyUyRmYlMkZmYiUyRkludGVyc3RlbGxhcl9zcGFjZXNoaXAuanBnJTJGcmV2aXNpb24lMkZsYXRlc3QlM0ZjYiUzRDIwMjAwODE1MTUyMjQ5JTIyKSUzQiUwQXMxLmluaXRWaWRlbyglMjJodHRwcyUzQSUyRiUyRm1lZGlhLmdpcGh5LmNvbSUyRm1lZGlhJTJGV3JPRTdPQW01b2RBTmxJMG5wJTJGZ2lwaHkubXA0JTIyKSUwQXMyLmluaXRWaWRlbyglMjJodHRwcyUzQSUyRiUyRm1lZGlhLmdpcGh5LmNvbSUyRm1lZGlhJTJGUmNpZHc2Y3oxMlp5TSUyRmdpcGh5Lm1wNCUyMiklMEElMEFzcmMoczApLnNhdHVyYXRlKDEwKS5yb3RhdGUoMTAlMkMtMSkubW9kdWxhdGVSZXBlYXQob3NjKDEwKSUyQzMlMkMzJTJDMSUyQzEpLmthbGVpZCgyKSUwQSUyMCUyMC5hZGQob3NjKDAuOSUyQzElMkMuMikuY29sb3JhbWEoMSUyQzAlMkMxKS5waXhlbGF0ZSgxKS5zY2FsZSgwLjEpLnJvdGF0ZSgxMCUyQzEpKSUwQSUyMCUyMC5ibGVuZChub2lzZSgxMCUyQzAuMSklMkMwLjUpLnJvdGF0ZSgxMCUyQy0wLjUpLnNjYWxlKDAuMiklMEElMjAlMjAuYWRkKHNoYXBlKDEwMCkucm90YXRlKDElMkMxKSklMEElMjAlMjAuYWRkKG9zYygpLnBpeGVsYXRlKDEwMCkpLnNhdHVyYXRlKDEwKS5zY2FsZSgyKSUwQSUyMCUyMC5ibGVuZChzcmMoczApJTJDMC42KSUwQSUyMCUyMC5tYXNrKHNyYyhzMikuc2NhbGUoMC4yKSUyQzEpJTBBJTJGJTJGLm11bHQoc3JjKHMxKSUyQy44KSUwQSUyMCUyMC5vdXQoKSUwQQ==), 
realized I need the .mp4 not the .gif! silly me

![Screen Shot 2021-04-14 at 12.47.28 PM.jpg]({{site.baseurl}}/Screen Shot 2021-04-14 at 12.47.28 PM.jpg)

kinda too much goign on but idk, kinda cool, yeah I like it now 

[HOME](README.md)
