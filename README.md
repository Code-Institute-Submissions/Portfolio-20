# Takafor Yannick Portfolio
This website has been created to serve the purpose of my portfolio as a Full-Stack Web Developer. It has six sections namely: Home, About, Portfolio, Skills, Contact, and CV. The Portfolio section highlights four projects covering a range of technologies.The main target audience for this project is prospective employers, clients with any visitor who would like to keep up to date with my latest projects.

In addition, this website has been developed to serve the purpose of my User-Centric Front End Development Milestone Project for [Code Institute](https://codeinstitute.net/)'s Full Stack Development course. Upon completion of the course, I will be awarded a diploma in Software Development accredited by [Edinburgh Napier University](https://www.napier.ac.uk/).

## UX

### User Stories

As an employer, I would like to see a showcase of Yannick's projects.

As an employer, I would like to see Yannick's CV.

As an employer, I would like to be provided with means of contacting Yannick by email, direct call or by post if I choose to. 

### Strategy
My objective in the design was to build a fully responsive site that provides easily accessible information to prospective employers with a visually appealing format.

### Scope
For employers, my goal was to provide a brief overview of myself as a Full-stack Web Developer. This includes a brief introduction about me, my projects, my skillset, my CV, with many options for contacting me.

### Structure
In the Home section, I wanted employers to know my name and job title. In the about section, I wanted to briefly introduce my self. In the Portfolio section, I wanted them to see the projects I have done and the technologies used. In the Skills section, I wanted them to have an overview of my skill set. In the contact section, I wanted to provide many options for contacting me. And lastly, on my CV I wanted to provide them with my educational background and work experience.

### Skeleton

[Home wireframe](https://github.com/Takaforyannick30/Portfolio/blob/master/assets/wireframes/home-wireframe-idea-2.pdf)

[About wireframe](https://github.com/Takaforyannick30/Portfolio/blob/master/assets/wireframes/about-wireframe-idea.pdf)

[Portfolio](https://github.com/Takaforyannick30/Portfolio/blob/master/assets/wireframes/portfolio-wireframe-idea.pdf)

[Skills wireframe](https://github.com/Takaforyannick30/Portfolio/blob/master/assets/wireframes/skills-wireframe-idea.pdf)

[Contact wireframe](https://github.com/Takaforyannick30/Portfolio/blob/master/assets/wireframes/contact-wireframe-idea.pdf)


### Surface

I wanted to keep it simple while practicing responsive design. In order to make different elements visually distinct, I chose a color palette of soft contrasting colors that complements each other. I used Google font "Manrope" with Sans-Serif as the fall back font. In addition, I used font awesome Icons for my social media link's image and also in the contact section.

## Features

### Features implemented

1.Hamburger menu - the navigation bar toggles into a hamburger menu in tablet and mobile allowing users to effectively navigate.

2.CSS hover overlay portfolio - the portfolio section has a hover overlay effect with a "LEARN MORE" button linked to my GitHub repository.

3.Contact form - the contact section has a contact form but at the moment it is not fully functional. messages can't be sent across to me via the contact form.

4.Scrollspy effect - [Bootstrap](https://getbootstrap.com/)'s Scrollspy feature was used in the project.

### Features Left To Implement

1.Add a "smooth scrolling" effect to Scrollspy.

2.Add portfolio Modals instead of just linking to my GitHub repository.

3.Add [firebase](https://firebase.google.com/) to allow potential employers and visitors to get in touch with me by filling and submitting a contact form.

4.Complete the projects in the planning stage and add more projects in the portfolio section.

## Technologies used

### languages used

* [HTML](https://en.wikipedia.org/wiki/HTML) 

The use of HTML which stands for Hypertext Markup Language was very paramount to this website as with every website or web-based app. HTML5 was used in this project to keep up with the latest industry standards. 

* [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

The use of CSS which stands for Cascading Style Sheet was also very paramount to this project. CSS was used for styling the content on the website.

### Libraries and framework

*[Font Awesome](https://fontawesome.com/)

Font Awesome is a font and icon toolkit based on CSS and LESS. It was made by Dave Gandy for use with Bootstrap, and later was incorporated into the BootstrapCDN. All the icons used in this project were obtained from Font Awesome.

*[Google Fonts](https://fonts.google.com/)

Google Fonts is a library of 991 free licensed font families, an interactive web directory for browsing the library, and APIs for conveniently using the fonts via CSS and Android. Manrope designed by Mikhail Sharanda was obtained from Google Fonts and used in this project.

* [Bootstrap](https://getbootstrap.com/)

Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains CSS-and Javascript-based design templates for tools, typography, forms, buttons, navigations, and other interfaces.  Bootstrap classes were used to build the navigation bar and to make the website responsive.

### Tools used

* [Git](https://git-scm.com/)

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.Git was used in this project for version control.

* [Gitpod](https://www.gitpod.io/)

Gitpod is an online integrated development environment for GitHub. It creates a complete and disposable development environment for any GitHub repository directly in a browser. This project was developed in Gitpod.

## Testing

This project has undergone extremely thorough testing. The user story of this project achieved the intended outcome. The manual test was carried out at every stage to ensure user experience standards remained at consistently high levels with each new implementation. The header with 6 menu items toggles into a hamburger menu on all screen size width below 992px.
Each navigation menu takes us to the section of the page when clicked with the exception of "CV" which takes us to a new tab where it can be viewed and downloaded.

In the "About" section employers and visitors can read about me with a view of my image But the image will not be displayed on all screen size width below 768px. Initially, when I was doing the wireframe,I wanted the image to be displayed below the paragraphs on the screen size mentioned above but I later changed my mind on this.

The portfolio section has four projects with hover overlay effects that work well as intended.The overlay has "LEARN MORE"  link buttons which opens my GitHub repository in a new tab. This was achieved using "target ="_blank".

The contact form works well as intended.All the fields must be field before submitting if not a little saying "please fill out this field" will popup. This was achieved using the attribute "required" on all input fields. And if an email with the wrong format is submitted a little message will popup saying what seems to be wrong with the email. This was achieved using 'type="email" ' attribute. The form is not fully functional at the moment as any message can't be sent through the form. If all input fields are filled in and submitted the page will reload and return to the home page. This was achieved using "onsubmit="return" attribute on the form.

The Scrollspy effect was tested by scrolling down the page. As soon as the top of the next page touches the border-bottom of the header,the navigation link of the section changes color from white to black thereby indication the section is currently been viewed or active.

This website was tested across multiple browsers such as Google Chrome, Safari, Microsoft Edge, Mozilla Firefox,and Opera Mini. It was also tested on multiple mobile devices such as iPhone 4, 5, 7, 8(plus) Chrome and Safari, iPad, Samsung Galaxy,and Huawei P30 Pro to ensure compatibility and responsiveness. During the testing process,I realized that the progress bar in the skills section displayed a different color across different browsers.To make the color consistent across browser I used;

1. For Chrome and Safari `::-webkit-progress-value` (for background color) and `::-webkit-progress-bar` (for color)

2. For Mozilla Firefox `::-moz-progress-bar` (for background color) `::-moz-progress-value` (for color)

Another issue found was in Microsoft Edge were the progress bar displayed a 1px solid black border. The progress bar in Mozila also displayed a border. To fix this issue I added `border: none` to my default css styling for the progress bar which works for microsoft edge and to the background color styling for Mozila Firefox.

In addition, Mozilla firefox displays a default browser color(reddish)  on the contact form focus state of all unfilled input fields, unlike other browsers that displayed the color I assigned to the "contact-form:focus" in my CSS. This issue was not fixed.

The HTML and CSS code file of this project was tested by direct input to [W3C Validator](https://validator.w3.org/)and no error was found. A mobile friendly test of this website was done using [search.google.com](https://search.google.com/test/mobile-friendly). The responsiveness was also done using websites such as [Am I Responsive](http://ami.responsivedesign.is/) and [Responsinator](http://www.responsinator.com/) .

## Deployment

This project has been deployed to Github Pages from the master branch. A link to the deployed version of the site can be found [here](https://takaforyannick30.github.io/Portfolio/).

This site was developed using Gitpod. All changes to the code were then added and committed to a local repository. The commits were then pushed to my GitHub repository.The process can be seen as bellow;

`git add (add file name)`

`git commit -m (add a commit mesage)` with "initial commit" always serving as the first commit message to a new repository.

`git push` 

 The project was hosted using GitHub pages directly from the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html. The process of deploying this project on GitHub pages can be seen as bellow; 

* Go to the settings tab of the repository, and scroll down to GitHub pages.

* Under GitHub pages, click on "source" and select the master branch.

* You will be automatically taken to the top of the page wherein a light blue bar will be stated: "GitHub pages source saved".

* Scroll down to GitHub pages where will be stated "your site is ready to be published at "[https://takaforyannick30.github.io/Portfolio/](https://takaforyannick30.github.io/Portfolio/)".

* Click on the URL and you will be auto-referred to the published webpage. When returning to the GitHub repository setting, scroll down to GitHub pages and you will see a light green block stating "Your site is published at " [https://takaforyannick30.github.io/Portfolio/](https://takaforyannick30.github.io/Portfolio/)".

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone  https://takaforyannick30.github.io/Portfolio.git` into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.

You can submit a pull request to the master branch and await approval. To do this:

* Navigate to the [original repository](https://github.com/Takaforyannick30/Portfolio)

* Click on **New pull request** on the right of the Branch menu

* On the compare page, click **compare across forks**

* Confirm that the base fork is the repository you'd like to merge into

* Use the head fork drop-down menu to select your fork,then use the compare branch drop-down menu to select the branch you made your changes in* Type a little description for your pull request

* If you do not want to allow anyone with push access to the upstream repository to make changes to your PR, unselect **Allow edits from maintainers**

* Click **Create pull request**

## Credits

### Content
The content in the "ABOUT" and "PORTFOLIO" section in this project was written by me.

My Curriculum Vitae attached in the CV section as an external pdf file was built using [resume.io's](https://resume.io) resume builder.

### Media
The background image used on the home page was taken from [Unsplash](https://unsplash.com/). I added a black color overlay on the image to enable the text in the section to be more visible.

### Acknowledgements
I received inspiration for this project from Code Institute's [StudentExampleProjectGradeFive](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive).

The Scrollspy nav link automation with Bootstrap 4 is something I learnt from a Youtube tutorial by [System 22 I.T Solutions](https://www.youtube.com/watch?v=Iy96iPwzY18).







