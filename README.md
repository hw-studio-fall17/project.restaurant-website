# Restaurant Website

##### You're going to create a restaurant website. This can be a real restaurant or a fake restaurant!

#### Check out some examples for inspiration:
* [https://oddduckaustin.com](https://oddduckaustin.com/)
* [https://torchystacos.com](https://torchystacos.com/)
* [http://www.lucysfriedchicken.com](http://www.lucysfriedchicken.com/)

## Look at what was given to you...
* You have three HTML files `home.html`, `menu.html`, `about-us.html`
* You have a `style.css` that is already linked to all of your HTML files using: `<link rel="stylesheet" type="text/css" href="style.css">` in the `<head>` tag on every HTML file
* jQuery is linked in the `<head>` of ALL of your HTML pages using: `<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>` in the `<head>` tags
* You have a `script.js` that is already linked in all of your HTML files using: `<script type="text/javascript" src="script.js"></script>` in the `<head>` tags

_____________________________________________________________________________
## LEVEL ONE

## Home Page in `home.html`
* Add the restaurant name where it says "WEBSITE NAME"
* Add a [heading](https://www.w3schools.com/html/html_headings.asp) to your website
* Add a brief bio for the restaurant using a `<p>` tag.
* Put an `id` on the `<body>`. See below for an example
  ``` HTML
  <body id="example-id">
    ...
  </body>
  ```
* In style.css select the `id` to add a background image on the home page using the `background-image` CSS property. Look [here](https://css-tricks.com/perfect-full-page-background-image/) for more help. 
  * The website [stocksnap.io](https://stocksnap.io/) has some great free images. Try typing "food" or "restaurant" into the search bar
* Change the color of the text on the page

## Menu Page in `menu.html`
* Set a background color on the `<body>` using a pretty [hex color](https://www.google.com/search?q=hex+color+picker&oq=hex+color+picker&aqs=chrome.0.35i39j0l5.3193j0j1&sourceid=chrome&ie=UTF-8)
* Add a `<div>` inside the `<body>` and put the `id` "menu" on it like this:
  ``` HTML
    <body>
      <div id="menu">

      </div>
    </body>
  ```
* Use `<ol>`, `<li>`, and `<p>` tags to create menu items. For example:
  ``` HTML
    <body>
      <div id="menu">
        <ul>
          <li class="menu-item">
            <p class="item">Grilled Cheese</p>
            <p class="description">Melty cheddar cheese served between two pieces of perfectly toasted slices of bread.</p>
          </li>
        </ul>
      </div>
    </body>
  ```
  ** Make sure you add the same classes because you will use them later to style
* Add a border to the menu `div` using the css border property. See [here](https://www.w3schools.com/cssref/pr_border.asp) for help

## About Us Page in `about-us.html`
* Create a `div` with the `id` set equal to "about"
  ``` HTML
    <body>
      <div id="about"> 

      </div>
    </body>
  ```
* Add a location(address) to this page using a `<p>` tag
* Add a phone number to this page using a `<p>` tag
* Add a couple of fake reviews to the page using a `<p>` tag

_____________________________________________________________________________
## LEVEL TWO

## Home Page in `home.html`
* Try changing your background color to be a [linear-gradient()](https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient) instead of one solid color
* Add a [google font](https://fonts.google.com/) to your page.
  * Click on the red plus sign of the font you want to use
  * Click on the black bar at the bottom of the page that says 1 Family Selected
  * Copy the `<link>` and put it inside the `<head>` tag in your HTML file
  * Follow the font-family instructions for your CSS
* Change the color of the text on your page

## Menu Page in `menu.html`
* In `style.css` select everything with the class `item` to make the food names bold. HINT: you will use the CSS `font-weight` property
* In `style.css` select everything with the class `description` make the food descriptions italicized
* Add a border to your `<ul>` to make a double border on the page
* Add the [`hover` effect](https://www.w3schools.com/cssref/sel_hover.asp) to your `menu-item`s, so that when you hover on each item some of the colors change. (or something else changes!)

_____________________________________________________________________________
## LEVEL THREE

### Home Page 
* In `script.js` select the nav bar by it's `id` using jQuery and save it in a variable called `navBar`. It will look something like this 
  ` var exampleSelect = $("#example-id") `
* Make your navigation bar slowly fade in when the page loads. Hint: you will need to use the jQuery [fadeIn() function](http://api.jquery.com/fadein/). Google it if you forget how it works.
* Get rid of the underlines on the link tags in your navigation. Google "how to remove underlines from link tags with CSS"

## Menu Page
* Create a secret spot on the page. When the user clicks on it, they will be alerted with a super secret menu item! Follow the steps below:
  * Create a new HTML element to be clicked or decide which old HTML element you would like to use. Add an id to the element so that it is easy to select using jQuery.
  * Select your element in `script.js` using jQuery and save it in a variable.
    * ``` var exampleVariable = $("#example-id") ```
  * Call the [click() jQuery function](https://api.jquery.com/click/) on your variable. 
  * When the user clicks on the secret spot use the [alert() function](https://www.w3schools.com/jsref/met_win_alert.asp) to create a pop up saying the super secret menu item

_____________________________________________________________________________
## LEVEL FOUR

## About Us Page
* Add a parallax image to your page. [See an example here](https://www.w3schools.com/howto/howto_css_parallax.asp)

### Other ideas
* Add a [slide show](https://www.w3schools.com/howto/howto_js_slideshow.asp) of images to one of the pages.
* Try to use spotify or soundcloud to embed a song on one of the pages

### CREATE!
* Use your creativity to make your website even more awesome!

_____________________________________________________________________________
