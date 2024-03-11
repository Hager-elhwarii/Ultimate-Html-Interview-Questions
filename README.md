# HTML Interview Questions :bulb: 
<a name="readme-top"></a>
![image](https://github.com/Hager-elhwarii/HTML-Interview-Questions/assets/80959882/801a5144-2c86-4dd8-ad0e-d7182a543939)
<br/>

|  Q |   Questions                        |
|----|------------------------------------|
| 01.|[What does HTML stand for and what is its purpose?](#q-what-does-html-stand-for-and-what-is-its-purpose)|
| 02.|[Describe the basic structure of an HTML document](#q-describe-the-basic-structure-of-an-html-document)|
| 03.|[How do you set language in HTML?](#q-how-do-you-set-language-in-html)|
| 04.|[What does a `<DOCTYPE html>` do?](#q-what-does-a-doctype-html-do)|
| 05.|[What happens when DOCTYPE is not given?](#q-what-happens-when-doctype-is-not-given)|
| 06.|[Describe the difference between a `cookie`, `sessionStorage` and `localStorage`?](#q-describe-the-difference-between-a-cookie-sessionstorage-and-localstorage)|
| 06.|[In how many ways can we specify the CSS styles for the HTML element?](#q-in-how-many-ways-can-we-specify-the-css-styles-for-the-html-element?)|
| 07.|[What is the difference between a `<span>` and a `<div>`?](#q-what-is-the-difference-between-a-span-and-a-div)|
| 07.|[Difference between link tag `<link>` and anchor tag `<a>`?](#q-difference-between-link-tag-link-and-anchor-tag-a)|
| 07.|[How to specify the link in HTML and explain the target attribute?](#q-how-to-specify-the-link-in-html-and-explain-the-target-attribute)|
| 07.|[In how many ways you can display HTML elements?](#q-in-how-many-ways-you-can-display-html-elements)|
| 07.|[What is the difference between `display: none` `visibility: hidden` and `opacity:  0` when used as attributes to the HTML element?](#q-what-is-the-difference-between-display-none-visibility-hidden-and-opacity-0-when-used-as-attributes-to-the-html-element)|
| 08.|[Name 5 common block-level and inline HTML elements?](#q-name-5-common-block-level-and-inline-html-elements)|
| 09.|[What are semantic and non-semantic elements?](#q-what-are-semantic-and-non-semantic-elements)|
| 10.|[What is Character Encoding?](#q-what-is-character-encoding)|
| 11.|[What is the purpose of meta tags?](#q-what-is-the-purpose-of-meta-tags)|
| 12.|[What does async and defer refer in script tag? Describe the difference between `<script>`, `<script async>` and `<script defer>`](#q-what-does-async-and-defer-refer-in-script-tag-describe-the-difference-between-script-script-async-and-script-defer)|
| 13.|[What are `data` attributes good for?](#q-what-are-data-attributes-good-for)|
| 13.|[How can we club two or more rows or columns into a single row or column in an HTML table?](#q-how-can-we-club-two-or-more-rows-or-columns-into-a-single-row-or-column-in-an-html-table)|
| 14.|[Ways to improve website performance](#q-ways-to-improve-website-performance)|


<br/>

## Q. ***What does HTML stand for and what is its purpose?***

HTML or Hyper Text Markup Language is the standard language for creating web pages and applications. HTML5, the latest version as of 2022, introduces several new elements and attributes, elevating user experience and software application standards.

HTML is responsible for structuring web content, ensuring accessibility, and guiding how web pages are visually presented. It remains the foundational structure for running nearly all web content.

<br/>

## Q. ***Describe the basic structure of an HTML document***

**HyperText Markup Language** (HTML) serves as the backbone of web content, defining its structure and semantics. We will now walk you through the fundamental elements of an HTML document.

### Basic Structure of an HTML Document

An HTML document consists of two primary sections: the `head` and the `body`.

#### Document Type Declaration (DOCTYPE)

The **Document Type Declaration** (DOCTYPE) is not an HTML tag; it's an instruction to the web browser about what version of HTML the page is written in.

```html
<!DOCTYPE html>
```

This declaration shows that the document is an HTML5 document.

#### HTML Element

The `html` element is the root element of an HTML page. It encompasses the entire content, both head and body.

```html
<html>
    <!-- Head and Body Sections Are Nested Inside -->
</html>
```

#### Head Section

The `head` section provides meta-information about the document. It isn't displayed in the web browser itself but serves various other purposes, from providing a title to linking external resources.

```html
<head>
    <!-- Title and Meta-Tags, Styles, Scripts, etc. -->
</head>
```

##### Title Element

The `title` element specifies the document's title, which is displayed in the browser's title bar or tab.

```html
<title>Your Page Title</title>
```

#### Body Section

The `body` section encapsulates the document's visible content—what users see and interact with.

```html
<body>
    <!-- Content Visible to Users: Headings, Paragraphs, Images, etc. -->
</body>
```
<br>

    <b><a href="#readme-top">↥ back to top</a></b>

<br>
<p align="right"><a href="#readme-top">[↑] back to top</a></p>


## Q. ***How do you set language in HTML?***
There are multiple ways to set language in HTML
*   By setting content-language in headers for language of the page
*   By setting accept-language in headers for list of language that a page accept
*   Setting lang attribute in html tag

**Example:**
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Document Title</title>
</head>
<body>

</body>
</html>
```
<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. ***What does a `<DOCTYPE html>` do?***

**DOCTYPE** is an abbreviation for **DOCument TYPE**. A DOCTYPE is always associated to a **DTD** - for **Document Type Definition**.

A DTD defines how documents of a certain type should be structured (i.e. a `button` can contain a `span` but not a `div`), whereas a DOCTYPE declares what DTD a document _supposedly_ respects (i.e. this document respects the HTML DTD).

For webpages, the DOCTYPE declaration is required. It is used to tell user agents what version of the HTML specifications your document respects. Once a user agent has recognized a correct DOCTYPE, it will trigger the **no-quirks mode** matching this DOCTYPE for reading the document. If a user agent doesn't recognize a correct DOCTYPE, it will trigger the **quirks mode**.

The DOCTYPE declaration for the HTML5 standards is `<!DOCTYPE html>`.

###### References

- https://html.spec.whatwg.org/multipage/syntax.html#the-doctype
- https://html.spec.whatwg.org/multipage/xhtml.html
- https://quirks.spec.whatwg.org/

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. ***What happens when DOCTYPE is not given?***

The web page is rendered in quirks mode. The web browsers engines use quirks mode to support older browsers which does not follow the **W3C specifications**. In quirks mode CSS class and id names are case insensitive. In standards mode they are case sensitive.


## Q. ***Describe the difference between a `cookie`, `sessionStorage` and `localStorage`?***

**localStorage:** localStorage is a way to store data on the client’s computer. It allows the saving of key/value pairs in a web browser and it stores data with no expiration date. localStorage can only be accessed via JavaScript, and HTML5. However, the user has the ability to clear the browser data/cache to erase all localStorage data.

**SessionStorage:**  stores data only for a session, meaning that the data is stored until the browser (or tab) is closed.

**cookie:** Stores data that has to be sent back to the server with subsequent XHR requests. Its expiration varies based on the type and the expiration duration can be set from either server-side or client-side .

|                                        | `cookie`                                                 | `localStorage` | `sessionStorage` |
| -------------------------------------- | -------------------------------------------------------- | -------------- | ---------------- |
| Initiator                              | Client or server. Server can use `Set-Cookie` header     | Client         | Client           |
| Expiry                                 | Manually set                                             | Forever        | On tab close     |
| Persistent across browser sessions     | Depends on whether expiration is set                     | Yes            | No               |
| Sent to server with every HTTP request | Cookies are automatically being sent via `Cookie` header | No             | No               |
| Capacity (per domain)                  | 4kb                                                      | 5MB            | 5MB              |
| Accessibility                          | Any window                                               | Any window     | Same tab         |


*Note: If the user decides to clear browsing data via whatever mechanism provided by the browser, this will clear out any `cookie`, `localStorage`, or `sessionStorage` stored. It's important to keep this in mind when designing for local persistance, especially when comparing to alternatives such as server side storing in a database or similar (which of course will persist despite user actions).*

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. In how many ways can we specify the CSS styles for the HTML element?

* `Inline:` Here we use the `style` attribute inside the HTML element.
* `Internal:` Here we use the `<style>` tag inside the `<head>` tag. To apply the style we bind the elements using `id` or `class` attributes.
* `External:` Here we use the `<link>` tag inside `<head>` tag to reference the CSS file into our HTML code. Again the binding between elements and styles is done using `id` or `class` attributes.

## Q. ***What is the difference between a `<span>` and a `<div>`?***

* `<div>` is a block level element which means it will render it on it's own line with a width of a 100% of the parent element.
* `<span>` is an inline element which means it will render on the same line as the previous element, if it is also an inline element, and it's width will be determined by it's content.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. Difference between link tag `<link>` and anchor tag `<a>`?

* The anchor tag `<a>` is used to create a hyperlink to another webpage or to a certain part of the webpage and these links are clickable, whereas, link tag `<link>` defines a link between a document and an external resource and these are not clickable.

## Q. How to specify the link in HTML and explain the target attribute?

HTML provides a hyperlink - `<a>` tag to specify the links in a webpage. The `href` attribute is used to specify the link and the `target` attribute is used to specify, where do we want to open the linked document. The ‘target’ attribute can have the following values:

* `_self`: This is a default value. It opens the document in the same window or tab as it was clicked.
* `_blank`: It opens the document in a new window or tab.
* `_parent`: It opens the document in a parent frame.
* `_top`: It opens the document in a full-body window.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. In how many ways you can display HTML elements?

* `inline`: Using this we can display any block-level element as an inline element. The height and width attribute values of the element will not affect.
* `block`: using this, we can display any inline element as a block-level element.
* `inline-block`: This property is similar to inline, except by using the display as inline-block, we can actually format the element using height and width values.
* `flex`: It displays the container and element as a flexible structure. It follows flexbox property.
* `inline-flex`: It displays the flex container as an inline element while its content follows the flexbox properties.
* `grid`: It displays the HTML elements as a grid container.
* `none`: Using this property we can hide the HTML element.

  <p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. What is the difference between `display: none` `visibility: hidden` and `opacity:  0` when used as attributes to the HTML element?

* `display: none`
  - Completely removes and doesn't render the element.
  - No space is reserved, and it's non-interactive.

* `visibility: hidden`
  - Hides the element but still occupies space.
  - The element remains interactive, affecting layout.

* `opacity: 0`
  - Renders the element transparent.
  - Space is reserved, and it remains interactive.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. ***Name 5 common block-level and inline HTML elements?***

* block elements `<h1>, <p>, <ul>, <ol>, <li>`,
* inline elements `<span>, <a>, <strong>, <i>, <img>`


## Q. ***What are semantic and non-semantic elements?***

* **Semantic elements**: clearly describes its meaning to both the browser and the developer. For example: `<form>`, `<table>`,  `<article>`, `<aside>`, `<details>`, `<figcaption>`, `<figure>`, `<footer>`, `<header>`, `<main>`, `<mark>`, `<nav>`, `<section>`, `<summary>`, `<time>` clearly defines its content.
  
* **Non-semantic elements**: `<div>` and `<span>` tells nothing about its content. 

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. ***What is Character Encoding?***

Character encoding is a method of converting bytes into characters. To validate or display an HTML document properly, a program must choose a proper character encoding. This is specified in the tag:

```html
<meta charset="utf-8"/>
```

* **UTF-8**: A Unicode Translation Format that comes in 8-bit units that is, it comes in bytes. A character in UTF8 can be from 1 to 4 bytes long, making UTF8 variable width.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. ***What is the purpose of meta tags?***

The META elements can be used to include name/value pairs describing properties of the HTML document, such as author, expiry date, a list of keywords, document author etc.

```html
<!DOCTYPE html>
<html>
  <head>
        <!--Recommended Meta Tags-->
        <meta charset="utf-8">
        <meta name="language" content="english"> 
        <meta http-equiv="content-type" content="text/html">
        <meta name="author" content="Author Name">
        <meta name="designer" content="Designer Name">
        <meta name="publisher" content="Publisher Name">
        <meta name="no-email-collection" content="name@email.com">
        <meta http-equiv="X-UA-Compatible" content="IE=edge"/>

        <!--Search Engine Optimization Meta Tags-->
        <meta name="description" content="Project Description">
        <meta name="keywords" content="Software Engineer,Product Manager,Project Manager,Data Scientist">
        <meta name="robots" content="index,follow">
        <meta name="revisit-after" content="7 days">
        <meta name="distribution" content="web">
        <meta name="robots" content="noodp">
      
    <title>HTML5 Meta Tags</title>
  </head>
  <body>
       ...
  </body>
</html>
```
<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. ***What does async and defer refer in script tag? Describe the difference between `<script>`, `<script async>` and `<script defer>`***

* **Async**: Downloads the script file during HTML parsing and will pause the HTML parser to execute it when it has finished downloading potentially before the HTML document is fully parsed..
  
   - Execution Order: If multiple scripts with the async attribute are present, they may be executed out of order, depending on which one finishes downloading first.

* **Defer**: Defer downloads the script file during HTML parsing and will only execute it after the HTML parser has completed. Not all browsers support this.

   - Execution Order: Scripts with defer are guaranteed to be executed in the order they are encountered in the HTML document.
    
The async attribute is used to indicate to the browser that the script file can be executed asynchronously. The HTML parser does not need to pause at the point it reaches the script tag to fetch and execute, the execution can happen whenever the script becomes ready after being fetched in parallel with the document parsing.

The defer attribute tells the browser to only execute the script file once the HTML document has been fully parsed. 

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. ***What are `data` attributes good for?***

* The HTML5 data attribute lets you assign custom data to an element. When we want to store more information/data about the element when no suitable HTML5 element or attribute exists
  
## Q. How can we club two or more rows or columns into a single row or column in an HTML table?

* HTML provides two table attributes `rowspan` and `colspan` to make a cell span to multiple rows and columns respectively.

## Q. ***Ways to improve website performance***

* Minimize HTTP Requests
    * Sites are mainly slow because of too many (or too large) HTTP requests. We can eliminate unnecessary request;
        * combined files: js to a file, css to a file
        * CSS sprites: CSS Sprites are the preferred method for reducing the number of image requests. Combine your background images into a single image and use the CSS background-image and background-position properties to display the desired image segment.

* Use a Content Delivery Network CDN

    * A CDN is essentially many optimized servers around the world that deliver web content to users based on their geographic location. This means big performance improvements for site users. Because, say, if a person accessing your site in India, they will be retrieving web content from a server nearby

* Optimize Images:

    * image sizes make a huge difference to site speed. The larger content/images, the slower the site. we could:
        * Changing the resolution: reducing the “quality” of the image (and thereby the file size)
        * Compressing the picture: increasing the efficiency of image data storage
        * Cropping the picture: when cropping, you are cutting out unneeded areas and thus making the image smaller in size

* Put Scripts at the Bottom:

    * Javascript files can load after the rest of your page. The simplest solution is to place your external Javascript files at the bottom of your page, just before the close of your body tag. Now more of your site can load before your scripts. Another method that allows even more control is to use the defer or async attributes when placing external .js files on your site.
        
        * Async tags load the scripts while the rest of the page loads, but this means scripts can be loaded out of order. Basically, lighter files load first. This might be fine for some scripts, but can be disastrous for others.
        
        * The defer attribute loads your scripts after your content has finished loading. It also runs the scripts in order. Just make sure your scripts run so late without breaking your site.

* Add an Expires or a Cache-Control Header

    * Web page designs are getting richer and richer, which means more scripts, stylesheets, images, and Flash in the page. A first-time visitor to your page may have to make several HTTP requests, but by using the Expires header you make those components cacheable. This avoids unnecessary HTTP requests on subsequent page views. Expires headers are most often used with images, but they should be used on all components including scripts, stylesheets, and Flash components.

* Gzip Components

    * Compression reduces response times by reducing the size of the HTTP response. Gzipping generally reduces the response size by about 70%.

* Put Stylesheets at the Top:

    * This is because putting stylesheets in the HEAD allows the page to render progressively.

* Avoid CSS Expressions

* Use GET for AJAX Requests:

    * Ajax is that it provides instantaneous feedback to the user because it requests information asynchronously from the backend web server

* Make JavaScript and CSS External:

    *  Using external files in the real world generally produces faster pages because the JavaScript and CSS files are cached by the browser. JavaScript and CSS that are inlined in HTML documents get downloaded every time the HTML document is requested. This reduces the number of HTTP requests that are needed, but increases the size of the HTML document. On the other hand, if the JavaScript and CSS are in external files cached by the browser, the size of the HTML document is reduced without increasing the number of HTTP requests.

* Use get to ajax request:

    *  POST is implemented in the browsers as a two-step process: sending the headers first, then sending data. So it's best to use GET, which only takes one TCP packet to send (unless you have a lot of cookies).

* No 404s:

    * HTTP requests are expensive so making an HTTP request and getting a useless response (i.e. 404 Not Found) is totally unnecessary and will slow down the user experience without any benefit.

* Reduce Cookie Size:

    * HTTP cookies are used for a variety of reasons such as authentication and personalization. Information about cookies is exchanged in the HTTP headers between web servers and browsers. It's important to keep the size of cookies as low as possible to minimize the impact on the user's response time.

* Reduce DNS Lookups
* Minify JavaScript and CSS
* Avoid Redirects
* Remove Duplicate Scripts
* Configure Etags
* Make Ajax Cacheable
* Post-load Components
* Preload Components
* Reduce the Number of DOM Elements
* Minimize the Number of iframes
* Minimize DOM Access
* Optimize CSS Sprites
* Don't Scale Images in HTML
* Make favicon.ico Small and Cacheable
* Avoid Empty Image src

<p align="right"><a href="#readme-top">[↑] back to top</a></p>


## 🦄   Author
> If you want to get in-touch with me you can reach me at:

-  [Email](https://mail.google.com/mail/?view=cm&to=hager.a.elhawary@gmail.com)
-  [LinkedIn](https://www.linkedin.com/in/hager-omar-elhawary/)
-  [GitHub](https://github.com/Hager-elhwarii)

## 📘 License
This project is **Totally Free**,  and does not contain any license.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>
