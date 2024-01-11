## Table of Contents

[Introduction ⬇](#introduction) </br>

- [HTML Tags ⬇](#html-tags)
- [HTML Comments ⬇](#comments)

[HTML Page Structure ⬇](#html-page-structure) </br>

[HTML Elements ⬇](#html-elements) </br>

- [Nested HTML Elements ⬇](#nested-html-element)
- [Block and Inline Elements ⬇](#block-inline-elements)

[Most time used Elements ⬇](#most-time-used-elements)

[Entities ⬇](#entities)

[Hyperlinks ⬇](#hyperlinks)

[Images ⬇](#images)

- [Picture ⬇](#picture)
- [Image Map ⬇](#image-map)

[Table ⬇](#table)

- [colspan, rowspan and colgroup ⬇](#col-row)

[List ⬇](#list)

[ifram ⬇](#iframe)

[HTML Attributes ⬇](#html-attributes) </br>

- [class and id ⬇](#class-id)

[Semantic HTML ⬇](#semantic-html) </br>

[HTML Forms ⬇](#html-form) </br>

- [input form ⬇](#input-form)

[Media and APIs ⬇](#media-apis)

[Head ⬇](#head) </br>

- [Meta ⬇](#meta) </br>
- [Link ⬇](#link) </br>
- [Icons ⬇](#icons) </br>

  <br />

## [Introduction](#introduction)

What is HTML ?

- HTML is the standard markup language for creating Web pages.

  - HTML stands for `Hyper Text Markup Language`
  - HTML describes the structure of Web pages using markup
  - HTML elements are the building blocks of HTML pages
  - HTML elements are represented by tags
  - HTML tags label pieces of content such as "heading", "paragraph", "table", and so on
  - Browsers do not display the HTML tags, but use them to render the content of the page
    <br />
    <br />

### [HTML Tags](#html-tags)

- HTML tags are element names surrounded by angle brackets `</>`：

- HTML tags normally come in pairs like `<p>` and `</p>`
  - The first tag in a pair is the start tag, the second tag is the end tag
  - The end tag is written like the start tag, but with a forward slash inserted before the tag name
  - The start tag is also called the **opening tag**, and the end tag the **closing tag**.

Use Lowercase Tags

- HTML tags are not case sensitive：`<P>` means the same as `<p>`.

- The HTML5 standard does not require lowercase tags, but W3C **recommends** lowercase in HTML, and demands lowercase for stricter document types like XHTML.
  <br />

### [HTML Comments](#comments)

HTML Comment

- Comment tags are used to insert comments in the HTML source code.

- You can add comments to your HTML source by using the following syntax：

  ```html
  <!-- Write your comments here -->
  ```

- There is an exclamation point `(!)` in the opening tag, but not in the closing tag.

- Comments are not displayed by the browser, but they can help document your HTML source code.

## [HTML page structure](#html-page-structure)

- All HTML documents must start with a document type declaration：`<!DOCTYPE html>`.

  > The <!DOCTYPE> declaration is not an HTML tag; it is an instruction to the web browser about what version of HTML the page is written in.

  > The <!DOCTYPE> declaration is NOT case sensitive.

- The HTML document itself begins with `<html>` and ends with `</html>`.

- The visible part of the HTML document is between `<body>` and `</body>`.

- Below is an HTML page structure：

  ```html
  <!DOCTYPE html>
  <html>
    <head>
      <title>Page Title</title>
    </head>

    <body>
      <h1>My First Heading</h1>
      <p>My first paragraph.</p>
    </body>
  </html>
  ```

  > Only the content inside the `<body>` section is displayed in a browser.

- Example Explained

  - The `<!DOCTYPE html>` declaration defines this document to be HTML5
  - The `<html>` element is the root element of an HTML page
  - The `<head>` element contains meta information about the document
  - The `<title>` element specifies a title for the document
  - The `<body>` element contains the visible page content
  - The `<h1>` element defines a large heading
  - The `<p>` element defines a paragraph

## [HTML Elements ⬇](#html-elements)

<a name="html-elements"></a>
HTML Elements

- An HTML element usually consists of a start tag and end tag, with the content inserted in between.

- The HTML element is everything from the start tag to the end tag.

- HTML elements with no content are called **empty elements**. Empty elements do not have an end tag, such as the `<br>` element (which indicates a line break).

<br />
<br />

#### [Nested HTML Elements](#nested-html-element)

- HTML elements can be nested (elements can contain elements).

- All HTML documents consist of nested HTML elements.
  <br />
  <br />

#### [Block and Inline Elements](#block-inline-elements)

Every HTML element has a default display value depending on what type of element it is. The default display value for most elements is block or inline.

**Block-level Elements**

- A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).

- Some examples of block-level elements：

  - `<div>`
  - `<h1> - <h6>`
  - `<p>`
  - `<form>`
    <br />
    <br />

**Inline Elements**

- An inline element does not start on a new line and only takes up as much width as necessary.

- Some Examples of inline elements：

  - `<span>`
  - `<a>`
  - `<img>`

<br />

## [Most time used Elements](#most-time-used-elements)

`<html>`: Defines the root of an HTML document.

`<head>`: Contains metadata about the HTML document, such as the title, character set, etc.

`<title>`: Sets the title of the HTML document.

`<body>`: Contains the content of the HTML document, such as text, images, links, etc.

`<h1>`, `<h2>`, `<h3>`, `<h4>`,`<h5>`, `<h6>`: Define headings of different levels (from largest to smallest).

`<p>`: Defines a paragraph.

`<a>`: Creates a hyperlink.

`<img>`: Embeds an image.

`<ul>`: Defines an unordered list.

`<ol>`: Defines an ordered list.

`<li>`: Defines a list item within `<ul>` or `<ol>`.

`<div>`: Defines a division or a section in an HTML document.

`<span>`: Defines an inline container.

`<br>`: Inserts a line break.

`<hr>`: Defines a horizontal line.

`<strong>` or `<b>`: Represents strong importance or bold text. `<strong>` is semantic tag.

`<em>` or `<i>`: Represents emphasized text or italic text. `<em>` is semantic tag.

`<blockquote>`: Defines a block of text that is a quotation from another source.

`<code>`: Defines a piece of computer code.

`<pre>`: Defines preformatted text.

<pre>          these line are
 using pre tag</pre>

`<small>`: Defines smaller text. It is often used to decrease the font size of text within the tag. <small>This is small</small>

`<sub>`: Defines subscript text, which appears half a character below the normal line. H<sub>2</sub>O

`<sup>`: Defines superscript text, which appears half a character above the normal line. 5<sup>2</sup>

`<mark>`: Defines text that should be highlighted or marked. <mark>marked</mark>

`<del>`: Defines text that has been deleted or removed from a document. It is often rendered with a strikethrough effect. <del>deleted</del>

`<blockquote>`: Defines a block of text that is a quotation from another source. The content within the `<blockquote>` tag is usually indented or styled to distinguish it from the surrounding text.

```html
<blockquote>
  <p>This is a quoted text from another source.</p>
</blockquote>
```

`<cite>`: Specifies the title of a creative work (e.g., a book, movie, or song) or the name of its author. It is often used within the `<blockquote>` tag to provide citation information.

```html
<blockquote>
  <p>This is a quote from a book.</p>
  <footer><cite>The Title of the Book</cite> - Author Name</footer>
</blockquote>
```

`<abbr>`: Used to define an abbreviation or acronym. It is often used to provide a full explanation or expansion of an abbreviation when a user hovers over the abbreviated text. The title attribute is used to specify the full form or explanation.

```html
<p>HTML stands for <abbr title="Hypertext Markup Language">HTML</abbr>.</p>
```

`<address>`: Used to define the contact information for the author or owner of a document or an article. It can include various types of contact information, such as an email address, physical address, phone number, etc.

```html
<address>
  <a href="mailto:jim@example.com">kmp@example.com</a><br />
  <a href="tel:+913445560132">+91 (344) 556‑0132</a>
</address>
```

mailto: and tel: are use to direct mail or call to the mentioned address.

`<bdo>`: (Bi-Directional Override) tag is used to override the current text
direction. It's primarily used in situations where the direction of text in a
block needs to be explicitly specified, overriding the default text direction
of the surrounding content.

```html

  <p>This text is in the default direction.</p>

  <bdo dir="rtl">This text will be displayed from right to left.
  </bdo>

  <p>This text is back to the default direction.</p>
  </bdo>
```

<a name="empty-html-elements"></a>
Empty HTML Elements

- HTML elements with no content are called empty elements.

- `<br>` and `</hr>` are empty element without a closing tag (the `<br>` tag defines a line break, the `</hr>` defines a horizontal ruler or line).

- Empty elements can be "closed" in the opening tag like this：`<br />`.

- HTML5 does not require empty elements to be closed. But if you want stricter validation, or if you need to make your document readable by XML parsers, you must close all HTML elements properly.

<br />

## [Entities](#entities)

HTML entities are special codes used to represent reserved characters and symbols in HTML. These entities help ensure that the characters are displayed correctly in browsers, regardless of the character encoding being used. Here are some common HTML entities:

#### Character Entities:

`&lt;` represents `<`

`&gt;` represents `>`

`&amp;` represents `&`

`&quot;` represents `"`

`&apos;` represents `(apostrophe ')`

#### Numeric Character References:

`&#65;` represents the ASCII character with the decimal code 65 (which is `'A'` in the ASCII table).

`&#x41;` represents the same character using hexadecimal representation.

#### Special Characters:

`&copy;` represents the copyright symbol `©`

`&reg;` represents the registered trademark symbol `®`

`&trade;` represents the trademark symbol `™`

`&nbsp;` represents a non-breaking space (useful for creating extra space)

## [Hyperlinks](#hyperlinks)

`<a href="URL">Link Text</a>`

`href`: Specifies the URL or destination of the link. It can be an absolute URL (e.g., "https://www.example.com") or a relative URL (e.g., `"page.html"`). If you want the link to perform some action on the current page or navigate to a specific section within the same page, you can use a hash (`#`) followed by an anchor name.

`target="_self"`: Opens the linked document in the same browsing context (e.g., the same tab or frame).

```html
<a href="https://www.example.com" target="_self">Open in this same tab</a>
```

`target="_blank"`: Opens the linked document in a new browsing context (e.g., a new tab or window). This is commonly used for links that should open in a new tab.

```html
<a href="https://www.example.com" target="_blank">Open in a new tab</a>
```

## [Images](#images)

The HTML <img> element is used to embed images into a web page. It stands for "image" and is an empty, self-closing tag, meaning it doesn't have a closing tag.

```html
<img src="image.jpg" alt="Description of the image" />
```

`src` (source): This attribute is required and specifies the URL or file path of the image. It can be a relative or absolute path to the image file or a URL.

`alt` (alternative text): This attribute is also required. It provides a text description of the image, which is displayed if the image cannot be loaded or for accessibility purposes. Screen readers use the alternative text to describe the image to users with visual impairments.

### Example with dimensions:

```html
<img src="image.jpg" alt="Description of the image" width="300" height="200" />
```

`width`: Specifies the width of the image in pixels.

`height`: Specifies the height of the image in pixels.

### [Picture `<picture>`](#picture)

The `<picture>` element in HTML is used to contain multiple `<source>` elements along with an `<img>` element to provide various sources for an image, allowing the browser to choose the most suitable one based on different conditions like screen resolution or viewport width.

Here's the basic structure of a `<picture>` element:

```html
<picture>
  <!-- Source elements with different image sources and descriptors -->
  <source srcset="image-large.jpg" media="(min-width: 1200px)" />
  <source srcset="image-medium.jpg" media="(min-width: 600px)" />
  <!-- Fallback image in case none of the sources match -->
  <img src="image-small.jpg" alt="Description of the image" />
</picture>
```

Inside the `<picture>` element, you include one or more `<source>` elements. Each `<source>` element contains the srcset attribute, which specifies the image sources and their descriptors.

The `media` attribute in each `<source>` element contains a media query. If the conditions specified in the media query are met (e.g., screen width is at least 1200px), the associated image source is considered.

The `<img>` element serves as a fallback. If none of the conditions in the `<source>` elements are met, the browser will use the image specified in the `<img>` element.

### [Image Map](#image-map)

image map in HTML is a way of associating multiple clickable regions (or hotspots) within a single image with different hyperlinks.

example :-

```html
<body>
  <img src="image.jpg" alt="Clickable Image" usemap="#exampleMap" />

  <map name="exampleMap">
    <!-- Define the coordinates and shape of the clickable regions -->
    <area shape="rect" coords="0,0,100,100" href="page1.html" alt="Link 1" />
    <area shape="circle" coords="150,150,50" href="page2.html" alt="Link 2" />
    <area
      shape="poly"
      coords="250,0,300,50,200,100"
      href="page3.html"
      alt="Link 3"
    />
  </map>
</body>
```

The `<img>` element includes the usemap attribute, which references the name of the associated <map> element.

The `<map>` element contains one or more <area> elements, each defining a clickable region within the image.

The `shape` attribute of the `<area>` element specifies the shape of the clickable region. It can be `"rect"` (rectangle), `"circle"` (circle), or `"poly"` (polygon).

The `coords` attribute in each `<area>` element provides the coordinates of the clickable region. The format of the coordinates depends on the shape.

The `href` attribute in each `<area>` element specifies the URL that the user will be directed to when clicking within that specific region.

## [Table](#table)

<table border="1">
<thead>
<tr>
<th>Country</th>
<th>Country Code</th>
<th>Capital</th>
</tr>
</thead>
<tbody>
<tr>
<td>India</td>
<td>IN</td>
<td>New Delhi</td>
</tr>
<tr>
<td>United States of America</td>
<td>USA</td>
<td>Washington D.C.</td>
</tr>
<tr>
<td>Japan</td>
<td>JP</td>
<td>Tokyo</td>
</tr>
</tbody>
 </table>

```html
<table border="1">
  <thead>
    <tr>
      <th>Country</th>
      <th>Country Code</th>
      <th>Capital</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>India</td>
      <td>IN</td>
      <td>New Delhi</td>
    </tr>
    <tr>
      <td>United States of America</td>
      <td>USA</td>
      <td>Washington D.C.</td>
    </tr>
    <tr>
      <td>Japan</td>
      <td>JP</td>
      <td>Tokyo</td>
    </tr>
  </tbody>
</table>
```

`<table border="1">`: This sets up the table with a border attribute set to "1," which will display a border around the table.

`<thead>`: This is the table header section, containing a single table row (`<tr>`).

`<tr>`: This represents a table row within the table header. It contains three header cells (`<th>`): "Country," "Country Code," and "Capital."

`<tbody>`: This is the table body section, containing multiple data rows.

Additional `<tr>` elements: These represent individual data rows within the table body.

`<td>` elements: These represent individual data cells within each row. They contain actual data for each column.

### [colspan, rowspan and colgroup](#col-row)

<table border="1">
    <colgroup>
      <!-- Define the width of the first two columns -->
      <col style="width: 150px;">
      <col style="width: 100px; background-color:#313131;">
      <!-- The third column will take the remaining space -->
      <col>
    </colgroup>
    <thead>
      <tr>
        <th rowspan="2">Country</th>
        <th colspan="2">Details</th>
      </tr>
      <tr>
        <th>Code</th>
        <th>Capital</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>India</td>
        <td>IN</td>
        <td>New Delhi</td>
      </tr>
      <tr>
        <td>United States of America</td>
        <td>USA</td>
        <td>Washington D.C.</td>
      </tr>
      <tr>
        <td>Japan</td>
        <td>JP</td>
        <td>Tokyo</td>
      </tr>
    </tbody>
  </table>

```html
<table border="1">
  <colgroup>
    <!-- Define the width of the first two columns -->
    <col style="width: 150px;" />
    <col style="width: 100px;" />
    <!-- The third column will take the remaining space -->
    <col />
  </colgroup>
  <thead>
    <tr>
      <th rowspan="2">Country</th>
      <th colspan="2">Details</th>
    </tr>
    <tr>
      <th>Code</th>
      <th>Capital</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>India</td>
      <td>IN</td>
      <td>New Delhi</td>
    </tr>
    <tr>
      <td>United States of America</td>
      <td>USA</td>
      <td>Washington D.C.</td>
    </tr>
    <tr>
      <td>Japan</td>
      <td>JP</td>
      <td>Tokyo</td>
    </tr>
  </tbody>
</table>
```

`<colgroup>`: This element is used to group together and apply styles to a set of columns. In this example, it is used to define the widths of the columns.

`<col>`: Represents an individual column within the `<colgroup>`. Styles are applied to set the width of the first two columns, while the third column will take the remaining space.

`<thead>`: The table header section.

`<tr>`: Table row.

`<th rowspan="2">`: Header cell that spans two rows, containing the label "Country."

`<th colspan="2">`: Header cell that spans two columns, containing the label "Details."

## [List](#list)

<h4>Unorderd List</h4>
  <ul style="list-style-type: square;">
    <li>1</li>
    <li>2</li>
    <li>3</li>
  </ul>

<h4>Ordered List</h4>
  <ol type="A">
    <li>one</li>
    <li>two</li>
    <li>three</li>
  </ol>

  <h4>Nested List</h4>
  <ul style="list-style-type: square">
    <li>
      First
      <ol>
        <li>first.1</li>
        <li>first.2</li>
      </ol>
    </li>
    <li>
      Second
      <ol>
        <li>second.1</li>
        <li>second.2</li>
      </ol>
    </li>
  </ul>

   <h4>Description List</h4>
    <dl>
      <dt>HTML</dt>
      <dd>HyperText Markup Language</dd>
      <dt>CSS</dt>
      <dd>Cascading Style Sheets</dd>
    </dl>

```html
<h4>Unorderd List</h4>
<ul style="list-style-type: square">
  <li>1</li>
  <li>2</li>
  <li>3</li>
</ul>

<h4>Ordered List</h4>
<ol type="A">
  <li>one</li>
  <li>two</li>
  <li>three</li>
</ol>

<h4>Nested List</h4>
<ul style="list-style-type: square">
  <li>
    First
    <ol>
      <li>first.1</li>
      <li>first.2</li>
    </ol>
  </li>
  <li>
    Second
    <ol>
      <li>second.1</li>
      <li>second.2</li>
    </ol>
  </li>
</ul>

<h4>Description List</h4>

<!-- Description list -->
<dl>
  <!-- Term and Definition Pair 1 -->
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>

  <!-- Term and Definition Pair 2 -->
  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
</dl>
```

### [iframe](#iframe)

An `<iframe>` (Inline Frame) is an HTML element used to embed another HTML document or content from an external source within the current document. It allows you to include content from one webpage into another, often used for embedding videos, maps, or external web pages.

```html
<h2>Embedding a YouTube Video</h2>

<!-- The iframe element with the source attribute pointing to a YouTube video -->
<iframe
  width="560"
  height="315"
  src="https://www.youtube.com/embed/dQw4w9WgXcQ"
  frameborder="0"
  allowfullscreen
></iframe>
```

The `<iframe>` element is used to embed a YouTube video.

The `src` attribute contains the URL of the external content (in this case, a YouTube video). Make sure to use the embeddable link provided by the external service.

The `width` and `height` attributes determine the dimensions of the `iframe`.

The `frameborder` attribute is set to `"0"` to remove the border around the `iframe`.

The `allowfullscreen` attribute allows the content to be viewed in full-screen mode.

<br />

## [HTML Attributes](#html-attributes)

HTML Attributes

- All HTML elements can have attributes.

- Attributes provide additional information about an element.

- Attributes are always specified in the start tag.

- Attributes usually come in name/value pairs like：name="value".

<br />
<br />

<a name="global-attributes"></a>
Global Attributes

- [The global attributes]() can be used on **any** HTML element, such as `id`, `class` and `style`.

### [class and id](#class-id)

The `class` and `id` attributes in HTML are commonly used to select and target elements.

`class` Attribute:
The `class` attribute is used to apply a style or group of styles to multiple HTML elements. You can assign the same `class` to multiple elements, and a single element can have multiple classes.

<style>
  .highlight {
    color: red;
    font-weight: bold;
  }
</style>

<p class="highlight">This paragraph has the "highlight" class.</p>
<div class="highlight">This div also has the "highlight" class.</div>

```html
<style>
  .highlight {
    color: red;
    font-weight: bold;
  }
</style>

<p class="highlight">This paragraph has the "highlight" class.</p>
<div class="highlight">This div also has the "highlight" class.</div>
```

`id` Attribute:
The `id` attribute is used to uniquely identify a specific HTML element on a page. Each `id` attribute within a page must be unique, meaning no two elements should have the same `id`.

<style>
  #uniqueElement {
    background-color: lightblue;
  }
</style>

<div id="uniqueElement">This div has the unique "uniqueElement" id.</div>

```html
<style>
  #uniqueElement {
    background-color: lightblue;
  }
</style>

<div id="uniqueElement">This div has the unique "uniqueElement" id.</div>
```

<br />
<br />

## [Semantic HTML](#semantic-html)

Semantic HTML refers to the use of HTML elements to convey meaning about the structure and content of a web page, rather than just presentation. Using semantic elements helps both browsers and developers understand the purpose and context of the content, leading to better accessibility, search engine optimization (SEO), and maintainability.

- Here are some commonly used semantic HTML elements:

`<header>`: Represents a header section that typically contains a logo, navigation, and other introductory content for a page or section.

`<nav>`: Represents a navigation menu, usually containing links to other pages or sections of the same document.

`<main>`: Represents the main content of a document, excluding headers, footers, and sidebars.

`<article>`: Represents a self-contained piece of content that could be distributed and reused independently, such as a news article or blog post.

`<section>`: Represents a thematic grouping of content within a document. It helps organize content into meaningful sections.

`<aside>`: Represents content that is tangentially related to the content around it, often used for sidebars or pull quotes.

`<footer>`: Represents a footer section that typically contains metadata, copyright information, or links to related documents.

`<figure>` and `<figcaption>`:

`<figure>` is used to encapsulate media content, such as images or videos.
`<figcaption>` provides a caption for the content within the `<figure>`.

`<time>`: Represents a specific period in time or a range of time. It is often used to mark up dates, times, or durations.

`<mark>`: Represents text that has been highlighted or marked for reference or emphasis.

`<blockquote>` and `<cite>`:

`<blockquote>` is used to represent a block of text quoted from another source.

`<cite>` is used to provide the source or author of the quote.

## [HTML Forms](#html-form)

```html
<form action="/submit" method="post" autocomplete="off">
  <!-- Text Input -->
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" required />

  <!-- Password Input -->
  <label for="password">Password:</label>
  <input type="password" id="password" name="password" required />

  <!-- Radio Buttons -->
  <fieldset>
    <legend>Gender:</legend>
    <label><input type="radio" name="gender" value="male" /> Male</label>
    <label><input type="radio" name="gender" value="female" /> Female</label>
  </fieldset>

  <!-- Dropdown (Select) -->
  <label for="country">Country:</label>
  <select id="country" name="country">
    <option value="usa">United States</option>
    <option value="canada">Canada</option>
    <option value="uk">United Kingdom</option>
  </select>

  <!-- Checkbox -->
  <label
    ><input type="checkbox" name="subscribe" checked /> Subscribe to
    newsletter</label
  >

  <!-- Textarea -->
  <label for="comments">Comments:</label>
  <textarea id="comments" name="comments" rows="4" cols="50"></textarea>

  <!-- Submit Button -->
  <button type="submit">Submit</button>
</form>
```

The `<form>` element wraps the entire form and has attributes:

`action`: Specifies the URL where the form data should be sent.

`method`: Specifies the HTTP method (e.g., `"get"` or `"post"`) used to submit the form data.

`autocomplete`: attribute is used to control whether the browser should automatically complete form fields based on user input.

Various form controls include:

`<input>` for text input and password.

`<select>` for dropdown lists.

`<textarea>` for multiline text input.

`<button>` for submitting the form.

Additional attributes used in form controls:

`id` and `name`: Identify form controls and are used for scripting and styling.

`label`: Provides a text label for form controls.

`required`: Specifies that a form control must be filled out before submitting the form.

`checked`: Pre-checks a checkbox or radio
button.

### [input form ](#input-form)

```html
<form action="">
  <label for="username">Username:</label>
  <input type="text" id="username" placeholder="Username" />

  <!-- Color Input -->
  <label for="colorPicker">Choose a color:</label>
  <input type="color" id="colorPicker" name="colorPicker" value="#ff0000" />

  <br />

  <!-- File Input -->
  <label for="fileUpload">Choose a file:</label>
  <input
    type="file"
    id="fileUpload"
    name="fileUpload"
    accept=".jpg, .jpeg, .png"
  />

  <label for="email">Email:</label>
  <input type="text" id="email" placeholder="Email" />

  <label for="password">Password:</label>
  <input type="password" name="password" id="password" />

  <input type="reset" value="reset" />
  <select name="editors" id="" multiple>
    <option value="vscode">vscode</option>
    <option value="sublime">sublime</option>
  </select>

  <label for="volume">Volume:</label>
  <input
    type="range"
    id="volume"
    name="volume"
    min="0"
    max="100"
    value="50"
    step="5"
    list="tickmarks"
  />
  <!--min="0" :min="0" Minimum value of the slider -->
  <!-- max="100": Maximum value of the slider -->
  <!--  value="50": Default value of the slider -->
  <!-- step="5": Increment/decrement step for the slider -->
  <!-- list="tickmarks": Reference to a datalist for custom tick marks -->

  <datalist id="tickmarks">
    <option value="0">0</option>
    <option value="25">25</option>
    <option value="50">50</option>
    <option value="75">75</option>
    <option value="100">100</option>
  </datalist>
</form>
```

## [Media and APIs](#media-apis)

### Media

```html
<!-- Video Player -->
<video
  controls
  width="640"
  height="360"
  poster="thumbnail.jpg"
  preload="metadata"
>
  <source src="sample.mp4" type="video/mp4" />
  <!-- Specify the video source and type -->
  Your browser does not support the video tag.
</video>
<!-- Audio Player -->
<audio controls preload="auto">
  <source src="audio.mp3" type="audio/mpeg" />
  <!-- Specify the audio source and type -->
  Your browser does not support the audio tag.
</audio>
```

`controls`: This attribute enables the default browser controls for play, pause, volume, and other functions.

`width` and `height`: These attributes set the dimensions of the video player.

`poster`: This attribute provides a URL for an image to be displayed as the `poster` frame before the video starts playing.

`preload`: This attribute determines how much of the video or audio should be preloaded.
`"metadata"` preloads only metadata, while `"auto"` preloads the entire file.

`<source>`: This element is used to specify the source file and its type. Multiple `<source>` elements can be used to provide different formats for broader browser compatibility.

### API

`HTML` itself does not have the capability to directly interact with `APIs` (Application Programming Interfaces) because `HTML` is a markup language for structuring content on the web. However, you can use `JavaScript`, often in conjunction with `HTML`, to make `API` requests and handle the responses.

# [🤯 HEAD](#head)

> A simple guide to HTML `<head>` elements

## Recommended Minimum

Below are the essential elements for any web document (websites/apps):

```html
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<!--
  The above 2 meta tags *must* come first in the <head>
  to consistently ensure proper document rendering.
  Any other head element should come *after* these tags.
 -->
<title>Page Title</title>
```

`meta charset` - defines the encoding of the website, `utf-8` is the standard

`meta name="viewport"` - viewport settings related to mobile responsiveness

`width=device-width` - use the physical width of the device (great for mobile!)

`initial-scale=1` - the initial zoom, 1 means no zoom

Valid `<head>` elements include `meta`, `link`, `title`, `style`, `script`, `noscript`, and `base`.

These elements provide information for how a document should be perceived, and rendered, by web technologies. e.g. browsers, search engines, bots, etc.

```html
<!--
  Set the character encoding for this document, so that
  all characters within the UTF-8 space (such as emoji)
  are rendered correctly.
-->
<meta charset="utf-8" />

<!-- Set the document's title -->
<title>Page Title</title>

<!-- Set the base URL for all relative URLs within the document -->
<base href="https://example.com/page.html" />

<!-- Link to an external CSS file -->
<link rel="stylesheet" href="styles.css" />

<!-- Used for adding in-document CSS -->
<style>
  /* ... */
</style>

<!-- JavaScript & No-JavaScript tags -->
<script src="script.js"></script>
<script>
  // function(s) go here
</script>
<noscript>
  <!-- No JS alternative -->
</noscript>
```

## [Meta](#meta)

```html
<!--
  The following 2 meta tags *must* come first in the <head>
  to consistently ensure proper document rendering.
  Any other head element should come *after* these tags.
-->
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />

<!--
  Allows control over where resources are loaded from.
  Place as early in the <head> as possible, as the tag  
  only applies to resources that are declared after it.
-->
<meta http-equiv="Content-Security-Policy" content="default-src 'self'" />

<!-- Name of web application (only should be used if the website is used as an app) -->
<meta name="application-name" content="Application Name" />

<!-- Theme Color for Chrome, Firefox OS and Opera -->
<meta name="theme-color" content="#4285f4" />
<!-- List of keywords or phrases that described the content of an HTML document.-->

<meta name="keywords" content="web development, HTML, CSS, JavaScript, SEO" />

<!-- Short description of the document (limit to 150 characters) -->
<!-- This content *may* be used as a part of search engine results. -->
<meta name="description" content="A description of the page" />

<!-- All Search Engines -->
<meta name="googlebot" content="index,follow" /><!-- Google Specific -->

<!-- Tells Google not to provide a translation for this document -->
<meta name="google" content="notranslate" />

<!-- The Refresh meta tag is used to automatically refresh or redirect a web page after a specified number of seconds. -->

<meta http-equiv="refresh" content="5;url=https://example.com" />

<!-- The <base> element defining the base URL -->
<base href="https://www.example.com/" />
```

- 📖 [Meta tags that Google understands](https://support.google.com/webmasters/answer/79812?hl=en)
- 📖 [WHATWG Wiki: MetaExtensions](https://wiki.whatwg.org/wiki/MetaExtensions)
- 📖 [ICBM on Wikipedia](https://en.wikipedia.org/wiki/ICBM_address#Modern_use)
- 📖 [Geotagging on Wikipedia](https://en.wikipedia.org/wiki/Geotagging#HTML_pages)

## [Link](#link)

```html
<!-- Points to an external stylesheet -->
<link rel="stylesheet" href="https://example.com/styles.css" />

<!-- Provides information about an author or another person -->
<link rel="me" href="https://google.com/profiles/thenextweb" type="text/html" />
<link rel="me" href="mailto:name@example.com" />
<link rel="me" href="sms:+15035550125" />

<!-- The first, last, previous, and next documents in a series of documents, respectively -->
<link rel="first" href="https://example.com/article/" />
<link rel="last" href="https://example.com/article/?page=42" />
<link rel="prev" href="https://example.com/article/?page=1" />
<link rel="next" href="https://example.com/article/?page=3" />
```

## [Icons](#icons)

```html
<!-- For IE 10 and below -->
<!-- Place favicon.ico in the root directory - no tag necessary -->

<!-- Icon in the highest resolution we need it for -->
<link rel="icon" sizes="192x192" href="/path/to/icon.png" />

<!-- Apple Touch Icon (reuse 192px icon.png) -->
<link rel="apple-touch-icon" href="/path/to/apple-touch-icon.png" />

<!-- Safari Pinned Tab Icon -->
<link rel="mask-icon" href="/path/to/icon.svg" color="blue" />
```

