# HTML-and-CSS 

 
HTML (HyperText Markup Language) is the standard language used to create web pages. It is used to structure content and add elements such as headings, paragraphs, images, links, and more.

CSS (Cascading Style Sheets) is used to describe the presentation of HTML documents. It allows you to control layout and appearance by defining styles for elements such as fonts, colors, margins, borders, and more.


## Your First Web Page
Creating a web page is quite easy! We simply need to create a file, put some text into it, and open it within a web browser. 
While you can use any text editor, web developers often use editors that are better suited for programming. 
These are called code editors or Integrated Development Environments (IDEs

3. Create a new file called `webpage.html` and type the following code into it:


```html
<html>
    <head>
        <title>My First web page</title>
    </head>
    <body>
        Hello HTML and CSS
    </body>
</html>

```

Save the file once you've added the code. We'll take a closer look at the code shortly.

## Wireframes for Web Pages

When building a web page, it's a good idea to plan ahead and create a wireframe before diving into the code.

<img src="https://i.imgur.com/5FwNvaG.png" width="480">



- A wireframe is a rough drawing of what the page should look like.


- It serves as a visual guide while you're writing the HTML & CSS code


- You can create a wireframe using pen and paper, or using digital whiteboards like [excalidraw.com](https://excalidraw.com)


- Separating the design and implementation processes helps you focus on one component at a time

 

The following wireframe was created using [excalidraw.com](https://excalidraw.com) :

Let's recall the problem statement and create a wireframe:

> **Excercies**: Create a web page that showcases Cource listing for Exceed, including the following:
> 
> - A navbar at the top showing the Exceed logo
> - A header section displaying a picture and some relevant information
> - A list of cources
> - A footer at the bottom of the web page with important links
>
> Make the page visually appealing and informative.


## Adding Content in HTML

Different tags are used to create headings, paragraphs, lists, images, links, and other elements. Let's build our page step by step using various tags.

### Headings

HTML headings are used to create headings or titles within a web page


<img src="https://i.imgur.com/j57DzJM.png" width="360">

- Headings are defined using the HTML `<h1>` to `<h6>` tags
    
    
- `<h1>` is the highest level of heading and `<h6>` is the lowest.


- Headings should be used in a logical order and accurately describe the content of the page


- The `<h1>` tag should be used for the most important heading, `<h2>` for subheadings, and so on


Let's add some headings into the body of our page:

```html
<body>
    <h1>About Exceed</h1>
    <h2>Our Cources</h2>
    <h3>Digital Marketing</h3>
    <h3>Web Development</h3>
    <h3>Data Scientist</h3>
</body>
```

We can now use the `p` tag to add some description below "About Jovian":

```html
<h1>About Exceed</h1>
<p>At Exceed, we're on a mission to build
    the world's most highly reputed technical
    university, and we're building completely
    online. We offer several beginner friendly 
    courses that are taken by 300,000+ registered
    users. 
</p>

```

We can also add some `div`s and `span`s to indicate the locations for each cources role under "Our Cources":

```html
<h2>Job Opportunities</h2>
<div>
    <h3>Frontend Developer</h3>
    <span>Bengaluru, India</span>
</div>
<div>
    <h3>Backend Developer</h3>
    <span>Delhi, India</span>
</div>
<div>
    <h3>Data Scientist</h3>
    <span>Mumbai, India</span>
</div>
```

**Tip**: You can right click within VS Code and select "Format Document" to add proper indentation into the code.

### Lists

<img src="https://i.imgur.com/eUjGQsU.png" width="480">

Special HTML tags are used to create lists, which allow for the presentation of information in an organized and structured manner. 

There are two types of lists in HTML:

1. Unordered lists:

  - Created using the `<ul>` tag
  - List items are added using the `<li>` tag
  - Bullet points are used to denote list items.
  - Appearance of bullet points can be customized with CSS
  
  
2. Ordered lists:

  - Created using the `<ol>` tag
  - List items are added using the `<li>` tag
  - Numbers/characters are used to denote list items.
  - Appearance of numbers can be customized with CSS
  
 

Lists can be nested within each other, allowing for the creation of sublists. It's important to close all tags properly to ensure that the page is rendered correctly.

Let's some footer items to our page using the `ul` tag:


```html
<div>
    <ul>
        <li>Courses</li>
        <li>Programs</li>
        <li>YouTube</li>
    </ul>
    <span>© 2023, Exceed</span>
</div>

```

### Links


The `a` tag is used to create hyperlinks in HTML i.e. links to other web pages or a different part of the same page.




- The `a` tag must have an `href` attribute that specifies the URL of the destination page.


- The text that is displayed as the link is placed between the opening and closing `a` tags.


- You can use the `target` attribute to specify where the linked page should be opened, such as in a new tab or window.


You can also create links to specific sections of a page by using the `id` attribute to identify the section and adding it to the URL in the `href` attribute.

Let's update the description section to include links to the two programs offered at Jovian:


```html
<ol>
    <li>
        <a href="https://google.com">
            Exceed Full Stack Developer Bootcamp
        </a>
    </li>
    <li>
        <a href="https://google.com">
            Exceed Data Science Bootcamp
        </a>
    </li>
</ol>

```


Let's also update the footer section with appropriate links, and set them to open in a new tab:

```html
<ul>
    <li>
        <a href="https://google.com" target="_blank">
            Courses
        </a>
    </li>
    <li>
        <a href="https://google.com" target="_blank">
            Programs
        </a>
    </li>
    <li>
        <a href="https://youtube.com" target="_blank">
            YouTube
        </a>
    </li>
</ul>

```

### Images

The img tag is used to add images to an HTML page.


- The `src` attribute of the `img` tag is used to specify the URL or file path of the image.


- The `alt` attribute of the `img` tag is used to provide alternative text for the image, which is displayed if the image cannot be loaded.


- The width and height attributes of the `img` tag can be used to specify the size of the image in pixels or as a percentage of the containing element.


- It's good practice to include a descriptive `alt` attribute for each image, not only to improve accessibility but also for search engine optimization (SEO).


- The `img` tag is a self-closing tag, meaning it doesn't need a closing tag. Example: `<img src="image.jpg" alt="A beautiful sunset" width="800" height="600">`.


[Unsplash.com](https://unsplash.com) is a good place to find royalty-free images for your websites. You can place images in your project folder next to your HTML page, or upload them to a cloud service like [imgur.com](https://imgur.com)

Let's add an image above "About Us":

```html
<body>
    <img src="banner.jpg" alt="Banner" height="240">
    <h1>About Us</h1>
...

```

Let's add another image before Our cources:

```html
<img src="team.jpg" height="240" alt="team">
<h2>Our cources</h2>

```

Note that we've added a height attribute to each image to limite the space it takes up on the page.


## Adding Styles with CSS

**CSS (Cascading Style Sheets)** is used to describe the presentation of HTML documents. It allows you to control layout and appearance by defining styles for elements such as fonts, colors, margins, borders, and more.

Let's look at different ways to apply CSS styles by attempting to center the heading "About Jovian" and changing its color to indigo. The resulting page will look like this:

<img src="https://i.imgur.com/vzWqYMW.png" width="480">

### Inline Styles

One way to achieve this is using the `style` attribute directly within HTML:


```html
<h1 style="text-align: center; color: indigo;">About Jovian</h1>
```

`text-align` and `color` are both properties and `center` and `indigo` are their respective values. 

<img src="https://i.imgur.com/40iT36z.png" width="360">

### The `style` Tag

Another way to do this is using a style tag within the `head` or `body`. 


```html
<head>
    <title>My First Web Page</title>
    <style>
        h1 {
            text-align: center;
            color: indigo;
        }
    </style>
</head>
```

In this case, the properties are applied to all `h1` tags on the page.


<img src="https://i.imgur.com/Nb0Na9X.png" width="360">

### CSS Files

Yet another way is to create a separate file containing the styles with a `.css` extension and connect it to the HTML page using the `link` tag.

Create a file `styles.css` and put the following content into it: 


```css
h1 {
    text-align: center;
    color: indigo;
}
```

Then, put the following content into the `head` of `webpage.html`:

```html
<head>
    <title>My First Web Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
```

### Selectors

When using the style tag or a separate CSS file, CSS properties can be applied to the desired elements on the page using different types of selectors:


1. **Tag**: We've already seen this in action above with the `h1` tag.


```css
h1 {
    text-align: center;
    color: indigo;
}
```


2. **ID**: We can set the `id` attribute of a tag and then use the `#` prefix to select it in a CSS

```html
<img id="banner" src="...">
```

```css
#banner {
    width: 100%;
}
```



3. **Class**: We can set the `class` attribute of one or more tags and use the `.` prefix to select it in CSS


```html
<div>
    <h3>Frontend Developer</h2>
    <span class="location">Bengaluru, India</span>
<div>
<div>
    <h3>Backend Developer</h2>
    <span class="location">New Delhi, India</span>
<div>

```

```css
.location {
    color: gray;
}
```



Selectors of various types can also be combined to selecting a specific set of elements matching all the conditions.

## The CSS Box Model

The CSS box model describes how HTML elements are rendered as rectangular boxes in a web page. The box is composed of several layers that determine the layout and sizing of the element. 

<img src="https://i.imgur.com/ThKeB4Y.png" width="360"> 


Here are the main components of the CSS box model:

1. **Content**: The actual content of the HTML element, such as text, images, or videos.

  - The size of the content can be controlled using the `height` and `width` properties.


2. **Padding**: The space between the content and the border of the element. 

  - Padding can be set for all sides or for each side individually.
  - The background color set for the content also applies to the padding area


3. **Border**: The border that surrounds the content and padding. 
  - Borders can be set for all sides or for each side individually
  - Borders can be styled with various properties such as color, width, and style.


4. **Margin**: The space between the border of the element and the adjacent elements. 
  - Margins can be set for all sides or for each side individually.
  - The background color set for the content does not apply to the margin area.
  - Margins for two elements can overlap, and collapses to the larger value
