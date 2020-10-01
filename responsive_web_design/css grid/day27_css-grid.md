# 100 Days of Projects

## Day 27 – Responsive Web Design | CSS Grid

Today, I am focusing on dividing the grid into an area template, the `grid-area` property, the `repeat` function, and item sizing. Another celebration for today: *It's Thursday! The week is nearly wrapped up!*

## Grid time!   🤓

![GIF image of man dancing because he is happy that today is Thursday](https://media.tenor.com/images/786e9f64a3fc074fcc54549798dbab63/tenor.gif)

---

## NOTES

## Introduction to the CSS Grid Challenges, 22 lessons to complete

### [Introduction to the CSS Grid Challenges](https://www.freecodecamp.org/learn/responsive-web-design/css-grid/)

*These are general notes that can be used by anyone.*

---
## Divide the Grid Into an Area Template

When cells are grouped together they're collectively called an *area*. You can give the area a custom name in your code by using the property `grid-template-areas`.

The code provided in the tutorial is showing us how the code dictates grid items' placement in the area. Take a look at the following code:

```
grid-template-areas:
  "header header header"
  "advert content content"
  "footer footer footer";
```

The `header` area is showing three merged cells, each called "header". The same is happening for the "footer" cells.

Now, take a look at "advert" and "content". While these cells are merged, they are considered to be in two different *areas*.

**Note from fCC**:

> Every word in the code represents a cell and every pair of quotation marks represent a row. In addition to custom labels, you can use a period (.) to designate an empty cell in the grid.

## Place Items in Grid Areas Using the grid-area Property

One you've created templates for each area, you can style them with CSS by referencing their respective names. You'll use the `grid-area` property and the area's name as the value.

```
.item1 {
    grid-area: header;
}
```

The code is telling the browser that `item1` styling is designated to the "header"-named area.

## Use grid-area Without Creating an Areas Template

So, what happens if your areas don't have templates? You can still use `grid-area` to create an area for an item. The example given is this:

```
item1 { grid-area: 1/1/2/4; }
```

This code reflects what we've learned in a previous lesson about *line numbers* which define where the area for the grid item will be.

fCC states this about the code (above):

> ```grid-area: horizontal line to start at / vertical line to start at / horizontal line to end at / vertical line to end at;```

This one will probably take a bit of practice (or at least, it did for me) so I recommend playing in the sandbox with it [here](https://www.freecodecamp.org/learn/responsive-web-design/css-grid/use-grid-area-without-creating-an-areas-template).

Here's the instructions from the tutorial:

> Using the `grid-area` property, place the element with `item5` class between the third and fourth horizontal lines and between the first and fourth vertical lines.

Review the resulting code here; put it in your CodePen to see what it looks like in action:

```
<style>
  .item1{background:LightSkyBlue;}
  .item2{background:LightSalmon;}
  .item3{background:PaleTurquoise;}
  .item4{background:LightPink;}

  .item5 {
    background: PaleGreen;
    /* CODE ADDED TO THE TUTORIAL */
    grid-area: 3/1/4/4;
  }

  .container {
    font-size: 40px;
    min-height: 300px;
    width: 100%;
    background: LightGray;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
    grid-gap: 10px;
  }
</style>

<div class="container">
  <div class="item1">1</div>
  <div class="item2">2</div>
  <div class="item3">3</div>
  <div class="item4">4</div>
  <div class="item5">5</div>
</div>

```

## Reduce Repetition Using the repeat Function

In previous lessons, we learned to use `grid-template-columns` and `grid-template-rows`, and to give them values, to define the structure of grids. This would be cumbersome to write out if you have a grid with 100+ rows and columns, right?

That's where `repeat` comes in. This function will specify the number of times the column and row will repeat. `repeat` is followed by a comma and a value that represents the row or column you want to repeat.

Example:

```
grid-template-rows: repeat(250, 30px);
```

or the following which represents repeated multiple values:

```
grid-template-columns: repeat(2, 1fr 50px) 20px;
```

## Limit Item Size Using the `minmax` Function

`minmax` is used to limit the size of grid items when the container's size changes by specifying the acceptable size range for the grid item.

fCC provides the following example:

```
grid-template-columns: 100px minmax(50px, 200px);
```

fcc explains:

> In the code above, `grid-template-columns` is set to create two columns; the first is 100px wide, and the second has the minimum width of 50px and the maximum width of 200px.

Putting this new function rule into practice will be the best way to understand its power. I like that fCC has provided us with an example that shows `minmax` can be nested inside another function like so:

```
grid-template-columns: repeat(3, minmax(90px, 1fr));
```

It's meant to explain that the column will repeat three times, and that the column sizes will have a minimum of 90px width and a maximum of 1fr width once the browser is resized.

---

### Overall thoughts:

As I mentioned yesterday, retention is key when taking any coding or programming tutorial. I'm finding that these deep notetaking is helping me understand the "why" behind what I am learning, instead of just following along with the modue and c+p the code snippets provided.

I hope that these notes help not only myself to retain the information that I'm gaining, but others who are concerned about not being able to fully understand the lessons they're taking.

Tomorrow should be the final day of the CSS Grid lesson which is very exciting because that means we're jumping into the **Responsive Web Design Projects** (the whole purpose of my #100DaysOfProjects participation).

The lessons will include creating flexible layouts using both `auto-fill` and `auto-fit`, media queries for responsive layout creation, and creating grids within grids.

This is going to be fun!

🥳  Until tomorrow, keep on coding!

![GIF of Ron Swanson squeeling with glee](https://media1.tenor.com/images/3781fb49f9f50c4b7d5c9590dcf9e710/tenor.gif?itemid=14647008)