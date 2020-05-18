# Crochet & Coffee Website

Crochet & Coffee is a marketing website promoting a crochet focused craft learning group with social benefits.  A live version of the site is available at: https://gemherbertson.github.io/crochet-and-coffee/.  

The inspiration for the website came from personal experience, having a number of friends who are developing small businesses in their spare time with aim of making a financial return on their passion.  

The Crochet & Coffee website creates a dedicated online presence for such a small business that outlines the basic services provided, costs and associated benefits.  

## UX

The Crochet & Coffee website has been developed using HTML5 and CSS3 to target:
* Individuals who want to learn how to crochet without any prior knowledge.
* Those who have experience in crochet but wish to further develop their skills.
* The option for those seeking social interaction to take part with, or without, a craft element.

The website succinctly puts across the benefits in joining Crochet & Coffee, the session schedule and an easy to complete form to register interest.

The design of the site grew organically during the development process. Both initial and final wireframes are available to view via https://github.com/GemHerbertson/crochet-and-coffee/tree/master/wireframes.

## Features

### Existing Features

* Feature 1 - a contact form has been added to the site to enable site users to register their interest to attend learning and social sessions through form completion/submission.  The form has been kept purposefully simple, with minimal information required (name and email), in order to improve UX.  Users are provided with checkboxes to facilitate easy indication of their area of interest however the option to send a message as part of the form submission is also offered, for more complex inquiries.
* Feature 2 - a floating button has been added to the right-hand side of the site to enable users to easily return to the top of the page from any section of the site.  

### Features to Implement

* Feature 3 - inclusion of a dropdown navigational menu for mobile devices.
* Feature 4 - addition of a modal to the login.html page to acknowledge that the form has been successfully submitted.
* Feature 5 - creation of a gallery page, where members can upload photographs of their projects. 
* Feature 6 - creation of a shop page craft kits can be purchased.

## Technologies Used

* HTML5
* CSS3 
* Bootstrap - https://getbootstrap.com/
    The Bootstrap library was used to:
    * Create the responsive grid system to structure the site.
    * Create the form, including styling of the send button.  
    * A variety of Bootstrap classes have also been utilised across the site to achieve the required styling.
    Bespoke code was added to the library features to achieve unique styling and is detailed in the style.css file.
* Google Fonts - https://fonts.google.com/
    Google Fonts was used to style the text of the website content and the link to the specific font is detailed within the style.css file.
* Fontawesome - https://fontawesome.com/
    All icons are displayed using code provided from the fontawesome website. 

## Testing

1. Code Validation:
    1. Code for all .html files was passed through the W3C validator at https://validator.w3.org/
        * One issue warning was given for index.html, line 68, col 17 - 51 whereby it was stated that the section lacks a heading.  For styling purposes, it is necessary to position the heading outside of the relevant section. 
    2. Code for the style.css file was passed through the W3C validator at https://jigsaw.w3.org/css-validator/
        * No issues were identified. 

2. Contact Us:
    1. Go to 'Contact Us' section.
    2. Try to submit the form empty and an error message pops up to state fields are required.
    3. Try to submit an email in an incorrect format and an error message pops up to state the correct format is required.
    4. Submit the form and the form clears. 

3. Responsivity:
    1. The site has been developed to display on a variety of screen sizes.  Following deployment, the site has been viewed on a selection of available devices, as well as using Chrome Developer Tools, to determine its suitabilty.  
    2. @media queries have been included, where necessary, to increase UX. 

4. Issues:
    1. On some devices, a white void appears intermittently down the right-hand side of the screen, seemingly outside of the site contents.  Further testing is required to identify the cause of the issue.

## Deployment

* The website was deployed via GitHub Pages by:
    * Go to github.com.
    * Opening the Crochet & Coffee repository.
    * Selecting the 'Settings' option from the navigation group located above the file structure.
    * Scrolling down to the 'GitHub Pages' section.
    * Selecting the 'master branch' from the Source dropdown menu. 
    * After a period of time, a link will be displayed to the live site.
    * Right click on the link and select 'copy link address' from the context menu.
    * Issue the live link via appropriate media.

## Credits

### Media

* Needpix - https://www.needpix.com

about-image: https://www.needpix.com/photo/651866/woman-female-beauty-young-girl-healthy-person-people-adult
make-friends-image: https://www.needpix.com/photo/1036905/people-girls-women-coffee-drink-unwind-relax-talking-friend
new-skill-image: https://www.needpix.com/photo/806543/crochet-wool-yarn-needles-hand-labor-knit-hobby-colorful-creative

* Pixabay - https://pixabay.com

heart-hero-image: https://pixabay.com/photos/heart-mother-s-day-love-pink-5068441/
balance-image: https://pixabay.com/photos/balance-inspiration-motivation-life-865828/ 

### Acknowledgements

* Sources utilised to address design challenges are detailed within the body of the code at appropriate junctures.

* Site design inspiration from:
    * Laura Holland Jewelry - https://www.lauraholland.co.uk/
        The inspiration from this site was the particular use of soft colours and the distribution of content primarily across three columns. 
    * The Boho Shed - https://thebohoshed.co.uk/ 
        The inspiration from this site was it's use of colour to break up the site content into row sections as well as its use of images to put across the focus of the business. 