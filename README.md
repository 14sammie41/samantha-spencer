![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Samantha Spencer

This page is all about me, where i've come from, what i've done and how i can be the best candidate for your next project or job role. The page will be split into three sub pages containing a 'Home' with my basic about information, a career page setting out what i have done up to this point and a contact page with all of my contact information and a form to ask me questions.

## User interactions

I would like for all of these pages to link into one another as seamlessly as possible by utilising a nav bar to move from page to page and a footer to link to my socials and GitHub accounts. As this page is all about me most of the information will be interchangeable so I will ensure to add buttons to access other areas of the page for speed of navigation.

## Wireframes of all three pages of the site:

I have sketched up all three pages in mobile, tablet and monitor sizes so that there is a baseline to work from. The bulk of the text will come from my actual CV, so there will be no risk of plaguerism. I intend on using mostly AI created images alongside some images of myself.

![wireframe of my homepage](home-page-wireframe.png)
![Wireframe of my career page](career-page-wireframe.png)
![Wireframe of my contact page](contact-page-wireframe.png)

## How to:

### Dependancies

This will be for dependancies as i go through this project - complete as they come through.
*Bootstrap.com has been used throughout the project to add items like a navbar, a carousel and a footer. The main reason for this is to mitigate the need for written Javascript to create a responsive site.
*Microsoft Create was used to create AI images to utilize for the Home page and some content in other areas.
*IMGonline.com was used to pull the key colours out of the gaming.jpeg file. These colours were used to create the Root colours.
*Google Fonts used to import two font styles into the style.css file. Both fonts were attributed to the Root in CSS making the styles uniform accross the site.
*Font Awesome used to import icons for social links in the footer section. Will most likely be used elsewhere too.
*Favicon.io used to create a simple favicon with the correct colours and fonts as used throughout the site. Then linked to each page.
*iloveimg.com was used to compress all of my images to optimise page load up.

### Installing

This will be the basics of how to run and use the site as a user and developer - add to closer to the end of the project

### Executing program

Break down in bullet point commands how to execute the program as a developer - add at the end of the project

## Bug problems and solutions

Add each bug as it occurs and the solution for it.
Ensure to credit any solutions found through other developers or sites.

*Found that the cards added from Bootstrap on my index.html page were overlapping when on an xl screen size. After doing some comparisons against my code for the Boardwalk-games project and browsing the documentation from Bootstrap i realised there was a style of max-width: 18rem; that had been added to the HTML. When removed the cards stopped overlapping and responded better on xl screens.
*Found that the padding on the navbar was creating a banner effect on top and bottom in the wrong colour. Attempted initially to fix it by re-writing the HTML for the navbar ensuring i hadn't missed anything, this did not work. Then i looked on Chrome DevTools to make sure there weren't any pieces of CSS over-riding my CSS, confirmed there wasn't and finally looked at the bottom of Chrome DevTools to find there was basic padding of 8px on top and bottom. Adjusted the padding on CSS to 0 with my own styles.
*Used horizontal cards on the careers page to change it up, found that the amount of text i wanted to put in was overflowing on smaller screen sizes. Having discussed with my fellow class mates about different ways to resolve the problem. We decided the most aesthtically pleasing option was to use an overflow-scroll rule on screen sizes over 992px so the content is scrollable rather than overflowing the card. On screens under 992px i used grid flex box rules with media queries to force the boxes to stay horizontal until the mobile screen size at which point the images sit on top of the text rather than next to.
*Wanted to add a dowload for my CV because it's all very well talking about what i can and can't do on a site but some businesses still want a proper Cv for their files etc. Went to Google and searched how to make something a download link, found the W3 Schools page had an example of how to on their so read the documentation, added the code and tested as per testing document further on. Link is as follows: https://www.w3schools.com/howto/howto_html_download_link.asp .

## Source for images and text

Add all images with their alt and source in here.
Don't forget to compress images where possible for best performance accross different platforms.

## Deployment process

Step-by-step guide to deploying the project if it was to be cloned

## Testing

This section should be large so if it is too large add a new read only file and use that for this task and then link into this page for ease of use.

-Expected
-Testing
-Result
-Fix

Link up to bug fixes here also.
