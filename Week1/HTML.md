# Introduction to HTML

![html5 logo](https://user-images.githubusercontent.com/22002193/69446950-26f68b00-0d5e-11ea-96dd-eb217f407b56.jpg)

HTML is one of the most widely used languages on Web to develop web pages. It helps you delve into the world of Web Development and improve your skills.

## Contents

- Origin of HTML
- What is HTML?
  - Tag exploration
- HTML Structure
- How does HTML work?
- Fundamentals of HTML

## Origin of HTML

HTML - Hyper Text Markup Language is a language that was created by Tim Berners-Lee was putting together his first elementary browsing and authoring system for the Web and created a quick little hypertext language that would serve his purposes.

HTML was text-based and anyone could use any editor or word processor to create or convert documents for the Web. The developers started implementing new features in their browsers and started releasing advanced versions of HTML.

## What is HTML?

A markup language is a computer language that is used to apply layout and formatting conventions to a text document. Markup language makes the text more interactive and dynamic. It can turn text into images, tables, links, etc.

![html blocks](https://user-images.githubusercontent.com/22002193/69431669-dde40e00-0d40-11ea-9eca-eebebf65e58f.jpg)

HTML describes the structure of a Web page, this structure consists of a series of elements that tell the browser how to display the content.

HTML elements are represented by tags that label pieces of content such as "heading", "paragraph", "table", and so on...

Let's look at an example:
https://codepen.io/shiryz/pen/pooBWVW?editors=1000#0

## Task

Try it yourself, add the following line to the pen:

```html
<h2>This is an h2 tag</h2>
```

### Tag exploration

Let's explore our paragraph element a bit further:

![paragraph tag](https://user-images.githubusercontent.com/22002193/69439165-10950300-0d4f-11ea-99cf-3509e06cf8f9.png)

The main parts of our element are:

1. The opening tag - `<p>`: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets `<>`. This states where the element begins or starts to take effect — in this case where the start of the paragraph is.
2. The closing tag - `</p>`: This is the same as the opening tag, except that it includes a forward slash before the element name `</>`. This states where the element ends — in this case where the end of the paragraph is. Failing to include a closing tag is a common beginner error and can lead to strange results.
3. The content: This is the content of the element, which in this case is just text.
4. The element: The opening tag plus the closing tag plus the content equals the element.

## Basic structure of an HTML page

![html basic structure](https://user-images.githubusercontent.com/22002193/69439363-72556d00-0d4f-11ea-8779-2005751cdd10.png)

The three tags that you need for your HTML document are <html>, <head>, and <body>.

1. The `<html></html>` tag is the highest level element that encloses every HTML page.
2. The `<head></head>` tag holds meta information such as the page’s title and charset.
3. Finally, the `<body></body>` tag encloses **all the content that appears on the page**.

## How does HTML work?

HTML documents end with the .html or .htm extension. You can view it using any web browser. The browser reads the HTML file and renders the content for users to view it.

### Task: Build a basic HTML page

- open your favourite editor and create a file called `my-first-page.html`
- type `html` in the page and press the `tab` key, this will automatically generate an html page for you.

The result should look like the following:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title></title>
  </head>
  <body></body>
</html>
```

_Note: We will explore all the tags later_

- In the `<body>` tag add an `<h1>`

Your code should look something like this:

```html
<body>
  <h1>The Main Heading</h1>
</body>
```

- Right click on your html file and click on `open in browser`, this should open the browser with the result of this file. You should see the h1 heading with `The Main Heading` on the page.

- Let's explore this a bit more, in the browser, open the inspector. You can do so by either pressing `f12` or right clicking on the page and then inspect or pressing `ctrl+shift+i`.
  - You should see be able to see the elements you created before (raw html), in the elements tab. You can edit/delete/add elements here like you did in your editor.

### Task

Your task is to change the elements in the browser from the inspector, delete the current `h1` tag and add a `div` tag.

- Find out more about [`div`](https://www.w3schools.com/tags/tag_div.asp)

_Notice_ that these changes will not be saved in your file and only affect the browser, if you wish to save them then you will have to actually do it from the file itself.
