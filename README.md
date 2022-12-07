# Barber Shop

The [Barbershop Website](https://flashdrag.github.io/barber-shop) is a site for Successful Barbershop Business.

The website provides users with information about barbershop services and their cost. It's targeted toward people who are looking for a high quality haircut, beard trim or shave. Using a special form, the user can book a date and time for a haircut and/or other available service. After booking the service, user also can find the location of the Barbershop itself on the Google Map.
![Responsive Mockup](documentation/supp-images/amiresponsive.png)

## Table of Contents

- [**Project Goals**](#project-goals)
  - [Bussiness Goals](#bussines-goals)
  - [User Goals](#user-goals)
- [**User Experience UX**](#user-experience-ux)
  - [Wireframes](#wireframes)
  - [Site Structure](#site-structure)
  - [Design Choices](#design-choices)
    - [Typography](#typography)
    - [Color Scheme](#color-scheme)
    - [Images](#images)
- [**Features**](#features)
  - [Header](#header)
  - [NavBar](#navigation-bar)
  - [Services](#services)
  - [Detail Services](#detail-services)
  - [Footer](#footer)

## Project Goals

### Bussines Goals

- Provide essential info about the business and services to customers.
- Automate the booking process by allowing customers to independently book the date and time of visiting the barbershop.
- Expand the client base and increase the credibility of the business, making it more and more popular.
- Promote business and increase the number of customers.
- Attract the attention of potential visitors.

### User Goals

- Find out information about the services provided and their prices.
- Find out the work schedule, contacts and the location of the barbershop itself.
- The ability to book an appointment through the site on their own.

[Back to top](#table-of-contents)

## User Experience (UX)

### Wireframes

The Barbershop Website was designed based on wireframes produced in [Balsamiq](https://balsamiq.com/). All design features were implemented.

| Index                                                                 | Book Now                                                                  |
| --------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| ![Index page wireframe](documentation/wireframes/wireframe-index.png) | ![Booking page wireframe](documentation/wireframes/wireframe-booking.png) |

### Site Structure

The Barbershop site has three pages with a clear and semantic structure, the information is well organized, every element is easy to find. The consistency and similarity of the structure is manifested on all pages and sections of the site and covers interactivity. The main menu is designed with intuitive and familiar navigation which includes the barbershop logo on the left side, the navigation links in the center and the book now link on the right side.

### Design Choices

The website is designed in such a way as to interest the user, give useful information about the services and increase the chances of visiting the Barbershop. The appearance and UI design is quite user-friendly, stylish and responsive.

- #### Typography
  The main website font is a geometric slab-serif typeface family _Arvo_ and it's fallback font is _Serif_. The flavour of the font is rather mixed, being nearly monolinear to increase legibility.
  The font implemented on the website using [Google Fonts API](https://fonts.google.com). Heading weights are bold(700) and body text is regular(400).
- #### Color Scheme
  The colour scheme based on warm yellow and brown tones and matches the images on the page.

![Color palette](documentation/supp-images/palette.png)

- #### Images
  Grunge borders, brush-stroke and logo were created in [Adobe Photoshop](https://www.adobe.com/products/photoshop.html) using paint brushes and other tools.
  All photos used in the project were downloaded from sources with a free license and do not require attribution. The images were colored and resized in [Adobe Lightroom](https://www.adobe.com/products/photoshop-lightroom.html) for a light moody style.

[Back to top](#table-of-contents)

## Features

The Barbershop website is designed to strictly adhere to accessibility guidelines across all pages/sections and all interactive elements.
Any interaction causes a positive response to the user through the semantic structured information, colors, clear and unambiguous navigation structures.
All external links open in another tab and use the noopener attributes to prevent external pages from being manipulated.

### Home Page

- #### Header
  The page header welcomes users, introduces barbershop and gives a brief overview of how it can be useful. The section is responsive for each screen size and occupies 70% of available browser space vertically.

![Header section](documentation/features/header.png)

- #### Navigation Bar
  The navbar is sticky, fully responsive and changes to a toggler (hamburger menu) on smaller screens. It includes logo on the left side, the navigation links(home, price and gallery) in the center and the book now link on the right side. The background of each menu item is a brush stroke created in [Adobe Photoshop](https://www.adobe.com/products/photoshop.html) using a painting brush.
  Only the central part of the menu is hidden in the toggle at lower screen resolutions. The sticky menu is implemented in such a way that the "Book now" button is always visible to users, and they can make an appointment at any time without returning to the very top of the page.

|                       **Full NavBar**                        |                           **Mobile Navbar**                           |
| :----------------------------------------------------------: | :-------------------------------------------------------------------: |
| ![NavBar on Desktop](documentation/features/full-navbar.png) | ![Navigation Bar on Mobile](documentation/features/mobile-navbar.png) |
|                      **Sticky NavBar**                       |                          **Dropdown NavBar**                          |
|  ![Sticky NavBar](documentation/features/sticky-navbar.png)  |    ![Dropdown Navbar](documentation/features/dropdown-navbar.png)     |

- #### Services
  This section presents three lists of services provided by the barbershop. Icons were used to attract the users eyes and allow them to quickly understand what type of service was being offered. On the big screen, the lists are arranged horizontally in 3 columns. On smaller devices, the services stack one on top of the other.

Desktop|Mobile
:-:|:-:
![Services Desktop](documentation/features/services-desktop.png)|![Services Mobile](documentation/features/services-mobile.png)

- #### Detail Services
  The section is implemented in the form of a chessboard on which pictures alternate with blocks of text. Each text block is supported by a picture and succinctly describes the main services to assure the user of what the company does and what is available. Also each block contains a link to the service booking page.

Desktop|Mobile
:-:|:-:
![Services Desktop](documentation/features/detail-service-desktop.png)|![Services Mobile](documentation/features/detail-service-mobile.png)

- #### Footer
  The footer is valuable to the user as it includes three blocks of useful info. This is address and phone number of the barbershop, opening times and links to the relevant social media sites.
  The footer section is also fully responsive and on smaller devices the info blocks stack one on top of the other.

![Footer](documentation/features/footer.png)