# horiseon_refactor

~HTML
I changed the title to Horiseon to make the webpage load the title as 'Horiseon' instead of 'website'.

I refactored the hero content by giving #search-engine-optimization, #online-reputation-management and #social-media-marketing the same class 
of .company-services, since they all have basically the same styling. To the images, I added alt texts for accessibility standards.

Similarly I refactored .benefit content by giving them the same class of .benefit-title.


~CSS
To the p statements, I added two modifiers: a margin of 10px at the right and left & a lighter font-weight for ~style (To make the webpage look like the
intended screenshot, I commented font-weight to make it have no effect when loading the webpage).

Since all the benefits were classified under the same class, I was able to clean up the CSS to be able to style all three using just .benefits,
.benefit-title, .benefit-title img, and .benefit-title h3. A similar method was applied to simplify the CSS for .company-services.

Comments were inputted to help make the code more organized and easier to interpret based on their differing sections. 
