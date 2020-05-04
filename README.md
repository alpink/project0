# Project 0

Web Programming with Python and JavaScript

My project consists of 4 html files plus suporting files in sub-folders.
The images folder contains the images in the site, 
the css folder contains the 2 CSS files I created,
the scss folder contains the file I used to generate list.

I used Bootstrap for column layout as required and I also found advice on how to use web fonts to ensure the same display across devices.

I tested the site on my Windows laptop uses Chrome, Firefox, Edge and Internet Explorer, on an Android phone using Chrome and on an Amazon tablet using Silk. I did not have access to any Apple devices.

PROBLEMS

I had problems with the media query not working. I wanted an image, in a figure element, to float to the right of the screen but on smaller screen float to the left.
Eventually I realised that the line 
	@media screen and (max-width: 600) 
should have been
	@media screen and (max-width: 600px).



