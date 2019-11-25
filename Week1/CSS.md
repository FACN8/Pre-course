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

- Add the following line of code inside the curly braces: `color: red;`.

- You should see the color changing to red :tada:.

### Analysis

The rule opens with a selector . This selects the HTML element that we are going to style. In this case we are styling level one headings (`<h1>`).

We then have a set of curly braces { }. Inside those will be one or more declarations, which take the form of property and value pairs. Each pair specifies a property of the element(s) we are selecting, then a value that we'd like to give the property.

Before the colon, we have the property, and after the colon, the value. CSS properties have different allowable values, depending on which property is being specified. In our example, we have the color property, which can take various color [values](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Values_and_units#Color).

## CSS syntax and selectors

You can't talk about CSS without meeting selectors. A selector is how we target something in our HTML document in order to apply styles to it. If your styles are not applying then it is likely that your selector does not match the thing you think it should match.

Each CSS rule starts with a selector or a list of selectors in order to tell the browser which elements or elements the rules should apply to.

#### CSS Element Selector

The element selector selects the HTML element by name.

```css
p {
  text-align: center;
  color: blue;
}
```

#### CSS Id Selector

The id selector selects the id attribute of an HTML element to select a specific element. An id is always unique within the page so it is chosen to select a single, unique element.

It is written with the hash character (#), followed by the id of the element.

_Example_

HTML code, the id applies to a specific p tag

```html
<p id="para1">Hello Javatpoint.com</p>
```

Adding rules in the css to the `para1` id

```css
#para1 {
  text-align: center;
  color: blue;
}
```

#### CSS Class Selector

The class selector selects HTML elements with a specific class attribute. It is used with a period character . (full stop symbol) followed by the class name.

_Example_

HTML

```html
<h1 class="center">This heading is blue and center-aligned.</h1>
<p class="center">This paragraph is blue and center-aligned.</p>
```

CSS

```css
.center {
  text-align: center;
  color: blue;
}
```

_Notice_ that the `center` class applies to both the `h1` and the `p` tag, unlike the id selector it is not unique.

## CSS RULES!

How to add css to your html

link in html