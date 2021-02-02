# Rock Hoppers Kayaking Club

![Main Mockup](README-files/main-mockup.png)

[Link to Live Website](https://crypticcaroline.github.io/ms1-plantfactory/index.html)

[GitHub Repo](https://github.com/crypticCaroline/ms1-plantfactory)

*** 

## About  

Rock Hoppers is a Kayaking Club sport website created for my MS1 project with Code Institute.

Rock Hoppers are a niche Kayaking club that offer membership for intermediate/advanced kayakers and playboaters, who have already completed beginners courses and training outside of the club. They are a 'roof rack' club which means that they do not have facilities or a premises like traditional club houses. They do not have a clubhouse, changing rooms or club gear for members but this keeps the membership cost low. You are expected to have your own kayak, gear or vehicle to get you to the rivers. They are members of Canoeing Ireland of which all members will have the option of joining if not a member already. 

There is a scope to add a blog with upcoming events, river trips, kayaking holidays and the integration of a membership system. The events can be paid for or booked using an external provider such as Eventbrite. A big part of the website will be to link members to each other via social media and platforms such as Whatsapp so they can organise meetups and river sessions. Forums are hard to maintain/update and monitor and keep activity going with all members being volunteers.  At the moment payment is taken by cash or revolut but is hard to keep track of financially. 
   


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
* A user looking for to join a kayaking club in Ireland
* A user looking for an established club with experienced members/peers so that they can advance in the sport.
* A user is looking for a social club that is friendly and welcoming.
* A user is looking for a roof-rack club as they already have their own gear/boat and don't want that factored into fees.
* A user looking for a club with a lot of river trips/events and kayaking holidays abroad.
* A user is looking for easy ways to connect with other members to organise peer trips and meet ups.
* An inclusive vibe, fun atmosphere, less expense/politics than a bigger club with premises. 

#### Reasons for the website
* Increase club membership, currently membership numbers are low.
* Provide an alternative to members of beginners kayaking clubs where they can join to advance their skills.
* People can join from all over Ireland and meet up at various river locations.
* A lot of other kayaking club websites are poorly maintained, have a bad UXD and are very dated.
* No fixed premises so contacting the comittee is dificult so a website is important to provide information and contact details.

## Scope
#### What a user may expect
* Easy to navigate website 
* Good presentation and visually appealing regardless of screen size.
* Able to view the site on any device they may have, including mobile, tablet, desktop.
* Links and functions work as expected.
* Information about upcoming river trips, meet ups and events.
* A way to get in contact with other members but primarily invitation to Whatsapp groups and the Facebook page/group for regular events.

#### What a user may want 
* To be able to find links to social media pages.
* To join the club with/without Canoeing Ireland Membership.
* Find out about upcoming events and trips.
* To sign up to events/trips/pool sessions online.
* How it works - from start to finish, i.e., who the club are, how many members, how to join, how many trips are there? Are there trainings/courses etc? Is there room for progression?
* Winter pool sessions to learn to roll and refine techniques in a safe/warm environment.
* To sign up and pay for membership online (potential for Adult/Student/Couples membership) - future.


#### As a developer / Club I expect
* To provide information about the club - history, USP.
* To provide an easy way for new and existing members to contact us.
* To list the regular weekly trips, rivers we run and annual trips away
* To provide an easy to navigate website with links that work as expected.
* To showcase members testimonies and expect potential members to read them.
* To encourage clients to use contact us page for membership/trips enquiries. 

* Note that not all -What the user may wants- will be implemented at this step in the club development as this would need volunteers and resources from the club (committee) to manage during their free time. Additional features may be added as the scope mandate changes and the club grows.

## Structure
The website will consist of 3 separate pages
* A home page with “Whats Our Club About”, “Why Kayaking” and “Whats Happening” events section. 
* A “Events/Trips” page with a list of upcoming weekly and annual events.
* A page with a form to contact the club and enquire about membership and events.

***

## Designs

## Surface


#### Colour

I have used blue as my main colour theme for the website. This has been paired with an off-white colour for contrast. This will help with Accessibility for visually impaired users. This goes with the theme of the website and the club. The kayaking club is about white water so this associated with blue and white.  


These colours feature several times throughout the website which is why I have set a variable in the code.


I have used the following 

     :root {
    --main-green:#0b720b;
    --off-white:#fdfdfd;
    --dk-brown:#0c0606;
    --md-brown: #2a2020;
     }
    
This means if the business decides at any point to change the key colours they can easily change it in the variable so that they do not need to go through and change every colour individually.     
![Colour scheme](README-files/colors.png)


For the rest of the colour scheme, I have kept the range of colours to a minimum using only a few additional colours where needed. I have used a mid-brown and dark brown for some text. This still ties in with the theme of water and kayaking but provides a better design. Another reason I have chosen not to use black and white is because it is estimated that 20% of the general population has a form of visual stress (significantly higher percentage in those with disorders such as dyslexia). It is a processing perception problem which can cause issues with processing text and patterns. Black on white has been shown as one of the most difficult for sufferers of visual stress to read.


I initially used https://mycolor.space/ to help me narrow down my design choice after using the colour picker on my hero image. I had already decided to use green but hadn’t decided on the exact shade. Although this was helpful in finding colours that worked well, I chose to alter the palette to my choosing.


I have purposely not used any red on the website as this may have cause issues for people with a red/green colour deficiency.


#### Typography 

I have used https://fonts.google.com/ for my fonts.  I have chosen to use the Oswald Font for my headers and Oxygen as a complementary fonto to Oswald, as my main font throughout the website.  This is a fairly modern style that is easy to read at various sizes.  To increase the readability, I have increased the letter spacing in most cases.  To find the compatiblity of fonts I referred to https://typ.io/fonts/oswald

For the use in the headers, I have increased the letter spacing further to make the headings more defined and stand out. I have also used a variety of font weights to make some sections easier to read and stand out. 

I imported the following code into the top of my style.css file

        @import url('https://fonts.googleapis.com/css2?family=Oswald:wght@200;300;400;500;600;700&family=Oxygen:wght@300;400;700&display=swap');

#### Call to Action

I made all my call to actions as easy to see as possible. 

* The links in the Nav/Logo are highlighted using a change in background colour and text colour when the mouse is hovered over them.
* Request a Quote is styled as a button to be more inviting for the users to click.  I have used a complete colour switch when the mouse is hovered over the link so that the user can clearly see it is a link.
* "Submit link" on the form and the "Contact Us" link in the form have also been styled as a button with a complete colour switch.  The colour used are the 2 main colours for consistency and because the change between the colours is easy to see. 
* The "Request a Quote" in the main body of index.html and the "Contact us" in the Footer which takes them to the form. 
* The social links will send the user to the company's social media pages.  They also change colour when hovered over.

### Imagery   


Seeing as the business is a concept I had no images to use from the company. I looked for simple and eye-catching designs that mirrored the website ideals when looking for hero images and carousel images. I used a jumbotron for the hero image and I placed an overlay over the top of the carousel. This was to increase the contrast between the imagery and text. I used images of people in the testimonials and for the “About” section. This was to make the business seem friendly and approachable. These images also grow when hovered over. This is so the user can see the images more clearly. I resized some of the images using tiny.png and cropped and flipped the hero image for use on smaller devices.


Image Links - 
* [Hero](https://unsplash.com/photos/x2Tmfd1-SgA)
* [About Image](https://unsplash.com/photos/8FAEyjo3Dek)
* [Testimony Image ](https://unsplash.com/photos/Jnxtlv_Fo14)
* [Testimony Image](https://unsplash.com/photos/HrpYHchKb5Y)
* [Testimony Image](https://unsplash.com/photos/ROJFuWCsfmA)
* [Carousel Images](https://unsplash.com/photos/K86O7q3jddY)
* [Carousel Images](https://unsplash.com/photos/VWcPlbHglYc)
* [Carousel Image ](https://unsplash.com/photos/p_kICQCOM4s)

I also used a pattern background of leaves for the "Contact us" page and the "What we Offer" section on the homepage.  This was to tie into the theme of the business and increase visual appeal. 

[Pattern background](https://www.freepik.com/free-vector/mostera-background_4258347.htm#page=2&query=pattern+background+plant&position=46)


Should the hero or pattern image fail there is a background colour set so that the colours of the text can still be read. The images in the body of the website all have "alt" attributes. This is to ensure that screen readers can describe the image to the user or if the image fails to load. This is also to help with the ranking of the website.


***



## Skeleton 


### Layout 

* I have used responsive design when creating the website. as When the page is expanded from a mobile, some of the content goes from being stacked to being in adjacent coloumnscolumns. This allows the user to see more of the website on a larger screen. I have also set a Max-Width for the site so on very large screens the content stays neat and is well formatted.
* I used Bootstraps for the use of the grid system and for the carousel. I used chrome dev tools in the development of the website and altered the column classes in devtools first before implamentingimplementing into my code.
* I have also used a max-width, this is to ensure the content still looks good. As this is a Business-to-Business company the decisions may not be made by an individual but as a collective. This means that meetings may take place and the site presented on a larger screen. The max-width keeps the website looking neat and professional.
* I have used containers, paddings and margins to make sure that the content is not too close together.


#### Homepage Wire Frame 

![Homepage Wireframe](README-files/homepage.png)

#### Testimonial Wireframe

![Testimonial Wireframe](README-files/testimonials.png)

#### Form Wireframe 

![Form Wireframe](README-files/form.png)
 

***


### Mockup

![Mock ups](README-files/mock-ups.png)

***



## Features

#### Universal Features Across the Site

###### Logo and Navigation Bar
The Navigation Bar is at the top of the webpage. The logo and nav links all change colour and are highlighted when hovered over. The nav links direct the user to the correct page of the website. When the logo is clicked on it will take the user to the home page. When the page is active, I used bootstraps class .text-uppercase. This causes all the letters to be capitalized and made the text a different colour. By having both these features accessibility is improved. When on smaller devices the nav goes underneath the logo and it is centred. For the larger screens, the nav is aligned to the right-hand side of the page and is on the same line as the Logo. I used white-space:nowrap to stop the (Request a Quote) from splitting when the size of the screen in lowered. The colour of the nav is our off-white and the text is the main green colour.


###### Responsiveness

The page is scaled up and down for different screen resolutions to help the content stay neat. This has been done using a mixture of media queries and Bootstraps responsive columns.


###### Accessibility

All images and navigations have an alt attributes or aria-label. This is to make the site easier to use for people with visual impairments by allowing them to navigate the site easily. There is high contrast used throughout the design. Header elements have been used in sequence so that the site makes semantic sense to screen readers. Links are consistent when hovered over. I have also set the font to rem so that if someone has their font settings higher for visibility the font size will increase accordingly.


###### Footer 

The footer is split into 3 sections:. “Opening Hours”, “Contact Info” and “Social”. The colour used for the background is our the main-green colour with a reduced opacity as the colour is very bold when at 100%. Theses The three sections are stacked on smaller devices and are arranged in 3 coloumns on larger devices.


The “Opening Hours” section includes the times the office would is be open. The “Contact Details” section offers the user alternative different ways of getting in contact with the business,. sSuch as the business’ aAddress, telephone numbers, and email. The last section “Social” section has links to social media sites using Icons from Font Awesome. When hovered over these links change from a white colour to a different shade of green than the background. The “Ssocial” section also includes a “Contact Us” link that is styled as a button to promote contact to Plant Factory.

##### Meta data


I have included descriptions, author, and keywords into the head element to increase traffic to the website. I have also labelled each page differently so that if the user has multiple tabs open it is easy to recognise each tab.


##### Redirect

I have also included a redirect file so if any of the links don't work or the page does not show up they are redirected back to the homepage. Please see credit for the code used for this function. 

*** 

#### Features Specific to Pages

###### Homepage 
* A hero image reminder of the name of the company (Plant Factory) and a slogan to entice users to continue reading.
* An “About” section with information of what Plant Factory does, including an image of the owner. On smaller devices are stacked, and in 2 columns on larger resolutions.
* A “Benefits sections” listing 3 benefits of having more plants in the office. On smaller devices this is stacked, medium devices have 2 columns, and the last benefit is arranged underneath, and larger devices is in 3 separate columns.
* A “What we offer” section which is displayed stacked on smaller devices and in 2 columns on larger screens. It offers potential clients the option of potted plants or bespoke features. Underneath the option is another link to the “Contact Us” form.

###### Testimonial
* The “Testimonial” page includes a carousel at the top, paired with an overlay for text colour contrast. The carousel gives the user the ability to click on the arrow to go forward or back and also allows the user to change which image is viewed using the buttons on the bottom. I changed the controls on the carousel to invert the colour from the standard white so it would be easier to see. The text includes information about the client and the type of option they opted for. Below the carousel is the testimonies. The testimonies are in relation to the images in the carousel and at the bottom of the text is where each testimony is from. I have scaled the carousel images to be large. This is because it is a showcase of the type of work the business has carried out. 
* I have staggered the testimonies on all devices.
 

###### Form 
* The “Form” page consists of the form and universal features only.
* The form includes fields for the user to enter their business name and contact details using - input type="text"
* The email input field requires the answer to be an email
* The phone number input field must be a number to be valid.
* The preferred contact method is selected using a radio button. This is because there is an option for both contact methods to be selected. By using a radio button errors are avoided that may upset the user.
* Options they would like to talk about is a checklist. This is to ensure the submitted form goes to the correct team.
* There is a - textarea - to allow the user to ask any further details. I have used placeholder text to encourage the user to make any further comments.
* The submit button is large and changes colour when hovered over.
* The form is stacked for mobile use. For the larger screens, the radio buttons and check list appear inline.
* The labels are clear as to what should go in the field and all fields are set to “required”.


I have set the form to POST with an action of "contact.php" this will not currently go anywhere as github pages is static hosting only. 

### Future Features 

* Nav collapses on mobile
* Has a log in area where users can chat online with members of the team and has the ability to share designs and discuss offers.
* Has a “form submitted” status to give users peace of mind that the form has been sent correctly and sends the form to Plant Factory email.
* Create an option for businesses to buy smaller plants online with a way to make online payments.

    

***

## Technologies Used 

* HTML5 - Mark-up language using semantic structure.
* CCS3 - Cascading style sheet used to style.
* Gitpod.io - for writing the code. Using the command line for committing and pushing to Git Hub
* GitHub - Used to host repository 
* GIT - for version control of the project.

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
* Contact us and Request a Quote opens links to Form.
* Hovers over links are clear and not default blue.
* Social links works. 
    
[HTML Validator](https://validator.w3.org/)
![HTML Validator](README-files/html-valid.png)

[CSS Validator](https://validator.w3.org/)
![HTML Validator](README-files/css-valid.png)


A few warnings were displayed when using the validator this is because of the variblesvariables I have used to help with the maintenencemaintenance of the site. The other error is due to the useing of external style sheets. I am happy with the outcome of this test.


### Usability Testing

I sent the project to a few of my peers in the slack community and to a few friends within the industry.  I had them check to ensure all links were working and the website was responsive at different screen resolutions.
One of my friends viewed the project in simplified mode and commented that the website was still easy to navigate and displayed clearly. 


I wanted to carry out Accessibility Testing on the website.  I used [Wave](https://wave.webaim.org/) This was to check to make sure the website the website would work well with screen readers.  I also manually checked the web site by increased the REM settings on my browser and making sure that the content was still visible.  This highlighted a BUG which was FIXED prior to deployment. 

    
### Browser Compatibility

Tested on Chrome, Firefox, Brave, Internet Explorer, Microsoft Edge, Safari.
I tested on older version of Internet Explorer, the website works from Internet Explore 9 and onwards, although not all the content is as designed the overall layout means the content is still easy to read and the images are still visible. 
I used [IE NetREnderer](https://netrenderer.com/index.php) to test the older versions. 

### OS Compatibility
Tested on iOS, Android 10, and Windows 10. - I asked a friend with an IPhone to test that it was working.  
Tested for responsiveness using Chrome DevTools.

### Performance Testing
Tested on the Developer Tools Lighthouse.  This was the first time running through Lighthouse

![Lighthouse results](README-files/lighthouse-before.png)

I made some changes, such as increasing contrast, adding meta data and making sure my HTML was semantic and this was the results.

![Lighthouse results](README-files/lighthouse-after.png)

### Testing User Stories

* ###### A user looking for office plants to add to the office or workspace or business. 
The user can find the information quickly on the first page of the site. The user is given the option to get in contact with us and can have a look at testimonies and images of work carried out.
* ###### A user looking to install a plant feature. 
The user can easily see that this is something we offer.   
The user is given the option to get in contact and can have a look at testimonies and images of work carried out previously. 
* ###### A user who already has a quotation but wants to get in contact.
The user can find our contact details in the footer, this includes a phone number, address, and email.  There is also a big button that the user can click to be taken to a page to contact us. 
* ###### A user doing research on what we offer. 
The user can find information about what services we offer on the main page, can then go onto looking at testimonies and images of work we have previously carried out. Each tab has a different description so if the user has more than one tab open they can navigate between them easily. 
* ###### A user looking to see if we have done previous work. 
Easy to navigate to and from the main page. Testimonials clearly seen in the nav bar.
* ###### A user showing the site to other people within their business.   
Max-width set so if the site is being shown in a meeting or on a larger screen the content still looks presentable. 


*** 

## Deployment 

### Adding and Committing files

To add files to the repository take the following steps

In the command line type -
        git add .  
        git commit -m "This is being committed"
        git push

To add all new files or modified file use " ."  - To add a single file use the pathway to the file eg .index.html  or assets/css/style.css
When committing make sure your comments are clear about what changes have been made. 
Pushing will send your work to the repository

### Deployment 

The project was deployed with the following steps

* Logged into git hub
* Clicked the "Settings" button in the menu above the Repository.
* Scroll down the Settings page to the "GitHub Pages" Section.
* Under "Source", click the dropdown called "None" and then select "Master Branch".
* The page will automatically refresh, and a link displaced.  It may take some time for the link to show the website.
* If the page will not load go down to "template" under the "source" and select a template. 
* Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.


### Forking

Forking the GitHub Repository


By forking the GitHub Repository, you can make a copy of the original repository in your own GitHub account.  This means we can view or make changes without making the changes affecting the original.

* Log into GitHub and locate the GitHub Repository.
* At the top of the Repository there is a "Fork" button about the "Settings" button on the menu.
* You should now have a new copy of the original repository in your own GitHub account.

### Cloning 

Making a Local Clone

* Log into your GitHub then find the gitpod repository
* Under the repository name there is a button that says "Clone or download". Click on this button.
* If cloning with HTTPS "Clone with HTTPS", copy this link.
* Open Gitbash
* Change the current working directory to the location where you want the cloned directory to be.
* Type git clone, and then paste the URL you copied earlier.

        $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
        Press - Enter- Your local clone will be created.
        $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
                > Cloning into `CI-Clone`...
                > remote: Counting objects: 10, done.
                > remote: Compressing objects: 100% (8/8), done.
                > remove: Total 10 (delta 1), reused 10 (delta 1)
                > Unpacking objects: 100% (10/10), done.
[Click Here](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository) for more info on cloning. 

## Known Bugs 
* BUG -There was an issue with testimonial when the content was view on a phone in landscape mode. FIX - I changed the layout of the page so the content would render better. 
* BUG- The text on the carousel takes a moment to snap to uppercase.  This is likely because of the delay in reaching the Bootstrap style sheet. FIX -Written the follow code directly into my style.css 
         
         .carousel-caption h5, .carousel-caption p {
        color:var(--md-brown);
        font-weight: 600;
        font-size: 1.4rem;
        letter-spacing: 1px;
        text-transform: uppercase;
         }

* BUG- When the rem size is increased on a users screen the text on the hero image is lost and the form is cut off from the bottom.  FIX - Changed the code so that the container-pattern-form was set to min-content.  I changed the position of the jumbotron.  
* BUG The links to social media were not working. FIX the URL to the website had a typo. 


***

## Acknowledgements

### Credit

* Brian Macharia- Mentor support, guidance, tips, and key things to look out for throughout the project. Helping me to check for errors and looking at my code. 
* Matt Rudge - Template for gitpod.io 
* Rob Beaney - for testing and reporting any bugs or issues, helping me to trouble shoot an issue with positioning. 
* Anthony Lomax - for testing and reporting any bugs or issues and giving me feedback on usability.
* Harry Smith - for pointing out issue with carousel text taking a moment to change to uppercase.
* Megan Turner - for proof reading my README.md.
* Full Stack Developers WhatApp group (memebers of the codeinstitute slack community) - for taking the time to test the website and point out some padding issues on different resolutions, pointing out the testimonial landscape bug, also for pointing out the social links were not working. 

* [Bootstrap](https://mdbootstrap.com/)  - Carousel used and customised for use in the project. 
* [Code Institute SampleREADME](https://github.com/Code-Institute-Solutions/SampleREADME)
* [Code Institute README Template](https://github.com/Code-Institute-Solutions/readme-template)
* [W3schools](https://www.w3schools.com/) - for various code information and trouble shooting.
* [Google fonts](https://fonts.google.com/) - CDN for the fonts were used in the project.
* [Balsamiq wireframe](https://balsamiq.com/) - To build wireframes in the design phase. 
* [Font Awesome](https://fontawesome.com/) - for social media icons) - CDN for icons used in the project.
* [Unsplash](https://unsplash.com/) Images taken from unsplash - see [Imagery](#imagery) for links.
* [Freepik](https://www.freepik.com/)- pattern background
* [HTML Validator](https://validator.w3.org/) - Testing validity of HTML.
* [CSS Validator](https://validator.w3.org/) -Testing validity of CSS.
* [IE NetREnderer](https://netrenderer.com/index.php)
* [Am I Responsive](http://ami.responsivedesign.is/#) - Checking the responsive nature.
* [Beautifer](https://beautifier.io/) - Allowing me beautify my code.
* [Tiny PNG](https://tinypng.com/) – changing some images to smaller sizes
* [HTML Online](https://html-online.com/articles/smart-404-error-page-redirect/) - Redirect page 



*** 

### Code:

*  Bootstrap library was used to create a responsive design.
Carousel taken directly from bootstrap - altered to fit needs 

        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
            <img src="..." class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
            <img src="..." class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
            <img src="..." class="d-block w-100" alt="...">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
        </div>



* Code customised for use of the website from [HTML-online](https://html-online.com/articles/smart-404-error-page-redirect/)

        <!doctype html>
        <html lang="en">
        <head>
            <meta charset="utf-8">
            <meta http-equiv="x-ua-compatible" content="ie=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Redirecting</title>
        </head>
        <body onload="redirect()">
            <h1 style="text-align: center; padding-top: 50px; display: block;">Redirecting...</h1>
            <script>
            function redirect() {
                setTimeout(function(){ 
                        window.location.replace("/");
                    }
                    , 100);	
                }
            </script>
        </body>
        </html>
***

### Content:

Code & Content (not already attributed): Rebecca Kelsall

### Inspiration: 

https://wwww.wwkc.net
https://www.canoe.ie
https://www.rockhoppers.ie
https://www.baltokayak.com






