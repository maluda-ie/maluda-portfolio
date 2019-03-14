# Maluda Portfolio Website

User-Centric Frontend Development - First Milestone Project

This website was the first I developed as part of Code Institute's Full Stack Web Development Diploma. It is a portfolio site
aimed at promoting Maluda's pattern design work to potential clients. 

The finished demo site can be found here: 
[Maluda](https://ide.c9.io/maluda/maluda-portfolio) 


## UX

Providing a positive user experience was one of the main goals of this project. Bearing in mind that the majority of web users 
use their phones to access the internet, a mobile-first approach was implemented. That said, the site is fully responsive and 
works well on all devices in accordance with the brief. 

The primary aim of the site is to showcase Maluda's pattern design work to potential clients. However, anyone with an interest in 
pattern,illustration or design might also access the site. THerefore, with this in mind, for this version it was considered crucial 
to include about, portfolio and contact sections. The about page provides information about the studioto potential clients and site 
visitors. The portfolio section which uses Bootstrap cards, is a clean and neatly organised selection of current and past projects. 
The contact section allows users to get in touch with the studio easily.

As such, some user stories are as follows:

1. As a potential client, I want to be able to navigate the site with ease. 
2. As a potential client, I want to be able to find out about the designer/design studio.
3. As a potential client, I want to view a selection of the designer's work in an accessible way.
4. As a potential client, I want to be able to see past projects. 
5. As a potential client, I want to be able to contact the designer easliy. 

The interaction design included Bootstrap's scrollspy feature to enable ease of navigation on this one page site. Conventions were 
adhered to to ensure the site was intuitive and easy to use. Social media links can be found in the footer of the site. The navbar 
is fixed to the top on large devices and becomes a hamburger menu on smaller screens. Clean and minimal styling is used throughout the site 
to showcase the patterns without background distractions. Hover effects on the nav and social media links mirror colours found on the
landing page image to enhance consistency. 

Wireframes can be found here: [mockups](/wireframes/website-wireframes.pdf)


## Features 

### Existing Features
1. Navbar
   - The navbar is fixed to the top of the screen to allow ease of navigation. It becomes a dropdown on smaller devices.
2. Hover
   - All links change colour on hover to enhance the visual design of the site. These colours are taken from the landing page image. 
3. ScrollSpy
   - This feature enhances navigation. 
4. Landing Page Jumbotron
   - This full screenimage provides the user with a feel for the aesthetic of the designer. It introduces the rest of the site. 
5. About
   - This page provides information about the designer and the studio. 
6. Portfolio
   - A showcase of the designer's past designs and collaborations. It is laid out using Bootstrap's Card feature.
7. Ekko Lightbox
   - This feature is enabled on screen widths of 750px and above and uses JavaScript to function. 
8. Contact
   - This section uses Bootstrap. The form is intuitive and enables ease of input for the user.
9. Social Media Links
   - These are provided at the footer of the site to enhance user experience and use Font Awesome icons. 

### Future Features

In the future I would like to add a password protected page to offer potential buyers an opportunity to view a
complete catalogue of designs easily without making unseen work public. I would also like to add a page with client 
testimonials. 


## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) 
   - Used to build the skeleton of the site.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
   - Used to style the site.
- [Bootstrap 4.2.1](https://getbootstrap.com/docs/4.2/getting-started/introduction/)
   - Used for rapid structure and styling of the site. 
- [JavaScript](https://www.javascript.com/)
   - Used to enable and disable lightbox function. 
- [Ekko Lightbox](http://ashleydw.github.io/lightbox/)
   - Used to implement the lightbox feature. 
- [GitHub](https://github.com/)
   - Used for version control and to deploy the site. 


## Testing

To ensure that the potential client user stories were achieved, the following testing was carried out:

#### Home page and Navigation
1. Open website in Firefox.
2. Check that the landing page image displays correctly.
3. Hover over logo and navbar links to ensure that they function. 
4. Click navbar links to ensure ScrollSpy feature is working. 
5. Repeat these steps in Chrome, Safari and Opera browsers, checking responsiveness in dev tools. 

#### About Page
1. Navigate to the about page.
2. Ensure that the page content is well laid out, and that the text provides relevant information about the designer. 
3. Ensure that the navigtion to the rest of the site is functional.
4. Repeat these steps in Chrome, Safari and Opera browsers, checking responsiveness in dev tools.  

#### Portfolio Page
1. Navigate to the portfolio page. 
2. Ensure that the cards are well laid out and that they give value to the designer. 
3. Check that the navigation from the page functions flawlessly. 
4. Ensure that the lightbox feature works on each card on medium and large browsers using dev tools. 
5. Ensure that this feature is disabled on devices with screen sizes below 750px using dev tools. 
6. Repeat these steps in Chrome, Safari and Opera browsers, checking responsiveness in dev tools.  

#### Contact Page
1. Navigate to the contact page. 
2. Ensure that the contact from is laid out correctly. 
3. Ensure tha the user must fill in all fields before submitting the form.
4. Repeat these steps in Chrome, Safari and Opera browsers, checking responsiveness in dev tools. 

During the development of the site I used Firefox and Chrome dev tools to debug any issues that arose. I also utilized these tools to check
responsiveness as I implemented each feature. I tested the functionality and features of the site on Chrome, Firefox, Opera and Safari. The 
only browser that I encountered issues with was Safari 5.1.7 for Windows. Using this browser, the navbar links failed to appear, the portfolio 
section didn't render properly, the contact page was misaligned and the social media links were missing. When I tested the site using Safari 
on an ipad, it functioned perfectly. It appears that Apple no longer release Safari updates for Windows. Therefore the latest version 5.1.7 is 
not adequate. Safari should not be used with Windows. 


## Deployment

The site is deployed on GitHub 

<<<<<<< HEAD
The primary aim of the site is to showcase Maluda's pattern design work to potential clients. With this in mind, for this version 
it was considered crucial to include about, portfolio and contact sections. The interaction design included Bootstrap's scrollspy 
feature to enable ease of navigation on this one page site. Conventions were adhered to to ensure the site was intuitive and 
easy to use. Social media links can be found in the footer of the site and the navbar is fixed to the top on large devices and
as a hamburger menu on smaller devices. The wireframes can be viewed here: [wireframes](/website-wireframes.pdf)
=======
>>>>>>> readme file

## Credits

### Content
All of the site content was written by myself. 

### Media
All images used in the site are copyrighted to Maluda. 

### Acknowledgements
- I adapted code from this [tutorial](https://bootstrapious.com/portfolio-themes) to implement Bootstrap Cards. 
- I used this [code](http://ashleydw.github.io/lightbox/) to implement the lightbox feature. 
- The scrollspy feature uses this [plugin](https://www.w3schools.com/booTsTrap/bootstrap_scrollspy.asp).

