## Table Of Contents:
1. [Design & Planning](#design-&-planning)
    * [User Stories](#user-stories)
      * [User](#user)
      * [Site Owner](#site-owner)
    * [Wireframes](#wireframes)
    * [Typography](#typography)
    * [Colour Scheme](#colour-scheme)
    
2. [Features](#features)
    * [Navigation](#Navigation)
    * [Footer](#Footer)
    * [Home page](#Home-page)
    * [About page](#about-page)
    * [Contact page](#contact-page)
    * [Contact complete page](#contact-complete-page)
    * [Map](#map)
    * [FAQ](#faq-frequently-asked-questions)
    * [Contact form](#contact-form)

3. [Technologies Used](#technologies-used)

4. [Testing](#testing)
  * [Googles lighthouse performance](#googles-lighthouse-performance)
  * [Browser compatibility](#browser-compatibility)
  * [Responsiveness](#responsiveness)
  * [Code Validation](#code-validation)
    * [HTML](#html-validation)
    * [CSS](#css-validation)
  * [Manual testing](#manual-testing-user-stories-orand-features)

5. [Bugs](#bugs)

6. [Deployment](#deployment)

7. [Credits](#credits)

## Design & Planning:
### User Stories
#### User 
As a user, I want to be able to:

- browse available paranormal experiences so that I can see the different options available.
- view detailed information about the paranormal experiences so that I can clearly understand what is included in each service.
- submit a contact form so that I can reach out to the organiser for more information or to book an experience.
- get directions to the haunted house locations where paranormal experiences take place, so I know how to get there.
- read an FAQ section to quickly find answers to common questions.
- view social media links so that I can follow or share the page with others.

#### Site Owner
As the site owner, I want to be able to:
- display all the necessary information clearly so that users can easily understand what services are offered and how to contact me.
- provide a simple contact form so that potential customers can reach out for bookings or enquiries.
- embed social media links to increase visibility and encourage users to share the page with their networks.
- ensure the page looks good on different devices so that users have a smooth browsing experience.

### Wireframes
Wireframes were created in Balsamiq.

#### Desktop
![Desktop Wireframe](assets/images/readme/wireframes/desktop-wireframe.png)

#### Mobile
![Mobile Wireframe](assets/images/readme/wireframes/mob-wireframe.png)

### Typography
I searched for a suitable font pairing on [fontpair.co](https://www.fontpair.co/pairings/oswald-source-sans-pro). I liked the look of this font as I think they fit with the spooky theme for the website. Source Sans Pro was unavailable on Google Fonts so I went with Source Sans 3 which is very similar.

### Colour Scheme
This is the colour scheme I used for this project. It was generated at [coolors.co](https://coolors.co/e6e8e6-9c072c-0e3449-c8963e-030406). I chose darker colours to keep to the spooky theme of the site with a brighter white for contrast.

![Colour Scheme](assets/images/readme/colour-scheme.png)

## Features:

### Navigation
The website consists of three sections (Home, About, Contact) with navigation elements that link to each.
When viewed on a mobile device, the navigation elements are condensed into a collapsed list.
A user can navigate to the about page by clicking the "our services" button on the homepage.
A user can navigate to the contact page by clicking the "Make an enquiry" button on the homepage.
After submitting the contact form, a user can return to the homepage by clicking the "Return to home" button.

#### Desktop Navbar
![Navbar Desktop](assets/images/readme/features/nav-desktop.png)

#### Mobile Navbar
![Navbar Mobile](assets/images/readme/features/nav-mobile.png)

### Footer
The footer on every page contains links to social media sites Facebook, Youtube, Instagram, and WhatsApp. The icons change colour when the user mouses over them to give some feedback.

![Footer](assets/images/readme/features/footer.png)

### Home Page
The home page shows a large callout section which grabs the users attention. It allows a user to click the "Our Services" or "Make an enquiry" buttons to go to the "About" and "Contact" pages.
When a user scrolls down, they can see some brief information about the services offered and some testimonials from previous customers.

![Home Page](assets/images/readme/features/homepage.png)

### About Page
The about page gives detailed information about each of the services allowing the user to find out more about each service and what can be expected.

![About Page](assets/images/readme/features/about-page.png)

### Contact Page
The contact page consists of a contact form which allows a user to enter their personal details, choose one or more of the services, and ask questions to the company. Once a user submits the form, they are taken to a page to confirm that the form has been submitted.

![Contact Page](assets/images/readme/features/contact-page.png)

### Contact-complete Page
This page confirms the submission of the contact form. It contains a brief "thank you" message and lets the user know that the company will contact them soon. This page ensures that the user is receiving feedback on the form submission. It then gives the user a link back to the homepage with the "back to home" button conveniently located.

![Contact Submitted Page](assets/images/readme/features/contact-complete-page.png)

### Map
A user can view the haunted locations offered by the company on the about page.

![Map](assets/images/readme/features/about-map.png)

### FAQ (Frequently Asked Questions)
The FAQ contains frequently asked questions that users may be wondering about. This allows a user to view questions and get quick answers. The FAQ is in an accordion style which keeps it condensed.

![FAQ](assets/images/readme/features/faq.png)

### Contact Form
A user can submit a contact form to learn more about or book one of the services offered.

![Contact Form](assets/images/readme/features/contact-form.png)

## Technologies Used
* HTML - used for structuring the website
* CSS - for style and layout
* Bootstrap - for style and layout
* Font Awesome - for icons
* Google Fonts - for the fonts
* Google Maps - for embedding an iFrame with the map on the about page
* Github - for hosting and deploying the website
* BrowserStack - for testing the website compatibility with different browsers
* Responsinator - to view website on different devices

## Testing
### Google's Lighthouse Performance
This section contains screenshots of the Home, About, and Contact pages lighthouse scores.
Each page has a mobile and desktop score. 

#### Home
#####  Mobile
![Home Mobile](assets/images/readme/testing/lighthouse/lighthouse-home-mob.png)

##### Desktop
![Home Desktop](assets/images/readme/testing/lighthouse/lighthouse-home-desk.png)

#### About
##### Mobile
![About Mobile](assets/images/readme/testing/lighthouse/lighthouse-about-mob.png)

##### Desktop
![About Desktop](assets/images/readme/testing/lighthouse/lighthouse-about-desk.png)

The about page 'Best Practices' section is showing a depreciated API error relating to the embedded google map.

#### Contact
##### Mobile
![Contact Mobile](assets/images/readme/testing/lighthouse/lighthouse-contact-mob.png)

##### Desktop
![Contact Desktop](assets/images/readme/testing/lighthouse/lighthouse-contact-desk.png)

### Browser Compatibility
#### Chrome
##### Desktop
![Chrome Test Desktop](assets/images/readme/testing/browser/chrome-desk-test.png)

Result: No issues

##### Mobile
![Chrome Test Mobile](assets/images/readme/testing/browser/chrome-mob-test.png)

Result: No issues

#### Firefox
##### Desktop
![Firefox Test Desktop](assets/images/readme/testing/browser/firefox-test.png)

Result: No issues

##### Mobile
![Firefox Test Desktop](assets/images/readme/testing/browser/firefox-mob-test.png)

Result: No issues

#### Safari
##### Desktop
![Safari Test Desktop](assets/images/readme/testing/browser/safari-test.png)

Result: No issues

##### Mobile
![Safari Test Mobile](assets/images/readme/testing/browser/safari-mob-test.png)

Result: The map on the about page overhangs onto the FAQ section. 
(Resolved) - No issues.

### Responsiveness
This section shows the website responsiveness on a mobile device, iPad, and desktop. You can see how the site adapts to the different screen sizes through these screenshots.

#### Home Page
##### Mobile
![Home iPhone](assets/images/readme/testing/responsiveness/mob-home.png)

##### iPad
![Home iPad](assets/images/readme/testing/responsiveness/home-ipad.png)

##### Desktop
![Home Desktop](assets/images/readme/testing/responsiveness/desktop-home.png)


#### About Page
##### Mobile
![Home Services](assets/images/readme/testing/responsiveness/about-mob.png)

##### iPad
![Home Services](assets/images/readme/testing/responsiveness/about-ipad.png)

##### Desktop
![Home Services](assets/images/readme/testing/responsiveness/desktop-services.png)

#### Contact Form
##### Mobile
![Contact Mobile](assets/images/readme/testing/responsiveness/mob-contact-form.png)

##### iPad
![Contact iPad](assets/images/readme/testing/responsiveness/ipad-contact-form.png)

##### Desktop
![Contact Desktop](assets/images/readme/testing/responsiveness/desktop-contact.png)

### Code Validation
#### HTML Validation
##### Home
![Home HTML](assets/images/readme/testing/html/home-html-valid.png)

Result: No Errors.

##### About
![About HTML](assets/images/readme/testing/html/about-html-valid.png)

Result: No Errors.

##### Contact
![Contact HTML](assets/images/readme/testing/html/contact-html-valid.png)

Result: No Errors.

##### Contact-Complete
![Contact Complete HTML](assets/images/readme/testing/html/contact-complete-html-valid.png)
Result: No Errors.

#### CSS Validation
![CSS Validation](assets/images/readme/testing/css/css-valid.png)

Result: No Errors.

### Manual Testing user stories or/and features
#### Testing for links, FAQ, and form
Test | Pass
--- | :---:
All navigation links lead to the correct pages  | &check;
Callout buttons lead to the correct pages  | &check;
Footer links open a new tab and lead to the correct sites  | &check;
FAQ accordion functions correctly  | &check;
Contact form doens't submit without entering information  | &check;
Contact form submits when required information is present  | &check;
Back to Home button takes user back to homepage | &check;

#### User Story Testing
Number | User Story |  Test | Pass
--- | --- | --- | :---:
1 | A user wants to browse available paranormal experiences so that I can see the different options available. | The user scrolls down to see the services offered | &check;
2 | A user wants to view detailed information about the paranormal experiences so that I can clearly understand what is included in each service. | The user clicks the Our Services button or the about navigation link. They then scroll down to view the detailed information. | &check;  
3 | A user wants to submit a contact form so that I can reach out to the organiser for more information or to book an experience. | The user clicks the make an enquiry button or the contact navigation link and fills out the contact form. | &check;
4 | A user wants to get directions to the haunted house locations where paranormal experiences take place. | The user clicks the Our Services button or the Our Services navigation link and scrolls down to the haunted house section. The user can see an interactive map and can click the directions arrow. | &check;
5 | A user wants to read an FAQ section to quickly find answers to common questions. | The user clicks the Our Services button or the about navigation link and scrolls down to the FAQ section. | &check;
6 | A user wants to view social media links so that they can follow or share the page with others. | The user scrolls to the bottom of any page and clicks the social media icon. | &check;

##### User stories testing screenshots
###### 1. Browse available paranormal experiences

![Services](assets/images/readme/user-stories/services.png)

###### 2. View detailed information about experiences offered.

![Services](assets/images/readme/user-stories/detailedservices.png)

###### 3. Submit a contact form.

![Contact Form](assets/images/readme/user-stories/contact1.png)
![Contact Form Submitted](assets/images/readme/user-stories/contact2.png)

###### 4. Get directions to to the haunted houses.

![Haunted House Directions](assets/images/readme/user-stories/map-directions.png)

###### 5. Read an FAQ section.

![FAQ](assets/images/readme/features/faq.png)

###### 6. View social media links.

![Social Links](assets/images/readme/user-stories/social-links.png)

## Bugs

Images not showing in services section.
- Was missing "assets/" from the file path.

FAQ 3, 4, 5 buttons expand/collapse all 3 together
- ID was set to "collapseThree" for all 3 buttons. Changing IDs fixed the problem. 

Removing bootstrap script stopped FAQ accordion functioning.
- Re-adding bootstrap scripts resumed functionality.

## Deployment
#### Creating Repository on GitHub
- First make sure you are signed into [Github](https://github.com/) and go to the code institutes template, which can be found [here](https://github.com/Code-Institute-Org/gitpod-full-template).
- Then click on **use this template** and select **Create a new repository** from the drop-down. Enter the name for the repository and click **Create repository from template**.
- Once the repository was created, I clicked the green **gitpod** button to create a workspace in gitpod so that I could write the code for the site.

#### Deloying on Github
The project was deployed using GitHub pages. The steps to deploy using GitHub pages are:

1. Go to the repository on [Github](https://github.com/)
2. Select **Settings** near the top of the page.
3. Select **Pages** from the menu bar on the left of the page.
4. Under **Source** select the 'Branch' dropdown menu and select the main branch.
5. Once selected, click the **Save**.
6. Deployment should be confirmed by a message saying "Your site is published at" followed by the web address.

## Credits
### Code & Text Content
  
  Using a linear gradient to make a background image darker without affecting the text - Arthur Serafim on stackoverflow: https://stackoverflow.com/questions/15765550/darkening-an-image-with-css-in-any-shape

### Media
  
    Index Hero-image: Photo by Karolina Kaboompics: https://www.pexels.com/photo/cloth-behind-window-in-darkness-5422603/

    Seance image: Taken from Wikimedia commons: https://commons.wikimedia.org/wiki/File:Weird_or_What_seance.JPG

    Ouijia board image: Photo by goodfriendo : https://www.flickr.com/photos/illuminated_photography/3151863727

    Haunted house image: Photo by Monica: https://www.flickr.com/photos/scorpio58/3548967552

    Sarah photo: Photo by Andrea Piacquadio: https://www.pexels.com/photo/woman-wearing-coat-762020/

    Pete photo: Photo by Brett Sayles: https://www.pexels.com/photo/man-in-grey-crew-neck-t-shirt-1073097/

    About Hero-image: Photo by: Kaboompics.com: https://www.pexels.com/photo/white-sheet-thrown-over-an-illuminated-pumpkin-to-make-a-ghost-decoration-for-halloween-5422596/

    Contact header backgroud: Photo by Oleksandr P: https://www.pexels.com/photo/close-up-of-wooden-surface-background-12932215/

    Contact background image: Photo by Ekaterina Astakhova: https://www.pexels.com/photo/black-metal-framed-glass-window-4147563/
    
### Acknowledgment
#### Antonio Rodriguez
> My mentor who provided me with constructive feedback and advice.