# Website Planning Document

## Color Palette
- Primary Color: #3A506B (Deep Blue)
- Secondary Color: #5BC0BE (Teal)
- Accent Color: #FAF33E (Bright Yellow)
- Background Color: #1C2541 (Dark Blue)
- Text Color: #FFFFFF (White)
- Alternative Text: #D1D1D1 (Light Grey)

## Typography
- Headers: 'Montserrat', sans-serif (Bold, clean, modern)
- Body Text: 'Open Sans', sans-serif (Highly readable)

## Page Layouts

### Page 1: Home/About Me

```
+-----------------------------------------------+
| LOGO          NAV BAR                         |
+-----------------------------------------------+
| +-----------+ +---------------------------+   |
| |           | |                           |   |
| |  PROFILE  | |  <H1>Nikolas Vincenti</H1>|   |
| |   IMAGE   | |  Full Stack Developer     |   |
| |           | |                           |   |
| +-----------+ +---------------------------+   |
|                                               |
| +-------------------------------------------+ |
| |  <H2>About Me</H2>                        | |
| |  Background information, education,       | |
| |  personal journey in tech                 | |
| +-------------------------------------------+ |
|                                               |
| +-------------------------------------------+ |
| |  <H2>Skills & Technologies</H2>           | |
| |  Languages, frameworks, tools I use       | |
| +-------------------------------------------+ |
|                                               |
| +-------------------------------------------+ |
| |  <H2>Current Focus</H2>                   | |
| |  What I'm learning and building now       | |
| +-------------------------------------------+ |
|                                               |
+-----------------------------------------------+
| FOOTER: Social links, copyright               |
+-----------------------------------------------+
```

#### HTML Elements:
- `<header>` with logo and navigation
- `<nav>` with links to all four pages
- `<main>` containing:
  - `<section>` with `<img>` for profile picture
  - `<h1>` for name and title
  - Three `<section>` elements each with:
    - `<h2>` headings for each section
    - `<p>` paragraphs for content
- `<footer>` with social links

### Page 2: Contact Form

```
+-----------------------------------------------+
| LOGO          NAV BAR                         |
+-----------------------------------------------+
|                                               |
| <H1>Contact Me</H1>                           |
|                                               |
| +-------------------------------------------+ |
| |                                           | |
| |  <fieldset>                               | |
| |    <legend>Send Me a Message</legend>     | |
| |                                           | |
| |    Name: [______________________]         | |
| |                                           | |
| |    Email: [______________________]        | |
| |                                           | |
| |    [ ] I'm interested in hiring you       | |
| |                                           | |
| |    Your Message:                          | |
| |    [                                  ]   | |
| |    [                                  ]   | |
| |    [                                  ]   | |
| |                                           | |
| |    [SEND MESSAGE]                         | |
| |                                           | |
| |  </fieldset>                              | |
| +-------------------------------------------+ |
|                                               |
+-----------------------------------------------+
| FOOTER: Social links, copyright               |
+-----------------------------------------------+
```

#### HTML Elements:
- `<header>` with logo and navigation
- `<nav>` with links to all four pages
- `<main>` containing:
  - `<h1>` heading for the page
  - `<form>` with:
    - `<fieldset>` with `<legend>`
    - Two text `<input>` elements with `<label>`s
    - One checkbox `<input>` with `<label>`
    - `<textarea>` with `<label>`
    - Submit `<button>`
- `<footer>` with social links

### Page 3: Resources

```
+-----------------------------------------------+
| LOGO          NAV BAR                         |
+-----------------------------------------------+
|                                               |
| <H1>Developer Resources</H1>                  |
|                                               |
| +-------------------------------------------+ |
| |                                           | |
| |  <ul>                                     | |
| |    <li><a href="#">Resource 1</a></li>    | |
| |    <li><a href="#">Resource 2</a></li>    | |
| |    <li><a href="#">Resource 3</a></li>    | |
| |    <li><a href="#">Resource 4</a></li>    | |
| |    <li><a href="#">Resource 5</a></li>    | |
| |  </ul>                                    | |
| |                                           | |
| +-------------------------------------------+ |
|                                               |
| Brief descriptions of why I recommend         |
| each resource                                 |
|                                               |
+-----------------------------------------------+
| FOOTER: Social links, copyright               |
+-----------------------------------------------+
```

#### HTML Elements:
- `<header>` with logo and navigation
- `<nav>` with links to all four pages
- `<main>` containing:
  - `<h1>` heading for the page
  - `<ul>` with 5 `<li>` elements containing `<a>` links to external resources
  - `<p>` elements with brief descriptions
- `<footer>` with social links

### Page 4: Projects Gallery

```
+-----------------------------------------------+
| LOGO          NAV BAR                         |
+-----------------------------------------------+
|                                               |
| <H1>My Projects</H1>                          |
|                                               |
| +-----------+ +-----------+ +-----------+    |
| |  PROJECT  | |  PROJECT  | |  PROJECT  |    |
| |   IMAGE   | |   IMAGE   | |   IMAGE   |    |
| +-----------+ +-----------+ +-----------+    |
| Project 1     Project 2     Project 3        |
|                                               |
| +-----------+ +-----------+ +-----------+    |
| |  PROJECT  | |  PROJECT  | |  PROJECT  |    |
| |   IMAGE   | |   IMAGE   | |   IMAGE   |    |
| +-----------+ +-----------+ +-----------+    |
| Project 4     Project 5     Project 6        |
|                                               |
+-----------------------------------------------+
| FOOTER: Social links, copyright               |
+-----------------------------------------------+
```

#### HTML Elements:
- `<header>` with logo and navigation
- `<nav>` with links to all four pages
- `<main>` containing:
  - `<h1>` heading for the page
  - 6 `<figure>` elements arranged in a grid, each with:
    - `<a>` linking to the project (target="_blank")
    - `<img>` project screenshot
    - `<figcaption>` for project name/description
- `<footer>` with social links

## CSS Classes

### Global Classes
- `.container`: Centers content, provides consistent padding
- `.nav-links`: Styles navigation links
- `.btn`: Base button styling
- `.btn-primary`: Primary call-to-action button

### Page-Specific Classes
- `.profile-section`: Styles the profile image and name section
- `.about-section`: Formats about me content
- `.skills-section`: Styles the skills list/grid
- `.contact-form`: Styles form elements
- `.resource-list`: Styles the resource links
- `.project-grid`: Creates grid layout for projects
- `.project-card`: Styles individual project images and captions

### Component Classes
- `.nav-active`: Highlights current page in navigation
- `.social-icon`: Styles social media icons
- `.form-group`: Styles form input groups
- `.project-image`: Styles project images consistently
