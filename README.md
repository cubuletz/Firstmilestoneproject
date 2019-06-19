# Wings Shop Website

This is a front-end only website named Wings Shop. The purpose of this website is to target the adventure lovers, peoples who love nature, peoples who love freedom and want to get involved in this sport.
They have now the opportunity to explore this sport through our test wings. 
The first idea of the page started with bicycles because I tried to use my pictures but when I had to add a video to the page I realized I have no proper one to use on it then I decided to change the webpage theme whit the actual one.

Website link:

https://cubuletz.github.io/Firstmilestoneproject/
 
## UX
 
This website was designed for existing and for potential lovers of flying to give them the occasion to see a suit of wings as well as give them the occasion to book a flight whit them.

### User stories

- As a user, I want to navigate my way easy on the website, so I find the information I need.
- As a user, I want to find out how this works and how can I book a test.
- As a user, I want to get the contact informations easily, so I don’t have to browse too much on the website.
- As a user, I want to follow the company on social media, so I keep an eye on the news about products.
- As a user, I want to make a booking easily.

## Features

#### Across the entire site

- Navbar: Allows all users to navigate to any part of the website without the use of browser 'back' and 'forward' buttons.
- Collapsed Navbar: Gives all users the ability to navigate the site while in the mobile view.
- Social media links: Allows users to follow WingsShop on social media platforms available (the links are sending the users to the homepage of each platform only)
- I have aligned the navigation to the left, this is where the users look to find a list of options according to Norman Nielsen (https://www.nngroup.com/articles/horizontal-attention-original-research/).
- On the Navbar I marked in bold the link on the active page, that means a location indicator for the user, because the search engines not always send the users on the home page (https://www.nngroup.com/articles/navigation-you-are-here/).
- Across the entire website, I used a minimum colour contrast of 4.5:1 between the foreground and the background according to WCAG (web content accessibility guideline) AA standard. To check the colour contrast I used https://webaim.org/resources/contrastchecker/.
- I used the page heading name the same as the navbar link label because is ideal that users to know they have arrived in the right place (https://www.nngroup.com/articles/link-promise/).

### Features Left to Implement

In the future I would like to implement the below features:
- The possibility to buy wings.
- The possibility to book and buy flying lessons.
- A feedback page for the users.


## Technologies Used

- [HTML](https://www.w3.org/TR/html52/)
     - I used this to structure the website.

- [CSS](https://www.w3.org/Style/CSS/specs.en.html)
     - I used this to add styling to the HTML structure.

- [Visual Code Studio](https://code.visualstudio.com/) 
     - I used this as IDE.

- [GitHub](https://github.com/)
     - I used this to push my website and save my commits on it. 

- [JQuery](https://jquery.com/)
     - I used this for the responsive navbar.

- [DevTools-Light House](https://developers.google.com/web/tools/lighthouse/v3/scoring)
     - I used this to test some parts of the code and to analyze how the webpage works online and how can be improved.

- [Bootstrap 4.3.1](https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css)  
     - This was used for the Navbar, for making the site responsive, for the grid system and also I used the modals for booking options.

- [Font Awesome](https://use.fontawesome.com/releases/v5.8.2/css/all.css) 
     - This was used in the footer for the social media icons.

- [Google Fonts](https://fonts.googleapis.com/css?family=Heebo&display=swap) 
     - I used the font family of Heebo across the site.
    
- [GoPro Quick](https://shop.gopro.com/EMEA/softwareandapp/quik-%7C-desktop/Quik-Desktop.html) 
     - I used this to edit the video presented on about.html.

- [Balsamiq](https://balsamiq.com/index.html) 
     - I used this to create the prototype of the page. The prototype can be found in "assets/wireframes" folder.

## Testing

- I used [This HTML validator](https://validator.w3.org/) to ensure my code was legal.
- I used [This CSS validator](https://jigsaw.w3.org/css-validator/) to ensure my CSS was legal.
- I used [Color Contrast Checker ](https://webaim.org/resources/contrastchecker/) to ensure that I have a minimum of contrast between
foreground and background colors.


## Viewport and responsive testing

-I used Bootstrap to create responsive content in mobile devices and JQuery for the collapsing nav menu.

### index.html

1. From a mobile view, the NavBar menu is vertically collapsing pushing down the content to be visible for use in menu mode.  
2. In the mobile view, the lead of the title will be hidden to leave a clean and easy to read page.


### wings.html

1. From a mobile view, this is vertically aligned.
2. In the mobile view, the images are coming on the bottom and the text and buttons on the top in three rows.
3. I wrapped all the content in a container and then gave a separate column for text and pictures whit class col-12 col-md-6 for a better view in the mobile mode.


### about.html

1. From the mobile view, the user can see paragraphs one above the other which makes the text easy to read.
2. I have used for each paragraph col-12 col-sm-6 to set them one in the top of the other.
3. I used the bootstrap class 'embedded-responsive' to wrap the 'iframe' which includes the video. This making the video size responsive to the mobile screens.

### contact.html

1. In the contact file, I used two forms wrapped in a container.
2. First form it is a 'card form' where I have included 3 fields of information and the second form it is a
submit form.
3. For the wrapper container, I gave the class 'col-12 col-md-6' to make the page responsive for the mobile screens.



## Deployment

I used GitHub Pages to deploy my website by following the steps below:

1. I have created a repository in GitHub.

2. I used the Visual Studio Code to clone the GitHub repository copying the URL from my GitHub repository founded in 'Clone od Download Green button' then pasted in Visual Studio Code IDE.
  
3. I also used Visual Studio Code to commit my work and push it to the GitHub not using the terminal just using the Visual Studio Code buttons.

4. Then from my GitHub repository I have gone to settings, I have selected the master branch, I have saved and the website was published at:

    https://cubuletz.github.io/Firstmilestoneproject/

5. After this was done I did regular commits after every important update to the code, and I pushed the changes to GitHub.


### Content

- The text for 'wings' also was copied from [U-Turn website](http://www.u-turn.de/web/).
- The text for 'about' is entirely written by me.
- The comments added are based on what I have learned through the lessons.

  
### Media
- The video used on 'about' page is entirely recorded by miself , edited whit GoPro Quick published on https://www.youtube.com/watch?v=ShCQOMgwgl0 and linked to WingsShop website.
- The pictures for 'home' and 'wings' were copied from [U-Turn website](http://www.u-turn.de/web/).

### Acknowledgements

- I received my inspiration for this project from my hobbies then I used as an example some Bootstraps example pages. I also I used the knowledge acquired along the course been inspired by the miniprojects.
- Thank you to my mentor Antonija Simic who gave me support along with the project.
- Thank you to Anna Greaves who helped me whit valid answers on my questions and bootstrap documentation page created by herself.
