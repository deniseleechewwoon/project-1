# Ardour Photography - Website for a Photography Firm  
##  Code Institute - User Centric Frontend Development Milestone Project (1)
##  Student Name: Denise Lee Chew Woon

For this project, a website was created for a fictitious photography company.

<a href="https://ibb.co/8dd0fDr"><img src="https://i.ibb.co/CMMzY5b/Project-Pages.jpg" alt="Project-Pages" border="0"/></a>

The site may be viewed [here](https://deniseleechewwoon.github.io/project-1-ardourphotography/index.html)

This website aims to showcase the company's best photography work and eventually achieve a call to action from the user. From the company name, logo, corporate colour scheme to the website design concept, the objective is to provide a forthright, passionate yet sincere approach to attract the target audience. 

After visiting the website, the user should be able to fully understand the company's background and basic team structure via the introduction on the About Us page. The best photography works of the firm will also be interactively illustrated on the Galleries page. Eventually, with hopes to establish a connection with the customers at the Contact Us page.
 
## UX

The target audience for the website will be
* Consumers looking for professional photographers
* Photography enthusiasts

In order to achieve the intent of converting viewers of the website into company customers or potential photography collaborations, the website aims to portray a forthright, passionate yet sincere image for the company. It uses clean, minimalist yet attention seeking elements to capture and leave an impression on the viewers. A four-colour palette scheme consisting of both warm and cool colours was maintained throughout the whole website design. The website strives to represent a certain degree of professionalism by keeping the minimalist look and feel throughout. This is consistent and evident through the initial sketching of the wireframe. A copy of the sketch may be viewed [here](https://drive.google.com/open?id=1v517SFDDMVm5ZJ5zaNFKmwJi8O_Qc_-k).

Besides the look, the website also ensure that it is user-friendly and interactive. When a user first enter the website, they will be greeted by a captivating photo, company logo, quote followed by a button. This will induce the user to look at the company name, quote and photo before they officially enter to the About Us page.

By bringing the users directly to the About Us page, it guides them immediately to find out about what the company is doing. In there, users will be "greeted" by the team as they hover over their photos. On hovering each profile photo, it shows: I'm Name (Joseph) followed by their designation (Chief Photographer). Using this, I hope to create a light-hearted and welcoming ambience to the page. 

Naturally, the core of the website is the galleries page since this is a photography company website. To ensure that users can view their desired categories of photography works, the various galleries were carefully categorized using prominent images. Upon entering each gallery, users will be able to view the photographs clearly via the modal image gallery (lightbox). Needless to say, the vibrant photographs will do the talking/selling!

Last but not least, I hope to finally establish a contact with the user of the website. To keep the users, I hope to keep it simple by establishing a clear and painless contact form for them to fill in. The email and message segment was made a required field so the company will be able to follow up with them on their wishes or requests.

## Features

* Centralised Navigation Bar - Easy access and is mobile responsive
* [Home Page](https://deniseleechewwoon.github.io/project-1-ardourphotography/index.html) 
    1. Animated Page, slides in together with Company Logo from top of page - Brings some life to the static page.
    2. Animated button on hover - making it interactive
* [About Us Page](https://deniseleechewwoon.github.io/project-1-ardourphotography/about-us.html) 
    1. Animated Top Jumbotron, slides in from top of page - Brings some life to the static page.
    2. Profile Pictures tranisitions into overlay with text on hover - making it interactive
* [Galleries Page](https://deniseleechewwoon.github.io/project-1-ardourphotography/galleries.html)
    1. Animated Top Jumbotron, slides in from top of page - Brings some life to the static page.
    2. Image tranisitions into an overlay with text on hover
    3. Mobile responsive modal image gallery (lightbox) using css and javascript
* [Contact Page](https://deniseleechewwoon.github.io/project-1-ardourphotography/contact-us.html)
    1. Animated Top Jumbotron, slides in from top of page - Brings some life to the static page.
    2. Required fields for email and message - to ensure leads for company
    3. Form validator for email


### Features Left to Implement
* To add in a full video background on landing page - increase the interactive element and tell a story via the video
* To add in a smooth scrolling effect with CSS for the Galleries Page - when the galleries page categories grow, it will be easier for the viewers
* To add in a depository for the contact us page - make the form workable

## Technologies Used

* [HTML](https://www.w3schools.com/html/) - standard markup language for creating web pages
    - HTML is basically used throughout the whole document to construct the various segments and putting things together

* [CSS](https://www.w3schools.com/css/) - describes the style of the HTML document
    - CSS is important to maintain the look, style and feel of the website

* [Bootstrap 4.4](https://getbootstrap.com/docs/4.4/getting-started/introduction/) - popular framework for building responsive, mobile-first sites
    - Bootstrap framework makes things easier to have basic features and minimised the use of css styling with bootstrap features

* [Javascript](https://www.youtube.com/watch?v=gnDOjWUSHks)
    - Javascript is used to create a responsive lightbox - modal image gallery

* [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing
The site is manually tested on a macbook pro, windows laptop, mobile device (Samsung note 9) and ipad pro to ensure the responsiveness and that all the links work well.

On all platforms, the following were tested

1. Landing Page
    - The animated slide in effect of the page works well with every refresh
    - The button ia able to bring the users to the About Page works well
2. About Us
    - The navbar to access all the pages (Home > About Us > Galleries > Contact) is tested to ensure it works well
    - There is a image hover effect on all the profile pictures of the team and it is tested to work well
3. Galleries
    - The navbar to access all the pages (Home > About Us > Galleries > Contact) is tested to ensure it works well
    - There is a image hover link to each gallery and is tested to work well
4. Contact
    - The navbar to access all the pages (Home > About Us > Galleries > Contact) is tested to ensure it works well
    - Try to submit an empty form and verify that an error message about the required fields appears
    - Try to submit the form with an invalid email address and verify that a relevant error message appears

The site was manually tested on different browsers (Chrome, Safari, Morzilla Firefox and Internet Explorer).
The site works well on all browsers except for internet explorer. In internet explorer, the individual gallary page was not able to load the photos nicely as it does on other browsers.

The site was also tested using online platform [Mobile-Friendly Test](https://search.google.com/test/mobile-friendly) and results show that page is mobile friendly and easy to use on a mobile device.

## Deployment

This site is hosted on Github Pages and directly deployed from the master branch.
A repository was firstly created using github and commits were pushed to the master branch. Materials are pushed to the GitHub repository with git add, git commit, and git push.
Eventually, the deployed site will be updated automatically upon any new commits. 

The landing page of the site is named index.html.
There are 2 folders, namely CSS and Img to place the css stylesheet and images on the website respectively. 

## Credits

### Content
- The text for the About Us section was modified from the [Firefly Photography SG](https://fireflyphotographysg.com/)
- The text for the Galleries and Contact Section was modified from [Lisa Michele Burns](https://www.lisamicheleburns.com/)


### Media
- Only the photo from the home page is taken by me. All the other photos used in this site are obtained from [Unsplash](https://unsplash.com) and [Pexels](https://www.pexels.com). Please refer to the full credits and link for each image [here](https://drive.google.com/open?id=1okGs7z2vhfrdHt4a5wS5srXpBuL7fmJd).
- The company logo was created using [Photoshop](https://www.adobe.com/sea/products/photoshop.html?gclid=EAIaIQobChMI_rXt5v2c6AIVWq6WCh3BSwRuEAAYASAAEgIzIPD_BwE&sdid=YP7XGDLR&mv=search&ef_id=EAIaIQobChMI_rXt5v2c6AIVWq6WCh3BSwRuEAAYASAAEgIzIPD_BwE:G:s&s_kwcid=AL!3085!3!400503272159!e!!g!!photoshop) by myself.

### Acknowledgements
- CSS Styling by [Bootstrap4](https://getbootstrap.com/).
- All fonts used for this site are obtained from [google fonts](https://fonts.google.com/).
- The landing page camera icon is obtained from [Font Awesome](https://fontawesome.com/).
- The navbar center aligned is inspired by [User: Skelly @ Codeply](https://www.codeply.com/u/skelly) and code take from [here](https://www.codeply.com/go/0xSGj0EsAu).
- Image Hover Overlay effects and Image Hover Fullscreen Zoom are learnt from [w3schools](https://www.w3schools.com/howto/howto_css_image_overlay.asp).
- Responsive lightbox image gallery is learnt and obtained from [webseotips](https://www.youtube.com/watch?v=gnDOjWUSHks).

### This website created is for educational use.