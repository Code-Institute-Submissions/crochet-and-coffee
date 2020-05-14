# Crochet & Coffee Website

Crochet & Coffee is a marketing website promoting a crochet focused craft learning group with social benefits.

A live version of the site is available at: https://gemherbertson.github.io/crochet-and-coffee/

## UX

The Crochet & Coffee website has been developed to target:
* Individuals who want to learn how to crochet without any prior knowledge.
* Those who have experience in crochet but wish to further develop their skills.
* The option for those seeking social interaction to take part with, or without, a craft element.

The website succinctly puts across the benefits in joining Crochet & Coffee, the session schedule and an easy to complete form to register interest.

The design of the site grew organically during the development process. Initial wireframes are available to view via https://github.com/GemHerbertson/crochet-and-coffee/tree/master/wireframes.

## Features

### Existing Features

* Feature 1 - allows users to register their interest to attend learning and social sessions by completing the form contained within login.html.

### Features to Implement

* Feature 2 - inclusion of a dropdown navigational menu for mobile devices.
* Feature 3 - addition of a modal to the login.html page to acknowledge that the form has been successfully submitted.
* Feature 4 - creation of a gallery page, where members can upload photographs of their projects. 
* Feature 5 - creation of a shop page craft kits can be purchased.

## Technologies Used

* HTML5
* CSS3 
* Bootstrap - https://getbootstrap.com/
    The Bootstrap library was used to:
    * Create the responsive grid system for each .html file.
    * Create the form contained within the login.html file.
    * Style the submit button located within the login.html file.  
    Bespoke code was added to the library features to achieve unique styling and is detailed in the style.css file.
* Google Fonts - https://fonts.google.com/
    Google Fonts was used to style the entirity of the website content and the link to the specific font is detailed within the style.css file.
* Fontawesome - https://fontawesome.com/
    All icons were taken from the fontawesome website. 

## Testing

1. Code Validation:
    1. Code for all .html files was passed through the W3C validator at https://validator.w3.org/
        * One issue warning was given for index.html, line 62, col 9 - 43 whereby it was stated that the section lacks a heading.  For styling purposes, it is necessary to position the heading outside of the relevant section. 
    2. Code for the style.css file was passed through the W3C validator at https://jigsaw.w3.org/css-validator/
        * No issues were identified. 

2. Register Interest:
    1. Go to 'Sign Up' page.
    2. Try to submit the form empty and an error message pops up to state fields are required.
    3. Try to submit an email in an incorrect format and an error message pops up to state the correct format is requried.
    4. Submit the form and the form clears. 

3. Responsivity:
    1. The site has been developed to display on a variety of screen sizes.  
    2. @media queries have been included, where necessary, increase UX. 

4. Issues:
    1. A white void has appeared down the right-hand side of the screen seemingly outside of the site contents and further testing is required to identify the cause of the issue.

## Deployment

* The website was deployed via GitHub Pages by:
    * Opening the Crochet & Coffee repository.
    * Selecting the 'Settings' option from the navigation group located above the file structure.
    * Scrolling down to the 'GitHub Pages' section.
    * Selecting the 'master branch' from the Source dropdown menu. 

## Credits

### Media

* Needpix - https://www.needpix.com

about-image: https://www.needpix.com/photo/651866/woman-female-beauty-young-girl-healthy-person-people-adult
make-friends-image: https://www.needpix.com/photo/1036905/people-girls-women-coffee-drink-unwind-relax-talking-friend
new-skill-image: https://www.needpix.com/photo/806543/crochet-wool-yarn-needles-hand-labor-knit-hobby-colorful-creative
beginner-image: https://www.needpix.com/photo/1469094/yarn-colorful-wool-balls-skeins-knitting-wallpaper-publicdomain-background
advanced-image: https://www.needpix.com/photo/73815/yarn-colored-multi-colored-knitting-needlework-sock-yarn-blue-green-red
freestyle-image: https://www.needpix.com/photo/561661/coffee-shop-barista-cafe-worker-coffee-man-adult-employee-business
login-bg-image2: https://www.needpix.com/photo/1039942/yarn-wool-knitting-hooks-around-thread-needle-knitting-yarn-knitted-fabric

* Pixabay - https://pixabay.com

heart-hero-image: https://pixabay.com/photos/heart-mother-s-day-love-pink-5068441/
balance-image: https://pixabay.com/photos/balance-inspiration-motivation-life-865828/ 

### Acknowledgements

* Rahul Lakhanpal (Mentor)
    * Guidance regarding use of 'container-fluid' class for Bootstrap grid system.
    * Advise regarding inclusion of the meta description tag.
    * Clarification regarding background-image syntax. 

* Site design inspiration from:
    * Laura Holland Jewelry - https://www.lauraholland.co.uk/
    * The Boho Shed - https://thebohoshed.co.uk/ 