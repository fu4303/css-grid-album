# css-grid-album

This project explored basics properties of CSS Grid and how it allows responsive layouts.

Also took into account how the use of images affect the page's performance and explored tools to detect and solve issues with the images.

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/jpmti2016/css-grid-album)
![GitHub last commit](https://img.shields.io/github/last-commit/jpmti2016/css-grid-album)
![GitHub top language](https://img.shields.io/github/languages/top/jpmti2016/css-grid-album)
![GitHub language count](https://img.shields.io/github/languages/count/jpmti2016/css-grid-album)
![W3C Validation](https://img.shields.io/w3c-validation/html?targetUrl=https%3A%2F%2Fjpmti2016.github.io%2Fcss-grid-album%2F)

## CSS Grid properties used

1. Properties
   1. grid-template-columns
   2. grid-template-rows
   3. justify-content
   4. gap
   5. grid-column
   6. grid-row
2. Special Functions and Keywords
   1. repeat()
   2. minmax
   3. fr
   4. auto-fit

## Image processing tools

1. Gimp used to
   1. Scale the image to the needed dimensions.
   2. Reduce the image size.
2. imageoptim used to
   1. Compress the image taking into account factors like
      1. Quality
      2. Format
      3. DPI mode
      4. Color quality

In detecting the images issues was very useful the Google Console tool for auditing the page known as Lighthouse and RespImageLint.

## Page auditing tools

1. Lighthouse
   1. Used to check the overall quality of the webpage
      1. Performance
      2. Accesibility
      3. SEO
      4. Best practices
   2. RespImageLint used to detect images's issues.

### The idea came from the Wes Bos's great course [CSS Grid](https://courses.wesbos.com/).
