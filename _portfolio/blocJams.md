---
layout: post
title: BlocJams
thumbnail-path: "img/blocJams.png"
short-description: BlocJams is a music player

---

{:.center}
![]({{ site.baseurl }}/img/blocjams.png)


## Summary

BlocJams was the first project in using Javascript html and CSS all in one. It required some more complex Javascript and was a great challenge to me but I am very proud of the end product.


## Explanation

BlocJams was the first project that I had to do for the Bloc curriculum. It allowed me to combine all the html, CSS, and Javascript that I had just learned at the time. It was probably the hardest project I had worked on so far since it asked for me to implement all the concepts I had just learned and put them together in a functional way. I had a blast doing it in the end.

## Problems

The main problems in this project were using Javascript in a way that I had never done before. I had to learn how to dynamically load elements onto a page versus just statically placing everything. Then I had to make a music player that took mp3 and figure out how to get them to play, pause, load their current times, and all other things normal music players do. Most of all the issues were helped by the Bloc curriculum.

So for the initial problem of loading elements dynamically onto a page I had to learn how to do animations with CSS and Javascript to load a section of my home page when someone scrolled down to it. I figured out how to do this with some basic transition CSS and Javascript. Then I wanted the section to animated only when someone scrolled down to it. So I learned how to measure how far my section was on the page and set an event to fire once the user had scrolled that far. Next was loading all the albums that our fake artist had onto the album page by removing our static template and using Javascript to load as many albums as he had by dynamically loading a template. 

Following dynamically loading the albums was the actual album view. Which I pulled data from an object that we had created to load each of the track numbers, titles, and lengths. This was done again with some DOM scripting. Next in the album view we had to create a hover effect so that whenever a use hovers over a song a play button would appear and once they click it the corresponding song would play. Some CSS and more DOM scripting allowed for me to achieve this. Once the hover effect was completed we created a player bar that would display the current song playing, how far the song had already played, and some controls that allowed you to skip to the next song, pause, go to a track back, and change the volume. First setting everything up in a static way to make sure I was happy with how everything displayed would allow me to add in Javascript later so everything could be responsive. 

## Conclusion

This project was the most challenging thing I have done to date. Using the technologies in a way that I knew was possible but had never done before was very gratifying. Once the application was built in vanilla Javascript I then refactored it using jQuery and then Angular to learn the technologies on something that I had already built. Looking back on the project I wish I had taken my time more and really gotten a chance to play around more with things so I knew exactly why I was using certain code snippets in certain ways. So for the future I am making sure to take my time and fully understand why I am doing when I am doing it instead of just completing something to get it done.
