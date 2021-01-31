This is a recreation of the google homepage for The Odin Project. This is my first time recreating a webpage.

I am designing this in Firefox (fullscreen), in case another browser displays this differently.

The skills I will have demonstrated upon completion is a basic understanding of HTML and CSS.

As I undergo the project, I will write what I have gleaned. 
Everything below I'm writing along as I do the project:

The importance of CSS specificity using > cannont be understated.

In styling, a tags feel like they have a mind of their own.

Having more div tags with unique classes for specificity gives more control.

Google's class names are ridiculously difficult to keep track of due to their obfuscation. 
Because of this, I'd rather be redundant in styling than relying on inheritance (because a lot of the time it doesn't inherit for some reason, especially a tags).

I understand how a second monitor could increase productivity.
Update from two days later: I got one and it made a world of difference. My workflow is much easier.

The active skill I am learning is definitely organization and specificity. It feels good when something actually works... even if it works incorrectly. 
Because I know that I'm selecting the correct element, I can manipulate it better.

I decided against using the background image manipulation for the apps icon that google uses and went with an icon from bootstrap instead. 
I edited the color and opacity in the same way google did to achieve similar visual results. 

The .nav-item and .footer-item class were created in case the items had enough similarities that I could give styling to multiple items. 
I then added an id to each so I could make individual changes if needed (I actually did to #images). 
As it turned out, most of the time it was different across the classes so it was easier to be specific. 
But being general and specific simultaniously has it's advantages. 

The active styles shown in the developer tools inspector change depending on the viewport size.
This caused a ton of misstyling errors before I realized this was happening. 
If looking at an element's styles, make the screen the size you want it and pop out the developer tools window so that it doesn't interfere by changing the screen size.

A span tag has a differing function than a div tag. A span tag keeps all elements in line with one another, which has it's uses, like the footer. 

