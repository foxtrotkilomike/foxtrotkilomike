## :bow: Who am I
I'm Phil - a frontend developer, a graduate of [BMSTU](https://www.bmstu.ru/) informatics and control systems department. Keen on learning new technologies in web-dev, which improve user experience and benefit the business!

My **[projects](#trophy-other-achievements)**.

You can also check out my [self-introduction video](https://www.youtube.com/watch?v=mdsK340TMpw).

## :mailbox: Contact me!
- TG [@foxkilomike](https://t.me/foxkilomike)
- Mail <a href="mailto:filooloog@mail.ru">filooloog@mail.ru</a>
- LinkedIn [linkedin.com/in/foxtrotkilo](https://www.linkedin.com/in/foxtrotkilo)
- DS Foxtrot#0879

## 🛠 My tech stack
- React, Redux & RTK
- JavaScript, TypeScript
- Node.js, Express
- Webpack, Vite

## :bar_chart: Stats

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="top" src="https://github-readme-stats-yca3.vercel.app/api?username=foxtrotkilomike&show_icons=true&hide_rank=true&hide=stars&count_private=true&theme=flag-india&bg_color=00000000" />
</a>
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="top" src="https://github-readme-stats-yca3.vercel.app/api/top-langs/?username=foxtrotkilomike&layout=compact&theme=flag-india&bg_color=00000000" />
</a>

## :trophy: Other achievements
<a href="https://www.codewars.com/users/foxtrotkilomike">
  <img src="https://www.codewars.com/users/foxtrotkilomike/badges/small">
</a>

## 👨‍💻 Projects

<details>
<summary><b>Projects list</b></summary>

## Project Management App

An application which helps a team of developers to track project's tasks.

- [Repository](https://github.com/foxtrotkilomike/project-management-app)
- [Deploy](https://dashing-phoenix-851f28.netlify.app/)

<br>
<img width="571" alt="image" src="https://user-images.githubusercontent.com/83244224/206625049-5e03731f-3fa1-431a-8d0b-726ea0e61f8d.png">

### Tech stack
- React
- TypeScript
- React Router
- React Bootstrap, SASS
- React Hook Form
- React Beautiful DnD
- Vite

### Features
- boards display in a grid with a board preview
    - accessible confirmation modal window on creation, editing, and deletion of a board, a column, a task
- drag & drop for tasks reordering, moving to other columns, and columns reordering
- user registration, authentication & authorization
- editing & deletion of a user profile
- accessible log-in forms with validation
- routes protection
- redirects to the Main page on log-in, or when a user's token expires, or when a user is logged in and tries to reach the log-in form
- a column with a scrollbar in case of tasks overflow
- a header with a changing set of buttons:
    - "Sign up" & "Sign in" for unregistered users,
    - "Create board", "Edit Profile", "Main page", and "Sign out" for logged-in users
- custom 404 page
- custom scrollbars
- user-friendly toast notifications
- adaptive & responsive layout, burger menu


## RS Recipes

A recipe portal, a clone of [allrecipes.com](https://www.allrecipes.com/). 

- [Repository](https://github.com/kravchuk-st/rs-clone)
- [Deploy](https://kravchuk-st.github.io/rs-clone/)
<br>
<img width="571" alt="image" src="https://user-images.githubusercontent.com/83244224/214542353-cdb2b192-642e-46e2-bd34-24dcfa6ee6d7.png">

### Tech stack
#### Frontend
- TypeScript
- noUiSlider, SwiperJS
- SASS
- Webpack

#### Backend
- NodeJS (Express JS) + MongoDB (mongoose)
- [open API](https://github.com/public-apis/public-apis) + [Recipes API](https://spoonacular.com/food-api) is used as a data source

### Features
#### Frontend
- user registration, authentication & authorization, a user session is saved; forms with validation
- the main page contains quick access blocks to recipes categories
- the recipes page has dozens of filters, several sorting options, and a search bar to find suitable recipes
- recipes constructor shows relevant recipes, which can be cooked with the ingredients you have
- article page has relevant recipes at the end of the page
- add recipe and article to favorite or save for later by clicking on a bookmark or a heart icon - *for registered users*
- watch (and modify) saved and favorite articles and recipes, as well as products and a shopping list on the user profile page
- adaptive & responsive layout, burger menu

#### Backend
- implemented REST API with GET/POST requests handling
- API documentation is implemented (using openAPI 3.0)
- implemented MVC pattern (DB entities are divided to model, router, service)
- user registration, authentication & authorization with JWT tokens + cookies
- configured CORS settings and correct error handling, implemented custom error object and custom error messages, grouped in configs

## Virtual keyboard
	
A virtual keyboard, which represents physical keys pressing and can be used to type via the UI.

- [Repository](https://github.com/foxtrotkilomike/virtual-keyboard)
- [Deploy](https://foxtrotkilomike.github.io/virtual-keyboard/)
<br>
<img width="571" alt="image" src="https://user-images.githubusercontent.com/83244224/167428508-0fdb6745-9cdd-4775-87d6-5e1a1d4e914c.png">

### Tech stack
- vanilla JavaScript bundled with Webpack

### Features
- keys highlighting while pressing physical buttons
- text navigation using arrow keys
- clearing the text field on pressing a cross icon
- expanding text field within certain limits
- layout changes on language change and on special keys press (CapsLock, Shift...)
- responsive design
- *an easter egg on pressing `Win` key*
	
## Pet shelter

A two-page site of pets' shelter.
	
- [Repository](https://github.com/foxtrotkilomike/Pet-haven)
- [Deploy](https://rolling-scopes-school.github.io/foxtrotkilomike-JSFE2022Q1/shelter/)
<br>
<img width="571" alt="image" src="https://user-images.githubusercontent.com/83244224/214547537-24e078f7-1e0e-493f-8078-626f0074131d.png">

### Tech stack
- JavaScript
- SASS

### Features
- a burger menu
- a custom slider
- a custom pagination
- an adaptive design
- interactive elements with hover effects
- a smooth scroll
	
## Cars asynchronous race game
A task to practice asynchronous requests for cars' race and detecting winners.

- [Repository](https://github.com/foxtrotkilomike/async-race)
- [Deploy](https://rolling-scopes-school.github.io/foxtrotkilomike-JSFE2022Q1/async-race/) (**Note**: to be able to watch working version ones need to start up a local server with cars data. The code and instructions can be found **[here](https://github.com/mikhama/async-race-api).**)
<br>
<br>
<img width="571" alt="image" src="https://user-images.githubusercontent.com/83244224/184881481-89593f9b-1d40-45a4-ba07-0116957b21b4.png">

### Tech stack
- TypeScript, bundled with Webpack
- SASS

### Features
- cars generation & updating with a name and a color, also a random generation of 100 cars to start the app quickly from scratch
- starting/stopping & position reset for all the cars on the current page (implemented via `fetch` requests)
- starting/stopping a particular car
- a car stops if an HTTP 500 status code is returned
- a winner detection
- a pagination
- the winners page gets updated via an HTTP query
	
## Online keyboard store

An online store with filtering, sorting, and searching for keyboards.
	
- [Repository](https://github.com/foxtrotkilomike/keyboard-store)
- [Deploy](https://rolling-scopes-school.github.io/foxtrotkilomike-JSFE2022Q1/online-store/)
<br>
<img width="571" alt="image" src="https://user-images.githubusercontent.com/83244224/179624000-93d8095e-dcec-46f1-98ce-e385766fbc73.png">

### Tech stack
- TypeScript bundled with Webpack
- SASS
- Jest

### Features
- goods filtering by multiple criteria
- goods sorting and search
- dynamic cards generation
- adding of goods to the cart
- adaptive design
	
## JS mini projects

- [Repository](https://github.com/foxtrotkilomike/JS-mini-projects)
<img width="571" alt="image" src="https://user-images.githubusercontent.com/83244224/192508435-06db58de-fa6d-41c4-9f48-5b4187be63b3.png">
<br>
<br>
	
4 mini-projects in JavaScript:
1. [A photographer's landing page](https://foxtrotkilomike.github.io/JS-mini-projects/portfolio/)
2. [An audio player](https://foxtrotkilomike.github.io/JS-mini-projects/audio-player/) (media usage in a browser)
3. [Images gallery](https://foxtrotkilomike.github.io/JS-mini-projects/image-galery/) (a work with an API)
4. [A browser game](https://foxtrotkilomike.github.io/JS-mini-projects/random-game/) (a runner game with JavaScript)\
	

#### More projects could be found in my 👉 [github respositories](https://github.com/foxtrotkilomike?tab=repositories)
</details>

<!--
**foxtrotkilomike/foxtrotkilomike** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
