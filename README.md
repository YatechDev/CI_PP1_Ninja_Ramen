# Ninja Ramen 
(Developer: Mateusz Smalarz aka YatechDev)

![Mockup image](docs/responsiveness.png)

[Ninja Ramen - Live webpage](https://yatechdev.github.io/CI_PP1_Ninja_Ramen/) (Right click to open in new tab)

First project portfolio for Code Institute. A website for the imaginary Japanese restaurant based in Lincoln, UK.

## Table of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requirements and Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
3. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Fonts](#fonts)
    3. [Structure](#structure)
    4. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks & Tools](#frameworks-&-tools)
5. [Features](#features)
6. [Validation](#validation)
    1. [HTML Validation](#HTML-validation)
    2. [CSS Validation](#CSS-validation)
7. [Testing](#testing)
    1. [Accessibility](#accessibility)
    2. [Performance](#performance)
    3. [Device testing](#performing-tests-on-various-devices)
    4. [Browser compatibility](#browser-compatability)
    5. [Testing user stories](#testing-user-stories)
8. [Bugs](#Bugs)
9. [Deployment](#deployment)
10. [Credits](#credits)
11. [Acknowledgements](#acknowledgements)

## Project Goals

### User Goals
- Find a restaurant with oriental cuisine.
- Find a restaurant where you can eat good quality food.
- Find a place where you can spend time with family / friends in a nice atmosphere.
- Find a place where you can try something new / different.
- Find the restaurant localisation & contact details.
- Contact the restaurant through the page.
- Read about restaurant.
- Check the restaurant menu & prices.

### Site Owner Goals
- Promote the restaurant on the internet.
- Provide contact details for the users of the website.
- Provide the online form of contact.
- Show restaurant menu for existing and potential new customers.
- Provide links to the restaurant's social media.
- Make website responsive for mobile devices.
- Increase profit & amount of customers.

## User Experience

### Target Audience
- People who looking for a place to eat oriental cuisine.
- People who looking for a place to pend time with family / friends in a nice atmosphere.
- People who want to book a table for a meeting in a place with a high standard.
- People who are looking for a place to celebrate a birthday.
- People who want to organise parties & events.

### User Requirements and Expectations
- A website that is quick to load.
- Responsive website for mobile devices.
- Easy navigation system.
- A website where you can quickly and easily find the essential information.
- Easy to find the restaurant's menu with prices.
- Easy way to contact the restaurant online.
- Find links for social media.
- Simple and interesting content.

### User Stories

#### First-time users
1. As a first time user, I want to know what kind of cuisine is in restaurant.
2. As a first time user, I want to easily navigate the page.
3. As a first time user, I want to know the restaurant menu & prices.
4. As a first time user, I want to know the story about the restaurant.
5. As a first time user, I want to know where restaurant is located.
6. As a first time user, I want to know restaurant opening time.
7. As a first time user, I want to know the restaurant contact details.

#### Returning visitor
8. As a returning user, I want to quickly check the menu.
9. As a returning user, I want to know about any changes in opening times.
10. As a returning user, I want to check the contact details.
11. As a returning user, I want to check if restaurant have any social media.
12. As a returning user, I want to contact the restaurant online.
13. As a returning user, I want to check the phone number for quick contact the restaurant.
14. As a returning user, I want to quickly find the restaurant menu.

### Site owner
15. As a site owner, I want to show what kind of cuisine is in our restaurant.
16. As a site owner, I want users to easily navigate the website.
17. As a site owner, I want users to easily find the restaurant menu.
18. As a site owner, I want to provide contact details for users.
19. As a site owner, I want to provide online contact form.
20. As a site owner, I want to provide links to restaurant's social media.
21. As a site owner, I want to show pictures of the restaurant for users.

## Design

### Design Choices
As a design for the website, I did not use ready-made colour palettes, and instead, I decided to choose themed photos as
the background for each of the subpages.  
Each of the main subpages has its photo, with a layer blurring the background and emphasizing the content of the page.  
In addition, the navbar and footer are in grey shades that match the style of the rest of the site.

Below is a list of photos selected for each subpage.

<details><summary>Home</summary>
<img src="docs/backgrounds/bg-home.webp" alt="Background for Home-Page">
</details>

<details><summary>About</summary>
<img src="docs/backgrounds/bg-about.webp" alt="Background for About-Page">
</details>

<details><summary>Menu</summary>
<img src="docs/backgrounds/bg-menu.webp" alt="Background for Menu-Page">
</details>

<details><summary>Gallery</summary>
<img src="docs/backgrounds/bg-gallery.webp" alt="Background for Gallery-Page">
</details>

<details><summary>Contact</summary>
<img src="docs/backgrounds/bg-contact.webp" alt="Background for Contact-Page">
</details>

Pages "404" & "ThankYou" don't have specific photos, instead, they have a black background.


### Fonts
'Roboto' regular 400 - taken from Google Fonts and apply via @import method to CSS file.  
I chose this font because of its popularity, simplicity and ease of reading.

![FONT](docs/font.png)

### Structure

The website is constructed in one of the most frequently chosen and user-friendly ways. At the top of the page, there is
a navigation bar with links to other subpages, below the main content of the page and a footer at the bottom.

The website consists of five main pages and two additional pages.

- Home
- About
- Menu
- Gallery
- Contact

and

- 404 page
- Thank You page

### Wireframes
This is the prototype of the project that may change during its development.

<details><summary>Home</summary>
<img src="docs/wireframes/home.png" alt="Wireframe of Home-Page">
</details>
<details><summary>About</summary>
<img src="docs/wireframes/about.png" alt="Wireframe of About-Page">
</details>
<details><summary>Menu</summary>
<img src="docs/wireframes/menu.png" alt="Wireframe of Menu-Page">
</details>
<details><summary>Gallery</summary>
<img src="docs/wireframes/gallery.png" alt="Wireframe of Gallery-Page">
</details>
<details><summary>Contact</summary>
<img src="docs/wireframes/contact.png" alt="Wireframe of Contact-Page">
</details>

## Technologies Used

### Languages
- HTML 5
- CSS 3

### Frameworks & Tools
- [Balsamiq](https://balsamiq.com/) (create wireframes for the project)
- [GitHub](https://github.com/) (create, hold and deploy repository)
- [Git](https://git-scm.com/) (source code management)
- [WebStorm](https://www.jetbrains.com/webstorm/) (IDE use to build the website)
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/) (checking & testing the site)
- [W3C HTML Validator](https://validator.w3.org/) (validation of HTML code)
- [W3C JigSaw Validator](https://jigsaw.w3.org/css-validator/) (validation of CSS code)
- [Webaim](https://wave.webaim.org/) (accessibility & contrast checker)
- [Am I Responsive](https://ui.dev/amiresponsive) (website mockup)
- [Canva](https://www.canva.com/) (images, logo & other graphic elements)
- [Paint](https://www.getpaint.net/index.html) (images edit)
- [Freeconvert](https://www.freeconvert.com/jpg-to-webp) (convert jpg to webp format)
- [TinyPNG](https://tinypng.com/) (compress images)
- [Google Fonts](https://fonts.google.com/) (fonts)
- [Font Awesome](https://fontawesome.com/) (icons)
- [Favicon.io](https://favicon.io/) (favicon)
- [Evernote](https://evernote.com/) (notes, screenshots)
- [Grammarly](https://www.grammarly.com/) (typography)

## Features

### Navigation Bar
![NAVBAR](docs/features/feat-navbar.png)
The navigation bar is present on all subpages of the website, it is easily noticeable, intuitive and easy to use. The
navigation bar highlights the selected page where the user is located.
On the left side, there is a logo that, when clicked, leads to the main page. The navigation bar is responsive to mobile
devices - it then turns into a common in-use "hamburger menu".

- User Stories covered: 2, 14, 16, 17

### Hero Section & Restaurant Goals
![HERO SECTION](docs/features/feat-hero_section.png)
![Restaurant Goals](docs/features/feat-restaurant_goals.png)
The section on the main page is a first eye-catcher. It contains a short description of the restaurant,
thanks to which the user learns what cuisine the restaurant has to offer.
In the section, we can see two buttons that lead to the menu of the restaurant and additional information about the
restaurant.
The section also includes logos and photo thumbnails for attention and additional visual effect.  

Immediately below the section, there are restaurant goals, which are quick to read and are designed to arouse the
curiosity and interest of the user to continue browsing the site and take advantage of the restaurant's offer.

- User Stories covered: 1, 8, 14, 15, 17

### Footer
![FOOTER](docs/features/feat-footer.png)
Footer, like the navigation bar, is present on all subpages and is responsive to mobile devices. It contains links to
restaurant's profile on the most popular social media, opening hours, contact details and copyrights.  
Links to social media are shown as icons, making it easy to find a platform that interests the user.
The links open in a new browser tab, so the user stays on the restaurant's website.

- User Stories covered: 5, 6, 7, 9, 10, 11, 13, 18, 20

### About Us
![ABOUT](docs/features/feat-about_us.png)
The "about us" section gives the user a greater description of the restaurant, and a short history and encourages the
organization of meetings and events in the restaurant.

- User Stories covered: 1, 4, 5

### Menu
![MENU](docs/features/feat-menu.png)
The section contains the restaurant's menu and is divided into categories. Each of the categories contains a drawing of
the dish, which is hidden on mobile devices to ensure greater comfort in viewing the offer.  
Each dish has a short description and price.

- User Stories covered: 1, 3, 8, 15

### Gallery & Video
![GALLERY](docs/features/feat-gallery.png)
![VIDEO](docs/features/feat-video.png)
A section where the user can see photos of both meals and the interior of the restaurant.
The photos are in grayscale, but when you hover over one of them, it zooms in and shows in full colour. This gives an
interesting visual effect to the user.  
Below is a short promotional video to encourage the user to take advantage of the restaurant's offer.


- User Stories covered: 1, 15, 21

### Contact Section
![CONTACT SECTION](docs/features/feat-contact_section.png)
Section where you can find a contact form that allows you to freely contact the restaurant online.  
Next to the form, the user can find a map that shows exactly where the restaurant is located.

- User Stories covered: 12, 19

### 404 Page
![CONTACT SECTION](docs/features/feat-404_page.png)
The 404 page is the page for displaying the HTTP 404 error message. It informs the user that there is no resource at the
URL entered.  
This page has all the navigation, footer and an easily visible button thanks to which the user can quickly return to the
home page.

### Thank You - Page
![CONTACT SECTION](docs/features/feat-thankyou_page.png)
This page displays after submitting the form and informs the user that his inquiry or message has been successfully
sent.  
This page has all the navigation, footer and an easily visible button thanks to which the user can quickly return to the
home page.

### Favicon & Name on tab
![CONTACT SECTION](docs/features/feat-page_card.png)  
Each of the subpages has a favicon, the name of the restaurant and the subpage on which the user is currently located.
Thanks to these additions, the user can easily locate the opened tab among others in his browser.

## Validation

### HTML Validation

I used "W3C Markup Validation Service" to validate the code.  
I validated each of the subpages and no error was found on any of them.

<details><summary>Home</summary>
<img src="docs/validation/validation-home.png" alt="Validation of Home-Page">
</details>

<details><summary>About</summary>
<img src="docs/validation/validation-about.png" alt="Validation of About-Page">
</details>

<details><summary>Menu</summary>
<img src="docs/validation/validation-menu.png" alt="Validation of Menu-Page">
</details>

<details><summary>Gallery</summary>
<img src="docs/validation/validation-gallery.png" alt="Validation of Gallery-Page">
</details>

<details><summary>Contact</summary>
<img src="docs/validation/validation-contact.png" alt="Validation of Contact-Page">
</details>

<details><summary>404</summary>
<img src="docs/validation/validation-404.png" alt="Validation of 404-Page">
</details>

<details><summary>ThankYou</summary>
<img src="docs/validation/validation-thankyou.png" alt="Validation of ThankYou-Page">
</details>

### CSS Validation

I used "W3C CSS Validation Service" to validate the CSS code.

I have performed two validations:

1. The Whole page showed errors and alerts related to imported CSS stylesheet from Font Awesome but showed no errors with my
   CSS.

<details><summary>Whole Page</summary>
<img src="docs/validation/validation_whole_page_css.png" alt="Validation of Whole Page CSS">
</details>

2. During the second validation I loaded my CSS file and the program did not find any errors related to my code, it only
   suggested that the imported CSS sheet (google font) was not checked.

<details><summary>My CSS file</summary>
<img src="docs/validation/validation-my_css.png" alt="Validation of My CSS file">
</details>

## Testing

### Accessibility

I used "The WAVE WebAIM web accessibility evaluation tool" to test the code for accessibility.  
The first test I conducted detected an error on each of the subpages. The label I used to create the "hamburger menu"
had empty content and this was causing an accessibility error. The problem has been solved and described in the "Bugs" section, and
new tests have been carried out, which showed no errors with the accessibility on the site.

<details><summary>Home</summary>
<img src="docs/accessibility/access-home.png" alt="Accessibility of Home-Page">
</details>

<details><summary>About</summary>
<img src="docs/accessibility/access-about.png" alt="Accessibility of About-Page">
</details>

<details><summary>Menu</summary>
<img src="docs/accessibility/access-menu.png" alt="Accessibility of Menu-Page">
</details>

<details><summary>Gallery</summary>
<img src="docs/accessibility/access-gallery.png" alt="Accessibility of Gallery-Page">
</details>

<details><summary>Contact</summary>
<img src="docs/accessibility/access-contact.png" alt="Accessibility of Contact-Page">
</details>

<details><summary>404</summary>
<img src="docs/accessibility/access-404.png" alt="Accessibility of 404-Page">
</details>

<details><summary>ThankYou</summary>
<img src="docs/accessibility/access-thankyou.png" alt="Accessibility of ThankYou-Page">
</details>

### Performance

To test the performance on the website, I used Google Lighthouse in Google Chrome Developer Tools.
The test was carried out on all subpages, both for computers and mobile devices.  
Below is a list of screenshots:

<details><summary>Home</summary>
<img src="docs/performance/home-desktop.png" alt="Performance of Home-Page">
</details>

<details><summary>Home - mobiles</summary>
<img src="docs/performance/home-mobile.png" alt="Performance of Home-Page">
</details>

<details><summary>About</summary>
<img src="docs/performance/about-desktop.png" alt="Performance of About-Page">
</details>

<details><summary>About - mobiles</summary>
<img src="docs/performance/about-mobile.png" alt="Performance of About-Page">
</details>

<details><summary>Menu</summary>
<img src="docs/performance/menu-desktop.png" alt="Performance of Menu-Page">
</details>

<details><summary>Menu - mobiles</summary>
<img src="docs/performance/menu-mobile.png" alt="Performance of Menu-Page">
</details>

<details><summary>Gallery</summary>
<img src="docs/performance/gallery-desktop.png" alt="Performance of Gallery-Page">
</details>

<details><summary>Gallery - mobiles</summary>
<img src="docs/performance/gallery-mobile.png" alt="Performance of Gallery-Page">
</details>

<details><summary>Contact</summary>
<img src="docs/performance/contact-desktop.png" alt="Performance of Contact-Page">
</details>

<details><summary>Contact - mobiles</summary>
<img src="docs/performance/contact-mobile.png" alt="Performance of Contact-Page">
</details>

<details><summary>404</summary>
<img src="docs/performance/404-desktop.png" alt="Performance of 404-Page">
</details>

<details><summary>404 - mobiles</summary>
<img src="docs/performance/404-mobile.png" alt="Performance of 404-Page">
</details>

<details><summary>ThankYou</summary>
<img src="docs/performance/thankyou-desktop.png" alt="Performance of ThankYou-Page">
</details>

<details><summary>ThankYou - mobiles</summary>
<img src="docs/performance/thankyou-mobile.png" alt="Performance of ThankYou-Page">
</details>

### Performing tests on various devices
The website was tested on devices such as:

- MSI Katana GF76 17.3"
- ASUS TUF Dash F15 15.6"
- iPhone 11 PRO
- iPhone XR
- Xiaomi Redmi Note 9
- Samsung Galaxy Tab A (landscape & portrait mode)

### Browser compatability
The website has been tested on the following browsers:
- Google Chrome
- Chromium
- Mozilla Firefox
- Opera
- Microsoft Edge
- Safari

### Testing user stories

1. As a first time user, I want to know what kind of cuisine is in restaurant.

| **Feature**                     | **Action**                          | **Expected Result**                                                                  | **Actual Result** |
|---------------------------------|-------------------------------------|--------------------------------------------------------------------------------------|-------------------|
| Hero Section & Restaurant Goals | First section displayed on the page | User can see straight away and read what type of cuisine he can expect in restaurant | PASS              |
| Menu                            | Check the menu                      | Find what type of food restaurant has to offer                                       | PASS              |
| Gallery                         | Click on the gallery                | User is able to see some examples of the meals                                       | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-1-1.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-1-2.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-1-3.png" alt="Screenshot of testing user-stories">
</details>

2. As a first time user, I want to easily navigate the page.

| **Feature**    | **Action**             | **Expected Result**                                                                                                                          | **Actual Result** |
|----------------|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| Navigation Bar | Click on logo or links | Navbar is <strong>easy to see and use.</strong> While scrolling, the page is always at the top. The logo on the left leads to the home page. | PASS              |
| Buttons        | Click on the button    | User can find buttons in hero section, 404 and thankyou page for improved site navigation                                                    | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-2-1.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-2-2.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-2-3.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-2-4.png" alt="Screenshot of testing user-stories">
</details>

3. As a first time user, I want to know the restaurant menu & prices.

| **Feature**  | **Action**                             | **Expected Result**                                      | **Actual Result** |
|--------------|----------------------------------------|----------------------------------------------------------|-------------------|
| Menu Subpage | Click button / link to go to menu page | User can easily find the positions in the menu & prices. | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-3-1.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-3-2.png" alt="Screenshot of testing user-stories">
</details>

4. As a first time user, I want to know the story about the restaurant.

| **Feature**      | **Action**                     | **Expected Result**                                          | **Actual Result** |
|------------------|--------------------------------|--------------------------------------------------------------|-------------------|
| Restaurant Goals | Scroll down on home page       | User can see information about restaurant goals.             | PASS              |
| About subpage    | Click on "About" on the navbar | User can see more detailed information about the restaurant. | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-4-1.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-4-2.png" alt="Screenshot of testing user-stories">
</details>

5. As a first time user, I want to know where restaurant is located.

| **Feature** | **Action**                       | **Expected Result**                                      | **Actual Result** |
|-------------|----------------------------------|----------------------------------------------------------|-------------------|
| Google Map  | Click on "Contact" on the navbar | User can see Google Map with pinned restaurant location. | PASS              |
| Footer      | Scroll down on any page          | User can see the address of the restaurant.              | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-5-1.png" alt="Screenshot of testing user-stories">
</details>

6. As a first time user, I want to know restaurant opening time.

| **Feature** | **Action**              | **Expected Result**                               | **Actual Result** |
|-------------|-------------------------|---------------------------------------------------|-------------------|
| Footer      | Scroll down on any page | User can see the opening hours of the restaurant. | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-6-1.png" alt="Screenshot of testing user-stories">
</details>

7. As a first time user, I want to know the restaurant contact details.

| **Feature** | **Action**              | **Expected Result**                         | **Actual Result** |
|-------------|-------------------------|---------------------------------------------|-------------------|
| Footer      | Scroll down on any page | User can see the details of the restaurant. | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-7-1.png" alt="Screenshot of testing user-stories">
</details>

8. As a returning user, I want to quickly check the menu.

| **Feature**  | **Action**                           | **Expected Result**                   | **Actual Result** |
|--------------|--------------------------------------|---------------------------------------|-------------------|
| Menu subpage | Click on "Menu" on the Navbar        | User can quickly move to menu section | PASS              |
| Menu button  | Click on "View Menu" in Hero Section | User can quickly move to menu section | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-8-1.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-8-2.png" alt="Screenshot of testing user-stories">
</details>

9. As a returning user, I want to know about any changes in opening times.

| **Feature** | **Action**              | **Expected Result**                               | **Actual Result** |
|-------------|-------------------------|---------------------------------------------------|-------------------|
| Footer      | Scroll down on any page | User can see the opening hours of the restaurant. | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-9-1.png" alt="Screenshot of testing user-stories">
</details>

10. As a returning user, I want to check the contact details.

| **Feature** | **Action**              | **Expected Result**                                 | **Actual Result** |
|-------------|-------------------------|-----------------------------------------------------|-------------------|
| Footer      | Scroll down on any page | User can see the contact details of the restaurant. | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-10-1.png" alt="Screenshot of testing user-stories">
</details>

11. As a returning user, I want to check if restaurant have any social media.

| **Feature** | **Action**              | **Expected Result**                                  | **Actual Result** |
|-------------|-------------------------|------------------------------------------------------|-------------------|
| Footer      | Scroll down on any page | User can see the links for restaurant's social media | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-11-1.png" alt="Screenshot of testing user-stories">
</details>

12. As a returning user, I want to contact the restaurant online.

| **Feature**  | **Action**                       | **Expected Result**                                                      | **Actual Result** |
|--------------|----------------------------------|--------------------------------------------------------------------------|-------------------|
| Contact form | Click on "Contact" on the Navbar | User can quickly move to the contact section and see online contact form | PASS              |


<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-12-1.png" alt="Screenshot of testing user-stories">
</details>

13. As a returning user, I want to check the phone number for quick contact the restaurant.

| **Feature** | **Action**              | **Expected Result**                        | **Actual Result** |
|-------------|-------------------------|--------------------------------------------|-------------------|
| Footer      | Scroll down on any page | User can see the restaurant's phone number | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-13-1.png" alt="Screenshot of testing user-stories">
</details>

14. As a returning user, I want to quickly find the restaurant menu.

| **Feature**  | **Action**                           | **Expected Result**                   | **Actual Result** |
|--------------|--------------------------------------|---------------------------------------|-------------------|
| Menu subpage | Click on "Menu" on the Navbar        | User can quickly move to menu section | PASS              |
| Menu button  | Click on "View Menu" in Hero Section | User can quickly move to menu section | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-14-1.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-14-2.png" alt="Screenshot of testing user-stories">
</details>

15. As a site owner, I want to show what kind of cuisine is in our restaurant.

| **Feature**                     | **Action**                          | **Expected Result**                                                                  | **Actual Result** |
|---------------------------------|-------------------------------------|--------------------------------------------------------------------------------------|-------------------|
| Hero Section & Restaurant Goals | First section displayed on the page | User can see straight away and read what type of cuisine he can expect in restaurant | PASS              |
| Menu                            | Check the menu                      | Find what type of food restaurant has to offer                                       | PASS              |
| Gallery                         | Click on the gallery                | User is able to see some examples of the meals                                       | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-15-1.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-15-2.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-15-3.png" alt="Screenshot of testing user-stories">
</details>

16. As a site owner, I want users to easily navigate the website.

| **Feature**    | **Action**             | **Expected Result**                                                                                                                          | **Actual Result** |
|----------------|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| Navigation Bar | Click on logo or links | Navbar is <strong>easy to see and use.</strong> While scrolling, the page is always at the top. The logo on the left leads to the home page. | PASS              |
| Buttons        | Click on the button    | User can find buttons in hero section, 404 and thankyou page for improved site navigation                                                    | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-16-1.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-16-2.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-16-3.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-16-4.png" alt="Screenshot of testing user-stories">
</details>

17. As a site owner, I want users to easily find the restaurant menu.

| **Feature**  | **Action**                           | **Expected Result**                   | **Actual Result** |
|--------------|--------------------------------------|---------------------------------------|-------------------|
| Menu subpage | Click on "Menu" on the Navbar        | User can quickly move to menu section | PASS              |
| Menu button  | Click on "View Menu" in Hero Section | User can quickly move to menu section | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-17-1.png" alt="Screenshot of testing user-stories">
<img src="docs/user-stories/story-17-2.png" alt="Screenshot of testing user-stories">
</details>

18. As a site owner, I want to provide contact details for users.

| **Feature** | **Action**              | **Expected Result**                                | **Actual Result** |
|-------------|-------------------------|----------------------------------------------------|-------------------|
| Footer      | Scroll down on any page | User can see the contact details of the restaurant | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-18-1.png" alt="Screenshot of testing user-stories">
</details>

19. As a site owner, I want to provide online contact form.

| **Feature**  | **Action**                       | **Expected Result**                                                      | **Actual Result** |
|--------------|----------------------------------|--------------------------------------------------------------------------|-------------------|
| Contact form | Click on "Contact" on the Navbar | User can quickly move to the contact section and see online contact form | PASS              |


<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-19-1.png" alt="Screenshot of testing user-stories">
</details>

20. As a site owner, I want to provide links to restaurant's social media.

| **Feature** | **Action**              | **Expected Result**                                  | **Actual Result** |
|-------------|-------------------------|------------------------------------------------------|-------------------|
| Footer      | Scroll down on any page | User can see the links for restaurant's social media | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-20-1.png" alt="Screenshot of testing user-stories">
</details>

21. As a site owner, I want to show pictures of the restaurant for users.

| **Feature**     | **Action**                       | **Expected Result**                                            | **Actual Result** |
|-----------------|----------------------------------|----------------------------------------------------------------|-------------------|
| Gallery subpage | Click on "Gallery" on the Navbar | User can quickly move to Gallery section and see the pictures  | PASS              |

<details><summary>Screenshots</summary>
<img src="docs/user-stories/story-21-1.png" alt="Screenshot of testing user-stories">
</details>

<hr>

## Bugs
1.

| **Bug**                                                  | **Fix**                                                                          |
|----------------------------------------------------------|----------------------------------------------------------------------------------|
| Font Awesome icons are not displaying on Safari browser. | Remove link for Font Awesome script, link css stylesheet and make local library. |

Tested on iPhone 11 PRO & iPhone XR

<details><summary>Before</summary>
<img src="docs/bugs/icons-before.PNG" alt="Screenshot of bug with icons">
</details>
<details><summary>After</summary>
<img src="docs/bugs/icons-after.PNG" alt="Screenshot for fixed icons">
</details>

2.

| **Bug**                                     | **Fix**                                             |
|---------------------------------------------|-----------------------------------------------------|
| Hovered images are covered by other images. | Set position for relative and use z-index property. |

<details><summary>Before</summary>
<img src="docs/bugs/hover-before.png" alt="Screenshot of bug with hovered image">
</details>
<details><summary>After</summary>
<img src="docs/bugs/hover-after.png" alt="Screenshot for fixed hovered image">
</details>

3.

| **Bug**                                            | **Fix**               |
|----------------------------------------------------|-----------------------|
| Navbar after scrolling is covered by page content. | Use z-index property. |

<details><summary>Before</summary>
<img src="docs/bugs/navbar-before.png" alt="Screenshot of bug covered navbar">
</details>
<details><summary>After</summary>
<img src="docs/bugs/navbar-after.png" alt="Screenshot for fixed navbar">
</details>

4.

| **Bug**                                                       | **Fix**                                 |
|---------------------------------------------------------------|-----------------------------------------|
| Lost responsiveness of contact.html after changing html code. | Use correct class name in css document. |

<details><summary>Before</summary>
<img src="docs/bugs/contact_section-before.png" alt="Screenshot of bug with contact.html responsiveness">
</details>
<details><summary>After</summary>
<img src="docs/bugs/contact_section-after.png" alt="Screenshot for fixed responsiveness of contact.html">
</details>

5.

| **Bug**                                                                      | **Fix**                                                                                        |
|------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| Error with accessibility across the pages. Empty label for "hamburger menu". | Add < span > with text inside the label across the pages and use "display: none;" in css file. |

<details><summary>Before</summary>
<img src="docs/bugs/accessibility-before.png" alt="Screenshot of error with accessibility check.">
</details>
<details><summary>After</summary>
<img src="docs/bugs/accessibility-after.png" alt="Screenshot for fixed accessibility check error">
</details>


## Deployment
The website was deployed on GitHub by using following steps:
1. Login into GitHub and locate the repository - [CI_PP1_Ninja_Ramen](https://github.com/YatechDev/CI_PP1_Ninja_Ramen)
2. At the top of repository locate the "settings" button and click on it.
3. Now on the left sidebar find locate the "pages" button and click on it.
4. Under source heading click on the branch dropdown menu and select: master.
5. Click save.
6. You will receive link to your deployed repository like on the screen below.

![GitHub Pages](docs/github-pages.png)

Forking the GitHub repository:
1. Login into GitHub and locate the repository - [CI_PP1_Ninja_Ramen](https://github.com/YatechDev/CI_PP1_Ninja_Ramen)
2. At the top of repository in right corner locate the "fork" button and click on it.
3. Choose where you want to save your forked repository.

## Credits
1. [CI TEMPLATE](https://github.com/Code-Institute-Org/gitpod-full-template) - This repository was created using the template proposed by Code Institute
2. [Canva](https://www.canva.com/) - All photos and graphics are from Canva and are used under a license I have. I made most of the graphic elements
   myself using this program.
3. [JetBrains](https://www.jetbrains.com/webstorm/) - I use their software - WebStorm - as my main IDE.
4. [Animated Label - Tutorial](https://www.youtube.com/watch?v=524ycUqs3f0) - This tutorial taught me how to make
   animated labels for form input. I partially modified the code, although the idea is taken from this tutorial.
5. [Pretty Sticky](https://codepen.io/BurmesePotato/pen/qBbqpNB) - This code inspired me to create the menu section. It
   has been modified in large part by me, although the idea and the skeleton come from here.
6. [Code Institute](https://codeinstitute.net/) - As the main source of my knowledge.
7. [ZTM](https://zerotomastery.io/), [CodeCademy](https://www.codecademy.com/), [EduWeb](https://eduweb.pl/)
   , [Strefa Kursow](https://strefakursow.pl/) - As additional places where I often do additional courses and enrich my
   knowledge.

## Acknowledgements
Huge thanks to:
- Mo Shami - For being a great mentor I'm lucky enough to have. For his amazing guidance, support, tips and feedback.
- To My amazing wife Karolina, who supported me during the whole process of learning and creating the project, allowed
  me to focus on my work and keep me motivated to act all the time.
- To my family and friends - for being a great support and for their motivation.
- The entire Code Institute community on slack for great understanding and motivation every day!