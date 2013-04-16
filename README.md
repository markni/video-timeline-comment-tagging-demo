Just some experiments for school project

## Highlights

A few things that are useful in this application:

* How to use [videojs](http://videojs.com/) HTML5 player and its api to tag videos
 * see public/javascripts/script.js 
* How to create a **RESTful** json api using Node.js and Express
 * see app.js
* How to use a **object modeling tool** ([Mongoose](http://mongoosejs.com/) in this case) to bind data models into database schema (MongoDB in this case)
 * see models/index.js
* How to preform basic **CRUD**(create, read, update, delete) actions on data models without writing queries 
 * see app.js
* How to use AJAX call and RESTful api to dynamically update page content (all comments are loaded in front-end)
 * see public/javascripts/script.js 
* Some insights of mongoDB and how it works
 * see app.js


## Installation Guide

1. [mongoDB](http://www.mongodb.org/downloads) needs be installed and running , follow the README instruction if you have trouble.

2. ```npm install``` as always

3. run "util/import.js" to feed test data into database 'tag_database'

4. run 'app.js' and have fun


## Further Reading

		form
			input#make_comment_time(type="text",disabled="disabled",placeholder="00:00",data-time="0")
			button#btn_make_comment_time(title="Get Current Time") ↡
			input#make_comment_context(type="text",placeholder="Type your comment here and click submit")
			button#btn_make_comment_submit(type="submit") Submit

1. if you like object modeling tool for MYSQL, see [Sequelize](http://www.sequelizejs.com/)

2. a mode detailed tutorial: [Develop a RESTful API Using Node.js With Express and Mongoose](http://pixelhandler.com/blog/2012/02/09/develop-a-restful-api-using-node-js-with-express-and-mongoose/)
