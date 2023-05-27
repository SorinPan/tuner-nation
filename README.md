# Tuner Nation

Tuner Nation is a website that celebrates the art of tuning and all things automotive. The website will help car enthusiasts to connect, showcase their cars and learn from one another.

![Am I responsive view](docs/am-i-responsive.jpg)

[View live site](https://sorinpan.github.io/tuner-nation/)

## User Experience

### Website Owner Goals

- To increase the number of people attending events.
- To provide clear information about events and how to join.
- To provide clear background and mission information.

### User Stories

#### User Goals

- As a user, I want to see upcoming events so that I can plan to attend and showcase my car.
- As a user, I want to see photos from previous events so that I can so that I can get a sense of what to expect.
- As a user, I want to be able to view the information on a range of screen sizes.
- As a user, I want to easily navigate the website.

#### Returning Customer Goals

- As a returning customer, I want to find new information about upcoming events.
- As a returning customer, I want easily find contact information.

## Design

### Colour Scheme

![Colour Palette](docs/colour-palette.png)

The colours where choosen to reflect a modern feeling. The combination of Night and Gold gives the website modern look and it is easy on the eye. The colour palette was created with [Coolors](https://coolors.co/).  

### Typography

Google Fonts and FontJoy were used for the following:

- Fira Sans Condensed is used for logo and shorter text.
- Oswald is used for headings.
- Robot is used for the body text of the website.

I think this pairing provides a balanced and visually pleasing contrast.

## Features

The website contains three main pages which can be accessed from the menu bar on the top of the website.

### Home Page

#### Logo and Navigation Bar

- Simple and intuitive.
- A navigation bar at the top which allows the visitors to easily navigate the website. Includes links to Home page, About page and Meet Up page.
- A logo at the top left which allows the visitors to easily return to the Home Page.
- Both Logo and Navigation bar are responsive for smaller screens.

![Navbar feature](docs/navbar-feature.png)

#### Hero

- Contains a background image of a slightly tuned car to give the visitor an idea of what the website is about.
- Contains a heading and a short description of what the site is about.
- "Join Us" button so visitors can access the Meet Up page easily.

![Hero feature](docs/hero-feature.png)

#### Mission

- Introduces the visitors to the website's mission.
- Image of a couple of tuned cars.

![Mission Feature](docs/mission-feature.png)

#### City

- Allows thye visitors to see where the events will take place.
- Short paragraph to encourage the visitors to join.

![City feature](docs/city-feature.png)

#### Upcoming Events

- Allows the users to see the date of future events.
- Simple and Informative.

![Upcoming Events feature](docs/upcoming-feature.png)

### About Us Page

#### About

- Description of what the website is about.

![About Feature](docs/about-feature.png)

#### Gallery

- Images of the past events.

![Gallery feature](docs/gallery-feature.png)

### Meet Up Page

#### Form and Instructions

- Contains a Form that the user can submit in order to book and and get info on an event.
- Contains a short instructions about how to attend an event.

![Form feature](docs/form-feature.png)

## Future Feature

- Hamburger Button for navigation bar on mobile screens.
- Tracks. A section where user can book time on tracks where they can drive/race their tuned cars.
- Events Page. A page dedicated just for events where more descriptive iformation about specific events will be.

## Technologies Used

### Languages Used

- HTML5
- CSS3

### Programs Used

- Figma: Used for creating wireframes.
- Visual Studio Code: Used for writing and developing code.
- CodeAnywhere: Used for writing and developing code.
- Git: Used for version control.
- GitHub: Used to store the files and deploy.
- FireFox Developer Edition: Used to test new features before implementing into actual code.
- Google Fonts: Used to import the fonts.
- FontJoy: Used to find fonts pairing.
- Font Awesome: Used for icons.

## Doployment and Development

### Deployed with GitHub Pages

GitHub Pages was used for deployment:

1. Log in to GitHub.
2. Select repository for the project.
3. Go to "Settings".
4. Click on "Pages".
5. In the Source section, select branch "Main" and then select "Root" from the dropdown menu.
6. Click "Save".
7. Wait a couple of section and GitHub will provide the link to deployed website.

### Cloning Project to Local Machine

There are many ways to do this. I did it in the following way:

- Log in to [Github](https://github.com/).
- Select project [Repository](https://github.com/SorinPan/tuner-nation).
- Click on the "Code" button.
- Copy the URL under HTTPS.
- Open VsCode.
- Log in to VsCode with your Github account.
- Press SHIFT + CMD + P (For Mac), type "Clone" and select "Git:Clone".
- Paste in the URL and press Enter to create the local clone.

## Testing

### W3C Validator

Used to validate HTML and CSS code for all pages. H1 headings were used in section which resulted in a warning. Not able to fix the issue due to lack of time.

<details><summary>Home Page</summary>
<img src="docs/validation/index-validator.png">
</details>

<details><summary>About Page</summary>
<img src="docs/validation/about-validation.png">
</details>

<details><summary>Meet Up Page</summary>
<img src="docs/validation/meetup-validation.png">
</details>

<details><summary>CSS</summary>
<img src="docs/validation/css-validation.png">
</details>

### Solved Bugs

- Side scroll bar for mobile screen size. Adjusted the size of mission image.

## Lighhouse

Lighthouse was used on every page of the website to test the Performance, Accessibility, Best Practices and SEO.

Used a linear-gradient to darken the images for a better Accessibility result.

<details><summary>Home Page</summary>
<img src="docs/validation/index-lighthouse.png">
</details>

<details><summary>About Page</summary>
<img src="docs/validation/about-lighthouse.png">
</details>

<details><summary>Meet Up Page</summary>
<img src="docs/validation/meetup-lighthouse.png">
</details>