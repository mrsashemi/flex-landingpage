# odin-flex-landingpage

The Odin Project - Foundations - Project: Landing Page

Wed Dec 29 20:55 
This is the second project I will be taking on via the Odin Project. The focus will specifically be on using Flexbox in CSS to creating a landing page. As I still am early in my coding journey, the goal is to demonstrate problem solving skills by recreating a landing page provided by Odin from scratch using HTML and styling with CSS to include flex elements. I intend on returning to this README to update my progress and share any new learnings. 

Thu Dec 30 2:15
Commenting to update my progress. Flexbox is challenging! I created an HTML sheet with 4 containers and 1 footer for the landing page. I then got to work on styling the top container in CSS and nearly finished it before calling it for the night. The thing I found most difficult was sizing images in flex containers and keeping them static when resizing a browser page. I kept running into an issue where the image would shrink as I reduced the width of the browser. As it pushed into the text in the flex container next to it, the container began to overflow. 

I tested a lot of different properties using dev tools in chrome, including flex-shrink, width: %, creating a new div for the img, etc. Ultimately, I found that the img needed specific px for height and width properties (258px and auto), as well as putting a flex-shrink: 0 on the container property. I used a similar solution to prevent overflow and text-wrapping on the flex container next to the image. Now the flex items cleanly slide along the main axis while resizing the page. 

Sat Jan 1 11:19
Next update. Realized that my solution to my previous issue created more problems with resizing issues than I had hoped...perhaps I'm getting ahead of myself. Also figured I might be getting a little ahead of myself. I looked through multiple solutions and ultimately decided to remove specific widths, and used flex-wrap instead so the image wraps underneath its sibling instead of sliding towards it and shrinking. Works much better this way, but I still have a lot to learn if I want to make awesome websites one day. 

That said, the project was pretty simple. I powered through the rest. I can more or less call it done, but plan on returning to it one more time to spruce things up a bit. I'd like to play around with image settings more, and just generally want to do more than the bare minimum.

Thu Jan 6 7:05 
Added some final touch ups to fex wrapping and to fix any mistakes after checking code in W3C Markup. Finally done! 

COPYRIGHT DISCLAIMER:
All images included are original artworks produced by myself (otherwise known as WizardsRobbingKids). The only exception is the TMFA Punk, which is an NFT created in my likeness by Matty Mo, The Most Famous Artist. I currently own the NFT and am part of the TMFA DAO. 