# Bootstrap-Portfolio

## Description
My web development portfolio created using Bootstrap v4.4 Framework with custom CSS. The Bootstrap framework's responsive web layout design is used for the webpage layout at all screen sizes.

## Usage

Custom colours, font families, and text decoration are applied additionally with another stylesheet to match the developer portfolio created from scratch.

### Navigation Menu
The webpage features fixed navigation bar at the top of the viewport to move around the webpage. On smaller width devices such as phones, the navigation bar collapses into a hamburger menu containing the links. The original hamburger menu is intended as a toggle button, however in this project, the data-toggle attribute is changed from "collapse" to "dropdown." This has minor side-effects such as loss of animation styles, removing functionality from other dropdown mensu (none on this webpage) and not being able to collapse the expanded navigation menu. However, automatically collapsing menu reduces user input required to navigate the webpage as the menu collapses when anywhere else on the webpage is clicked.

Custom styling is used to add hover effects to the links as Bootstrap is limiting. The background is also styled with a custom sheet.

### Hero/Jumbotron Section
The self image, name and welcome text is laid out using Bootstrap's jumbotron template. The background image is applied through custom CSS as it will require atleast using the z-index property to layer correctly. The background image does not add any meaningful value to the webpage other than being aesthetically pleasing. The borders of elements within the jumbotron have custom shadows and glow applied to match the custom developer portfolio, because it is not possible via Bootstrap.

### Work Section
The layout from the developer portfolio is recreated using Bootstrap cards. The card sizing behaviour is dependant on Bootstrap's flexbox parameters. Hover effects that vary the opacity is also added separately.

### Skills Section
The list template from Bootstrap is used for the skills section. Bootstrap success, warning, and danger colours are used to indicate understanding/proficiency. Headings with custom colours are used to list the skills and in the future, will include more information - such as combining frameworks with languages or linking to related project work.

### About Section
Bootstrap's layout classes are sufficient to include the section heading and paragraph of this section, and place the section on the same row as the contact form.

### Contact Form
The contact form is created using Bootstrap form templates with changes to the names and labels of input fields within the .html file. The send button functionality does not currently exist. Custom style properties are applied so the send text is visible while hovered/active. It will be added in the future using javascript (maybe idk). The about section and contact form separates on smaller width devices.

### Socials
Bootstrap's layout and visibility classes are used to control the sizing and position of each element. The footer heading is hidden on smaller devices so that the icons can be larger and easier to click or tap. The hover effects are customised separately. Hovering the icons enlarges them and adds a box shadow.

## Deployment
The portfolio is deployed using GitHub Pages. The site can be accessed at: https://aywink.github.io/Bootstrap-Portfolio/

## Credits
MDN HTML, CSS, and Accessibility Guides - https://developer.mozilla.org/en-US/
Stack Overflow threads - https://stackoverflow.com/
CSS SECRETS better solutions to everyday web design problems by Lea Verou - ISBN: 978-1-449-37263-7
Bootstrap v4.4 documentation - https://getbootstrap.com/docs/4.4/getting-started/introduction/
W3Schools Bootstrap tutorials - https://www.w3schools.com/bootstrap4/default.asp

## License
MIT License