1. Created my firs Scratch game: https://scratch.mit.edu/projects/293434934/ and wanted to publish it to Play Store as apk. At that time i was completely new to mobile/game dev.

2. Decided to use PhoneGap Template - supports android and apple, and other strange things - ok, i take it.

3. So now i just need to find out how to convert .sb3 to html5

4. Tried to use Phosphorus but it has no support for sb3 files, later found sb3 mention at github in fresh fork of Sorforus player - so... i decided to give it a try: after some testing, tuning i finally manage to resolve critical bugs and decided to publish to play store

5. Found and fixed major performance problem encountered while apk was deployed to tablet - "IsColorTouchingColor" is extremely slow... core Scratch 3.0 collision detection function is one of its greatest weakness.  ...but... in fact you can just run your Scratch game directly from mit scratch site and you will be happy ;) it works, but i still want to publish my game as standalone product, i want to be a part of new mobile world, become a real mobile developer (not kidding)

6. Decision: The only right direction from this point is to fix all this libraries on my own and give my shitty game the boost it deserves! So... Im not js expert, nut im always eager to learn something funny. At my third attempt i can say that i like JS, i have fun from coding in JS, i like this feeling of freedom. (in fact i had no option, my Scratch code is based on this function, and at this point i was completely focused on my product - template/player or publisher that can produce .apk for any .sb3 - whatever with a real use case)

7. I have to admit i was not prepared enough, and now i slowly started to feel how hard is to understand the code fully, unveil its secrets, after hours spend with this code you must admit you stuck in the main loooop... with self animating queues... invocations from within compiled sb3->javascipt, and how it just working, or not. When you are able to see not so obvious "goto" statement you are almost here.

8. Maybe the result is not as spectacular as expected, but perf improvement is visible and now I can close this chapter of my life as a new man.

* try it here in your browser: https://pgasienica.github.io/outerjam/
* or download from play store: https://play.google.com/store/apps/details?id=com.larva440.outerjam

source links:

phosphorus prohject: https://phosphorus.github.io/
sulfurous project: https://dardoro.github.io/Sulfurous/
