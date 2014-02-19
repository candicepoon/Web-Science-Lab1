Candice Poon
Web Science
Lab 1

This was the first lab back into Web Science and I definitely had mixed feelings about it. Just a month away can cause a lot of the good practices I had last semester to be forgotten. But I also did surprised myself with what I could remember and comfortably do. 

This was my first time using Bootstrap and I barely scratched the surface. My lab lives within the template files that you download from the website and holds many of their design details. I had trouble with CSS styling, but switching to their full CSS file rather than the minimized version helped a lot. Using Bootstrap in this lab makes me want to use it again, just so I can better understand and use it for projects. Even the sidebars I utilized in Bootstrap made it somewhat responsive to screen size. Yay!

My lab is two components that are built with the same principle. JavaScript makes an AJAX call to read the JSON file. It takes every "item" that matches the criteria, whether it be the tweet, picture, or hashtags and stores it in an array. I only put it into an array as a precaution early on to make sure the data I was using later to output was correct. Javascript then iterates through the array, adds HTML to make them <li> elements, and places them into the DOM. 

My scrolling functionality comes from a jQuery plugin called Totemticker. It takes an unsorted list and makes them scroll. I was able to control the number of items to be displayed, the speed of the transition, and the time in between items. It worked relatively well and was easy to set up. If I had to do this again, I would have spent more time looking at a fully jQuery solution tailored for Twitter specifically.  

My main problem which is visible is the alignment of my profile picture and tweet. The way I designed this is tricky, so bear with me. Both the profile picture and the tweet are in separate DIVs. These DIVs are within a larger DIV. Then that DIV is listed under each <li> element. It seemed to make sense on paper when I was designing the solution, but this sort of nesting has made move elements the most difficult part. It made timing and moving both the tweets and profile pictures easy but I still have trouble positioning these two elements. The troubles with the alignment has caused some of my scrolling animation to be off, which is extremely frustrating.  