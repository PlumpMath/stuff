# Game idea - 2015-04-15

## Synopsis
A classic turn-based RPG with a non-classic setting. Instead of a heroic party with warriors, mages and thieves, the party is made up of programmers with different abilities. Setting, enemies, bosses, skills and items are all programming related.

## Name
Not yet decided.
Some ideas :
- Break point in the style of the breaking bad logo
- Debug hard : Compile another day

## Story
You're the lead programmer of a huge multi-language project mixing all sorts of programming languages, using cutting edge programming patterns as well as dealing with ancient legacy code.
It's late at night, you sit there, waiting for the build to finish and watch line after line of your CI output flickering on the screen.
Then, all of a sudden (what else?) you get some obscure compiler error that even StackOverflow has no answer to!
You start digging deep into the bug because your deadline is just days away and your production code is not compiling.
For hours, days, weeks, you try everything to make it work, without realizing that the obscure compiler bug is dragging you into a different dimension, where compilers, programming languages, patterns (and stuff) come to life, where compiling and debugging is no longer done in an IDE but a matter of survival.
So you're tasked with gathering a party of talented programmers to help you on your (not so much) epic quest of finding and defeating that compiler bug deep inside a dark dungeon!

## Tech
JavaScript, WebGL for 3D viewport with pixel art style and retro CRT-shader, HTML5 (or also WebGL) for UI. Layout like old-school dungeon crawlers (e.g EOB). Upper left (bigges part) with 3D presentation of "dungeon", left part with party info and lower part with status text and action buttons.
Using random dungeon generator for creating dungeons, maybe with fixed "cities".

## Party generation
Could be in the style of a (humorous) job interview, or could look like browsing some programming forums and social media to gather a balanced group of developers for your quest. Or you get a stack applications and select the ones you see best fit.
Names are randomly generated and related to programming to. E.g. Ed D.bug.

## Characters
Attributes, skills and traits will all refer to programming and software development in general. Attributes can be object orientation, inheritance, compile speed (kinda like stamina), link speed (for construction things?), etc.
Instead of health, there could be motivation that is boosted by fixing (killing) bugs, etc.

## Enemies
Enemies are grouped into several categories, with rising difficulty depending on their group. Bugs are the easiest ones, while bosses are very rare and are necessary to defeat for advancing. Compilers are special enemies, e.g. like named enemies (aka "specials") in other RPGs.
### Bugs
The most common enemy. Usually no thread to a good and balanced developer teams, as long as they don't come in huge packs.
#### Examples
- Memory leaks
- Infinite loops
- CTDs

### Languages
Some language constructs and drawbacks can cost you lots of time, so these usually pack more punch than basic bugs.
#### Examples
- You are attacked by a variadic C++ template, it hits you with a compiler error for 500 dmg
- You encounter a static Delphi class with non-static members. It hits you with a global state variable.

### Compilers
Compilers have the ability to drive even experienced coders into utter madness. There's not much that deals more lethal hits than an internal compiler error at the end of a working day!
#### Examples
- A Pascal unit attacks you with a recursive uses clause! Object oriented programmers are stunned for 2 turns!

### Virtual machines
There is a life after a compiler, so virtual machines for interpreted languages are in for a kill too. Especially if paired with some aged browser or runtime environment.

### Miscellaneous
Enemies that don't fall into any of the other categories.
#### Examples
- Ambush attack by a new JavaScript framework! It casts "clone" and spawns yet another random JavaScript framework!

### Bosses
Bosses are special encounters at the end of a level, each with it's own story. At some point you might fight a buggy C++ 17 compiler iteration, and at some other point a CI system gone mad!
These fights will be totally epic. At least for a programmer, and totally boring for everyone else.
