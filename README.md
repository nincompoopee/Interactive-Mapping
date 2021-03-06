# Interactive Mapping: Vancouver Food Stalls & Public Bathrooms

In this lab, my goal was to use turf.js to add interactivity to a map of public bathrooms in the city. I decided it would be useful to know the nearest location of a public bathroom to a food stall. Food stalls are mobile restaurants, like hot dog stands, where vendors sell food on the street. They aren't restaurants, so they don't have built in washrooms. So someone might find it handy to be able to locate the nearest public washroom with a single click on a map. I attempted to use the turf.js function "nearestPoint" so that you could click on a food stall, and it would highlight the nearest public bathroom by enlarging the marker. UNFORTUNATELY, I got really, really stuck, and I just can't figure out where I went wrong. So the click function doesn't work :( I will continue to try and tinker with the code for the next couple days, but I figured I need to at least hand something in now.

Here's the downtown core, where the highest density of food stalls is found, but there aren't many public bathrooms around.
![alt text](https://github.com/nincompoopee/Interactive-Mapping/blob/master/Screen%20Shot%20bathroomsmap.png)

Link to map: https://nincompoopee.github.io/nincompoopee-web/bathrooms.html

I consulted this tutorial on using turf.js with mapbox https://docs.mapbox.com/help/tutorials/analysis-with-turf-mapbox-js/ but it was only so useful, because it assumed that I didn't already have a map created. When in fact, I had already spent hours customizing my map in mapbox. So I attempted to find a way to work with the part of the code where they bring in the turf function. I tried to write my own code, but I suck at it so I was unsuccesful. I also consulted the code for my map from the first lab, where I was able to put in pop ups. I tried using the same pop ups code with this map, but even that didn't work - and when I put my code into p5.js and ran it, I got errors telling me that the data layers did not exist. After hours re-uploading, re-naming, and playing with every combination of upper and lowercase letters, I'm still stuck. 

I took the time to add a custom toilet icon to mark the bathrooms, and I did this for several reasons. 1- the typical man/woman bathroom symbol is really similar visually to the fork and knife symbol that I use to denote food stalls. I wanted the bathrooms to stand out, and be at the top of the visual hierarchy. 2- A colourful, interesting icon makes the map more eye catching and fun. 3- I wanted to challenge myself! 


Toilet icon source: <div>Icons made by <a href="https://www.flaticon.com/authors/smalllikeart" title="smalllikeart">smalllikeart</a> from <a href="https://www.flaticon.com/" 			    title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" 			    title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>
