# 100 Days of Projects

## Day 21 and Day 22 – Responsive Web Design | Introduction to the CSS Flexbox Challenges

While it's always great to get a few projects knocked out by the end of the day, it's even better to have an hour left over to jump into coding.

That's why I'm going to get a headstart on Day 21 right now (it's still technically Day 20, but it's alllll goood). Let's go!

## Gettin' ahead of the game   🤓

![GIF image of Cookie Monster from Sesame Street dancing very enthusiastically because it is Tuesday](https://media1.tenor.com/images/0f0d44966ccf348f21b56edf40e5fe6d/tenor.gif?itemid=113972566)

EDIT/UPDATE: Jumping here to say that these notes are combined over the course of days 20, 21, and 22.

---

## NOTES

## Introduction to the CSS Flexbox Challenges, 17 lessons to complete

### [Introduction to the CSS Flexbox Challenges](https://www.freecodecamp.org/learn/responsive-web-design/css-flexbox/)

*These are general notes that can be used by anyone.*

---

## Introduction to the CSS Flexbox Challenges

From freeCodeCamp:

> A website's **User Interface ("UI")** has two components. First, there are the *visual elements*, such as colors, fonts, and images. Second, there is the *placement or positioning* of those elements. In Responsive Web Design, a **_UI layout must accommodate many different browsers and devices accessing the content_**.

> CSS3 introduced **Flexible Boxes**, or **flexbox**, to create page layouts for a dynamic UI. It is a layout mode that arranges elements in a predictable way for different screen sizes and browsers. While somewhat new, *all popular modern browsers support flexbox*. This section covers how to use flexbox and the different layout options it offers.

## Use `display: flex` to Position Two Boxes

According to fCC, when you place the CSS property `display: flex;` on an element, it allows the developer (*that's you*) to use other flex properties to build a responsive web page.

We use the code `display: flex;` to do so.

## Add Flex Superpowers to the Tweet Embed

It's best to see how the code works by taking the challenge [here](https://www.freecodecamp.org/learn/responsive-web-design/css-flexbox/add-flex-superpowers-to-the-tweet-embed).

## Use the `flex-direction` Property to Make a Row

When you add `display:flex` to an element, you're turning it into a flex container making "it possible to align any children of that element into rows and columns."

To turn these now flexible elements into rows or columns, you will need to add `flex-direction` to the parent item. You will set the parent item's direction as a row (giving the element horizontal alignment) or column (giving the element vertical alignment).

**It's important to remember that the default setting for `flex-direction` is `row`.**

## Apply the `flex-direction` Property to Create Rows in the Tweet Embed

It's best to see how the code works by taking the challenge [here](https://www.freecodecamp.org/learn/responsive-web-design/css-flexbox/apply-the-flex-direction-property-to-create-rows-in-the-tweet-embed).

## Use the `flex-direction` Property to Make a Column

Just as we were able to create rows with `flex-direction`, we can do the same thing for columns using `flex-direction: column;`.

## Apply the `flex-direction` Property to Create a Column in the Tweet Embed

It's best to see how the code works by taking the challenge [here](https://www.freecodecamp.org/learn/responsive-web-design/css-flexbox/apply-the-flex-direction-property-to-create-a-column-in-the-tweet-embed)

---

## Align Elements Using the `justify-content` Property

This is the most comprehensive explanation of how the flexbox position works when `justify-content` is used. I'm copying and pasting directly from freeCodeCamp here because I will most likely use it as a reference:

> Sometimes the flex items within a flex container do not fill all the space in the container. It is common to want to tell CSS how to align and space out the flex items a certain way. Fortunately, the `justify-content` property has several options to do this. But first, there is some important terminology to understand before reviewing those options.

> [Here is a useful image showing a row to illustrate the concepts below.](https://www.w3.org/TR/css-flexbox-1/images/flex-direction-terms.svg)

> Recall that setting a flex container as a row places the flex items side-by-side from left-to-right. A flex container set as a column places the flex items in a vertical stack from top-to-bottom. For each, the direction the flex items are arranged is called the main axis. For a row, this is a horizontal line that cuts through each item. And for a column, the main axis is a vertical line through the items.

> There are several options for how to space the flex items along the line that is the main axis. One of the most commonly used is `justify-content: center;`, which aligns all the flex items to the center inside the flex container. Others options include:

> - `flex-start`: aligns items to the start of the flex container. For a row, this pushes the items to the left of the container. For a column, this pushes the items to the top of the container. This is the default alignment if no `justify-content` is specified.
> - `flex-end`: aligns items to the end of the flex container. For a row, this pushes the items to the right of the container. For a column, this pushes the items to the bottom of the container.
> - `space-between`: aligns items to the center of the main axis, with extra space placed between the items. The first and last items are pushed to the very edge of the flex container. For example, in a row the first item is against the left side of the container, the last item is against the right side of the container, then the remaining space is distributed evenly among the other items.
> - `space-around`: similar to `space-between` but the first and last items are not locked to the edges of the container, the space is distributed around all the items with a half space on either end of the flex container.

## Use the justify-content Property in the Tweet Embed

It's best to see how the code works by taking the challenge [here](https://www.freecodecamp.org/learn/responsive-web-design/css-flexbox/use-the-justify-content-property-in-the-tweet-embed).

## Align Elements Using the `align-items` Property

This is the most comprehensive explanation of how the flexbox position works when `align-items` is used. I'm copying and pasting directly from freeCodeCamp here because I will most likely use it as a reference:

> The `align-items` property is similar to `justify-content`. Recall that the `justify-content` property aligned flex items along the main axis. For rows, the main axis is a horizontal line and for columns it is a vertical line.

> Flex containers also have a cross axis which is the opposite of the main axis. For rows, the cross axis is vertical and for columns, the cross axis is horizontal.

> CSS offers the `align-items` property to align flex items along the cross axis. For a row, it tells CSS how to push the items in the entire row up or down within the container. And for a column, how to push all the items left or right within the container.

> The different values available for `align-items` include:

> - `flex-start`: aligns items to the start of the flex container. For rows, this aligns items to the top of the container. For columns, this aligns items to the left of the container.
> - `flex-end`: aligns items to the end of the flex container. For rows, this aligns items to the bottom of the container. For columns, this aligns items to the right of the container.
> - `center`: align items to the center. For rows, this vertically aligns items (equal space above and below the items). For columns, this horizontally aligns them (equal space to the left and right of the items).
> - `stretch`: stretch the items to fill the flex container. For example, rows items are stretched to fill the flex container top-to-bottom. This is the default value if no `align-items` value is specified.
> - `baseline`: align items to their baselines. Baseline is a text concept, think of it as the line that the letters sit on.

## Use the align-items Property in the Tweet Embed

It's best to see how the code works by taking the challenge [here](https://www.freecodecamp.org/learn/responsive-web-design/css-flexbox/use-the-align-items-property-in-the-tweet-embed).

I also recommend testing the code on W3Schools.com [here](https://www.w3schools.com/CSSref/css3_pr_align-items.asp)

---

## Use the `flex-wrap` Property to Wrap a Row or Column

I like this property and its value set because if you can wrap items to make them appear organized based on your web page's visual needs.

fCC states that when `flex-wrap` is used, "extra items move into a new row or column" and that "the break point of where the wrapping happens depends on the size of the items and the size of the container."

Here's a list of wrap directions (c + p from fCC):

> - `nowrap`: this is the default setting, and does not wrap items.
> - `wrap`: wraps items from left-to-right if they are in a row, or top-to-bottom if they are in a column.
> - `wrap-reverse`: wraps items from right-to-left if they are in a row, or bottom-to-top if they are in a column.

## Use the `flex-shrink` Property to Shrink Items

Since the flex container is the "parent", we're going to focus on the children or *flex items* and the properties used to style them starting with `flex-shrink`.

`flex-shrink` is used when the flex container is too small. "Items shrink when the width of the parent container is smaller than the combined widths of all the flex items within it."

This property uses numbers for values. "The higher the number, the more it will shrink compared to the other items in the container."

## Use the `flex-grow` Property to Expand Items

This is the opposite of `flex-shrink`! This property "controls the size of items when the parent element expands."

## Use the flex-basis Property to Set the Initial Size of an Item

This property "specifies the initial size of the item before CSS makes adjustments with `flex-shrink` or `flex-grow`."

fCC states: 

> The units used by the `flex-basis` property are the same as other size properties (`px`, `em`, `%`, etc.). The value `auto` sizes items based on the content.

## Use the flex Shorthand Property

`flex-grow`, `flex-shrink`, and `flex-basis` can all be set as a group by using the `flex` property.

Here is the fCC example:

`flex: 1 0 10px;` will set the item to `flex-grow: 1;`, `flex-shrink: 0;`, and `flex-basis: 10px;`.

**NOTE:** The `flex` shorthand property default settings are `flex: 0 1 auto;`.

## Use the `order` Property to Rearrange Items

fCC states:

> The `order` property is used to tell CSS the order of how flex items appear in the flex container. By default, items will appear in the same order they come in the source HTML. The property takes numbers as values, and negative numbers can be used.

## Use the `align-self` Property

fCC states:

> The final property for flex items is `align-self`. This property allows you to adjust each item's alignment individually, instead of setting them all at once. This is useful since other common adjustment techniques using the CSS properties `float`, `clear`, and `vertical-align` do not work on flex items.

`align-self` accepts the same values as `align-items` and will override any value set by the `align-items` property.

---

### Overall thoughts:

This comprehensive guide to CSS Flexbox was very will thoughtout and easy to digest. The next portion of the freeCodeCamp curriculum I will dive into is "Introduction to the CSS Grid Challenge" and this will begin tomorrow morning before I drive to San Marcos, Texas. I am visiting my best friend Christie and really in need of a good old fashioned road trip! These are exciting times, indeed. At least in my coding world.

👋🏾  Until tomorrow, keep on codin'!