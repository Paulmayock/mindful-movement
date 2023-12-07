# Mindful Movement

Mindful movement is a yoga website which shows users some of the main poses when doing yoga. The poses also include some images of each pose to give the user a better understanding of the stance. The website also gives the user the opportunity to sign up to the yoga club along with contact details and links to our social media.

![Mock](doc_images/readme_images/header-menu.PNG)

## Features

### o   Header

o	This menu contains links to Home, Poses and Sign up page and will allow users to navigate between menus.

o	On smaller screens the menu will change to a dropdown symbol called more so the menu will fit on smaller screens and the user can navigate the menu from there.

![Smaller-screen-menu](doc_images/readme_images/home-menu-more.PNG)

o   Footer
o	On the left of the footer it will feature contact info including phone number and email to contact Mindful Movement.
o	Underneath the contacts will include links to social media. When clicked on these links will open new tabs.

### o   Favicon

o	The Mindful Movement logo will show on the tab page so user know which tab the website is on.

![favicon](doc_images/readme_images/favicon.PNG)

## Landing page

o	This will be an image of the Mindful Movement logo. Below this will include a welcome message of what the aim of the club is. It also points to the poses and sign up if users are interested.

![main-footer](doc_images/readme_images/main-footer.PNG)

## Techniques page

o	The aim of this page is to show the user some of the most popular yoga poses. There are six poses featured. Each pose will give step by step instructions on how to move into each pose.
o	The page also contains an image for each pose so the user can have a better understanding of what position their body should be in when attempting each pose.

![mountain](doc_images/readme_images/mountain-pose.PNG)

![standing-forward](doc_images/readme_images/standing-forward.PNG)

![upward-facing](doc_images/readme_images/upward-facing.PNG)

![downward-facing](doc_images/readme_images/downward-facing.PNG)

![half-moon](doc_images/readme_images/half-moon.PNG)

![childs-resting](doc_images/readme_images/childs-resting.PNG)

## Design

o	Wireframe

o	Home page

![wireframe](doc_images/readme_images/wireframe.PNG)

## Sign up page

o  The aim of this page is for users who wish to sign up to the yoga club can do so by filling out their information. All fields are required so no information from the user can be left blank.

![sign-up-form]()

## Features

o	Responsive design
o	Clickable contact links which open app to contact yoga club
o	Sign up form with required fields

## Desired features not implemented

o	Thank you page and return to main page when sign up form has been completed
o	A timetable showing monthly classes and a booking system to sign up.

## Technologies

### o	HTML

o	The structure of the Website was developed using HTML as the main language.

### o	CSS

o	The Website was styled using custom CSS in an external file.

### o	Codeanywhere

o	The website was developed using Codeanywhere IDE.

### o	GitHub

o	The source code is hosted on Github and deployed using Git pages.

### o	Favicon

o	Favicon files created on <https://www.favicon-generator.org/>

### o	Font Awesome

o	Social media Icons downloaded using <https://fontawesome.com/>

### o	Cloud convert

o	To convert images to WEBP format to website was used <https://cloudconvert.com/>

### o	123rf

o	Used to create the mindful movement logo www.123rf.com

### o	balsamiq

o	wireframes were created using balsamiq from <https://balsamiq.com/wireframes/desktop/#>

## Websites

### o	W3schools

o	Website used to research HTML and CSS functions <https://www.w3schools.com/>

### o	Mind body green

o	Site used to research steps for yoga poses www.mindbodygreen.com

### o	Maji sports

o	Site used to research steps for yoga poses www.majisports.com

### o   Wave webaim

o   Site used to test the accessibility of the website

## Testing

### Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined on browsers including Chrome and Firefox.

Steps to test:

1. Open browser and navigate to [Mindful Movement](https://8000-paulmayock-mindful-movem-uaehkwojuv.us2.codeanyapp.com/index.html)
2. Open the developer tools (right click and inspect)
3. Set to responsive and decrease width to 320px
4. Set the zoom to 50%
5. Click and drag the responsive window to maximum width

Expected:

Website is responsive on all screen sizes and no images are pixelated or stretched. No horizontal scroll is present and no elements overlap.

Actual:

Website behaved as expected with the exception of switching to landscape view in Mozilla Firefox. Details can be found in [Unfixed Bugs](#Unfixed-Bugs)

### Accessibility

Testing was focused to ensure the following criteria were met:

o Color contrasts are applied for an easy to view on users vision
o Heading levels are npplied to ensure the importance of content is relayed correctly to the end user
o All content is contained within landmarks to ensure ease of use for assistive technology, allowing the user to navigate by page regions
o HTML page lang attribute has been set
o Aria properties have been implemented correctly
o WCAG 2.1 Coding best practices being followed

### Lighthouse Testing

Below shows the results for each page when tested using lighthouse testing.

o Home

[home](doc_images/testing_images/home-page.PNG)

o Poses

[poses](doc_images/testing_images/poses-page.PNG)

o Sign up

[sign-up](doc_images/testing_images/sign-up-page.PNG)

### Functional Testing

o **Navigation links**

Testing was performed to ensure all navigation links on all pages navigated to the correct pages as per design. This was done by clicking on the navigation links on each page.

| **Navigation Link** | **Page to Load** |
| ----------- | ----------- |
| Home | index.html |
| Poses | poses.html |
| Sign up | signup.html |




## Problems

Cannot get the main content to show on small screen (galaxy fold)
Cannot get the h1 header to center
Could not get page to scroll. Had to increase px of hero image
