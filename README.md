# My Portfolio

This is a portfolio website showcasing the work and experience of Victor Moenga, a frontend developer.

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Usage](#usage)
4. [Dependencies](#dependencies)
5. [Installation](#installation)
6. [Configuration](#configuration)
7. [Credits](#credits)
8. [License](#license)

## Description
This project is a personal portfolio website built with HTML, CSS, and JavaScript. It includes sections for about me, experience, projects, and contact information.

## Features
- Responsive design: The website is designed to be fully responsive and accessible across various devices and screen sizes.
- Smooth scrolling: The navigation menu allows users to smoothly scroll to different sections of the website.
- Hamburger menu: On smaller screens, the navigation menu is replaced with a hamburger menu for better user experience.
- Contact form: Users can easily get in touch with Victor Moenga via the contact section, which includes links to email and LinkedIn.

## Usage
To use this portfolio website, simply open the `index.html` file in a web browser. You can navigate through the different sections using the navigation menu or by scrolling. Clicking on the buttons in the "Contact Me" section will redirect you to the respective contact platforms.

## Dependencies
This project does not have any external dependencies.

## Installation
1. Clone the repository: `git clone https://github.com/your-username/your-repository.git`
2. Navigate to the project directory: `cd your-repository`

## Configuration
No configuration is required for this project.

## Credits
- Images: Images used in this project are sourced from [Pexels](https://www.pexels.com/) and [Icons8](https://icons8.com/).
- Fonts: The project uses the Poppins font from Google Fonts.

## License
This project is licensed under the [MIT License](LICENSE).

---

## Media Queries CSS

```css
@media screen and (max-width: 1400px) {
    /* Media queries content */
}

@media screen and (max-width: 1200px) {
    /* Media queries content */
}

@media screen and (max-width: 600px) {
    /* Media queries content */
}
function toggleMenu() {
    const menu = document.querySelector(".menu-links");
    const icon = document.querySelector(".hamburger-icon");
    menu.classList.toggle("open");
    icon.classList.toggle("open");
}

