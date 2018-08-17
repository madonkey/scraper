# Image Web Scraper
Simple web scraper using Node.js and Cheerio

Ensure you have Node insalled.

Run `npm install` then `node scrape`

Simply replace url with the page you wish to scrape and it will scrape the `src` of any `img` element it can find and place it in a csv file.

```javascript
const url = 'http://unsplash.com'; // URL you want to scrape
```

By default, images will be downloaded to `download` folder in order of appearance in DOM.
