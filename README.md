# Board Game Cafe

Board Game Cafe is place where people can gather and enjoy their times with man games provided. The website helps people to get to know more about the place and the history of the place. In addition, the website aim to show the variety  of the that the place offer. View the live site [here](https://addas3.github.io/board-game-cafe/index.html)

![Mockup](docs/readme_images/mockup.JPG)

## Features 

### Site wide
* Navigation Menu
    * Consist of links to the Home, What We Offer and Contact Us pages and will be responsive on all devices.
    * The concept of the navigation menu is to make it easier to navigate between the pages within the site on any size device. 

![Nav Menu](docs/readme_images/navigation_menu.JPG)
* Footer
    * This section contain links to social media websites that will open in new tap links.

### Landing Page
* Landing page image
    * This section shows image for group of people playing board games and enoying their time. 
    * This section give the user direct idea of wha the website about.    

 ![Landing Page Image]()
* Website information about us and history
    * Here there is information on about us and cafe hsitory.
    * this will help the user to get better knowledge about the cafe concept. 

![Bio]()  

* Contact form
    * Contact Us form is there to help the user to have a contact with the cafe. The form will consist of the following fields and attributes: 
        * First Name (required, type=text)
        * Last Name (required, type=text)
        * Email (required, type=email)
    * Once the form submitted successfully the user will be navigated to thankyou.html displaying a thank you message.
    * Contact form will help users to contact the cafe so they can send their details to either book a table or to get information.

![Contact Form]()

![Contact Form Received]()

### What We Offer Page
* Board Games
    * There is text and image in this section that help the user to see different types of board games that the cafe have.
    * The text and the image built to attract the user.

* Food
    * This sections shows the user image and text of different type of food the cafe have.
    * Showing different type of food the user can get while they are playing board games.

* Drinks
    * Having image and text helps the user to stay in the page and.
    * Drinks are very important so having it in the page help to convince the user to select the cafe.

![Gallery]()

### Existing Features

* Responsive design
* Contact us form and thank you page


### Features Left to Implement

* Building live booking so the user can book the table directly.

* Implementing in contact us google map location.

## Technologies

* HTML
    * The structure of the Website was developed using HTML as the main language.
* CSS
    * The Website was styled using custom CSS in an external file.
* GitHub
    * Source code is hosted on GitHub and delpoyed using Git Pages.
* Git 
    * Used to commit and push code during the development opf the Website
* Font Awesome
    * Icons obtained from https://fontawesome.com/ were used as the Social media links in the footer section. 
* Tinyjpg
    * https://tinyjpg.com/ was used to reduce the size of the images used throughout the website

### Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in [WCAG 2.1 Reflow criteria for responsive design](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) on Chrome, Edge, Firefox and Opera browsers.

Steps to test:

1. Open browser and navigate to [Board Game Cafe](https://addas3.github.io/board-game-cafe/index.html)
2. Open the developer tools (right click and inspect)
3. Set to responsive and decrease width to 320px
4. Set the zoom to 50%
5. Click and drag the responsive window to maximum width


Website is responsive on all screen sizes and no images are pixelated or stretched.
No horizontal scroll is present.
No elements overlap.

### Accessibility

[Wave Accessibility](https://wave.webaim.org/) tool was used throughout development and for final testing of the deployed website to check for any aid accessibility testing.

Testing was focused to ensure the following criteria were met:

- All forms have associated labels or aria-labels so that this is read out on a screen reader to users who tab to form inputs
- Color contrasts meet a minimum ratio as specified in [WCAG 2.1 Contrast Guidelines](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)
- Heading levels are not missed or skipped to ensure the importance of content is relayed correctly to the end user
- All content is contained within landmarks to ensure ease of use for assistive technology, allowing the user to navigate by page regions
- All not textual content had alternative text or titles so descriptions are read out to screen readers
- HTML page lang attribute has been set
- Aria properties have been implemented correctly
- WCAG 2.1 Coding best practices being followed

Manual tests were also performed to ensure the website was accessible as possible and an accessibility issue was identified.
