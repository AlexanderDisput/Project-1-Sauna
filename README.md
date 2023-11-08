# Happy Sauna 

[Welcome to the official repository of Happy Sauna, a website dedicated to promoting wellness through sauna experiences. Our website provides users with detailed information on our sauna offerings, pricing plans, health benefits and the opportunity to contact us for more personalized services.]

# Table of Contents

## Introduction
## User Experience UX
### Initial discussion 
### User Stories 
## Design
### Colour Scheme
### Typography
### Imagery
### Wireframes
## Features 
### Navigation 
### Home Page
### Pricing Page
### Contact Form 
## Accessibility 
## Technologies Used
### Frameworks & libraries
## Deployment & Local Development
### Deployment 
### Local Development
### How to Fork
### How to Clone

## Introduction


## User Experience (UX)


## Initial Discussion
[Happy Sauna was created with a simple goal: to help people relax and enjoy the health benefits of sauna sessions. We noticed that everyone seems to be busy these days, and finding time to unwind is hard. That's why we made a website where people can learn about our saunas, see the prices, and book a session easily.

We built this site for anyone who wants to take a break from their busy life and look after their health. Whether you're new to saunas or you've been enjoying them for years, we want to make it simple for you to find the information you need and get started with us.

Our website is designed to be easy to use. We chose colors and pictures that make you feel calm and peaceful, just like our saunas. We also made sure you can find your way around the site without any hassle.]

### User Stories
- As a new visitor, I want to understand the benefits of using a sauna, so that I can decide if it's right for me.
- As a potential customer, I want to easily navigate through the pricing plans, so I can choose a plan that suits my needs.
- As a returning customer, I want to contact Happy Sauna to schedule my sessions or inquire about services.

## Design

### Colour Scheme
- The website uses a simple setup of black, white and grey which matches the luxurious feel of our saunas and fits with the different brown tones of the wood within the images
![Alt text](<assets/images/Screenshot 2023-11-08 at 15.38.19.png>)

The palette was was chosen through testing. 
### Typography
The typography for the site is centered around the use of the "Poppins" font family. This font has been chosen for its modern and clean lines, which contribute to the overall aesthetic and readability of the site.

- Fallback: Sans-serif is specified as the fallback font to maintain a similar look in the event that Poppins cannot be loaded.

### Imagery
Imagery is carefully selected to showcase the saunas and provide the user with a sense of the quality that we try to provide

Sources: 
https://www.istockphoto.com/
https://pixabay.com/

## Features

The website is comprised of four pages, three of which are accessible from the navigation menu (home page, books page & contact us page). The fourth page is a 404 page which is shown once a user navigates to  a non existing link.

#### All Pages on the website have:

- The website features a dynamic top navigation bar that facilitates easy browsing. Adjacent to the bar on the left is the Happy Sauna Logo. On the right side of the bar, there are links to various sections of the website, including the homepage, benefits, pricing page, and a contact page. 

- On mobile devices, the traditional navigation links are replaced with a hamburger menu icon, providing a streamlined and familiar navigational experience for users. This design choice is aimed at maintaining a neat interface and ensuring a positive user experience across devices.

- A footer which contains social media icon links to Instagram and Facebook. In addition to the names, icons were used to keep the footer clean and because they are universally recognisable.

### Navigation
 The navigation feature is implemented as a header element containing a responsive navigation bar with links to various sections of the website.

- The navigation is wrapped in a <header> tag.
- It contains an unordered list with the class nav-bar that represents the navigation menu.
- A logo is placed as the first item in the navigation bar, which is also a link that can be set to redirect to the home page.
- The navigation items include links to the Home page, Pricing page, Benefits section, and the Contact Us page.
- The navigation bar is responsive, with a checkbox used to toggle a mobile-friendly menu.

Source: 
Was taken from the following video and slightly modified: https://www.youtube.com/watch?v=qzAAiKFfNLo

##### Dependencies
Requires FontAwesome for icons.

### Home Page
This outlines the structure and components of the homepage for "Happy Sauna". The homepage serves as the landing page and provides an overview of the services, benefits, and a glimpse into the sauna experience offered.

