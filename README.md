# README for Board Game Designers Ireland HTML/CSS Project

## Introduction

This is an informational website for board game designers who live in Ireland. It is to inform them about the services provided by the Board Game Designers Ireland co-operative group and to give them different ways of getting in contact. It is a professional-facing website, not typically of interest to the general public.

![BGDI website on various sized screens](/assets/images/readme-images/responsive.jpg)
Screenshot from ami.responsivedesign.is

## Features

The title section gives a brief outline of Board Game Designer Ireland's purpose and immiedately offers a way for somebody interested to get in touch (by attending a meet up). It also has an eye catching image with a subtle zoom animation. On a smaller screen, the text section moves above the main image.

The navigation bar links to other pages on the website. On all pages, it is in the top right corner.

Outside of the main page, the title and navigation bar sit side-by-side. On smaller screens, they stack on top of each other.

The About Us section further clarifies the activites carried out by the co-op and their wider ambitions. It uses a staggered layout and images to convey the information in a more interesting way. On a smaller screen, the images and text sections are stacked.

Meet Up section gives information about the different regional groups that belong to Board Games Designers Ireland. On smaller screens these divs increase in height to accomodate the text. On very small screens, the divs increase in width to 100% and then stack.

The Games page presents a portfolio of games made by the co-operative. On smaller screens, the images and text stack.

The Contact page provides a form that the visitor can use to send a message to the co-operative. 

Social media links sit at the bottom of every page and provide the visitor another way of getting in touch. All of these links open in external tabs.

## Testing

The site functions as expected. 

All internal and external links work.

The design is responsive to screen size.

The contact us form is working. The form validates input.

## Bugs

### Fixed Bugs

1. Font awesome does not provide alt text for screenreaders. The Social Media links have a function that requires alt text, but are presented as font awesome font icons. The alt text that I had initially provided wasn't working correctly for these. I had to ask on Slack for some guidance on this and was pointed to font awesome documentation that allowed me to establish aria-labels for the icons.

### Unfixed bugs

1. On very small screens, the navigation links stack but do so in a non-ideal order.
2. On Chrome, some of the responsive design elements do not trigger. Instead, Chrome appears to reduce font sizes so that they are not needed. They do trigger in Firefox. 
3. In chrome, paragraph text on the contact page does not scale.

## Validator Testing
    HTML
    CSS
    Accessibility using Lighthouse

## Deployment
    Steps taken to deploy project

## Credits
    Content
    Media



Code Sources

Navigation and meetup section are taken in part from the Love Running sample project.

Images

"About Us" images are placed as background images in CSS as decorative images go into CSS while images in HTML are for content. Subsequently, images on the "Irish made games" section are in HTML.

Assistive Technologies:

The call to action in the index was going to be a h3 tag, but read that it can be confusing for assistive readers if headings do not go in order. As such, I will style it with a unique ID.

Also, avoidance of all-cap headings. Instead, I have used CSS stying to create all-cap headings.