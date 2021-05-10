# Portfolio Project 1 - Playful Paws
## Purpose

Website for dog leadership courses providing information, inspiration and a booking page. 

This Website was created for the purpose of completing the Portfolio 1 project for the Code Institute's Full Stack Developer course and is entirely fictional.
The project covers HTML and CSS with a user centric approach in mind.  A full list of technologies used can be found in the technologies section of this document.

The live website can be found [here](https://ceciliaswe.github.io/portfolio-1st/index.html)

## Playful Paws Responsive Website

![Website Mock Up](assets/images/images-readme/Screenshot.png)


*** 
## User Experience (UX)

### User stories

#### First Time Visitor Goals
* As a First Time user, I want to understand the main purpose of the site at a glance and learn more about the organisation and what they offer.
* As a First Time user, I want to effortlessly navigate throughout the site to find content.
* As a First Time user, I want to view the website and content clearly on different size devices.

#### Returning Visitor Goals
* As a Returning user, I want to be able to book a course.

#### Frequent Visitor Goals
* As a Frequent user, I want to check if there are added content to the Inspiration page

### Design
#### Color Scheme
The Index page contains a large hero image. The color scheme consists of 3 eartly colors; beige (#fdfff5) grey (#bdc3C6) and green (#92c58d) picked out from the hero image.
#### Imagery
Images on index page and courses page are meant to emphasize the information on the page and be inspiring at the same time.	
#### Typography
Noto Sans JP from Google Fonts is used, with Sans Serif as fallback font.
#### Differences to Design
* The Book button on the book page does not generate a response as indicated in the wireframes (just clears the form) due to limitations of HTML and CSS.
* Images beside the book form on book page was replaced by font awesome icons in the form legend as this displayed more visually pleasing, while maintaining the visual cue for expected form contents.
* Header was split in 2 rows for mobile devices to keep visual integrity and readibility of header and navbar.


### Structure 

* The Home page follows a Z-shape design with the hero image on top and important sections displayed inline, finishing with a button linking to the Book sheet.
* The Courses page displays overview information availabe without scrolling. Page links as well as scrolling enables expanded information further down on the page.
* The Inspiration page displays images at a glance and optional video playing.
* The Booking page has clear sections with legend icons to aid identifying the information needed in the section.

No submenues are used and the navbar indicates to the user where they are at all times. THe Home page and courses page has direct links to the call to action - i.e. the book page.

### Wireframes
Wireframes created usig Balsamiq are uploaded to the assets folder - [View](https://github.com/CeciliaSwe/portfolio-1st/tree/master/wireframes_balsamiq)
- Return to [top](#purpose)

## Features
* Internal links (within sheet and between sheets) - both in nav bar and on the sheets
* External links (social media)
* Booking form 
* Images and embedded video

### Future features
* A booking form sending the data to the business owner - current form uses form method get and clears the form upon submit.
* Integrated feedback for course availability (available/few left/full)

## Technologies
### Languages used
* HTML5
	* This project uses HTML5 as the main language for content and structure of the Website.
* CSS3
	* This project uses CSS3 for Website styling

### Frameworks, Libraries & Programs used
* [Font Awesome](https://fontawesome.com/)
	* Font awesome Icons are used 
* [Google Fonts](https://fonts.google.com/)
	* Google fonts are used throughout the project to import the relevant fonts
* [GitHub](https://github.com/)
	* GithHub is the hosting site used to store the source code for the Website and [Git Pages](https://pages.github.com/) is used for the deployment of the live site.
* [GitPod](https://gitpod.io/)
	* GitPod is used as version control software to commit and push code to the GitHub repository where the source code is stored.
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
	* Google chromes built in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles.
* [balsamiq Wireframes](https://balsamiq.com/wireframes/)
	* Balsamiq was used to create wireframes and UX design during the planning and design process.
 * [Image Color Picker ](https://imagecolorpicker.com)
	* The color picker was used to find 3 main colors from the hero image for use throughout the portfolio.
* [Tiny JPG ](https://tinyjpg.com/)
	* Tiny JPG was used to reduce image file size for the website.
* [Am I Responsive?](http://ami.responsivedesign.is/)
	* Used to generate the screenshots for responsive design.
	

## Testing

### Validation
The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project.
-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) 

### Bugs
* Opaque part of the hero textbox floats on top on the header while the image itself clears behind
	* Fixed by setting header to absolute instead of fixed	
* Book button link on index page does not fill the div box - thus whole button is not clickable. Increased padding will increase clicking area but does not fully resolve issue
	* Fixed by wrapping anchor element in the flex item div and set display to inline-block and weight and height to 100%
* Scewed alignment of navbar ul for <600 px
	* Fixed by removing right side margin for media query only
* Book link buttons display as hyperlink but are not clickabe on courses - long section. 
	* Bug appreas to be caused by position: absolute and a z-index for the div. Fixed by changing positioning from absolute to relative and setting the img div to absolute instead (in order to retain the overlap)
* Footer sticks to middle of inspiration page for < 600px
	* Caused by flexitem overflowing the flexbox at last element on page before footer, fixed by setting flexbox height to auto instead of fixed height

### User stories testing
All pages (Home, Courses, Inspiration and Book) were wireframed for Desktop, Tablet and smartphone using Balsamiq and are uploaded is a separate assets folder. 

The header has a paw icon and the name "Playful Paws",  directly indication the company segment.
The landing page has a large hero image of dogs with associated text declaring "Leadership Courses". Textboxes with limited text declares both the philosphy and more about the company without scrolling.

The purpose of this is to fulfill user story:
"As a First Time user, I want to understand the main purpose of the site at a glance and learn more about the organisation and what they offer."


All pages has a Navigation menu at the top of the page that directs them to a new page. The active page will be highlighted in a green color to contrast the dark header.
The navigation menu will remain fully visible on all devices due to its limited size but will centered for smaller devices. The index (home) page and courses page also has large links to the book page in the same green contrast color as the active page to improve user call to action.
The intro section on the Courses page has internal links to each longer section for the course to give users who know what they are looking for direct access without scrolling.

The purpose of this is to fulfill user story:
"As a First Time user, I want to effortlessly navigate throughout the site to find content."


Custom CSS is used to make the Website responsive by the use of media queries with main cut-offs at <600px and <950px.
Text and images that will not display visually appealing on small devices will be disabled or replaced (for example, on mobile devices the small images in the courses page intro section are replaced by dog icons and the image on the book page is removed). 

The purpose of this is to fulfill user story:
"As a First Time user, I want to view the website and content clearly on different size devices."


### Further Testing

The site was testes to to ensure consistency across browsers and screen sizen. Full testing matrix can be found [here](https://github.com/CeciliaSwe/portfolio-1st/blob/master/miscellaneous/testing_matrix_portfolio-1st.xlsx)

Noted Issues
* Links in intro section correspond to the headers for each course in the long section and cuts off the image at some screen sizes depending on image placement.	
* Selection arrows for Book page input filed for age are not clickable. Input field itself is functioning.					

## Deployment
### GitHub Pages

The project was deployed to GitHub Pages through the below steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/CeciliaSwe/portfolio-1st)
2. Click the "Setting" button "Settings" Button.
3. In the left menu, scroll down to "Pages".
4. Under "Source", click the dropdown and select "Branch: master", then click "Save".
5. Once deployed, the now published site [link](https://ceciliaswe.github.io/portfolio-1st/) is found in the "Pages" section.

## Credits
### Images and videos
* Image on book page: [Photo by Richard Brutyo on Unsplash photo](https://unsplash.com/@richardbrutyo)
* Image on index page: own photo
* Imgaes on courses page: own photos
* Images on inspiration page: [HD Wallpaper](https://www.hdwallpaper.nu/)
* Video on Inspiration page: embedded from YouTube

### Code
All code has been custom written for this project, but inspiration and tutoritals are credited as per below:

* Form fieldsets (ledgend style and inline display of label and input field) was inspired by [Sanwebe](https://www.sanwebe.com/2014/08/css-html-forms-designs)
* Use of hero image and overlapping textfield was inspired by the  Code Institute Love Running Walkthrough
* Use of text transform for footer icons was inspired by the Code Institute Love Running Walkthrough
* The use of Flexbox was taught by [CSS tricks flexbox guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* The technique to omitt elements in media queries was taught by [The Site Wizard](https://www.thesitewizard.com/css/hide-images-on-mobile-website.shtml)

### Acknowledgements

-   To my Mentor [Chris Quinn](https://github.com/10xOXR) for patience during technical difficulties, for pushing me to make smart choices and for inspiration for the testing matrix.
-   To CI Tutor Jo for CSS debugging.




