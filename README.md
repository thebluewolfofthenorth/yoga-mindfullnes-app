# PUST Yoga & Mindfulness Center Website

This project encompasses a welcoming website for the PUST Yoga & Mindfulness Center, offering detailed insights on yoga and mindfulness techniques, a support section for enthusiasts, and a signup page for classes. The design is mobile-responsive, ensuring a smooth user experience across various devices.

![Screenshot of the website](screenshot.jpg) 

## Table of Contents

1. [Demo](#demo)
2. [Technologies Used](#technologies-used)
3. [File Structure](#file-structure)
4. [Setup](#setup)
5. [Features](#features)
6. [Sources](#sources)
7. [Contact](#contact)

## Demo

The live demo of the website is in progress. (You can update this section once your website is live)

## Technologies Used

- HTML
- CSS
- VS Code

## File Structures

```plaintext
project-root/
│
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── images/
│       └── ... (image files)
│
├── index.html
├── techniques.html
├── support.html
├── signup.html
└── README.mdgi
```

## Site Structure
The website is structured into four main pages:

- **Home Page**: Provides an overview of the center and its offerings.
- **Techniques Page**: Showcases various yoga and mindfulness techniques.
- **Support Page**: Lists support resources and frequently asked questions.
- **Sign-Up Page**: Features a form for interested visitors to join the center or request more information.

## Typography
The website employs the "Oxygen" and "PT Serif" fonts from Google Fonts to achieve a contemporary and refined design:

- **Font Family**: 'Oxygen', sans-serif for body text and 'PT Serif', serif for headings.
- **Font Import**: `@import url('https://fonts.googleapis.com/css2?family=Oxygen:wght@400;700&family=PT+Serif:ital@0;1&display=swap');`
- **Headings**: 'PT Serif' is utilized for headings, providing a classic serif style that contrasts with the body text.
- **Body Text**: 'Oxygen' is employed for body text, offering a modern and readable sans-serif style.

## Color Scheme
The color scheme of the project is vibrant and engaging, derived from a palette of warm and earthy tones:

- **Primary Color**: `#FFF5DC` (Beige)
- **Secondary Color**: `#FED777` (Light Goldenrod)
- **Tertiary Color**: `#FCBA12` (Selective Yellow)
- **Quaternary Color**: `#A77802` (Dark Gold)
- **Quinary Color**: `#342809` (Very Dark Brown)


### Wireframes:

The wireframes for PUST  [Balsamiq]("https://balsamiq.cloud/"). There are frames for a full width display and a small mobile device. The final site varies slightly.

![Picture from Home section](./assets/images/Home.png "Homepage")

![Picture from Techniques section](./assets/images/Techniques.png "Techniques")

![Picture from Support section](./assets/images/Support.png"Support")

![Picture from Sign up section](./assets/images/Sign_up.png.png "Sign up")

![Picture from mobile home section](./assets/images/Home_2.png "Home-mobile")

![Picture from Techniques-mobile section](./assets/images/Techniques_2.png "Techniques Mobile")

![Picture from Fun Support-mobile section](./assets/images/Support_2.png "Support Mobile")

![Picture from Sign-up-mobile section](./assets/images/Sign_up_1.png "Sign up-mobile")


Home page (index.html)

------------------------------------------------
|  Logo     | Hamburger Menu Icon (☰)         |
------------------------------------------------
| Hero Section with Image, Title, and CTA button|
|-----------------------------------------------|
| Introduction to Yoga and Mindfulness          |
|-----------------------------------------------|
| Techniques Preview                            |
|-----------------------------------------------|
| Testimonials                                  |
|-----------------------------------------------|
| Footer / Floating Action Button               |
------------------------------------------------

Tecniques page (technique.html)
------------------------------------------------
|  Logo     | Hamburger Menu Icon (☰)         |
------------------------------------------------
| Page Title: Yoga and Mindfulness Techniques  |
|-----------------------------------------------|
| Search and Filter Options                     |
|-----------------------------------------------|
| List of Techniques with images and descriptions|
|-----------------------------------------------|
| Footer / Floating Action Button               |
------------------------------------------------

Support page (support.html)
------------------------------------------------
|  Logo     | Hamburger Menu Icon (☰)         |
------------------------------------------------
| Page Title: Support                          |
|-----------------------------------------------|
| Frequently Asked Questions                    |
|-----------------------------------------------|
| Contact Form                                  |
|-----------------------------------------------|
| Footer / Floating Action Button               |
------------------------------------------------

Sign up page (signup.html)
------------------------------------------------
|  Logo     | Hamburger Menu Icon (☰)         |
------------------------------------------------
| Page Title: Sign Up                          |
|-----------------------------------------------|
| Sign Up Form (Name, Email, Password)          |
|-----------------------------------------------|
| Information on Benefits of Signing Up         |
|-----------------------------------------------|
| Footer / Floating Action Button               |
------------------------------------------------

## Features
The website incorporates several features to provide a user-friendly experience:

- **Responsive Design**: The website layout adjusts to various screen sizes, ensuring a pleasant user experience on both desktop and mobile devices.
- **Interactive Techniques Section**: The techniques section on the Techniques page presents various yoga and mindfulness exercises, each with a descriptive image and text.
- **Sign-up Form**: The Sign-up page features a form for interested visitors to join the center or request more information.
- **Accessible Navigation**: The navigation menu allows users to easily navigate through the website and find the information they need.


## Navigation Menu
The navigation menu is a crucial part of the website's user interface, allowing users to easily navigate through the site. The menu is responsive and accessible on both desktop and mobile devices. It consists of links to the following pages:

- **Home**: Returns the user to the main landing page.
- **Techniques**: Takes the user to the page showcasing different yoga and mindfulness techniques.
- **Support**: Directs the user to the support page listing resources and frequently asked questions.
- **Sign Up**: Navigates the user to the sign-up page with a form for more information.


## Web Pages

### Index Page
The main landing page introducing the center and its offerings.

### Techniques Page (`techniques.html`)
This page showcases the various yoga and mindfulness techniques offered, each accompanied by a descriptive image.

### Support Page (`support.html`)
A page listing support resources and frequently asked questions.

### Sign Up Page (`signup.html`)
A page with a form for interested visitors to sign up for more information.

## CSS Styles
The styling for the website is contained in the `style.css` file located in the `assets/css/` directory. The CSS code defines a color scheme, typography, layout, and responsive design settings to ensure the website is accessible across a variety of devices.

## Technologies Used

- [HTML5](#html5): provides the content and structure for the website

- [CSS](#css): provide the styling

- [Balssamiq](#balsamiq): used to create the wireframes

- [VS Code](vs-code): used to deploy the website.

## Testing

Please refer to <a href="https://github.com/DFCMK/Budapest/blob/main/TESTING.md"><em>here<em></a> for more information on testing Budapest - A Historical Travel Guide

## Deployment 

This site was depolyed to GitHub pages. The steps to deploy a site are shown below:

1. In the GitHub Repository called <b>Budapest</b> click on the <b>Settings</b> button on the Repoitory navigation menu.

2. In <b>Settings</b> on the left side, go down to the <b>Pages</b> item and click on it.

3. Make sure the <b>Source</b> item is set to: <b>Deploy from a branch</b>

4. at the <b>Branch</b> item underneth the <b>source</b> item, set the branch to main and save it.

5. Once you have selected the main branch, the page will automatically refresh to show a detailed ribbon display indicating that the deployment was successful. If the page does not refresh automatically, refresh it manually.

![Screenshoot from Github deployment](./assets/images/guthub-deployment.png "GitHub depoloyment")

To get to the live link of the GitHub repository - click here: <a href="https://github.com/DFCMK/Budapest">https://github.com/DFCMK/Budapest</a>


### To Fork the repository on GitHub:



Forking a GitHub repository creates a copy of the repository in your own GitHub account. You can view and modify the copy without affecting the original repository.

To fork a repository:

1. Log in to GitHub and navigate to the repository you want to fork.
2. Click the Fork button in the top-right corner of the page.
3. Select a name for your forked repository.
4. Click the Fork button to create the copy.

Once you have forked a repository, you can clone it to your local computer and start making changes. When you are ready to share your changes, you can create a pull request to the original repository.

![Screenshoot from Github deployment](./assets/images/forking.png "GitHub depoloyment")

#### To create a local clone of this project:

1. Click the Code tab under the repository's name.
2. Click the clipboard icon in the Clone with HTTPS section to copy the URL.

![Screenshoot from Github deployment](./assets/images/git-clone.png "GitHub depoloyment")

Once you have copied the URL, you can use a Git client to clone the repository to your local computer.
Here are the steps to clone a repository using Git Bash:

3. Open Git Bash.
4. Navigate to the directory where you want to clone the repository.
5. Type the following command and press Enter:

git clone <URL>

Replace <URL> with the URL of the repository that you copied in step 2.

This will create a local clone of the repository in the current directory.

You also can create and name the directory where the clone should be saved in, with adding the directory name after the <URL>. So the full command would look like this: git clone <URl> XXXX(This is a directory name)

## Credits

  ### Content:

   - The font came from <a href="https://fonts.google.com/">Google Fonts.</a>
   - The colour palate was compiled by  <a href="https://www.w3schools.com/colors/colors_monochromatic.asp">W3Schools</a>
   - The icons came from <a href="https://fontawesome.com/search?q=swi&o=r&m=free">Font Awesome</a>
   - The Navigation Menu got created with a <a href="https://www.youtube.com/watch?v=8QKOaTYvYUA">YouTube tutorial.</a>
   - The inspiration for the Project came during creation process.
   - <a href="https://balsamiq.cloud/s3wc28z/p2hs46j/r2278">Balsamiq</a> was used to create the wireframes.

   - The Gallery was build with code based on the <a href="https://github.com/DFCMK/Love-Running">Love Running</a>

   - The content of [Chainbridge](#chainbridge) on the [Historical Places](#historical-places) is mostly summarized from the book <b><q>Hungry History and Culture</q></b> chapter: <b><q>Reformation period</q></b> sub chapter: <b><q>Hitel written by Istvan Szechenyi 1830</p></b> 

   - The rest of the content are summerised wikipedia articles, see below: 
   <a href="https://en.wikipedia.org/wiki/Hungarian_Parliament_Building">Hungarian Parliament</a>
   <a href="https://en.wikipedia.org/wiki/Buda_Castle">Buda Castle</a> 
   <a href="https://en.wikipedia.org/wiki/Matthias_Church">Matthias Church</a> 
   <a href="https://en.wikipedia.org/wiki/Szimpla_Kert">Szimpla Kert</a> 
   <a href="https://en.wikipedia.org/wiki/Gell%C3%A9rt_Baths">Gellert Bath</a>
   <a href="https://en.wikipedia.org/wiki/Sz%C3%A9chenyi_thermal_bath">Széchenyi Bath</a>
   <a href="https://en.wikipedia.org/wiki/Great_Market_Hall,_Budapest">The Great Market Hall</a>     

   ### Media:

   - background image on Home page came from <a href="https://www.pexels.com/">pexels</a>

   - images on other pages came from <a href="https://www.pexels.com/">unspash</a> and <a href="https://www.istockphoto.com">istockphoto</a>

   ### Code: 

   The Navigation Menu was build with a <a href="https://www.youtube.com/watch?v=8QKOaTYvYUA">YouTube tutorial</a> and the code is based on this video. The code can be find in line 17 - 98 and line 646 - 666. 
   To see the code click <a href="https://github.com/DFCMK/Budapest/blob/main/assets/css/style.css">here</a>

   The Gallery page was build, while using the "Love Running" project as Guideline. (line 454 - 464) and (line 575 - 582).
   To see the code click <a href="https://github.com/DFCMK/Budapest/blob/main/assets/css/style.css">here</a>

   ## Acknowledgements:

   I extend my heartfelt thanks to several individuals and communities who contributed to the completion of this project:

- <a href="https://www.linkedin.com/in/precious-ijege-908a00168/">Precious Ijege</a>, my dedicated mentor, for providing valuable guidance and support throughout the development process.

- The Code Institute's Slack community, a source of inspiration and assistance from fellow learners and professionals.

- The entire Code Institute team, whose resources and expertise have been instrumental in my learning journey.