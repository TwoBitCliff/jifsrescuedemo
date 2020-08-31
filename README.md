# Jif's Rescue

[View the live project here](https://twobitcliff.github.io/jifsrescue/)

This is the main website for Jif’s Rescue, a fictional animal rescue sanctuary aimed at rehoming animals, fundraising and spreading awareness.
This is the first milestone project for the Full Stack Developer course, encompassing all skills learnt so far, including HTML and CSS, as well as using bootstrap for a user-friendly, mobile first design.
It is designed to be attention grabbing and encourage the user to return. To help achieve this, the website is responsive to different device sizes, altering the layout and functionality of the site depending on the device being used. To achieve this, bootstrap and media queries were used.

![Image of Home Page](./assets/images/readme/homepage.PNG)

## User Experience (UX)

- User Stories

  - First Time Visitor Goals

    - As a first time visitor, I want to be able to see all animals up for adoption.
    - As a first time visitor, I want to know about the sanctuary.
    - As a first time visitor, I want to be know how I can get in contact with the site owner.

  - Returning Visitor Goals

    - As a returning visitor, I want to know where the rescue is located.

    * As a returning visitor, I want to know of any upcoming events.

    - As a returning visitor, I want to find any social media accounts for Jif’s

  - Frequent Visitor goals

    - As a frequent visitor, I want to see any new animals available for adoption
    - As a frequent visitor, I want to know who volunteers for Jif’s Rescue.

- Design

  - Colour Scheme

    - The colour scheme of this project is green, white and black. This aligns with the environmental purpose of the site, as well as being clear and attention grabbing. An off white has been used for the background to make empty space easier on the eye.

  - Typography

    - There have been three fonts used in this project: ASAP, Lobster and Oswald.
      - Lobster was used for section headings
      - ASAP was used for all generic headings
      - Oswald was used for all content text

  - Imagery

    - Images are a large part of this website, being used for both animals and volunteers.
    - For the animals, it is important for the user to see a picture, as they are being advertised for adoption.
    - The images of volunteers are aimed at making the user feel
    - A hero image has been used on the index page to give a clear indication of what the site is about, as well as grabbing the attention of the user.

  - Wireframes
    - [Desktop](./assets/images/wireframes/desktop)
    - [Mobile](./assets/images/wireframes/mobile)

## Features

- Responsive across all devices
  - The responsive design reshapes, resizes and hides elements depending on the size and orientation of device being used
- Interactive elements
  - All image cards on the Animals and Volunteers pages enlarge on hover. This provides a slight emphasis to the specific image and accompanying information being targeted. This effect only appears on screens larger than 1224 pixels, as it was found to be ineffective on mobile devices.
  - A modal appears on the contact page if any required information is missing, or incorrect. This helps the user to see exactly what needs to be corrected.
  - The navigation bar is collapsible on small devices, the menu being replaced by a collapsible one, ensuring a clear navigation menu exists, but does not compromise the design.

## Technologies Used

- Languages Used
  - [HTML 5](https://en.wikipedia.org/wiki/HTML5)
  - [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- Frameworks, Libraries and Programs Used
  - [Bootstrap 4.5.2](https://getbootstrap.com/):
    - Bootstrap was used to assist with the responsiveness and styling of the website.
  - [Hover.css](https://ianlunn.github.io/Hover/):
    - Hover.css was used on the animal and volunteer cards, to add emphasis.
  - [Google Fonts](https://fonts.google.com/):
    - Google fonts were used to import the 'ASAP', ‘Lobster’ and ‘Oswald’ fonts into the style.css file which are used throughout this project.
  - [Font Awesome](https://fontawesome.com/):
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
  - [jQuery](https://jquery.com/):
    - jQuery came with Bootstrap to make the navbar responsive and aid other bootstrap functions.
  - [Git](https://git-scm.com/):
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
  - [GitHub](https://github.com/):
    - GitHub is used to store the projects code after being pushed from Git.
  - [Balsamiq](https://balsamiq.com/):
    - Balsamiq was used to create the wireframes during the design process.

## Testing

- First Time Visitor Goals
  - As a first time visitor, I want to be able to see all animals up for adoption.
    - A page is dedicated to display all animals, with a name and brief description. [Screenshot](documentation/readme/testing/animalcards.PNG)
    - Each animal has an “adopt me” button, which takes the user to the contact form. [Screenshot](documentation/readme/testing/adoptionbutton.PNG)
  - As a first time visitor, I want to know about the sanctuary.
    - On entering the site, a hero image is displayed, with the sanctuary’s mission statement over the top. [Screenshot](documentation/readme/testing/heroimage.PNG)
    - An about page was created to give more in depth information about the sanctuary. This includes the Mission Statement, an “About Us”, and a “What We Do”. [Screenshot](documentation/readme/testing/aboutpage.PNG)
  - As a first time visitor, I want to be know how I can get in contact with the site owner.
    - A contact form has been included, allowing users to email the sanctuary through the site. [Screenshot](documentation/readme/testing/contactform.PNG)
    - Included in the footer is both a link to the contact form, as well as a phone number. [Screenshot](documentation/readme/testing/contactusfooter.PNG)

* Returning Visitor Goals
  - As a returning visitor, I want to know where the rescue is located.
    - Within the footer is a link to google maps. [Screenshot](documentation/readme/testing/googlemapslink.PNG)
  - As a returning visitor, I want to know of any upcoming events.
    - On the home page is a list of upcoming events, with both a date and a brief description. [Screenshot](documentation/readme/testing/events.PNG)
  - As a returning visitor, I want to find any social media accounts for Jif’s Rescue.
    - Within the footer are links to various social media pages. [Screenshot](documentation/readme/testing/sociallinks.PNG)

* Frequent Visitor goals
  - As a frequent visitor, I want to see any new animals available for adoption
    - On the home page is a carousel, with the three most recently rescued animals. [Screenshot](documentation/readme/testing/recentrescues.PNG)
  - As a frequent visitor, I want to know who volunteers for Jif’s Rescue.
    - A page dedicated to volunteers, similar to that of animals has been created. [Screenshot](documentation/readme/testing/volunteers.PNG)
    - Each volunteer has a brief description, their name as well as a picture. [Screenshot](documentation/readme/testing/volunteercard.PNG)

### Further Testing

- The website was tested across multiple browsers, including Google Chrome, Firefox, Opera and Safari.
- The website was trailed on a range of devices of different sizes, including monitors, laptops, tablets and phones.
- The content has been run through spell checks.
- All links were checked to ensure they are active.
- Issues arose around sizing the Recent Rescues carousel on large devices. Fixed by using padding, instead of resizing content.

### Known Issues

- On some mobile devices, in landscape mode, the Useful Links in the footer become out of line.
- On some thin mobile devices, the collapsed navbar menu button is pushed below the logo.
* On Ipad Pro, there is a white gap below the footer.

### Validation

- The [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) were used to validate each page of the site.
- Each page had various errors that needed to be fixed. The details of each test can be found below:
  - Home Page - [Test](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/index.htmltest1.PNG) [Validated](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/index.htmltest2.PNG)
  - About Us - [Test](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/about.htmltest1.PNG) [Validated](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/about.htmltest2.PNG)
  - Volunteers - [Test](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/volunteer.htmltest1.PNG) [Validated](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/volunteer.htmltest2.PNG)
  - Animals - [Test](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/animals.htmltest1.PNG) [Validated](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/animals.htmltest2.PNG)
  - Contact Us - [Test](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/contact.htmltest1.PNG) [Validated](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/contact.htmltest2.PNG)
  - Style Sheet - [Test](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/style.csstest1.PNG) [Validated](https://github.com/TwoBitCliff/jifsrescue/blob/master/assets/images/validation/style.csstest2.PNG)

### Formatting

- To format the code, each page was run through an online formatter, https://www.freeformatter.com/.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the GitHub Repository
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
   - Alternatively Click Here for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the GitHub Repository
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the GitHub Repository
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `jifsrescue-clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

- The code for the vertical line next to the events list was adapted from here: https://dev.to/peterc/how-to-create-joined-bulletpoint-lists-with-css-bbc-news-style-1eem
- The contact form was adapted from here: https://mdbootstrap.com/docs/jquery/sections/contact/
- https://getbootstrap.com/docs/4.5/getting-started/introduction/ Bootstrap 4.5 was used throughout the project to help with responsiveness, the grid system and other elements such as the navbar.

### Content

- All content was written by the developer, and is fictitious.

### Media

- All images were sourced royalty free from https://pixabay.com/
- The Jif’s Rescue logo was created by my mother, Sarah Lithgow.

### Acknowledgments

- Thanks to my Code Institute tutor, who provided support throughout the duration of this project.
- Thanks to my Code Institute mentor, who provided ideas and feedback at pivotal stages of this project.
- Thanks to my parents, friends and colleagues who providing constructive criticisms and pointing out spelling issues.
- I used https://www.reddit.com/r/learnprogramming/ for issues with images displaying.
- I used the Code Institute source material and various blog posts for issues with both code and bootsrap.
