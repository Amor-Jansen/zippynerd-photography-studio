# ZippyNerd Photography Studio

![Image of mockup](/docs/screenshots/mockup-resize.png)

As a new photogropher what better way to show your work than with a website. The hope is to provide people with
lasting memories captured in a unique and beautiful way. I fell in love with macro photography, photographing insects 
and small flowres and now I want to branch out and start photographing people more.

The advantage of being new is the ability to offer competative rates and perhaps offer something different.
I want to offer beautiful and elegant, yet also fun and different.

## Features
1. [User stories](#user-stories)
    1. [First time visitor goals](#first-time-visitor-goals)
    2. [Returning visitor goals](#returning-visitor-goals)
    3. [Frequent user goals](#frequent-user-goals)
2. [Existing features](#exising-features)
    1. [Home page](#home-page)
    2. [Gallery](#gallery)
    3. [Contact us](#contact-us)
    4. [Features to add](#features-to-add)
3. [Testing](#testing)
    1. [HTML](#html)
    2. [CSS](#css)
    3. [Wave](#wave)
    4. [Lighthouse](#lighthouse)
4. [Unfixed bugs](#unfixed-bugs)
5. [Fixed bugs](#fixed-bugs)
6. [Deployment](#deployment)
7. [Credits](#credits) 
    1. [Content](#content)
    2. [Media](#media)

### User stories
- ### First time visitor goals:
    - As a first time visitor, I want to be able to easily navigate the page.
    - As a first time visitor, I would like to know what the page is about and what it offers.
    - As a first time visitor, I want to find social media links and view testimonials of previous clients.

- ### Returning visitor goals:
    - As a returning visitor, I want to see more images on display.
    - As a returning visitor, I would like to know where you are located.
    - As a returning visitor, I would like to have more social media links.

- ### Frequent user goals
    - As a frequent user, I would like to see blog posts.
    - As a frequent user, I would like to see the nature photos for sale as prints on canvas.
    - As a frequent user, I would like to be notified about specials.

### Existing features:
- ### Home page
   - The logo is functional as a home button:
    ![Image of the logo](/docs/screenshots/logo-home-button-resize.png)
   - The navigation bar is also functional to the three pages: Home, Gallery, Contact us. 
     There is a dashed line when hovered over and it becomes solid when selected.
    ![Image of the navigation bar](/docs/screenshots/nav-bar-resize.png)
   - Brief description of the company.
    ![Image of slogan and brief description](/docs/screenshots/slogan-about-resize.png)
   - Social media links that open to a new tab.
    ![Image of footer](/docs/screenshots/footer-resize.png)
   - Custom 404 page not found page.
    ![Image of 404 page](/docs/screenshots/404-page-resize.png)

- ### Gallery

   - Has the same navigation bar as on Home page.

   - Images are all taken by myself (Amor Jansen).
     I would like to keep these photos as copyrighted and not for use by anyone other than me.

   - It is valuable to see the level of photography.
    ![Image of some of the gallery images](/docs/screenshots/images-resize.png)

   - Contains the same footer as the Home page.

- ### Contact Us

    - Has the same navigation bar as the Home page.

    - When filled in the user will be taken to a thank you screen.
    ![Image of thank you page](/docs/screenshots/thank-you-resize.png)

    - Contains the same footer as home page.

- ### Features to add

    - I would like to add the option to purchase my original nature photos as prints or on canvas.

    - I would like to add more photos to the gallery.

    - I would like to add a blog post.

## Testing

- ### Validator testing
    - ### HTML 
        - I used the W3C HTML validator. I used url input.
        ![Image of validated HTML](/docs/screenshots/html-validation-resize.png)

    - ### CSS
        - I used the W3C CSS validator. I used direct input. (There were 4 warnings on the code I used from https://dcode.domenade.com)
        ![Image of validated CSS](/docs/screenshots/css-validation-resize.png)

    - ### Wave accessibility
        - I ran the entire website through wave and the only warnings to come up were links to home page that
          are adjacent.
          ![Wave accessibility Home page](/docs/screenshots/wave-homepage-resize.png)
          ![Wave accessibility Gallery page](/docs/screenshots/wave-gallery-resize.png)
          ![Wave accessibility Contact us page](/docs/screenshots/wave-contact-us-resize.png)
    
    - ### Lighthouse
        - I ran my page through lighthouse in chrome.
        ![Lighthouse Home page](/docs/screenshots/lighthouse-rating-resize.png)
        ![Lighthouse Gallery page](/docs/screenshots/lighthouse-gallery-resize.png)
        ![Lighthouse Contact page](/docs/screenshots/lighthouse-contact-resize.png)

- ### Unfixed bugs
|Bug  |Reason  |
|-----------|-----|
|Warning in Css validation| This is code from https://dcode.domenade.com|

- ### Fixed bugs
| Bug                                | How I fixed it            | Outcome |
|-----                               |----------------           |---------|
|Background image was not full screen| I used min-height: 100vh; | As desired|
|Images were not displaying correctly| I used a grid method (see credits)| As desired|
|Validator warning in HTML           | I icluded a heading in the contact us page| As desired|

## Deployment

The method I used to deploy this site is as follows:

    - Go to my Github and click on this repository
    - Click on settings 
    - On the left hand menu select pages
    - Select main branch 
    - Select save

The live website can be found at :  https://amor-jansen.github.io/zippynerd-photography-studio/contact.html

## Credits
 
 - ### Content
    - Some insperation from the love running project by Code Institute.
    - I did Google a lot of concepts and used information from w3schools.com.
    - I used https://dcode.domenade.com guide on grid in css for images.
    - I used Google fonts Shalimar and Overpass.
    - I used Fontawesome for the footer logos.
    - I used Favicon.oi for my favicon.
    - I used Balsamiq for the wireframes.
    - I used https://ui.dev/amiresponsive for the image under my README logo.

 - ### Media
    
    - All images used in this project are my own.
    - Images cannot be used by other students.