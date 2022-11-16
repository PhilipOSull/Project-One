# CUBE

The goal of my portfolio project is to spreading knowledge about NFTs. To teach anybody from novice or advanced beginner how to buy or sell an NFT. It's something I've been really interested in in recent years. 

![Mockup image](docs/responsive-screenshot-new.png)

[Live website](https://philiposull.github.io/Project-One/)

## Project Goals


### Users Goals

- Learn how to Buy & sell NFTs
- Find a website that does this with easy to follow steps
- Who are the top NFT projects

### My Goals

- Spread knowledge about NFTs to new users 
- Catch the users attention with a nice UI & UX
- 

## Technologies


### Languages

1. HTML
2. CSS

### Frameworks & Tools

- Git
- Github
- Gitpod
- Google Fonts
- Opensea.io
- Soft.io
- Shutterstock
- Istockphoto
- Unsplash.com
- W3schools
- PhotoScissors.com
- HTML-color-codes.info/colors-from-image/

## Features

### Favicon

- This Site features a favicon of the cube in the hero image reduced in size.

![Favicon](docs/features/Favicon-Image.png)


### Home

- The home section features a responsive navigation bar and a hero image. The text to the left of the hero image informs the user straight away what the site is intended for. Once I put background-size: cover on the original photo so that on screen sizes such as 5000px the image would look perfect the background image was then too centered, there was too much empty space to the right hand side which didn't look good. With that in mind the original photo was edited using [PhotoScissors](https://photoscissors.com/) so that the cube would sit to the right of the screen and the text would be on the left. The original photo itself is then used on the smaller 480px screens so that the cube is more centered and can be seen on all screen sizes. 

![Home](docs/features/Home-Section.png)


### About Us

- The About page features an eye catching logo in the center, with a complimenting color to the rest of the site, image was taken from [IstockPhoto](https://www.istockphoto.com/) To the left of the logo is Our Aim, letting the user know what we aim to do. To the right of the logo it informs the user what they will learn from signing up to the website. The About section uses flex, this made it a very easy and smooth experience when reducing the screen size for smaller devices, it looks just as good on all screens. At the very bottom there is an SVG wave, sticking with the same color palette as the website and making a nice flow into the Gallery section.

![About](docs/features/About-Section.png)


### Gallery

- The Gallery section uses the same color as the botoom of the SVG wave, using [HTML-color-codes](https://html-color-codes.info/colors-from-image/) to get the exact color from the SVG image, so they flow nicely into eachother. The Gallery consists of some of the top NFT projects to date. These are the most popular amongst the NFT community and some of the most expensive to aquire. Like the About section the Gallery section also uses flex, it reduces the images very smoothly on smaller screens and looks just as pleasing to the eye.

![Gallery](docs/features/Gallery-Section.png)


### Sign-up Form

- The Sign-up Form section has a dismanteled cube background image which I really liked the look of and the colors compliment the sites color palette, the image was taken from [ShutterShock](https://www.shutterstock.com/). The form was used from the challenge 1 & 2 I did for the [Love Running](https://code-institute-org.github.io/love-running-2.0/index.html) project, I removed code I didn't want to use for mine and altered code to better suit my site.

![Sign-up](docs/features/Sign-up-Section.png)


### Footer

- The Footer section has the same color as the main headings on the page aswell as the sign-up button on the form, so that they all compliment eachother very well. The footer has copyright info that protects business copyright. It also has social media links and icons with links, as the screen size reduces for smaller devices only the icons are shown so its important they also bring the user to the social media site when clicked.

![Footer](docs/features/Footer-Section.png)


### Features to Implement in the Future

In the future, I would like to add more pages to the website. I would also like to add the 'smooth-scrolling' feature and make the Gallery a slideshow feature which I think would add a little extra to the website. 

## Testing

### HTML Validation
---

![HTML Validation](docs/validation/HTML-Validator.png)

- The W3C Markup Validation Service was used and passed with no errors.

### CSS Validation
---

![CSS Validation](docs/validation/W3C-CSS-Validator.png)

- The W3C Jigsaw CSS Validation Service was used and passed with no errors.

### Accessibility
---

The WAVE WebAIM web accessibility evaluation tool was used so that the website was up to high accessibility standards. No errors were detected.

### Functionality
---

| **Feature** | **Action** | **Expected Outcome** | **Actual Outcome** |
|-------------|------------|---------------------|-------------------|
| Navigation | Press each Navigation link | Each Navigation link went to the correct place | PASS |
| Sign-up Form | Leave first name or last name blank | Form says "Please fill in this field" | PASS |
| Sign-up Form | Leave out '@' when putting in an email address | Form says "Please inlcude an '@' in the email address" | PASS |
| Sign-up Form | Fill in all details and press 'Sign-up' | Sends data to formdump website when submitted and shows all the key value pairs as expected | PASS |
| Footer Links | Click each social media link | Each social media site should open up in a new tab | PASS |

## Performance
---

### Desktop

![Performance Test Desktop](docs/validation/Performance-Test-Desktop.png)

- [PageSpeed Insights](https://pagespeed.web.dev/) was used to test the performance of the website for Desktop

### Mobile

![Performance Test Mobile](docs/validation/Performance-Test-Mobile.png)

- [PageSpeed Insights](https://pagespeed.web.dev/) was used to test the performance of the website for Mobile.

### Compatibility with browsers

The website was tested on these broswers:

- Google Chrome
- Brave
- Microsoft Edge
- Mozilla Firefox

### Performing tests on devices

The project website was tested on numerous devices:

- Acer TravelMate | P
- Samsung S10+

### Performing tests on different screen-sizes

The project website was tested on numerous screen-sizes:

- From 280px to 5000px

## Bugs

| **Bug** | **Fix** |
| ----------- | ----------- |
| The cube on the hero image goes off screen on smaller screens | Add a second image where the cube is centered for smaller screens |  
| About section logo moves to the right on smaller screens | Remove margin left/right and use `text-align: center`
| Gallery section wouldn't re-size properly on smaller screens | Used the flex property for a smoother experience
| 

## Deployment

The site is hosted using GitHub pages, deployed from the master branch. Every time there is a new commit to the master branch the deployed site will update automatically. The landing page must be named `index.html` in order for the site to deploy correctly on GitHub pages.

You can also clone this repository directly into the editor to run locally, for example you would type `git clone https://github.com/USERNAME/REPOSITORY` into the terminal. You can then type `git remote rm origin` into the terminal to cut ties with this GitHub repository.

## Credits

### Content

The content in the "About us" section was written by me.

### Media

The hero image was taken from [Unsplash](https://unsplash.com/)

The Gallery NFTs were taken from [OpenSea](https://opensea.io/)

The Sign-up Background image was taken from [ShutterShock](https://www.shutterstock.com/)

The About section logo was taken from [IStockPhoto](https://www.istockphoto.com/)
