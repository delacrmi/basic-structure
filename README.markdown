Master Structure
===

In this proyect we have the basic node proyect structure.
---

### Folders Structures

- ### **Project**
 1. *App*
	  1. Controllers
	  2. Models
	  3. Routes
	  4. Test
	  5. views
  2. *Config*
    1. Env
    2. Strategies
  3. *Public*
    1. Img
    2. Javascripts
    3. Stylesheets

The Gruntfile script performs the following steps:
---
1. Check source code with JSHint
2. Run unit tests with Jasmine
3. to concatenate and minify script

Running the server
---

Before to run the server, you need be sure that all the dependencies are installed

    npm install

When all the dependencies are installed

    node app.js
