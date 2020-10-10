# Code Refactor for Horiseon

## Goal for the assignment

Refactor HTML and CSS files to increase the accesibility of the website

## GitHub Repo

See the deployed GitHub Repo with all the changes here

## Changes made to the source code

### HTML

* Created more semantic HTML
    * Added more white space and organiziation for readability
    * Renamed `<div>`s to `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, and `<footer>` to give better meaning. This also allowed me to remove some unnecessary `class` names
    * Created a `class` for all `<section>`s in the `<main>`
    * Renamed the `class` in the `<div>`s in the `<aside>` to all be the same
* Adjusted elements for accessibility
    * Transferred the background image from the CSS to the HTML
    * Added `<alt>` tags with descriptions
* Fixed the broken link in the `<nav>` bar

See example of before (left) and after (right) code below:

![starting-vs-ending-html](.assets/images/starting-vs-ending-html.png)

### CSS

* Regrouping for more consise CSS
    * Updated my elements that were renamed in the HTML
    * Consolidated repeat code that was written multiple times by using the single `class` I created in the HTML
    * Reorganized the `content` class to be above the `benefits` class in the CSS to follow the order of the HTML
* Added comments for each item to explain its function
* Edited the parameters for the main image after having moved it from the CSS to the HTML
    
