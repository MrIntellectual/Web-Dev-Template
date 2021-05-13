# Web Dev Template

This is a template that anyone can use to make a website.

This is made for local development, and you need to have [mongodb community server](https://www.mongodb.com/try/download/community) installed.

Technologies Used: 
* HTML, CSS, JavaScript, and TypeScript for frontend.
  * Bootstrap 5
  * Font Awesome
  * JQuery
  * Three.js
  * Highlight.js
  * Lodash
  * SCSS
  * Badges(By @CoolCoderSJ)
* Node.JS for backend.
  * Express
  * EJS
  * Mongoose
  * Lodash
* MongoDB for database.

To Setup
```shell
git clone https://github.com/MrIntellectual/Web-Dev-Template && cd Web-Dev-Template
npm i
```

To Compile
```shell
npm run compile
```

Only do the commands to compile if you want to use SCSS, TypeScript, and CoffeeScript.

If you are using one of them but not the other there are 3 seperate commands
```shell
# For TypeScript
npm run tsc
# For CoffeeScript
npm run coffee
# For SCSS
npm run scss
```

To Start
```shell
npm run start
```