#### Structure
- Header: Contains the navigation bar with a logo, menu items, and a hamburger menu for responsive design.
- Banner: A fixed banner with a parallax effect showcasing the brand's message.
- Sauna Preview Section: Displays a selection of sauna images with "Learn More" buttons linking to the pricing page.
- Benefits Section: Details the health and wellness benefits of using saunas.
- Footer: Includes social media links for Instagram and Twitter.

### Pricing Page
The Pricing Page for "Happy Sauna" details the various subscription plans and provides exclusive video tours of the sauna facilities.

#### Structure

- Header: Includes the navigation bar with a logo and menu items, featuring a responsive hamburger menu.
- Banner: A fixed banner with a parallax effect and a motivational tagline.
- Video Showcases: Two video sections that autoplay on load, offering a virtual tour of the sauna environments.
- Pricing Section: Displays three different pricing plans - Basic, Premium, and Deluxe - with detailed information and a call-to-action button for each.

### Contact Form
This document provides details about the Contact Form feature implemented in the web application. The Contact Form is designed to collect user information such as name, email address, phone number, subscription preference, and additional information that the user may want to share.

- Collects user's first and last names, email, and phone number.
- Offers a dropdown for subscription options: Basic, Premium, Deluxe.
- Includes a text area for any additional user comments or information.
- Validates required fields on the client side.
- Submits the data to a "https://httpbin.org/" page upon completion.


#### Structure
- Header: Includes logo and a navigation bar with links to other pages, adaptable for mobile screens with a hamburger menu.
- Contact Form: Central feature of the page where users input their personal and contact information, select a subscription plan from a dropdown, provide additional comments in a text area, and submit the form.


## Accessibility
Throughout the development process, I have prioritized accessibility to make the website user-friendly for individuals with disabilities. This has been accomplished through the following measures:

- Implementing semantic HTML to enhance the site structure and context for assistive technologies.
- Adding meaningful alt attributes to images, ensuring content is conveyed even when the images cannot be seen.
- Including descriptive information for non-text content, such as videos, to aid screen reader users.
- Selecting color schemes that provide ample contrast, catering to users with visual impairments.
- Making navigation intuitive for screen reader users by indicating the active page within the menu structure.
reference all of the websites where you received 

-add testing section ot the readme with images of each page: 
Add screenshots for wave and lighthouse for mobile and desktop 
add plenty of screenshots for each of the features 
add 2 or 3 of the bigger bugs that you have with your website 


## Technologies Used

### Languages Used
- HTML5
- CSS3

### Frameworks, Libraries & Programs Used
- FontAwesome for icons
- Github - To save and store the files for the website.
- Google Fonts - To import the fonts used on the website.
- Google Dev Tools - To troubleshoot and test features, solve issues with responsiveness and styling.
- Convertio.co to convert my images to webp

## Deployment & Local Development


#### Deployment
Github Pages was used to deploy the live website. The instructions to achieve this are below:

- Log in (or sign up) to Github.
- Find the repository for this project, AlexanderDisput/Project-1-Sauna.
- Click on the Settings link.
- Click on the Pages link in the left hand side navigation bar.
- In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select folder menu.
- Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

#### How to Fork
How to Fork
To fork the Project-1-Sauna repository:

- Log in (or sign up) to Github.
- Go to the repository for this project, AlexanderDisput/Project-1-Sauna.
- Click the Fork button in the top right corner.


#### How to Clone
To clone the Bully-Book-Club repository:

- Log in (or sign up) to GitHub.
- Go to the repository for this project, AlexanderDisput/Project-1-Sauna.
- Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
- Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
- Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.


## Testing 

#### W3C Validator
The W3C validator was used to validate the HTML on all pages of the website. It was also used to validate CSS in the style.css file.

Index Page HTML
Pricing Page HTML
Contact Us Page HTML
404 Page HTML
style.css CSS

#### Lighthouse
I used Lighthouse to allow me to test the performance, accessibility, best practices and SEO of the website.