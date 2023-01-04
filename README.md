# Little Feets 

Little Feets is an imaginery website of an organisation dedicated to saving animals from exploitation and cruelty all over the world. 

The site is intended for people who are already engaged in this topic- rather than those who have no opinion or previous invlovement in animal rescue. The primary objective is to get people to signup to the newsletter- to get them involved and perhaps volunteer.

![Image of the main page of the website on various screen sizes](/README%20images/responsive%20check-%20index.png)

## Features

The project consists of 3 separate pages: 
- The main index landing page
- A gallery
- A signup/registration page

### Landing Page

The landing page has:

#### A Header
The header contains the H1, an icon of a paw, some text, and the navigation. The header reappears on all three pages and contains links (with an 'active' pseudo class). The header changes its format and size according to the different screen sizes used.

I am not pleased with my navigation- If i had more time i'd have done a little hamburger menu icon for small screens to hide the nav, and i'd have made it sticky for larger screens- both which i'll do in the future. 

![screenshot image of the header](/README%20images/screenshot-%20header.png)

### The Main Section
Next are three rows- the first one is the hero image with a small animation (inspired and coded from the Love Running website). 

The second and third rows contain an image next to a text that describe what the organisation's ethos is all about. 

![screenshot image of the second row](/README%20images/screenshot-%20main%20section.png)

The following section provides statstical information about the organisation's successes (numbers of animals freed, current ongoing investigations, and convictions). For this section I used floats just to show the assessors that i am able to use floats- in the rest of the page i have used other methods to place items on the page.

![screenshot image of the statistical info section](/README%20images/screenshot-%20stats%20info.png)

### The Footer
The footer contains a heading, and some social media icons as well as a final attribution tag to a 'future' portfolio link.

![screenshot of footer](/README%20images/screenshot%20footer.png)

### The Gallery

![screenshot of the entire gallery page](/README%20images/screenshot-%20gallery%20page.png)

The gallery page contains the header (minus the h3) and footer from the main page, as well as a gallery nested in-between. 

For the gallery i decided to use grid with a small spacing between the items as well as a softer border radius. The gallery is responsive and will change to a 1 column gallery on smaller screens.

### The Signup Page

The signup page contains an image with a form on top to register for a newsletter and/or volunteering. The header and footer are naturally also there.
![screenshot of registration page](/README%20images/screenshot-%20registration%20page.png)


### Testing

- HTML 

I have tested all three pages on the [W3C Validator](https://validator.w3.org/). No issues found on any of the tests.

![screenshot of validation result- index](/README%20images/html%20validator%20report-%20index.png)

![screenshot of validation result- gallery](/README%20images/html%20validator%20report-gallery.png)

![screenshot of validation result- signup](/README%20images/html%20validator%20report-%20signup.png)

- CSS

I have tested the CSS code on the [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/). No probelms were detected.

![screenshot of CSS validation report](/README%20images/CSS%20validator%20report.png)


I have also tested the site for accessibility using an accessibility validator recommended by W3C for all 3 pages and got a score of 100% on each test

![accessibility report - index page](/README%20images/accessibility%20report-%20index.png)

![accessibility report - gallery page](/README%20images/accessibility%20report-gallery.png)

![accessibility report - registration page](/README%20images/accessibility%20report-%20signup%20page.png)


### Deployment

Deployment was a bit difficult as i discovered that gitpages does not actually update itself despite the green tick appearing- sometimes  it'll be 10 or 15 minutes later. I had trouble with the relative paths of files and links and when changing them and correcting them, i still thought there was an error because gitpages didn't update when i checked again. This caused major confusion and annoyance. As soon as i realised this was the issue, i just allowed gitpages to take it's time and properly update things.

The live link for the page can be found here: [https://leverh.github.io/code-institute-portfolio-1/](https://leverh.github.io/code-institute-portfolio-1/)

### Credits

- For the animation in the hero section - The Love Running website tutorial. I found it inspiring and used some of the code for it on my website.

- The images i used were all from [unspalsh](https://unsplash.com/) - an open source site.

- The icons i used were from [fontawesome](https://fontawesome.com/) and [Flaticon](https://www.flaticon.com/)

- Fonts used on this page are all from the [Google Fonts](https://fonts.google.com/) website. I had initially chosen different font families altogether and changed them in the last minute. I found they were too rigid. I switched to fonts that are friendlier, warmer, and more inviting and less mechanical. 

The following fonts were used:

- 'Arimo', sans-serif;
- 'Lato', sans-serif;
- 'Lora', serif;




