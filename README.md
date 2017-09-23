# Mongo-The-Mongoose All the News That's Fit to Scrape
A Mongoosed Ars Technica News Scraper, wrestling with Bootstrap4 Beta.
Deployed to Heroku, https://mighty-tundra-80676.herokuapp.com using mLab provision remote MongoDB database.

### Overview
A web app that lets users view and leave comments on the latest news. But you're not going to actually write any articles; instead, you'll flex your Mongoose and Cheerio muscles to scrape news from another site.

### npm packages abused:
3. express
4. express-handlebars
5. mongoose
6. body-parser
7. cheerio
8. request
9. morgan

 ### Each scraped article contains:
     * Headline - the title of the article
     * Summary - a short summary of the article
     * URL - the url to the original article

        * Users may save articles 
        * Users may leave comments on saved articles
        * Users may delete articles
  
- - -

