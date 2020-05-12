 
 
# Half The Group
I have chosen to make a website for the improvisation theatre group Half The Group. They offer shows and company events.  
They have a website already but I wanted to improve it to reach out to more people what they offer and make it more appealing for people to watch them perform. 
I designed the website to make information about the group members and their shows easy accessible, to make it possible for people to follow them and companies to hire them. 
I wanted to make it to be easy to make contact so therefor I made a contact form to enable people to reach out with questions and for companies to show their interests.
Here you can view their existing website: https://www.halfthegroup.com/

# UX
I created this website with a wish to make it responsive and to be easy to navigate on all mobile devices.
The colors I choose are pink, grey, white and black since I feel they work well with the existing pictures of the theatre group. 
 
### Target audience:
- The members of the group
- Companies interested in impro events
- Supporters of the theatre group.

# User Story
- As a supporter, I want to be able to see upcoming events so I can buy tickets and see them perform.
- As a supporter, I want to see pictures and information about the cast in order get to know them more.
- As a company, I want information and a contact form so I can hire them at events and conferences to make my staff happy.
- As someone who wants to come and see a show at the theatre for the first time, I want to see the map to plan my trip to the theatre.
- As someone who has questions for the theatre group, I want to be able to reach the group easily through the contact form.
- As a user of this website, I want it to be easy to navigate and the pages to be visually appealing.

# Wireframes
Pictures from Balsamiq:
[Link](assets/photos/Balsamiq-1.pdf)
 
# Features
- Navigation Bar - This allows the user to easily navigate in the site, it is consistent throughout the whole website. 
The user should know where they are and how to find every page easily. 
- Footer Links -  To give easy access to social media pages. These are consistent on every page. 
- Home page: Image Carousel - Shows many pictures on the homepage. A shout out to the audience and companies! The goal is for the user to buy tickets to the show and for companies to hire them. 
- Ticket page: Shout out to companies again and presentation of shows and upcoming shows. 
- Meet the cast page: An opportunity to get to know the cast more in a fun and easy way so the user wants to see them perform. Every person is presented with a photo and a personal quote about love, since the theme is romantic comedy. 
- About page: The purpose is to give more information about impro, the cast, the shows and the theatre. A map is embedded to the theatre so people know where to see them perform. 
- Contact Form page - Allows users to submit questions and for companies to contact the group.
 
# Features Left to Implement
- Make a gallery with more photos and videos. 
- Write more information about each team member to get to know the cast even better. 
- Make one page only for companies and one page for upcoming shows. 
- Make a blog about the theatre group. Upload pictures from meetings and trainings.
- Offer monthly newsletters sent to email accounts. 
- Information about the corona-virus situation and what Half The Group is doing to prevent the spread of the virus. 
- Make an icon to the navigation bar. 
 
 
# Technologies Used
 
[HTML](https://en.wikipedia.org/wiki/HTML5)- I used HTML to give structure and content to the page. 
 
[CSS](https://sv.wikipedia.org/wiki/Cascading_Style_Sheets) - I used CSS to style my website. 
 
[Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/)- I used Bootstrap for every page and to make it responsive. For example the carousel image, the hero container and the columns. 

[Google Fonts](https://fonts.google.com/) - provided font-family, such as Roboto.
 
[Balsamiq](https://balsamiq.com/) - was used to design my website. 
 
[Coolors](https://coolors.co/806157-cccccc-cf5d9a-e5b6a9-c0287a) - I used this tool to get the colors I wanted to use on my page. 
 
[Font Awesome](https://fontawesome.com/)- provided symbols to the main page. 

[Embed Google Map](https://www.embedgooglemap.net/) - to provide a map to the About page. 

# Testing
The required needs and goals of the user in the user story section were met. 
Fans and audience can get easy access to upcoming shows. 
Companies can get information about the theatre group and can hire them on events using the contact form. 
Supporters can get to know the cast a little bit more by seeing the images and the personal quotes. 
Supporters who have questions about the theatre can read information on the About page.  
They can contact them through the contact form if they have any questions.
For visitors to a show there is a map so they can plan their trip when they are going to see them. 
 

Throughout the creating and building the website I tested the code in gitpod using “python3 -m http.server” to see how the page looked on the browser. 
A lot of testing was done by the developer tool in Google Chrome, to see how responsive the website was in different devices.
As I went along with the project I modified the code especially in the end to make sure it was working well on every device. 


To ensure that all users can successfully use the site, I have been tested it on many browsers such as:

- Chrome
- Internet Explorer
- Edge
- Safari
- Firefox
- Opera

I have also tested the page on different devices such as Chromebook, MacBook, Ipad, Galaxy, iPhone. 

CSS code was tested here: https://jigsaw.w3.org/css-validator/#validate_by_input

HTML-code was tested here: https://validator.w3.org/

I wrote in the address in the form and made changes after that. 

I have been testing all the links in the navigation menu which all worked fine. The buttons also work well.
The social links will be opened in a new window. I have been using "target="_blank" to manage that. 
All links are pointing to the correct destination.

I have been testing the map, zooming in and out which are working well. When using iPhone XR I discovered the map pops up when the user is pushing the "About" link in the navbar. When the user goes backward on the page the text appears. 

### Contact form:
I have tested to try to submit the form without a valid email address and I got an error message, noting the invalid email address. 
The "required" attribute has been added to the Email address. If this field are not filled in the user can not submit the message. 
If all fields are filled in the page will reload. 

## Issues found in testing
- The text in the hero image on the Ticket-page overflowed so I did some adjustments in padding and made the image size bigger and then it looked better. Later on I also decided to move some of the text below the image"
- The logo was too big on mobile devices so I deleted letter-spacing in the CSS-file and did adjustments with size and padding to the right which resolved the problem. 

# Deployment
I have used Github to deploy my website. 
The following steps were taken to deploy the page to GitHub Pages from its GitHub repository:

1. At the menu items select "Settings". 
2. Scroll down until you come to the section of "GitHub Pages".
3. Under Source, click the drop-down menu labeled None and select Master Branch instead. 
4. When selecting Master Branch the page is automatically refreshed and the website is now deployed.
5. To get the link to the deployed website scroll back down to "The Github pages" and there it is!

https://kristina-liv.github.io/Half-the-group/

When new commits are done in the master branch the webpage will update automatically. 
The landing page must be named index.html to work correctly. 

# Credits
- The navbar and the footer was created with the help of Bootstrap. 
- The tables and columns were created with the help of Bootstrap. 
- The carousel on the Home-page was created with the help of Bootstrap. 
- The hero container on the Ticket-page was created with the code from [w3schools](https://www.w3schools.com/howto/howto_css_hero_image.asp). 
- The cards were created with the code from [w3schools](https://www.w3schools.com/bootstrap4/bootstrap_cards.asp). 
- The image gallery was made with help from Bootstrap. 
- The about-page was made with help from Bootstrap and the map comes from [Embed Google Map](https://www.embedgooglemap.net/)
- The form was created with help from [Bootstrap](https://getbootstrap.com/docs/4.0/components/forms/)
 
# Media
The photos used in this site were obtained from Facebook. 
 
# Acknowledgements
- I have received a lot of support and inspiration from my husband. 
- Thanks to my mentor Aaron Sinnott for giving advice and help with the project. 
- Thanks to the patient people who have helped me in Code Institutes slack-channels.  
- Thanks to my friends who gave feedback and support along the process of creating this website.