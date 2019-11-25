# CSS

![css logo](https://user-images.githubusercontent.com/22002193/69540470-55a77800-0f8f-11ea-9898-0acd26043695.png)

## What's CSS?

CSS (Cascading Style Sheets) allows you to create great-looking web pages.

![What css looks like](https://user-images.githubusercontent.com/22002193/69540398-2c86e780-0f8f-11ea-9b64-812ed09956fc.jpg)

CSS describes how HTML elements are to be displayed on screen, paper, or in other media.

CSS saves a lot of work. It can control the layout of multiple web pages all at once.

## CSS example

Let's take a look at the following [example](https://codepen.io/shiryz/pen/VwwOBGa?editors=1100#0) in codepen.

As you can see you have an `h1` heading that appears in black, let's change it to red.

- In the CSS tab you can see the following code

```css
h1 {
}
```

- Add this line inside the curly braces: `color: red;`.

- You should see the color changing to red :tada:.

### Analysis

The rule opens with a selector . This selects the HTML element that we are going to style. In this case we are styling level one headings (`<h1>`).

We then have a set of curly braces { }. Inside those will be one or more declarations, which take the form of property and value pairs. Each pair specifies a property of the element(s) we are selecting, then a value that we'd like to give the property.

Before the colon, we have the property, and after the colon, the value. CSS properties have different allowable values, depending on which property is being specified. In our example, we have the color property, which can take various color [values](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units#Color).

How to add css to your html

classes/ids/tags

link in html
