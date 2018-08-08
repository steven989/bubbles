# bubbles
This is an algorithm to display bubbles like the Apple Watch UI

This is an experiment to see if I can use Javascript to replicate the look and feel of Apple watch UI "bubbles".

I'm trying to this UI for a project I'm working on, but could not find ready Javascript plug in. All the existing bubbles-like JS plugins are for bubble charts, which isn't what I'm looking for.

What makes this unique and different from the available plugins are:

1) There's a "central" bubble from which all other bubbles radiate out from
2) Each non-central bubble is defined by a distance from the center, and a size
3) Bubbles should not overlap with each other if possible

In the end, I used a combination of trignometry and pythagorean theorem, coupled with loop and recursion to accomplish this. 

Hopefully I can turn this into a ready-to-use plugin for other people at some point. If anyone has the skillset to do so, feel free to fork and change the code as necessary.
