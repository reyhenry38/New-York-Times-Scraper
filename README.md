# Mongo WebScraping
Mongo News Scaper is web application that scrapes news from Petapixel's photography web site. I made the app with mongoose and Cheerio technologies among other ancillary technologies.


<img width="400" alt="mongoscraper" src="https://user-images.githubusercontent.com/31670361/39391602-33b5b4be-4a74-11e8-88af-8b217e14b790.png">




* Whenever a user runs the app on the local server or on the heroku app link, article headlines, the article link, and the article snippet are scraped from petapixel.com's website. 
* I used cheerio to easily grab and scrape  petapixel's DOM elemnts. Mongoose was used to save the scraped data to our database (mongodb.)
* The comments button allows user to view comments on an article or add/delete their own comments; all comments are saved to our mongodb database. 



This app was made using cheerio to serve  as the ORM to simplify the database interactions.

---

### Pre-requisites

* Install Node.js. visit https://nodejs.org/en/ and download

### Technologies used

*node.js
*Express.js
*Bootstrap V4

### Getting Started
This app is built with anf made possible with the following npm packages:

* express 
* express-handlebars
* body-parser
* cheerio 
* mongoose 
* morgan
* request

Type `npm install` in the command line to install all the dependcies located within package.json

## Default test (included in package.json file)
In order to connect to the scraper web app on the local server, type the following in the command line:

 `node server.js`

The user will also be notified in the command line interface on which PORT its connected on.

`localhost:port/scrape` will scrape the petapixel website

`localhost:port/articles` will display all the scraped articles from petapixel.com



### Author
* [Ejike Onwe](https://github.com/reyhenry38)

### License
This project is licensed under the MIT [License](https://github.com/reyhenry38/mongo-news-scraper/blob/master/LICENSE.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  


