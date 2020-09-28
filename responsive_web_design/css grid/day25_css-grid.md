# 100 Days of Projects

## Day 24 – Responsive Web Design | CSS Grid

Pleased with my decision to code exclusively during the week, I am happy to be back in front of my laptop to study the power that is CSS Grid.

I concluded the previous week with an exploration into CSS Grid columns and rows. Naturally, I found myself breaking code to build a grid. I definitely need more information about grid building since what I made in CodePen looks like a flippin' travesty.

So without further ado, we can jump right into CSS Grid.

## No gridlock here, people   🤓

![GIF image of man yelling hysterically "we're going off the grid"](https://media1.tenor.com/images/d7d65f1d35920465582ec6445d1e322b/tenor.gif?itemid=13364332)

---

## NOTES

## Introduction to the CSS Grid Challenges, 22 lessons to complete

### [Introduction to the CSS Grid Challenges](https://www.freecodecamp.org/learn/responsive-web-design/css-grid/)

*These are general notes that can be used by anyone.*

---

## Add Columns with `grid-template-columns`

`grid-template-columns` will give our grid structure, making your columns show up. To make your grid form the column, you'll want to apply pixels to the code like this:

```
.container {
  display: grid;
  grid-template-columns: 50px 50px;
}
```

---

## Add Rows with `grid-template-rows`

This property also adds structure to your grid. You can also add values to this code so that the default sizing given to the grid by your browser can be overwritten, depending on the styling you have in mind for the container.

To override the existing code, write something similar to this:

```
.container {
  display: grid;
  grid-template-columns: 100px 100px;
  grid-template-rows: 50px 50px;
}
```
When you add the pixel sizing, you're adjusting/setting the **height** of the rows in the grid.

---

## Use CSS Grid units to Change the Size of Columns and Rows

Although we've been using pixels to set the size of rows and columns, we can use other units of measure. Here's what freeCodeCamp recommends for us:

> `fr`: sets the `column` or `row` to a fraction of the available space,

> `auto`: sets the `column` or `row` to the width or height of its content automatically,

> `%`: adjusts the `column` or `row` to the percent width of its container.

fCC also gives us this code snippet to illustrate how we can use code to structure a 5-column grid. Take a look:

```
grid-template-columns: auto 50px 10% 2fr 1fr;
```

Here an explanation of what the code (above) is telling the browser:

> The first column is as wide as its content, the second column is 50px, the third column is 10% of its container, and for the last two columns; the remaining space is divided into three sections, two are allocated for the fourth column, and one for the fifth. - freeCodeCamp

---

## Create a Column Gap Using `grid-column-gap`;  Create a Row Gap using `grid-row-gap`

It's important to consider gaps in the grid structure, to give your rows and columns a bit more breathing room. The code that's given to us in the tutorial shows us how to add gaps between these properties.

```
grid-column-gap: 10px;
grid-row-gap: 5px;
```

## Add Gaps Faster with `grid-gap`    

Shorthand is great because it helps us get right the point of our visual design. In this example, we're introducing a 10px gap between the rows and a 20px gap between the columns:

```
grid-gap: 10px 20px;
```

---

## Use `grid-column` to Control Spacing

Sometimes we're going to want to style the grid items themselves. To do this, we need to understand grid spacing. The diagram provided by fCC show where the grid lines for both rows and columns begin and end. The explanation provided is [here](https://www.freecodecamp.org/learn/responsive-web-design/css-grid/use-grid-column-to-control-spacing).

If we want certain grid items to take up space with a row or column, we'd first need to establish the grid lines. This is best illustrated in the lesson and tutorial sandbox [here](https://www.freecodecamp.org/learn/responsive-web-design/css-grid/use-grid-column-to-control-spacing).

You can do the same thing with rows using `grid-row`.

---  

### Overall thoughts:

This is a very useful lesson. I'm looking forward to applying it to the upcoming coding challenges. I'm wrapping up the lesson here since tomorrow will focus specifically on aligning items with CSS Grid.

Until tomorrow, keeping on codin'!

![GIF image of Michael Scott, enough said](https://media1.tenor.com/images/ca7430d955f70ba46c300ca5c04aaaa4/tenor.gif?itemid=4916381)