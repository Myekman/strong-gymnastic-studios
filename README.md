# Strong Gymnastic Studio
This website was created for a Gymnastics studio, located in Sweden's capital, Stockholm.

Strong Gymnastic Studio is a website for those who are interested in starting to practice gymnastic. 

![IMG](/assets/images/amiresponsive3.jpg)

A live version of the webbsite can be found here! [Strong Gymnastic Studios](https://myekman.github.io/strong-gymnastic-studios/)

# The purpose with the webbsite

The website is primarily created to attract more people to join. Therefore, there are clear choices on the start page with navigation links that takes the reader directly to: 
Contact information, Sign up form or to sections where you can read more about the oparation and different classes. The wish is to inspire curiosity and for the reader to make contact. 

The navigation links is constant through all pages to easily navigate in the website.

The feeling on the webbsite should be that the studio is for everyone!
In the form there are a welcoming message to beginners to book a free trial. 

# Table of content

### List of features:

* [Comming Features](comming-features "Comming Features")
* [Header](#header "Header")
* [Navigationbar](#navigationbar "Navigationbar")
* [Gymnastic Groups](#Gymnastic-groups "Gymnastic Groups")
* [Form](#form "Form")
* [Classes](#classes "Classes")
* [About us](#about-us "About us")
* [Footer](#footer "Footer")
* [Thank You Page](#thank-you-page "Thank You Page")


### UX/UI:

* [Site Goals](#site-goals "Site Goals")
* [User Stories](#user-stories "User Stories")
* [Requirements](#requirements "Requirements")
* [Design](#design "Design")
* [Typography](#typography "Typography")
* [Images](#images "Images")

### Technologies used:
* [CSS](https://en.wikipedia.org/wiki/CSS)
* [HTML](https://en.wikipedia.org/wiki/HTML)

### List of testing

* [Testing](#testing "Testing")
* [Manual Testning](#manual-testing "Manual Testing")
* [HTML Validator](#html "HTML")
* [CSS Validator](#css "CSS")
* [Lighthouse](#lighthouse "Lighthouse")

### Develop and Deployment

* [Deployment](#deployment "Deployment")
* [Content](#content "Content")
* [Media](#media "Media")
* [Credits](#credits "Credits")

## Site Goals 

The goal of the webbsite is to attract more gymnasts to join. It Should be easy to navigate between different pages and the following questions must be clear:
* How to join?
* I have more questions, how to get in touch?
* Who can join?
* Im a beginner, can i join?

## User Stories

As a visitor on site i want to:

* Find information about the operation.
* Find information where it is located.
* Find information of tel and email. 
* Find information on how to get in touch.
* Find information about what classes they offer.
* Ask for someone to contact me via the contact form.

## Requirements

A static responsive website that incorporates the technologies I have learned so far that contains some advanced functionality. The development process needs to be well documented through a version controls system such as GitHub.

Required technologies: HTML, CSS.

## Design 

* Since this is the first webbsite i ever done, the structure and design are inspired of the Love Running Project. 
*The color palette was at first inspired of the pictures i found at pexels.com. I know i wanted something pink and light from the start. 

### Color Palette

![IMG](/assets/images/hex-palette3.png)

* The Color Palette was made using [Coolors](https://coolors.co/413c58-a3c4bc-bfd7b5-ecbaf8-ffffff).

## Typography


* The typograpfy was imported from [Google fonts](https://fonts.google.com/) and pasted in style.css file. 
* For the headings i use [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue?query=bebas+neue) (Regular 400), with a fallback of Sans-Serif.
* For the paragraphs and links i use [Bitter](https://fonts.google.com/specimen/Bitter) (Light 300),  with a fallback of Sans-Serif. 

## Images 

*I chose the images for the clean feel. As they look clean and contain few colors them are easy to match with the rest of the design.
* Size of images are customized to fit the rest of the page structure. 

## Features 

### Comming Features
#### Left to implement:

1. More information about price and membership will be added in a table.
2. The Free Trial will be possible to book an appointment for directly on the page. 
3.  A page will be added to upload comming event and happenings. 
4. Images of coaches will be added to About us section to get more invited and personal feeling.

## Header 

![IMG](/assets/images/header.png)

The Header contains a background-image of gymnastic rings, to display the feeling what this site is about. 

 ### Navigationbar

 The header contains a navigationbar in top of page.


* *Contact* - Takes the reader to the footer where contact information is available.

* *Classes* - Takes the reader to a new page where it is more information about different kinds of gymnastic and training times. 

* *About us* - takes the reader to a new page where You can find out more about the oparation.

* *Sign upp here!* - Takes you directly to the form section in the same page.


## Gymnastic Groups

![IMG](/assets/images/Gymnasticsection.jpg)

* This section of the home page contains 3 pictures that announce that gymnastics is available for both men, women and children. 
* The section also have links "Read More", that takes the readers to more information about the different classes. (to same place as "Classes" link in nav bar).


## Form 

![IMG](/assets/images/form-section.jpg)

* In this section the opptions is clear and easy to follow. 
Choose which class you are interested in or choose the opption of free trial. 

## Classes

![IMG](/assets/images/classes2.jpg)

* This section contains shortly information about what different classes they offer to Men, Women, Yought and Kids. 

### Classes Practice Times:

![IMG](/assets/images/practice.jpg)
![IMG](/assets/images/rythmic.jpg)
![IMG](/assets/images/team.jpg)

* For they who want more information, are invited to call/email or sign upp via form.

This section have 3 Tables of practice times. 
* One for Artistic Gymnastic for Men and Woman. 
* Second one for Rythmic Gymnasic for Woman and Yought. 
* The the third one for Team Gymnastic. In this Men & Woman share the same practice times and Kids & Yought share same times. 

## About us

![IMG](/assets/images/about-us1.jpg)

* This section contains an image of Stockholm with the same height and width, and with border-radius of 50% to get to round image. 
* A paragraph telling the story behind Stong Gymnastic Studios.

## Footer 

![IMG](/assets/images/footer.jpg)

* The Footer has the same logo as the header to keep the feeling over the website. 
* Contact information and links to social media. 

## Thank you page 

![IMG](/assets/images/thankyoupage.jpg)


## Testing 


Here is a list of issues discovered and how they were solved. 

1. The link to get to form section didnt work. 
*  Solution: Addthe"#" to a href=#form-section. 
2. Images in gymnastic studios section disapered when i styled the page to smaller screen sizes. 
*  Solution: I set the float to left for the image in the middle from margin: 0 auto. 
3. Images was shown just at its bottom.
*  Solution: Set the background-position to center. 
4. The contet i wanted to add above images in gymnastic gruops section didnt show up.
*  Solution: Change to right section id. 
5. Poor performance on smaller screens.
* Solution: Fixed by using by media queries. 
6. The circle image beside the form that is floated to left, didn't appear to the right as att wished. 
* Solution: set the clear attribute to none. 
7. The sign upp here link didn't work from classes.html page.
* Solution: Added form section to classes.html page and the link was working. 
8. Apart from these problems i have had a ton of small ones. It can be for example that contet not fall in the right place i wish for.
* It has been solved with attribute of example: padding, margin, float, text-align.

### Unfixed bugs 

All the bugs were fixed and moved to the section Testing.

## Manual Testing 

### Home navigation bar:
They all works like expected: When click on the links it takes me to 
home, about us, classes.

### More links & social media links: 
* "Sign upp!" link in header works as expected, it takes me to form.
* "Read more" link in gymnastic groups section works as expected, it takes me to classes.html page. 
* Social media links in footer works like expected, takes me to facebook and instagram when clicked. 

### Form submit button:
Workes as expected, the form sucessfully submitted on click and take me to formdump page. 

## HTML 

* Testing of the site has been done several times during this project. To ensure that the page is suitable for different screen sizes, I have used Google DevTools and Also with: [Am I Responsive](https://ui.dev/amiresponsive).

* Test has been conducted using Google Chrome, Mozilla Firefox and Safari.

![IMG](/assets/images/html-validate.png)

* No errors were showed when passing thrue HTML [3Wc Validator](https://jigsaw.w3.org/css-validator/). 
* All three pages was tested and all passed validator. 

## CSS

![IMG](/assets/images/W3C-validator1.png)

* No errors were showed when passing thrue CSS [Jigsaw Validator](https://jigsaw.w3.org/css-validator/). 

## Lighthouse 

![IMG](/assets/images/lighthouse1.png)

* The results of Lighthouse testing above.

## Deployment 

The development environment used for this webbsite was GitPod. In GitPod a template enviorment was used provided by Code Institute.

Regular commits and pushes to GitHub have been implemented to save through  development.

The procedure for deployment was followed by the video from Love Running. 

1. Log into GitHub.
2. Find the Repository that you want to deploy live.
3. At the top of the repository, select Settings.
4. Click "Pages" to the left in menu. 
5. The ”Source” should be "deploy from branch". Then choose Branch as ”main” and "root" as folder and click ”Save”.
6. The website will deploy and the link to live webbsite will be ready when refresh the page. 

## Content
* All text content on this site has been produced by the author of the project and is fictional. There is no Strong Gymnastic Studio in real life. 
* All CSS and HTML is ispired of the Love Running project, HTML and CSS Essentials and from [w3schools](https://www.w3schools.com/tags/tag_em.asp).  
* The social media icons in the footer was taken from [Font Awesome](https://fontawesome.com/icons/dumbbell?s=solid&f=classic).

## Media

* All images was downloaded from [pexels](https://www.pexels.com/).

## Credits 

Martina Terlevic

* My fantastic mentor at Code Institute

And also all awesome people att slack code institute community who are warm and helpful every time. 

## Great sources

https://www.w3schools.com/ 

Image in top that present site in differns devices are made with:

http://ami.responsivedesign.is/

Best Regards 

[back to top](#strong-gymnastic-studio "Strong Gymnasic Studio")







