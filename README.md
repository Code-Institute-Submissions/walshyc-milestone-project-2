# EURO2020 Travel Guide - Milestone Project-2
This site allows a user to pick one of the 12 host cities for the UEFA European Championships taking place for the first time across Europe in 2020 as opposed to been held in a single country. The user can select from some popular services such as bars, hotels & museums in the selected city.

## UX

#### User Stories
A football fan who is following my nation, might want to check out the city they will be travelling to, so that they can book a hotel close to the stadium for when they travel to the city for Euro 2020.

A football fan who wishes to travel to a few of the cities during the tournament, would want to check the main transport hubs in each city, so that they can plan routes to and from each city.

A football fan who is not travelling to the tournament and is just interest in football, would want to know where and when the games are on, so that they could plan to watch the big games that interest them the most.



#### Wireframes

[Desktop - Start](assets/images/wireframes/desktop-start.png)

[Desktop - End](assets/images/wireframes/desktop-end.png)

[Mobile - Start](assets/images/wireframes/mobile-start.png)

[Mobile - End](assets/images/wireframes/mobile-end.png)


#### About the Site

This website is for anyone who wishes to travel to the UEFA Euro 2020 football tournament taking place in the June & July 2020. Once a user clicks on a host city the Google Map zooms into that city. Some information about the stadium that will host games is also displayed along with the fixtures that are due to be played at that venue.

Then the user can select from 6 services - Food, Bars, Hotels, ATM's, Travel & Museums. Once a service is selected by the user, markers appear on the map relating to the selected service.

A countdown to the start date of the tournament is also shown on the site.

## Features

#### Existing Features
- Facts about the stadium and city are displayed to the user
- A full list of the fixtures that the city is due to hold during the tournament including the fixture date and round.
- The user can select from 6 services (Food, Bars, Hotels, ATM's, Travel & Museums) to find information/location details on these local services. This includes key Bus, Train and Air transport links.
- Countdown timer that displays the time left until the tournament starts.

#### Features to add
- Once the final 24 teams are known UEFA will release the full schedule for the tournament. I will then update each city to show which teams are playing in this city.
- Were possible I would like to translate the website into as many of the European languages that will be used by the competing countries.
- When the fanzone locations in each city are confirmed I will add these to the maps for each city.


## Technologies Used

- [Bootstrap 4 / Bootswatch Theme - Materia](https://bootswatch.com/materia/)
    -  **Bootswatch Materia Theme** was used for the general styling and layout of the page.
    
- [jQuery](https://jquery.com)
    -  **jQuery** was used to manipulate the website. It allowed the user to click the buttons to show the requested information on the map and also information about each city.

- [Flag Icon](http://flag-icon-css.lip.is/)
    -  **Flag Icon** was used to improve the look of the buttons.

- [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript/tutorial)
    -  **Google Maps** was used to display the map and markers when a user selected a city and a service. The Google Maps Places API was used to get the rating information and direction for each business and display this in the info window.

## Testing

#### Validation

I ran the single HTML file through a HTML validator on [HTML Validator](https://validator.w3.org). This showed up no invalid HTML.

I used [CSS Validator](https://jigsaw.w3.org/css-validator) to validate my CSS file style.css, this proved to be all correct.

I also used [Color.review](https://color.review/) to refine the main green and blue colours that I had. This site allowed me to pick the best two main colours for my site so that the contrast was correct. The two main colours I ended up with were #0E5E67 and #c7d64f.

#### Usability
1. Select a City:
    1. Click any of the 12 city buttons
    2. The map then zooms to the stadium in that city.
    3. An information box appears to give some facts about the city/stadium along with a list of each game taking place at the stadium.
    4.  On screens smaller than 992px the information box and map are stacked on top of each other, so a hide/show button is used to collapse the information to make it easier to see the map.

2. Select a service:
    1. Click on any of the 6 service options.
    2. The map then zooms in or out if required so that the markers can be seen.
    3. A number of markers appear on the map
    4. Clicking on one of the markers presents an info window which has the service rating if applicable and a link to directions to that service which the user can click on.

3. Reset Button - The reset button once clicked brings the user back to the start of the website, where they can select another city.

4. The countdown timer at the top of the page is a visual element only, counting down the time until the tournament starts.


#### Browser Support
I used the Google Chrome Dev Tools to ensure that each page appears correctly at the most common screen sizes from large desktop to tablet to smartphone. The website was built using mobile first design as this site will mostly be used by people who are travelling.

I loaded each page on the following browsers:
- Google Chrome (Windows & Android)
- Firefox
- Safari (iOS)

The website & its features worked as expected on the above browsers at the Large, Medium, Small and Extra Small viewpoints where applicable.

I had to check the zoom level for each city and for each service within a city to make sure that the markers were visible to users across all viewports.



#### Speed Test
I used [GTMetrix](https://gtmetrix.com) to test the load speed the website. The page had a load speed of 1.3 seconds and a total page size of 643kb.


## Deployment

I created the Github repository called milestone-project-2 in my [GitHub Page](https://github.com/walshyc). After I had completed each minor step on the website such as getting the Google Map to appear, getting the country buttons aligned correctly I committed the changes to the Github repository along with a short message. This made it easy to fall back on old commits when needed.

After I deployed the site to Github pages, I had to make sure any file paths contained in the were absolute so that the correct image/file was loaded.

I have hosted the website using Github pages. This was done under the settings of my repository under the GitHub Pages section. I selected the master branch as the source. The site is then hosted [here](https://walshyc.github.io/milestone-project-2/).


## Credits

### Content & Media

- [UEFA Euro 2020](https://www.uefa.com/uefaeuro-2020/) - I sourced stadium/city information from the official Euro 2020 site as well as the Euro 2020 logos used in the header and for the stadium markers on the map. The breakdown of the games in each city was also sourced from here.

- [Google's Material Icons](https://material.io/tools/icons) - I used Google's Material Icons for the service icons across the website. I created the blue and green coloured markers in photoshop by using the 'Place' icon in this library as the template.

- [Transparent Textures](https://www.transparenttextures.com/) - I used this website to source the background effect for the page.

### Acknowledgements

- I received help and guidance from my mentor Chris Zielinski with the implementation of the Google Maps JavaScript API.

- I used stack overflow to help with some of the jQuery problems I had.
