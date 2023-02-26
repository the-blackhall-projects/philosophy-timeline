# Philosophy Timeline
## An interactive timeline of philosophy

### Repository Location:
https://github.com/the-blackhall-projects/philosophy-timeline

### Live page
https://the-blackhall-projects.github.io/philosophy-timeline/index.html

## Purpose

This is an attempt to provide a timeline of philosophy using generated content.  As well as displaying the timeline, the user can sign up for a newsletter and find further content on social media sites.

Use has been made of the Code Institute's "Love Running" project for the newsletter signup form and in the Nav and footer sections of the pages.

The text content (but not CSS and HTML code) has been machine generated by ChatGPT. 

## Target user
A student of philosophy or any person interested in philosophy and its history.

## Site user's goal:

The site’s users are interested in the historical facts about philosophy.

## Site owner's goal:

The goal of the site is to provide a reliable source of information pertaining to the history of philosophy.

Site includes:

*    A timeline of periods, schools and movements in philosophy.
*    Ability to expand a particular timeline entry to gain more background and further timeline entries.
*    Images are provided to add context to the text in question.

The website is incomplete as a fully complete site would require hundreds of pages.  However the intention here is to demonstrate techniques in HTML and CSS rather than completeness.

The site is designed to be extended with a template html file in the project folder. 

## Screnshots and responsiveness

Click on image below for live view on [Am I Responsive](https://ui.dev/amiresponsive).

[![Link to "Am I Responsive" view of site](https://the-blackhall-projects.github.io/philosophy-timeline/assets/images/responsive-screenshot.png)](https://ui.dev/amiresponsive?url=https://the-blackhall-projects.github.io/philosophy-timeline/index.html)

The design is responsive through the use of media queries and works on all sizes of device.  Widest is in three columns.  The left column is for an illustrative image and is of fixed width.  The middle column is for the main text describing the timeline and is of variable width.  The right-most column contains the timeline corresponding to the text.

As the screen is narrowed the first thing that happens is that the navigation menu on the top right moves to below the main heading.  This is to avoid it colliding with the heading in narrower screens.

As the screen is further narrowed, left most column is removed causing the image to dissapear.  This allows for a reasonably wide column of main text and the timeline to remain on the right-hand-side.

Finally, for phone devices, a single column display is produced with the timeline following on below the main text. 

## Accessibility

All font colours are dark on a bright background.  All images have an alt-text to cater to the visually impaired. 

Lighthouse gives the site and accessibility of 98%.

[![Lighthouse Accessibility score](https://the-blackhall-projects.github.io/philosophy-timeline/assets/images/lighthouse.png)](https://pagespeed.web.dev/report?url=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Findex.html&form_factor=desktop)



## Intellectual property

Text for the articles is generated by ChatGPT.  Images except one are from Wikipedia and are freely reproducible under the Creative Commons licence.  One image was generated by Dall-e 2.  

## Site navigation

At the top of the screen there is a site menu consisting of a home link and a newsletter sign-up link.  The active link is underlined and the link under which the mouse is hovering is also underlined.

On the right-hand-side is a timeline and clicking on one of the links (highlighted when hovered over) brings up further information on the timeline entry.  The linked page may contain a further timeline.  Each page has a link back to home or the newsletter page.

With the navigation menu and timeline links, site navigation is thus intuitive.

There are nine pages in total but the design is such that more can be added.  A complete website might contain about 100 pages.  
## Bugs found and fixed

No major bugs were found but minor bugs concerning rendering were found and fixed.  In particular, getting the 3-column layout to work correctly took time to fix.

## Design considerations

Semantic markup has been used within the pages to convey structure.  Header, nav and footer tags are used appropriately and the main text is enclosed in a section tag.  This makes it easier for sight reader software as well as improves SEO.

Site is easily navigated while presenting an uncluttered appearance.  Links are where the user might expect them to be and hovering the mouse over them changes their appearance thereby, it is felt, creating a positive emotional response.

Every page is created from the same template creating a consistent appearance and functionality.  When filling forms, the user is presented with feedback in order to enter the correct information.

A conservative, document-like style has been used a a guiding principle in the design.  Rather than spaced paragraphs, the first line is indendented with the exception of the first paragraph which is unindented. 

A pleasent readable font appropriate to the subject matter is used for the main text and used consistantly throughout.

Levels of importance of information are conveyed through the size and style of the fonts used in headings and text according to established convention.

There are no links to external pages but, were there to be, they would open in a new page.

## Coding considerations

All filenames, image names, IDs and classes are given meaningful and consistent names. The code is clear, understandable, and maintainable and therefore considered 'clean'.  

In terms of file structure, all html files are in the root directory.  There is also an "assets" directory divided in to "css" and "images" where stylesheets and images respectively are placed.  Files consistantly are lower case and without spaces with undescores used to separate words.

## CSS and HTML Validation

### CSS Validation

Using the [W3C W3C CSS Validation Service](https://validator.w3.org/).

Click here to validate the stylesheet [style.css](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en).

Errors: "Congratulations! No Error Found."
Warnings: 
-webkit-hyphens is a vendor extension
-moz-hyphens is a vendor extension
-ms-hyphens is a vendor extension

These vendor extensions are needed to encourage hyphenation and therefore justified.

### HTML

Click on the links below to validate them using the [W3C Markup Validation Service](https://validator.w3.org/)

[index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Findex.html)

[newsletter.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Fnewsletter.html)

[pre_socratic_philosophy.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Fpre_socratic_philosophy.html)


[socratic_platonic_tradition.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Fsocratic_platonic_tradition.html)

[hellenistic_philosophy.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Fhellenistic_philosophy.html)


[aristotelian_tradition.html.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Faristotelian_tradition.html.html)

[roman_early_christian_philosophy.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Froman_early_christian_philosophy.html)

[medieval_philosophy.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Fmedieval_philosophy.html)

[renaissance_philosophy.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthe-blackhall-projects.github.io%2Fphilosophy-timeline%2Frenaissance_philosophy.html)

All validations produce "Document checking completed. No errors or warnings to show".








