# accessibility-refactor
Refactoring a website for accessibility concerns and overall improvements.

The following things were done:

1. Replaced div tags where possible with more descriptive ones. 
2. Added alt text to all images.  I elected not to add alt text to the background image on the grounds that it does not convey information relevant to the page
3. rearranged and cleaned up the CSS to follow the flow of the HTML and remove redundant sections
4. rearranged the html to put the main page content in a hierarchical structure
5. replaced most instances of floats with flexboxes for better responsiveness
6. added min width requirements to prevent excess distortion when the viewpoint is rendered very narrow
7. added comments delineating the major sections of the page in both html and css. 

Overall the page ended up looking pretty good on desktop, but mobile does something odd with scaling the aside section and makes it too small.
