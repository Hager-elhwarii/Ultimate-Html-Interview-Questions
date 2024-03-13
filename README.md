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
| 07.|[In how many ways can we specify the CSS styles for the HTML element?](#q-in-how-many-ways-can-we-specify-the-css-styles-for-the-html-element)|
| 08.|[What is HTML Character Entities?](#q-what-is-html-character-entities)|
| 09.|[What is a marquee?](#q-what-is-a-marquee)|
| 10.|[What is the difference between href and src attributes?](#q-what-is-the-difference-between-href-and-src-attributes)|
| 11.|[Differentiate between inline, inline-block and block elements.](#q-differentiate-between-inline-inline-block-and-block-elements)|
| 12.|[What is the difference between a `<span>` and a `<div>`?](#q-what-is-the-difference-between-a-span-and-a-div)|
| 13.|[Define what is a Box model?](#q-define-what-is-a-box-model)|
| 14.|[Define Web Worker in HTML?](#q-define-web-worker-in-html)|
| 15.|[What is the difference between an absolute and relative URL?](#q-what-is-the-difference-between-an-absolute-and-relative-url)|
| 16.|[Difference between link tag `<link>` and anchor tag `<a>`?](#q-difference-between-link-tag-link-and-anchor-tag-a)|
| 17.|[How to specify the link in HTML and explain the target attribute?](#q-how-to-specify-the-link-in-html-and-explain-the-target-attribute)|
| 18.|[In how many ways you can display HTML elements?](#q-in-how-many-ways-you-can-display-html-elements)|
| 19.|[What is the difference between `display: none` `visibility: hidden` and `opacity: 0` when used as attributes to the HTML element?](#q-what-is-the-difference-between-display-none-visibility-hidden-and-opacity-0-when-used-as-attributes-to-the-html-element)|
| 20.|[Name 5 common block-level and inline HTML elements?](#q-name-5-common-block-level-and-inline-html-elements)|
| 21.|[What are semantic and non-semantic elements?](#q-what-are-semantic-and-non-semantic-elements)|
| 22.|[What is the role of the alt attribute in HTML?](#q-what-is-the-role-of-the-alt-attribute-in-html)|
| 23.|[What is Character Encoding?](#q-what-is-character-encoding)|
| 24.|[What is the purpose of meta tags?](#q-what-is-the-purpose-of-meta-tags)|
| 25.|[What does async and defer refer in script tag? Describe the difference between `<script>`, `<script async>` and `<script defer>`](#q-what-does-async-and-defer-refer-in-script-tag-describe-the-difference-between-script-script-async-and-script-defer)|
| 26.|[What are `data` attributes good for?](#q-what-are-data-attributes-good-for)|
| 27.|[Differentiate between tags and elements in HTML?](#q-eifferentiate-between-tags-and-elements-in-html)|
| 28.|[How can we club two or more rows or columns into a single row or column in an HTML table?](#q-how-can-we-club-two-or-more-rows-or-columns-into-a-single-row-or-column-in-an-html-table)|
| 29.|[What is SEO and How to improve it?](#q-what-is-seo-and-how-to-improve-it)|
| 30.|[Ways to improve website performance](#q-ways-to-improve-website-performance)|


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

* `Inline:` Here we use the **style** attribute inside the HTML element.
* `Internal:` Here we use the **<style>** tag inside the **<head>** tag. To apply the style we bind the elements using **id** or **class** attributes.
* `External:` Here we use the **<link>** tag inside **<head>** tag to reference the CSS file into our HTML code. Again the binding between elements and styles is done using **id** or **class** attributes.

## Q. What is HTML Character Entities?

HTML character entities are special codes used to represent characters that have a specific meaning or reserved purpose in HTML, preventing them from being treated as regular HTML code. These entities begin with an ampersand (&) and end with a semicolon (;).

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. What is a marquee?

A marquee allows you to put scrolling text on a web page. To do this, place whatever text you want to appear scrolling within the <marquee> and </marquee> tags.

## Q. What is the difference between href and src attributes?

* `href` is for hyperlinks, typically used with anchor <a> pointing to the location of a linked resource.
  
* `src` is for embedded content, typically included using elements like <img>, <audio>, <video> indicating the source URL of the resource being included.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. Differentiate between inline, inline-block and block elements?

 * `Inline elements`
   - Do not start on a new line.
   - Occupy only as much width as necessary .
   - Do not respect vertical styling such as padding, margin, width, and height.
  
* `Inline-block elements`
   - Can start on a new line if there's enough space.
   - Behave like inline elements but allow setting width, height, margins, and paddings.
  
* `Block elements`
  - Start on a new line.
  - Occupy the full width available.
  - Allow setting width, height, margins, and paddings.
  - Respect vertical styling such as padding, margin, width, and height.

  <p align="right"><a href="#readme-top">[↑] back to top</a></p>


## Q. ***What is the difference between a `<span>` and a `<div>`?***

* `<div>` is a block level element which means it will render it on it's own line with a width of a 100% of the parent element.
* `<span>` is an inline element which means it will render on the same line as the previous element, if it is also an inline element, and it's width will be determined by it's content.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. Define what is a Box model?

A box model provides the description for how elements are sized and displayed on the page. Each page may have a width, height, padding, borders, and margins. This is related to the CSS styling property.

## Q. Define Web Worker in HTML?

Web worker is a multithread object used for executing JavaScript. It runs in the background and doesn’t affect the performance of the webpage or application.

## Q. What is the difference between an absolute and relative URL?
* An `absolute URL` includes the full web address, the protocol (such as http or https) and the domain name (such as www.example.com). 
* A `relative URL`, on the other hand, specifies the location of a resource relative to the current web page. For example, a relative URL might include the file path (such as /images/picture.jpg) or the relative path (such as ../images/picture.jpg).
  
  <p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. Difference between link tag `<link>` and anchor tag `<a>`?

* The anchor tag `<a>` is used to create a hyperlink to another webpage or to a certain part of the webpage and these links are clickable, whereas, link tag `<link>` defines a link between a document and an external resource and these are not clickable.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

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

## Q. What is the difference between `display: none` `visibility: hidden` and `opacity: 0` when used as attributes to the HTML element?

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

## Q. What is the role of the alt attribute in HTML?

The alt attribute provides alternative text for an image in case the image cannot be displayed. This is important for accessibility, as screen readers can read the alt text to describe the image to visually impaired users.

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

* The HTML5 data attribute lets you assign custom data to an element. When we want to store more information/data about the element when no suitable HTML5 element or attribute exists.

## Q. Differentiate between tags and elements in HTML?

* `Tag` A keyword or code enclosed in angle brackets (<>) used to define HTML elements.
* `Element` A combination of an opening tag, its content, and a closing tag (if applicable), representing the building blocks of HTML documents.
  
## Q. How can we club two or more rows or columns into a single row or column in an HTML table?

* HTML provides two table attributes `rowspan` and `colspan` to make a cell span to multiple rows and columns respectively.

  <p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. What is SEO and How to improve it?

SEO (Search Engine Optimization) is the process of optimizing your website to improve its visibility and ranking in search engine results pages (SERPs). The goal of SEO is to attract more organic (non-paid) traffic to your website by increasing its relevance and authority in the eyes of search engines like Google, Bing, and Yahoo.

Key strategies to improve `SEO` :
  
 - `Keyword Research` : Identify relevant keywords and phrases that your target audience is likely to use when searching for products, services, or information related to your website. Use keyword research tools like 
 Google Keyword Planner, SEMrush, or Ahrefs to discover high-volume and low-competition keywords.

- `On-Page Optimization` : Optimize your website's on-page elements such as titles, meta descriptions, headings, and content to include your target keywords naturally. Ensure that your content is high-quality, valuable, and relevant to your audience.

- `Quality Content`: Create original, informative, and engaging content that provides value to your audience. Regularly update your website with fresh content, such as blog posts, articles, videos, infographics, and other multimedia formats.

- `Mobile Optimization` : Ensure that your website is mobile-friendly and responsive, as more searches are now performed on mobile devices than on desktop computers. Optimize your website's design and layout for smaller screens and faster loading times.

- `Site Speed` : Improve your website's loading speed by optimizing images, minimizing code, using browser caching, and leveraging content delivery networks (CDNs). Faster-loading websites tend to rank higher in search results and provide a better user experience.

- `User Experience (UX)` : Enhance the user experience of your website by making it easy to navigate, with clear calls-to-action (CTAs), intuitive menus, and user-friendly design. Search engines prioritize websites that offer a positive UX.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>

## Q. ***Ways to improve website performance***

* `Minimize HTTP Requests`:
   - Combine files like JavaScript and CSS into single files.
   - Use CSS sprites to reduce the number of image requests.

* `Utilize a Content Delivery Network (CDN)`:
   - Deliver web content from optimized servers around the world, improving load times.

* `Optimize Images`:
   - Reduce image sizes by changing resolution, compressing, or cropping.

* `Place Scripts at the Bottom`:
   - Allow the rest of the page to load before JavaScript files by placing them at the bottom of the page or using attributes like defer or async.
   - Use Expires or Cache-Control Headers:
   - Make components cacheable to avoid unnecessary HTTP requests on subsequent page views.

* `Enable Gzip Compression`:
   - Reduce response sizes by about 70% to improve load times.

* `Put Stylesheets at the Top`:
   - Render pages progressively by placing stylesheets in the HEAD of HTML documents.

* `Avoid CSS Expressions`:
   - They can significantly slow down page rendering.

* `Use GET for AJAX Requests`:
   - GET requests are generally faster than POST requests for AJAX.

* `Make JavaScript and CSS External`:
   - Improve page loading times by using external files that can be cached by the browser.

* `Avoid 404 Errors`:
   - Eliminate unnecessary HTTP requests and improve user experience.

*`Reduce Cookie Size`:
  - Minimize the impact on response time by keeping HTTP cookie sizes low.

* `Minify JavaScript and CSS`:
   - Reduce file sizes by removing unnecessary characters and white spaces.

* `Avoid Redirects`:
   - Redirects add extra HTTP requests and increase load times.

* `Remove Duplicate Scripts`:
   - Eliminate unnecessary duplication to streamline page loading.

* `Configure Etags`:
   - Use Etags effectively to reduce unnecessary HTTP requests.

* `Make Ajax Cacheable`:
   - Cache AJAX requests to improve performance.

* `Post-load Components`:
   - Load non-essential components after the main content.

* `Preload Components`:
   - Anticipate user actions and preload necessary components.

* `Reduce the Number of DOM Elements`:
   - Simplify page structure to improve rendering speed.

* `Minimize iframes`:
   - Limit the use of iframes to reduce page complexity.

* `Minimize DOM Access`:
   - Optimize JavaScript to minimize DOM manipulation.

* `Optimize CSS Sprites`:
   - Combine background images into CSS sprites to reduce image requests.

* `Avoid Scaling Images in HTML`:
   - Resize images before displaying them to reduce page load times.

* `Make favicon.ico Small and Cacheable`:
   - Optimize the favicon.ico file for faster loading.

* `Avoid Empty Image src Attributes`:
   - Eliminate unnecessary image requests by removing empty src attributes.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>


## 🦄   Author
> If you want to get in-touch with me you can reach me at:

-  [Email](https://mail.google.com/mail/?view=cm&to=hager.a.elhawary@gmail.com)
-  [LinkedIn](https://www.linkedin.com/in/hager-omar-elhawary/)
-  [GitHub](https://github.com/Hager-elhwarii)

## 📘 License
This repository is **Totally Free**,  and does not contain any license.

<p align="right"><a href="#readme-top">[↑] back to top</a></p>
