# HTML-and-CSS-Basics

HTML and CSS form the foundation of modern web design, allowing you to create visually appealing & functional web pages.

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

The following wireframe was created using [excalidraw.com](https://excalidraw.com) :

Let's recall the problem statement and create a wireframe:

> **Problem Statement**: Create a web page that showcases job listings for Jovian, including the following:
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

