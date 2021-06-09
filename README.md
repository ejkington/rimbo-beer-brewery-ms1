# Rimbo Beer Brewery.

[Link to Live Website](https://ejkington.github.io/rimbo-beer-brewery-ms1/)

[GitHub Repo](https://github.com/ejkington/rimbo-beer-brewery-ms1)


## About

Rimbo beer brewery is a business concept created for my MS1 project with Code Institute.

Rimbo beer brewery is a business dedicated to brewing the best craft beer in the north. Rimbo beer brewery offers both craft made beers and brewery tours  
Currently they do not offer sales directly from the website. 

Rimbo beer brewery would need to have a website to tell users a little bit about the business, show potential clients what services they offer and showcase some of their current or existing work. Rimbo beer brewery will need to have a contact form so that new and existing clients can reach them easily. Rimbo beer brewery is a small company with a small range of website needs. there is scope for the business to grow. As the business grows the website can be adapted to the growing business and additional features implemented.


## User Experience (UX)

## Strategy
### User Stories  

#### Reasons a user may visit the website
* A user looking for a craft made beer localy.
* A user looking to ordering beer too their resturant or bar.
* A user doing research on what we offer.
* A user interested in beer and beer making.

#### Reasons for the website
* Increase clients
* Showcase work
* Provide a way for new and existing clients to contact us.  

## Scope
#### What a user may expect
* Easy to navigate website 
* Good presentation and visually appealing regardless of screen size.
* Links and functions work as expected.
* Information about what Rimbo beer brewery does.
* A way to get in contact with Rimbo beer brewery.

#### What a user may want 
* To be able to find links to social media pages.
* To see examples of previous work carried out.
* To be able to chat with someone online.
* How it works - from start to finish.


#### As a developer / business I expect
* To provide information about Rimbo beer brewery.
* To provide an easy way for new and existing clients to contact us.
* To provide an easy to navigate website with links that work as expected.
* To encourage clients to contact us. 


## Structure
The website will consist of 4 separate pages
* A home page with the brewery moto and appealing pictures of beer styles.
* A our beers page showing what kind of beers the brewery makes, and what to expect when tasting it.
* A page with a form to contact the business and a map showing the business location.
* A brewery tours page with times and what the tour includes.



***



## Features across all pages.

###Navigation Bar

The navigation bar sits under the hero image. the bar when hovered shows a solid black underline.
The navigation links directs the user to the correct page of the website.
When the rimbo beer brewery text is pressed it takes the user to the main page.
On larger screens the navigation bar is horizontal and centered. on smaller screens it stacks verticaly in the center and has a black underline.

###Responsiveness
The page is scaled up and down for different screen resolutions to help the content stay neat. This has been done using of media queries.

###Accessibility
All images and navigations have an alt attributes. This is to make the site easier to use for people with visual impairments by allowing them to navigate the site easily. There is high contrast used throughout the design. Header elements have been used in sequence so that the site makes semantic sense to screen readers. Links are consistent when hovered over. I have also set the font to rem so that if someone has their font settings higher for visibility the font size will increase accordingly.

###Footer

The footer consists of social media links and will open in a new tab.
and a copywrite of the author.

###Meta data
I have included descriptions, author, and keywords into the head element to increase traffic to the website. I have also labelled each page differently so that if the user has multiple tabs open it is easy to recognise each tab.

## Features specific to page


###### Homepage.

A hero image of the brewery, and the company logo.
The brewery motto.
Images of the 3 diffrent beer styles that the brewery makes.

###### Our beers.

Showcasing pictures of the beers.
The names of the diffrent beers.
and a taste review.

###### Brewery tours.

Showing the times for when the brewery has tours of the brewery and showing dates and a email adress for contacting and booking.

###### Contact.

* A google map showing the location of the brewery.
* The “Form” page consists of the form.
* The form includes fields for the user to enter their name and lastname and is set to required.
* The email input field requires the answer to be an email
* The message field for a message to the company.
* submit button with the text beer me up!



## Features left to implent

- More beer that the brewery makes.
- links to resturants and bars that has the brewery beers in stock.
- an pop up for confirming the age of the user at the start page.
- popup for accepting cookies.
- slide show of pictures of the brewery on the header image.


## Technologies Used 

* HTML5 - Mark-up language using semantic structure.
* CCS3 - Cascading style sheet used to style.
* Gitpod.io - for writing the code. Using the command line for committing and pushing to Git Hub
* GitHub - Used to host repository 
* GIT - for version control of the project.

## Design

* [Google fonts](https://fonts.google.com/) - For styling the typography (roboto)
* [Font Awesome](https://fontawesome.com/) - for social media icons
* [Beautifer](https://beautifier.io/) - Allowing me beautify my code.

### Call to action

I made all my call to actions as easy to see as possible. 

* The links in the Nav/head image are highlighted using a underline when the mouse is hovered over them.
* "Submit link" on the form in the form have also been styled as a button. 
* The social links will send the user to the company's social media pages.  

### Images

The images  used on all the pages was taken from https://www.istockphoto.com/


### Layout 

* I have used responsive design when creating the website. This allows the user to see more of the website on a larger screen. I have also set a Max-Width for the site so on very large screens the content stays neat and is well formatted.
* I have also used a max-width, this is to ensure the content still looks good. As this is a Business-to-Business company the decisions may not be made by an individual but as a collective. This means that meetings may take place and the site presented on a larger screen. The max-width keeps the website looking neat and professional.
* I have used paddings and margins to make sure that the content is not too close together.


## testing

* Nav links work and the user is directed to the correct page of the site. 
* heading text takes the user back to the main page.
* Contact us and Request a Quote opens links to Form.
* Hovers over links are clear and not default blue.
* Social links works. 

### OS Compatibility
Tested on iOS, Android 10, and Windows 10.

### Performance Testing
Tested on the Developer Tools Lighthouse.
![Lighthouse results](README-files/lighthouse.png)


### Validator testing

- HTML
  - No errors were returned when passing through the official [W3C validator](Link to the test)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](Link to the test)

### Adding and commiting files

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



## Acknowledgements

### Credits
* Brian Macharia- Mentor support, guidance, tips, looking at my code. 
* The slack community.

* [Code Institute README Template](https://github.com/Code-Institute-Solutions/readme-template)
* [W3schools](https://www.w3schools.com/) - for various code information and trouble shooting.
* [Google fonts](https://fonts.google.com/) - CDN for the fonts were used in the project.
* [Font Awesome](https://fontawesome.com/) - for social media icons) - CDN for icons used in the project.
* [HTML Validator](https://validator.w3.org/) - Testing validity of HTML.
* [CSS Validator](https://validator.w3.org/) -Testing validity of CSS.
* [Beautifer](https://beautifier.io/) - Allowing me beautify my code.
* [Code Institute SampleREADME](https://github.com/Code-Institute-Solutions/SampleREADME)

### Content

- The text for the Home page was writen by the developer
- The text for the tast of the beer was taken from https://www.tastings.com/
- the page is made up and not a real brewery.

### Media 

- The images  used on all the pages was taken from https://www.istockphoto.com/





  
