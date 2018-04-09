# NYT-Scraper

NYT- Scraper is an app that gets articles from the New York Times website and lets users read, save, leave comments, or delete the latest news articles on the site. You can visit the site here.


**Key Dependencies

request: enables cheerio to get access to front-end code of https://www.nytimes.com/section/world

Cheerio: scrapes front-end code from https://www.nytimes.com/section/world

Mongoose: be in charge of database of NYT Scraper

Express: builds server-side routes and functions

Morgan: logs server-side requests, helping debugging

Express-handlebars: a powerful front-end builder without requiring multiple html pages


**Installation Instructions

1. `Clone or fork the repo to your computer. You will need node.js installed on your system.`

2. `At the command line navigate to the apps folder and run npm install, this will install the npm dependencies.`

3. `Install mongodb ,then run an instance of the db, more info can be found here https://www.mongodb.com/`

4. `Then run node server.js. The console should log the port number the app. Go to that localhost: address`
