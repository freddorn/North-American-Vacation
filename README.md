# North American Vacation

View website on [Github Pages](https://freddorn.github.io/north-american-vacation/)

North American Vacation is a travel planning webite for the United States, Canada and Mexico. Travelers can view where to stay,
the restaurants and bars nearby and tourist attractions in the area. The website will help the vacationer be aware of what is
available in the location they want to visit, so they can research and evaluate all the different possibilities.


## UX

The site is a single page where users can plan their trip in the United States, Canada or Mexico. It is presented in an
easy to use format with two banner images of North American places. The site features an email contact form to contact
us, if the traveler has any questions.

 ### User Stories

* As a user, I like that the website is easy to use and the information is presented well.
* As a traveler, I want to see all the overnight accomodations in a given city or area.
* As a diner, I would like to view all the restaurants and bars in the area and what type of food they serve.
* As a tourist, I am interested in the area's tourist attractions.
* As a user, I would like to see the reviews of others, to get some insight of each place.

**Wireframes** can be viewed [here](https://github.com/freddorn/north-american-vacation/tree/master/assets/mockups)

## Features:

### Existing Features
* A dropdown menu to select the country you are visiting, that will focus the country selected on the map.
* An autocomplete search bar for the city that is being entered. It allows for suggestions of cities, as city names appear based on letters that have already been typed in.
* Radio buttons to choose between looking up Accomodations, Restaurants/Bars or Tourist Attractions.
* A map window, where markers will drop on the map for each result. 
* The reset button, which resets the map to the default USA view and also clears the results table.
* A results table, listing up to 20 results with markers. if a marker is clicked in the results table, it will open an information window, at the corresponding marker on the map. 
* Each infornation window shows the address, phone number, review rating and website url and link.
* A contact form at the bottom of the page, if the user needs help or has questions.


### Features Left to Implement
* An actual booking engine, where travel could be booked from this website.

## Technologies Used

* HTML Language
* CSS Language
* [BootstrapCDN](https://www.bootstrapcdn.com/)
    - Used to simplify the building of a responsive website.
    
* [AutoPrefixer](https://autoprefixer.github.io/)
    - To make sure the css code is valid for all browsers.

* [jQuery](https://jquery.com/)
    - To simplify DOM manipulation.
    
* [Javascript](https://www.javascript.com/)
    - To add interactivity to the site.
    - To produce the map.
    - To have the search results list in a table, with markers on the map.
    
* [Google Maps and Places API](https://cloud.google.com/maps-platform/)
    - Allows users to search using a map and have the different establishments shown on the map.
    
* [Email JS](https://www.emailjs.com/)
    - Send email directly from your client-side Javascript code without server-side code.

* [Balsamiq](https://balsamiq.com/)
    - Used to create the wireframe mockups for this project.


## Testing

### Testing Details
Tested the site manually, did not use Jasmine for automatic testing, as it was unnecessary due to the nature of the project.

#### Testing Tools:

* [AutoPrefixer](https://autoprefixer.github.io/)
    - To make sure the css code is valid for all browsers.

* [W3C CSS validation](https://jigsaw.w3.org/css-validator/)
    - To check the the validity of the CSS code. 
    
* [W3C Markup Validation]( https://validator.w3.org/)
    - To check the the validity of the HTML code. 

* [Javascript Syntax Validator](https://esprima.org/demo/validate.html)
    - Checks for javascript mistakes and errors.
    
* [JS Hint](https://jshint.com/)
    - Validates javascript and checks for errors.
    
#### Testing the main page: 

1. Checked the functionality of the Google Maps and Google Places API's for proper operation.
2. Checked the functionality of the EmailJS API for ptoper operation making sure emails from the contact form came through with all the form fields complete.
3. Made sure the page was responsive at different screen sizes, with the different elements of the page stacking up on each other, below the screen size of medium. 
4. When selecting a country to search, made sure that country was zoomed in on, on the map.
5. In the City search field, made sure that only cities for the country chosen show up.
6. For the Type of search radio buttons, made sure that either accomodations, restaurants/bars or tourist attractions show in the results table, depending on which
   of the 3 categories that was chosen.
7. Made sure that all of the results, were shown in the results table.
8. Verified that the reset button, cleared the search results and reset the map back to the default United States.

#### More Testing:

1. Used the Chrome Dev tools for most of the responsive testing.
2. Tested with a device of each of the 5 Bootstrap screen sizes. (Extra small to Extra Large)
3. Tested with the Chrome, Firefox and Safari browsers.

#### Bugs Fixed

1. Added an alert for when an email was sent, so the user could know if it was sent successfully or not.
2. Made the contact form clear, after a message was sent, to show the user that it was sent.
    
## Deployment

### Deployment onto GitHub

To deploy to Github pages from its Github repository, the following steps need to be completed:

1. Log into Github.
2. Select the repository **freddorn/North-American-Vacation**
3. Select *Settings* from the menu, near the top of the page.
4. Scroll down to the **Github pages** section.
5. Under **Source**, change the drop-down menu **None** to **Master Branch**
6. Scroll down to the **Github pages** section for the link to the deployed website.

In development of this website, only the master branch was used. There is no difference between the deployed and development versions.



### How to run this project locally

To clone this project from GitHub:

1. Follow this link to the GitHub repository
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository. 
4. In your local IDE open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type ```git clone```, and then paste the URL you copied in Step 3.
7. Press Enter. Your local clone will be created.


## Credits

### Content


### Media

The photos used for this site were obtained by:

- The city skyline photo is from [Pxhere](https://pxhere.com/en/)
- The ocean beach photo was taken by myself.


### Acknowledgements

- I received inspiration for this project from travelling the United States, Canada and Mexico.
- The Slack community, where I have learned a great deal, reading through many posts.
- My mentor Sebastian Immel.
- W3SCHOOLS website for easy explanation of the code.

