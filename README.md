# Homework 02 CSS and Bootstrap: Responsive Portfolio

## Introduction

In this assignment we were to create a responsive design utilizing Bootstrap. We were to have 3 pages:

- About (the index.html file)
- Portfolio
- Contact

We were instructed to use the Bootstrap grid structure of rows and columns.

## Approach

I strived to use only Bootstrap to reach the desired look, without including my own customer CSS file. This was achieved by utilizing the following:

- All Pages
  - A nav-bar class outside of the main container so that it would stretch full width.
  - A Jumbotron in a fluid container to span the width of the page and hold all content
  - A fixed-bottom class footer outside of the main container to span the full width
- About:
  - One column within the Jumbotron
  - Image floated left and in-line with text to get text to wrap around the image
- Contact:
  - One column within the Jumbotron containing a form
- Portfolio:
  - Changing number of columns, depending on screen size, within the Jumbotron holding the images - such that a responsive tile layout was reached.

## Results

### Path to GitHub Repository

<https://github.com/JonPointer/DUFS_Homework_02_Responsive_Portfolio>

### Path to GitHub Hosted Application

<https://jonpointer.github.io/DUFS_Homework_02_Responsive_Portfolio/>

# The following is the original Readme file assignment

# Unit 02 CSS and Bootstrap Homework: Responsive Portfolio

Responsive design ensures that web applications render well on a variety of devices and window or screen sizes. As a developer, you will likely be asked to create a mobile-first application or add responsive design to an existing application.

## Directions

First, you will use the Bootstrap CSS Framework to create a mobile responsive portfolio. How do you deliver this? Here are some guidelines:

- Create the following files files: `index.html`, `portfolio.html` and `contact.html`.

- Using Bootstrap, develop your portfolio site with the following items:

  - A navbar

  - A responsive layout

  - Responsive images

- The Bootstrap portfolio should minimize the use of media queries.

- Screenshots are provided as a reference in the `Assets/Images` folder. Your app does not need to be _exactly_ like the images. Use Bootstrap to create a similar, responsive layout.

### Hints

- Use Bootstrap's grid system (containers, rows, and columns).

- On an `xs` screen, content should take up the entire screen. On `sm` and larger screens, you should have some margins on the left and right sides of the screen. Check out various sites on your mobile device vs. your computer to see examples of these differences.

- Use an HTML validation service to ensure that each page has valid HTML.

### Minimum Requirements

- Functional, deployed application

- GitHub repository with README describing the project

- Navbar must be consistent on each page.

- Navbar on each page must contain links to Home/About, Contact, and Portfolio pages.

- All links must work.

- Must use semantic html.

- Each page must have valid and correct HTML. (use a validation service)

- Must contain your personalized information. (bio, name, images, links to social media, etc.)

- Must properly utilize Bootstrap components and grid system.

### Bonus

- Using Bootstrap, make a sticky footer and use sub-rows and sub-columns on your portfolio site (**Hint:** Check out the Bootstrap documentation).

## Commit Early and Often

One of the most important skills to master as a web developer is version control. Building the habit of committing via Git is important for two reasons:

- Your commit history is a signal to employers that you are actively working on projects and learning new skills.

- Your commit history allows you to revert your codebase in the event that you need to return to a previous state.

Follow these guidelines for committing:

- Make single-purpose commits for related changes to ensure a clean, manageable history. If you are fixing two issues, make two commits.

- Write descriptive, meaningful commit messages so that you and anyone else looking at your repository can easily understand its history.

- Don't commit half-done work, for the sake of your collaborators (and your future self!).

- Test your application before you commit to ensure functionality at every step in the development process.

We would like you to have well over 200 commits by graduation, so commit early and often!

## Submission on BCS

You are required to submit the following:

- The URLs of the deployed applications

- The URLs of the GitHub repositories

---

© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
