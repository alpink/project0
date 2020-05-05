# Project 0

Web Programming with Python and JavaScript

My project consists of 4 html files plus suporting files in sub-folders.
The images folder contains the images in the site, 
the css folder contains the 2 CSS files I created,
the scss folder contains the file I used to generate list.

I used Bootstrap for column layout as required and I also found advice on how to use web fonts to ensure the same display across devices.

I tested the site on my Windows laptop uses Chrome, Firefox, Edge and Internet Explorer, on an Android phone using Chrome and on an Amazon tablet using Silk. I did not have access to any Apple devices.

PROBLEMS

<<<<<<< HEAD
I had problems with the media query not working. I wanted an image, in a figure element to float to the right of the screen but on smaller screen float to the left.
=======
I had problems with the media query not working. I wanted an image, in a figure element, to float to the right of the screen but on smaller screen float to the left.

Eventually I realised that the line 
	@media screen and (max-width: 600) 
should have been
	@media screen and (max-width: 600px).


LESSONS LEARNT

Lots! Here are some things:

Firstly, use GIT ommints more often. Being able to restore a file was incredibly useful and I need to make sure I can do this whenever needed.

Using <meta name="viewport" content="width=device-width, initial-scale=1.0"> to ensure that smaller screens aren't scaled down.

Being more precise. It took me too long to realise my error with the media query.

Using Bootstrap. I could have used more features of Bootstrap including its implementations of media queries. Using columns was easy using the bootstarp model - as long as I remembered the row!
