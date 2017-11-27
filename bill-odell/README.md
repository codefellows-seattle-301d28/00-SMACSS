##### How did you determine which rules should be placed in each new CSS file?

For the base I tried to find anything that applied to all elements in on the page. Since this page was heavy on the individual styling of elements, the only pervasive elements were the default font-family and the background color. 

In the layout I tried to place the overall design of the page. Mostly things that were div containers in the html. If something was coded into the html saying this goes here, then I would put it into the layout. A rule of thumb was if it didn't have a class or id I would put it into the layout. 

For the modules I used the most specific elements of the page. Single images. I thought it might be helpful to put anything with floats into the layout section, but I felt some items within other items were to specific to be put in the layout tab, so I decided to put them here. General rule I used was if an item had an id or class I would put it here. 

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not. I looked at the overall code and tried to find any redundant code, meaning if two items were styled the same way but had different code then I looked to integrate them, but I did not find any such instances. Otherwise I just left things how they were and moved them to the different pages. 
