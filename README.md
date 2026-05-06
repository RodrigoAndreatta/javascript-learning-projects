# JavaScript Learning Projects

This repository was created to organize the main projects I developed throughout my JavaScript learning journey in Jonas Schmedtmann's JavaScript course.

The goal is not only to showcase finished applications, but also to show my progression as I learned new JavaScript concepts step by step. Each project represents a different moment of the course and focuses on specific skills, from basic DOM manipulation to object-oriented programming, geolocation, local storage, dates, timers, and more complex application logic.

## Projects

### 1. [Guess My Number](https://guessmynumber-rodrigo.netlify.app/)

Guess My Number was one of my first JavaScript projects. It was developed using basic DOM manipulation and JavaScript fundamentals such as variables, conditionals, functions, event listeners, and simple manual UI updates.

This project is intentionally simple because it represents the beginning of my learning process, when I was still getting comfortable with how JavaScript interacts with the browser.

### 2. [Pig Game](https://piggame-rodrigo.netlify.app/)

Pig Game was a step forward in complexity. In this project, I practiced working with game state, multiple players, dice rolls, score tracking, DOM updates, and event-driven logic.

Compared to Guess My Number, this project required more organization because the interface changes constantly depending on the player turn, current score, total score, and winner state.

### 3. [Bankist App](https://bankistapp-rodrigo.netlify.app/)

Bankist App is a fictional banking application built to practice JavaScript array methods and more advanced data manipulation. It includes features such as logging in, viewing transactions, transferring money, requesting loans, closing an account, sorting movements, formatting values, working with dates, and handling a logout timer.

This project was especially important because it helped me understand how methods like `map`, `filter`, `reduce`, `find`, `findIndex`, `some`, `forEach`, and `sort` can be used to transform, search, filter, and display real application data.

### 4. [Bankist Site](https://bankistsite-rodrigo.netlify.app/)

Bankist Site is a fictional landing page that focuses on advanced DOM manipulation and browser events. It includes interactive interface patterns such as a modal window, smooth scrolling, event delegation, tabbed content, sticky navigation, section reveal animations, lazy loading images, and a slider component.

This project was an important step because it moved beyond basic DOM updates and helped me understand how JavaScript can be used to create smoother, more dynamic user experiences in a real website layout.

### 5. [Mapty](https://mapty-rodrigo.netlify.app/)

Mapty is a workout tracking application built with object-oriented programming, geolocation, the Leaflet map library, and local storage. It allows the user to register running and cycling workouts directly on a map.

This project introduced a more structured way of thinking about applications, using classes, inheritance, private fields, event handling, browser APIs, and data persistence. It also included more planning before coding, which made it feel closer to a real front-end project.

## Next project: Forkify

I am still developing the final project of the course, Forkify. It should be completed soon and will combine many of the concepts learned throughout the course, including asynchronous JavaScript, API calls, modules, application architecture, rendering, state management, and a more complete project structure.

Once Forkify is finished, I plan to add it to this repository as the final and most advanced project in this learning path.

## Technologies used across the projects

- HTML
- CSS
- JavaScript
- DOM Manipulation
- JavaScript Arrays and Objects
- JavaScript Numbers, Dates, and Timers
- Object-Oriented Programming
- Geolocation API
- Local Storage
- Leaflet
- Parcel

## Running a project locally

Each project has its own folder and its own `package.json`. To run one of them locally, open the project folder in the terminal and run:

```bash
npm install
npm run start
```

To create a production build:

```bash
npm run build
```

For Netlify, the usual configuration for each project is:

```txt
Build command: npm run build
Publish directory: dist
```
