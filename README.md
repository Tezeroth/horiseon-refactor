## UK-VIRT-FE-PT-11-2023-U-LOLC-1 - wk1

This website is part of the first week's challenge of the EDX boot camp UX/UI course. In it, we were given the task of editing HTML to make it more semantic and usable,
and then to deploy on GitHub


## Below are the tasks we were to complete, and what changes I made to the code

# 1: To ensure semantic HTML elements were found through the source code

- I ensured that the div, for the header class was renamed to 'header'
- I ensured that the div containing nav menu items was changed to nav, and edited the appropriate CSS
- I ensured the div with the class hero was titled main
- I ensured the div class named content was changed to content
- I ensured the divs in the content class were renamed to article
- I ensured the div containing the aside section was renamed to aside
- I ensured the aside sections divs were renamed to section
- I ensured the footer classes div was renamed to footer

two things that concerned me were that there were two definitions of class and id, one of which points to nowhere
I left them because they could be for something further down the line perhaps as the site grows. - please refer to the comments
in the HTML

# 2: To ensure image and icon attributes contained the 'alt' attribute

-I ensured the links in the nav bar had alt attributes - this may be excessive but I put them in for accessibility
-I ensured that the main landing image had an alt description of 'people in a meeting'
-I ensured the article images in the content section all had alt attributes and explanations of what they are
-I ensured all the icons in the 'aside' sections, all had alt attributes and explanations of what they are

# 3: To ensure the heading attributes fall in sequential order

- I ensured that the headings all fall in sequential order, with h1 being used on the header, h2 on the articles of the content classes, and the h3 heading used in the aside section
  
# 4: To ensure the title elements contain a concise descriptive title

- I ensured that all of the title elements were given a concise and descriptive title, that essentially matched the alt attributes.

## Lessons Learned

The teachings I have learned in today's lesson are that GitHub is very difficult and that it will require further study to become proficient and confident in using it. Thank you to our TA Sara Benchinoun, for helping me to deploy this website, due to misunderstandings of the concepts of 'main' and 'master'.

I also altered CSS attributes, even though not necessarily required to do so, to allow the aside column to fit to the side of the main content - this displays reasonably correctly on all four of my monitors, but not on my mobile device. 
The aforementioned changes are mentioned in the comments in the CSS file. The .body CSS attribute had its padding and margin reduced to 0px as well to ensure that the 'hero' landing image and header/nav bar were flush against the sides of the browser window as well.
