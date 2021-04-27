# Portfolio Project 1 - Playful Paws
## Purpose

Website for dog leadership courses providing information, inspiration and a booking page. 

This Website was created for the purpose of completing the Portfolio 1 project for the Code Institute's Full Stack Developer course. 
The project covers HTML and CSS with a user centric approach in mind.  A full list of technologies used can be found in the technologies section of this document.

*** 
## UX
### User stories
#### First Time Visitor Goals
* As a First Time user, I want to understand the main purpose of the site at a glance and learn more about the organisation and what they offer.
* As a First Time user, I want to effortlessly navigate throughout the site to find content.
* As a First Time user, I want to view the website and content clearly on different size devices.
#### Returning Visitor Goals
* As a Returning user, I want to be able to book a course.
#### Frequent Visitor Goals
* As a Frequent user, I want to check if there are added content to the Inspiration page



### Structure

All pages (Home, Courses, Inspiration and Book) were wireframed for Desktop, Tablet and smartphone using Balsamiq and are uploaded is a separate assets folder. 

The header has a paw icon and the name "Playful Paws",  directly indication the company segment.
The landing page has a large hero image of dogs with a textbox declaring "Leadership Courses". Textboxes with limited text declared both the philosphy and more about the company without scrolling.

The purpose of this is to fulfill user story:
>As a First Time user, I want to understand the main purpose of the site at a glance and learn more about the organisation and what they offer.


All pages has Navigation menu at the top of the page that directs them to a new page. The active page will be highlighted in a green color to contrast the dark header.
The navigation menu will remain fully visible on all devices due to its limited size but will centered for smaller devices. The index (home) page and courses page also has large links to the book page in the same green contrast color as the active page to improve the call to action.
The intro section on the Courses page has internal links to each longer section for the course to give users who know what they are looking for direct access without scrolling.

The purpose of this is to fulfill user story:
> As a First Time user, I want to effortlessly navigate throughout the site to find content.


Custom CSS is used to make the Website responsive by the use of media queries with cut-offs at <600px and <XXXpx.
Text and images that will not display visually appealing on small devices will be disabled or replaces (for example, on mobile devices the small images in the courses page intro section are replaced by dog icons and the image on the book page is removed). 

The purpose of this is to fulfill user story:
> As a First Time user, I want to view the website and content clearly on different size devices.


* The Home page follows a Z-shape design with the hero image on top and important sections displayed inline, finishing with a button linking to the Book sheet.
* The Courses page displays overview information availabe without scrolling. Page links as well as scrolling enables expanded information further down on the page.
* The Inspiration page displays images at a glance an optional video playing.
* The Booking page has clear sections with legend icons to aid identifying the information needed in the section.

No submenues are used and the navbar indicates to the user where they are at. Home page and courses page has direct links to the call to action - i.e. the book page.
### Design
#### Color Scheme
The Index page contains a large hero image. The color scheme consists of 3 eartly colors; beige (#fdfff5) grey (#bdc3C6) and green (#92c58d) picked out from the hero image.
#### Imagery
#### Typography
#### Wireframes
Wireframes created usig Balsamiq are uploaded to the assets folder
## Features
Internal links (within sheet and between sheet) - both in nav bar and on the sheets
External links (social media)
Booking form (mock)
### Future features
A booking form sending the data to the business owner
Integrated feedback for course availability (available/few left/full)
## Testing
### Bugs
* Opaque part of the hero textbox floats on top on the header while the image itself clears behind
* Book button link on index page does not fill the div box - thus whole button is not clickable. Increased padding will increase clicking area but does not fully resolve issue
	* Fixed by wrapping anchor element in the flex item div and set display to inline-block and weight and height to 100%
## Technologies
* HTML5
	* This project uses HTML5 as the main language for content and structure of the Website.
* CSS3
	* This project uses CSS3 for Website styling
* [Font Awesome](https://fontawesome.com/)
	* Font awesome Icons are used 
* [Google Fonts](https://fonts.google.com/)
	* Google fonts are used throughout the project to import the relevant fonts
* [GitHub](https://github.com/)
	* GithHub is the hosting site used to store the source code for the Website and [Git Pages](https://pages.github.com/) is used for the deployment of the live site.
* [GitPod]()
	* GitPod is used as version control software to commit and push code to the GitHub repository where the source code is stored.
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
	* Google chromes built in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles.
* [balsamiq Wireframes](https://balsamiq.com/wireframes/)
	* Balsamiq was used to create wireframes for 'The Skeleton Plane' stage of UX design.
 * [Image Color Picker ](https://imagecolorpicker.com)
	* The color picker was used to find 3 main colors from the hero image for use throughout the portfolio.
	
## Acknowledgements
### Images
* Image on book page: Photo by Richard Brutyo on Unsplash photo
* Image on index page: own photo
* Imgaes on courses page: own photos
* Images on inspiration page: https://www.hdwallpaper.nu/
* Video on Inspiration page: embedded from YouTube

### Inspiration
* Form filedsets (ledgend style and inline display of label and input field): https://www.sanwebe.com/2014/08/css-html-forms-designs




