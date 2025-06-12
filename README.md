# Ashley Zeal

Ashley Zeal is a landing page that aims to expand Ashley Zeals online presence as an artist. Ashley Zeal's landing page will serve as a hub where users can easily view and engage in Ashley's content. It will showcase Ashley Zeal's discography, a gallery containing photos and videos from previous events, a biography and a contact form.

The purpose of this landing page is to expand Ashley Zeal's online presence while maintaing a professional theme and maintaining and easy-to-navigate/easy-to-use page for users.

## Contents

- [User Goals](#user-goals)
- [User Stories](#user-stories)
- [Goals & Objectives of website](#-goals-and-objectives-of-the-website)
- [Wireframes](#wireframes)
- [Design](#design)
  - [Typography](#typography)
  - [Colour Scheme](#colour-scheme)
  - [Images video](#images-video)
  * [Audio](#audio)
  - [Responsiveness](#responsiveness)

* [Features](#features)
  - [Existing Features](#existing-features)
    - [Header and Navbar](#header-and-navbar)
    - [Discography](#discography)
    - [Gallery](#gallery)
    - [Biography](#biography)
    - [Contact Form](#contact-form)
    - [Footer and socials](#footer-and-socials)
  - [Future Updates](#future-updates)
* [Technologies Used](#technologies-used)
  - [Languages](#languages)
  - [Libraries and Framework](#libraries-and-framework)
  - [Tools](#tools)
* [Testing](#testing)
  - [Bugs fixed](#bugs-fixed)
  - [Responsiveness Tests](#responsiveness-tests)
  - [Code Validation](#code-validation)
    - [HTML](#html)
    - [CSS](#css)
  - [User Story Testing](#user-story-testing)
  - [Features Testing](#features-testing)
  - [Accessibility Testing](#accessibility-testing)
  - [Lighthouse Testing](#lighthouse-testing)
  - [Browser Testing](#browser-testing)
* [Deployment](#deployment)
  - [Deploy Project](#deploy-project)
  - [Fork Project](#fork-projet)
  - [Clone Project](#clone-project)
* [Credits](#credits)

## User Goals

- User friendly navigation
- Professional & consistent style/theme
- Written in english
- Responsiveness for different screen sizes

## User Stories

- As a user, I want to be able to view new releases and listen to them.
- As a user, I want to be able to contact/book Ashley Zeal for events.
- As a user, I want to be able to view content from events Ashley Zeal has performed at.
- As a user, I want to be able to learn more about what inspires Ashley's music and his story.
- As a user, I want to be able to use the website on different devices.
- As a user, I want Ashley Zeal's social handles to keep up to date with social media posts.
- As a user, I want clear, intuitive navigation.
- As a user, I want the content to be accessible for people with additional needs.

[Back to Top](#contents)

## Goals & Objectives of Website

- Provide users with entertainment whilst keeping up to date with Ashley Zeal's current events and music.
- Include or provide access to all of Ashley Zeal's discography.
- Provide accurate content.
- Easy-to-use and easy to navigate to cater for different audiences.
- Invite users to use booking/contact form to book Ashley Zeal for events.
- Intergrate accessibility features for user with additional needs.
- Increase overall website traffic by increasing rankings on search engine.

## Target Audience

- Fans of Ashley Zeal
- Music enthusiasts
- Music Industry professionals
- Casual users

[Back to Top](#contents)

## Wireframes

The wireframes are designed using Balsamiq tool. I will follow best practices and design mobile first, then tablet and lastly desktop/laptop display. It is a one page website to enhance logical flow.

- [Mobile Wireframe](docs/mobile-wireframe.pdf)
- [Tablet Wireframe](docs/tablet-wireframe.pdf)
- [Desktop Wireframe](docs/desktop-wireframe.pdf)

[Back to Top](#contents)

## Design

### Typography

I have chosen two font-families to use for Ashley Zeal's website. The first font-family I chose [Baumans](https://fonts.google.com/specimen/Baumans). It is a sans-serif font with an geometric, Artistic feel. I picked Baumans as the primary font I will be using for headings and buttons as it is a clean, stylish and easy-to-read font making it ideal to use for web design.

The second font-family I have chosen to use is [Savate](https://fonts.google.com/specimen/Savate). I chose this font to use for text like paragraphs or captions. It is also a sans-serif type font however, it has a more expressive, cursive style whilst maintaining being easy-to-read making it ideal to use in web design.

### Colour Scheme

The colour scheme was chosen based off images used throughout the site and colours commonly associated with rnb and soul music, (two genre's of music Ashley Zeal is known for).

![colour scheme](docs/colour-scheme.png)

I have also used [Contrast Grid](https://contrast-grid.eightshapes.com/ "Contrast Grid") to help decide a visually appealing combination.

![Contrast Grid](docs/contrast-grid.png)

| CSS Name           | HEX     | Comment                                                            |
| ------------------ | ------- | ------------------------------------------------------------------ |
| --platinum         | #EAE6E5 | Font colour for paragraph or caption like text and card background |
| --silver-lake-blue | #7392B7 | Button colour                                                      |
| --chrysler-blue    | #0000E1 | Highlight colour, button text colour                               |
| --tigers-eye       | #B66D0D | Font colour for headings and titles                                |
| --night            | #0A090C | Background colour of the site                                      |

[Back to Top](#contents)

### Images video

Ashley Zeal has provided images and videos he would like to include on the website. The images has a mix of professional studio shots and performace shots. The video is a performance of Ashley singing at an event.

### Audio

I will embed spotify player into the discography section where users are able to play Ashley Zeal's music and also be invited to follow him on spotify and/or copy song links.

### Responsiveness

Ashley Zeal's website will be responsive to different screen sizes depending what device the user is viewing the site on. This will allow users to view site as intended. I will use CSS media queries to achieve this and I will use breakpoints from Bootstrap (See image below).

![Bootstrap breakpoints](docs/breakpoints.png)

[Back to Top](#contents)

## Features

I will keep the layout of the site minimalistic and simple, whilst using intuitive navigation to make the site easy to use. I will also adhere to best practices when formatting and styling the site. Users will be easily able to navigate the different sections of the site using the navbar. Users will be able to use the spotify player to listen to Ashley Zeal's music. I will also include a video player and an image carousel on the gallery for users to view. I have included these interactive features to increase user engagement throughout the site.

### Existing features

#### Header and Navbar

Ashley Zeal's webpage will have a header and navbar that will be reponsive to device sizes (see images below). It will contain links to biography section, gallery section, discography section and contact section and will direct users to their desired section of the site onclick.

#### Discography

Ashley Zeal's webpage will have a discography section that will contain a spotify player so users can listen to music (see images below). The player will invite users to follow Ashley Zeal on spotify and provide users with a link to the song on spotify. I will also include links to other digital streaming platforms for users who don't possess a spotify account.

#### Gallery

Ashley Zeal's webpage will have a gallery section(see images below). It will contain a carousel (slideshow component) using [Bootstrap](https://getbootstrap.com/docs/5.3) and a media player also using Bootstrap for users to view.

#### Biography

Ashley Zeal webpage will have a biography section (see images below). It will just contain Ashley Zeal's logo and a paragraph element for users to read Ashley Zeal's biography.

### Contact Form

Ashley Zeal's webpage will have a contact form section for users to book Ashley Zeal for events (see images below). I will use [Bootstrap](https://getbootstrap.com/docs/5.3) for the form. On completion of the form users will be directed to a success page (see image below) to notify them the form has been completed and sent successfully.

#### Footer and Socials

Ashley Zeal's webpage will have a footer section (see images below). It will contain favicons that will direct users to Ashley Zeal's social media profiles when clicked.

### Future Updates

- Sticky music player so users can enjoy Ashley Zeal's music while browsing the site.
- A section for users to buy merch and tickets to events.
- A section for users to sign up and enter name and email to receive updates and promotional content directly from Ashley Zeal whilst providing Ashley Zeal to engage with users.

[Back to Top](#contents)

## Technologies Used

### Languages

- [HTML](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

### Libraries and Framework

- [Bootstrap](https://getbootstrap.com/)
- [Google fonts](https://fonts.google.com/)
- [Favicon](https://favicon.io/favicon-converter/)
- [Font Awesome](https://fontawesome.com/)

### Tools

- [Github](https://github.com/)
- [Balsamiq](https://balsamiq.com/wireframes/)
- [HTML Validation](https://validator.w3.org/)
- [CSS Validation](https://jigsaw.w3.org/css-validator/)
- [Image Resize](https://www.iloveimg.com/)
- [Google Forms](https://docs.google.com/forms/d/1Gqmx-HY9NAIf_ZpOSxjR_WMybNn-MgB_fLwkIXsZO-Y/edit)
- [Am I Responsive](https://ui.dev/amiresponsive?url=https://micahindigo.github.io/ashley-zeal-website/https://ui.dev/amiresponsive?url=https://micahindigo.github.io/ashley-zeal-website/)

[Back to Top](#contents)

## Testing

### Bugs Fixed

### Responsiveness Tests

I used Am I responsive to test responsiveness of site. When building the site, I used the mobile-first strategy and verified all my changes using Google dev-tools. After conducting the responsiveness test I did not make any modifications as I am happy with the responsiveness of the website at different breakpoints.

Final Test Results:

| Size | Device Example     | Navigation | Element Alignments | Content Placement | Functionality | Notes                                             |
| ---- | ------------------ | ---------- | ------------------ | ----------------- | ------------- | ------------------------------------------------- |
| sm   | iPhone 11 PRO      | Good       | Good               | Good              | Good          |                                                   |
| md   | iPad Air           | Good       | Good               | Good              | Good          |                                                   |
| lg   | iPad Pro           | Good       | Good               | Good              | Good          |                                                   |
| xl   | Mackbook Air       | Good       | Good               | Good              | Good          |                                                   |
| xxl  | Desktop            | Good       | Good               | Good              | Good          |                                                   |

[Back to top](#contents)


### Code Validation

#### HTML

#### CSS

### User Story Testing

### Features Testing

### Accessibility Testing

### Lighthouse Testing

### Browser Testing

## Deployment

### Deploy Project

I will deploy Ashley Zeal website early on in the web design process using Github pages via the steps below:

1. Navigate to repository on Github and click **Settings**.
2. Once in settings, select **Pages** in the side navigation.
3. In the none dropdown, select **Main**.
4. Click on **Save** button.
5. The website is now live at https://micahindigo.github.io/ashley-zeal-website/

_Any changes required for the website, can be made, comitted and pushed to Github._

[Back to Top](#contents)

### Fork Project

Forking the Github repository allows you to duplicate the local repository so changes/modifications can be made to the duplicate repository without compromising the original repository.

1. Login to **Github**
2. Locate the repository.
3. Click to open it.
4. Locate the **fork** button on the **right** side of the mennu.
5. To copy the repository to your Github account, **click** button.

### Clone Project

1. Login to **Github**.
2. Navigate to **Main** page of repository and click **Code**.
3. **Copy URL** of repository.
4. Open your **IDE**.
5. Change current working directory to location you want the cloned directory.
6. Type Git clone and then paste the URL you copied earlier.
7. Press **Enter** to create your local clone.

[Back to Top](#contents)

## Credits
