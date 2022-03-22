# React Portfolio Website with Sanity CMS

This is a personal portfolio website made with React.js using Sanity as a CMS for storing and retrieving information such as projects and skills.

To run the project clone or download the project then run

```
npm install
npm run
```

To start the project in a local environment. You would need to setup your own sanity backend with your personel content to fully utilize the project.

## Dependencies

```
"@sanity/client": "^3.1.0",
"@sanity/image-url": "^1.0.1",
"@testing-library/jest-dom": "^5.16.2",
"@testing-library/react": "^12.1.3",
"@testing-library/user-event": "^13.5.0",
"framer-motion": "^6.2.8",
"node-sass": "^7.0.1",
"react": "^17.0.2",
"react-dom": "^17.0.2",
"react-icons": "^4.3.1",
"react-scripts": "5.0.0",
"react-tooltip": "^4.2.21",
"web-vitals": "^2.1.4"
```

## To Do's
- [ ] Overall
  - [ ] Use `section` and `article` tags where necessary for better semantics
  - [ ] Populate with necessary data
  - [ ] Select a good 2 accent light color scheme from huemint and apply it
  - [ ] Add support for dark mode and select a color scheme from huemint for it
- [ ] Navbar
  - [ ] Fix logo
  - [ ] Add container to limit width
- [ ] Navdots
  - [ ] Use icons rather then dots for more intuitve navigation
  - [ ] Create a subtle animation for the icons for visual feedback
- [ ] Header section
  - [ ] Create better positioning for text
  - [ ] Add a primary and secondary CTA
  - [ ] Change profile picture
  - [ ] Create a orbit animation for skill circles
- [ ] About section
  - [ ] Fix layout so that there is a row for the title/headline
  - [ ] Add a brief self description highlight benefits I would provide
  - [ ] Make the animation on cards more subtle
- [ ] Work section
  - [ ] Rework it into "Projects" or "Portfolio" section
  - [ ] Show associated tags as pills on the bottom of the cards.
  - [ ] Create filter tags from retrieved projects dynamically
- [ ] Skills section
  - [ ] Check after populated with data
- [ ] Testimonials section
  - [ ] Remove testimonials section as it is unnecassary for now
- [ ] Contact section
  - [ ] Make sure the placeholder text is visible as labels when user input is recieved