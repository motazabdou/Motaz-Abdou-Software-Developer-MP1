# Motaz-Abdou-Software-Developer-MP1
Personal Portfolio Website

# Personal Portfolio Site – Motaz Abdou Software Developer  

  

[Link to Live Website](https://motazabdou.github.io/Motaz-Abdou-Software-Developer-MP1/)

  

[GitHub Repo](https://github.com/motazabdou/Motaz-Abdou-Software-Developer-MP1) 

  

***  

  

## About   

  

This is a personal Portfolio website created for my MS1 project with Code Institute. 

  

One of the key requirements for a web developer is to have an online presence. I wanted to showcase my current knowledge of HTML, CSS and some of the appropriate libraries and frameworks used alongside the aforementioned programming languages. The purpose of the website is to briefly tell my story, and present a lot of information without the browsing experience being overwhelming through a fun, interactive layout, which I intend to expand for as long as my knowledge of programming broadens. This project has been made for the purposes of referring potential customers for freelance work, employers who are keen on connecting with me and observing my thought process and work quality, and last but not least, for the love of coding, making mistakes and learning something new everyday. 

For those purposes, I have opted for an intuitive design, and a number of interactive methods to present information. Namely flip cards, a timeline and progress box. Also included are contact forms on two of the three pages as well as easy access to social media links on both the header and the footer. My portfolio site is a small site with a small range of website needs, however, there is scope for my capabilities and skills and projects to expand, and the website can be adapted to the growing demands and requirements, and additional features implemented. 

  

*** 

  

## Index – Table of Contents 

  

* [User Experience (UX)](#user-experience)  

* [Features](#features) 

* [Designs](#designs) 

* [Technologies Used](#technologies-used) 

* [Testing](#testing) 

* [Known Bugs](#known-bugs) 

* [Deployment](#deployment) 

* [Acknowledgements](#credit) 

  

***  

  

## User Experience (UX) 

  

## Strategy 

### User Stories   

  

#### Reasons a user may visit the website 

* A user looking to create personal or business website or web application. 

* A user who already has been referred to me but wants to get in contact. 

* A user doing research on what services offer. 

* A user looking to see if I have done previous work and/or curious about my skill level. 

* A user seeking to collaborate on a new project. 

  

#### Reasons for the website 

* Increase clients 

* Showcase work 

* Provide a way for new and existing clients to contact me. 

* Attract Employers’ attention and collaborate   

  

## Scope 

#### What a user may expect 

* Intuitive, easy to navigate website.  

* Good presentation and visually appealing regardless of screen size. 

* Links and functions work as expected. 

* Information about me and my journey to web development. 

* A way to get in contact with me. 

  

#### What a user may want  

* To be able to find links to social media pages. 

* To see examples of previous work carried out. 

* To be able to enquire and collaborate online. 

* Work flow and design process. 

  

  

#### As a developer I expect 

* To provide information about myself and my work. 

* To provide an easy way for new and existing clients to contact me. 

* To showcase some of the work I am proudest of.  

* To provide an easy to navigate website with links that work as expected. 

* To encourage clients to contact us for a quote.  

  

*Note that not all -What the user may wants- will be implamented at this stage of my coding journey, as I am still studying, and at the beginning of my coding path., Additional features may be added as the scope mandate changes and my goals become more clear. 

  

## Structure 

The website will consist of 3 separate pages 

* A home page with a “Header”, personal photograph for identification, a “Little about me” and “Contact” sections.  

* An “About” page with a header constituting of a “timeline” showcasing a brief background, education info, skills, technologies used and personal interests.  

* A section outlining my website development process from start to finish. 

* A contact form to facilitate communication and reaching out.  

  

*** 

  

  

  

## Designs 

  

## Surface 

  

  

#### Colour 

  

I have chosen a black and navy gradient throughout my pages as my main colour theme for the website. The choice being inspired by starry night skies. To compliment this choice of colours and emphasise the effect, I have used particles-js for the star-infused background. This has been paired with a yellowish orange colour for contrast. This will help with Accessibility for visually impaired users.  I have also opted for the glass neo-morphism effect for a number of my components. In order to inject some colour, I have opted for some colourful svg vector illustrations, but wanted to stick to the main colour scheme for the svg illustrations in the About page, primarily navy, orange and white. 

  

I have used the following  

  

     :root { 

    --main-navy: #091F7C; 

    --orange:#FDC51D; 

    --white:#ffffff; 

    --black: #000  

     } 

     

    

![Colour scheme](README-files/colors.png) 

  

  

 One of the main reasons for my choice of colours is to mimic a dark mode throughout large portions of the website for ease of readability. My initial plan was to provide both dark and light modes, but due this feature being out of the scope of the current project, I dismissed the idea for now, as it will require a lot of javascript. 

  

I initially used both https://colormind.io and https://mycolor.space/ to help me narrow down my design choice after using the colour picker on my hero image. I already knew I wanted to work with navy and yellow/orange but was not certain of the exact shades As I kept experimenting, the idea of incorporating a night sky came to mind, and hence particles-js. Although this was helpful in finding colours that worked well, I chose to alter the palette to suit my personal taste.  

  

#### Typography  

  

I have used https://fonts.google.com/ for my fonts.  I have chosen to use Quicksand as my main font throughout the website, with Montserrat used for the headers and titles.  Quicksand is one of my favourite fonts to use across various screen sizes, very easy to read, has a playful feel to it which I believe allows me to express my personality and showcase my love for creativity and design, and that I’m having fun with this process.  To increase the readability, I have increased the letter spacing on the headings for them to stand out and be more defined, and increased line height throughout most paragraphs to not overwhelm the user with large chunks of text that might discourage reading.   

  

For the use in the headers, I have increased the letter spacing further to make the headings more defined and allow them to stand out. I have also used a variety of font weights to make some sections easier to read and stand out.   

  

I imported the following code into the top of my style.css file 

  

        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;700&family=Montserrat:wght@100;200;400;900&family=Quicksand&display=swap'); 

 

  

#### Call to Action 

  

My main intention is to let the user know what I do, implicitly determine my programming capabilities through the design and techniques used, and to understand my design process and background, so as to increase my chances of collaborating with potential clients and connecting with employers. Therefore, my main call to action revolved around directing the user to my “About” page and downloading my CV.   

  

* The links in the Nav/Logo are highlighted using a change in the text colour when the mouse is hovered over them. 

* Call to action buttons change colour on hover with float shadow animations. 

* Call to action buttons on the back of the flip cards inviting the user to read more about me. 

* "Submit link" on the form and the "Contact Us" link in the form have also been styled as a button with a complete colour switch using the primary colours of choice for consistency.   

* The “Contact” button on the navigation bar takes the user the contact form available on the appropriate page. The reason to include contact forms on both the home and about pages is to encourage communication. 

* The social links will send the user to my social media pages.  They also change colour when hovered over. Social links available on the right side of the Header on the home page, as well as at the footer at the very bottom. 

  

### Imagery    

  

Since I’m still new to the world of web development, I did not have a lot of images to use. Images primarily were in the form of SVG vector illustration, used for the purpose of intuitive design, and to add some character to the website. I used two images of myself which I have designed using Adobe Photoshop, where I created opaque circular frames that match my colour scheme of choice as well as geometry used throughout the website.   

  

Images acquired from the following sites -  

* [Unsplash](https://unsplash.com/) 

* [ManyPixels](https://www.manypixels.co/) 

* [Flaticon](https://www.flaticon.com/) 

 

Some svg vectors have been edited using: 

* [Boxy svg editor](https://www.boxy-svg.com/) 

   

Should the particles-js background fail to load, a backup background colour has been set to navy so that the colours of the text can still be read. The images in the body of the website all have "alt" attributes. This is to ensure that screen readers can describe the image to the user or if the image fails to load. This is also to help with the ranking of the website. 

  

  

*** 

  

  

  

## Skeleton  

  

  

### Layout  

  

* I have used CSS grid while creating the website. I established grid-template-columns, grid-template-rows and defined the grid-template areas. These areas are then given to individual elements, classes and/or IDs. When the page is expanded from a mobile, some of the content goes from being stacked to being in adjacent columns and rows. This allows the user to see more of the website on a larger screen. This is done through redefining the grid-rows and columns using media queries, and rearranging the grid area where appropriate. 

* I used chrome dev tools in the development of the website and altered the column classes in dev tools first before implementing into my code. I have also used the various screen-size presets to determine how the layout looks on various devices of different sizes. 

* I have used containers, paddings and margins to make sure that the content is not too close together, and ensured clarity in my element naming convention for ease of following. I have also included comments to separate the various sections, and explain anything that might seem difficult to follow. 

  

  

*** 

  


## Features 

  

#### Universal Features Across the Site 

  

###### Logo and Navigation Bar 

The Navigation Bar is fixed at the top of the webpage, so it’s always there to see without the need to scroll up. I have given it a glass effect so as to not obstruct the content behind it, but compliment the existing content. The logo and nav links all change colour and are highlighted when hovered over and a hover animation has been implemented using hvr-css. The nav links direct the user to the correct page of the website. When the logo is clicked on it will take the user to the home page. When the page is active, an active class is added to the nav link. By having both these features accessibility is improved. When on smaller devices the navigation menu turns into a hamburger menu created using font-awesome and is located on the right of the navigation bar. For the larger screens, the nav is aligned to the right-hand side of the page and is on the same line as the Logo. The navigation links are orange, turn white when hovered over, and are bold with some text shadow when active. 

  

###### Responsiveness 

  

The page is scaled up and down for different screen resolutions to help the content stay neat. This has been done using a mixture of media queries and CSS grid. 

  

  

###### Accessibility 

  

All images and navigations have an alt attributes or aria-label. This is to make the site easier to use for people with visual impairments by allowing them to navigate the site easily. There is high contrast used throughout the design. Header elements have been used in sequence so that the site makes semantic sense to screen readers. Links are consistent when hovered over. I have also set the font to rem so that if someone has their font settings higher for visibility the font size will increase accordingly. 

  

  

###### Footer  

  

The footer is split into 4 sections:. “Footer-text”, “Footer-form” and “Footer-Social” and “Footer-copyright”. The colour used for the text is orange, as is the case with all headings and the form is made using an opaque black background giving the illusion of a glass card. Theses sections are arranged into 4 rows throughout all screen sizes. 

  

  

The “Footer-text” section includes a heading, and a short message prompting the user to get in touch. The form itself consists of three labels and a text input, an email input and a text area for the user comments or messages. The “Footer-Social” section has links to social media sites using Icons from Font Awesome, and they have been enlarged in comparison to the social links on the header section. When hovered over these links change from a white colour to orange, with a pulse animation. When clicked, the links open in a new tab. The copyright section is located at the very bottom of the web page. 

  

##### Meta data 

  

  

I have included descriptions, author, and keywords into the head element to increase traffic to the website. I have also labelled each page differently so that if the user has multiple tabs open it is easy to recognise each tab. 

   

***  

  

#### Features Specific to Pages 

  

###### Homepage  

* A photograph of myself created on Adobe Photoshop to put a face to my name, next to my name, job description and two call to action buttons. 

* Section-main: A brief introduction of my background, alongside an image of myself “seeking a new path” 

* Section-bottom: Flip cards that act as a summary of my web development goals, which flip around when hovered or clicked, with a call to action button on the back of each card, directing the user to the about page. 

* A Footer consisting of a title, paragraph, form, social icons created with font-awesome, and a copyright div at the very bottom. 

  

###### About 

*The “About” Page includes a timeline and progress bar which changes colour depending on the browsing stage. This was my method of choice for presenting a relatively large amount of information, without making the page seem cluttered. The interactivity aspect is intended to encourage the user to continue exploring the page and reading more, and in order to make it more enjoyable, I have incorporated plain text, institution logos, svg vectors, skills bars for competency level, and programming language logos to inject colour and increase visual appeal. 

* The bottom section of the page details my design process, through the use of visuals as well as plain text, in a staggered format. The images are scaled down and take up an entire row on mobile devices, and are scaled up to take up half the width of the rows on larger devices. They have been scaled up on larger devices to minimise white space.  

  

###### Form  

* The “Form” section is located at the bottom of both the “Home” and “About” pages, and consists of the form and universal features only. 

* The form includes fields for the user to enter their name and contact details using - input type="text" 

* The email input field requires the answer to be an email 

* There is a - textarea - to allow the user to ask any further details. I have used placeholder text to encourage the user to make any further comments. 

* The submit button is large and changes colour when hovered over. 

* The labels are clear as to what should go in the field and all fields are set to “required”. 

  

  

I have set the form to POST with an action of https://formdump.codeinstitute.net. This allows me to validate whether or not the form functions properly  

  

### Future Features  

  

* Nav collapses on mobile 

* A live chat feature. 

* Animate elements and divs on scroll. 

* Blog section in which I blog about my programming experience and share what I have learned. 

* Has a “form submitted” status to give users peace of mind that the form has been sent correctly and sends the form to Plant Factory email.     

  

*** 

  

## Technologies Used  

  

* HTML5 - Mark-up language using semantic structure. 

* CCS3 - Cascading style sheet used to style. 

* Gitpod.io - for writing the code. Using the command line for committing and pushing to Git Hub 

* GitHub - Used to host repository  

* GIT - for version control of the project. 

* jQuery 

* Particles-js javascript library for header background. 

* Hover-CSS for hover animation effects 

  

Design  

* [Bootstrap](https://getbootstrap.com/) - For responsive design/carousel - overwritten some code within my own stylesheet 

* [Google fonts](https://fonts.google.com/) - For styling the typography 

* [Balsamiq wireframe](https://balsamiq.com/) - To build wireframes in the design phase.  

* [Font Awesome](https://fontawesome.com/) - for social media icons 

* [Beautifer](https://beautifier.io/) - Allowing me beautify my code. 

* [Tiny PNG](https://tinypng.com/) – changing some images to smaller sizes 

  

Testing  

* [HTML Validator](https://validator.w3.org/) - Testing validity of HTML 

* [CSS Validator](https://validator.w3.org/) -Testing validity of CSS 

* [IE NetREnderer](https://netrenderer.com/index.php) 

* [Am I Responsive](http://ami.responsivedesign.is/#) - Checking the responsive nature 

* [Wave](https://wave.webaim.org/) - Accessibility Testing  

* DEV Tools - Lighthouse 

  

*** 

  

## Testing  

  

* Nav links work and the user is directed to the correct page of the site.  

* Logo takes the user back to the main page. 

* Contact directs user to the Form on either the home or about page, depending on the page user is browsing. 

* Hovers over links are clear and not default blue. 

* Social links works.  

     

[HTML Validator](https://validator.w3.org/) 

![HTML Validator](README-files/html-valid.png) 

  

[CSS Validator](https://validator.w3.org/) 

![HTML Validator](README-files/css-valid.png) 

  
