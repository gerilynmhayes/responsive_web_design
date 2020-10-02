# 100 Days of Projects

## Day 28 – Responsive Web Design | CSS Grid

Today, I am focusing on creating flexible layouts using both `auto-fill` and `auto-fit`, media queries for responsive layout creation, and creating grids within grids.

## Let's GRID it!   🤓

![GIF image of little girl dancing happily because it is Friday](https://media.tenor.com/images/7fd0b0a6c6a9d87ab96735c918eb1e8a/tenor.gif)

---

## NOTES

## Introduction to the CSS Grid Challenges, 22 lessons to complete

### [Introduction to the CSS Grid Challenges](https://www.freecodecamp.org/learn/responsive-web-design/css-grid/)

*These are general notes that can be used by anyone.*

---
## Create Flexible Layouts Using `auto-fill`

`auto-fill` is a option for the `repeat` function, allowing us to automatically insert however many columns and rows into containers. They can be of any size *depending on the size of the container*.

To create flexible layouts, you'll want to combine both `auto-fill` with `minmax`. Here's an example:

```
repeat(auto-fill, minmax(60px, 1fr));
```

The code above means that when the container size changes, the code will insert columns sized 60px and stretch them until another can be inserted.

Here's a note to remember from fCC:

> If your container can't fit all your items on one row, it will move them down to a new one.

It's best to test this code in the challenge [here](https://www.freecodecamp.org/learn/responsive-web-design/css-grid/create-flexible-layouts-using-auto-fill) to see how it works.

## Create Flexible Layouts Using auto-fit

The key difference between `auto-fit` and `auto-fill` is that when the container size exceeds the sixe of all the items combined, `auto-fill` will continuously insert empty rows or columns while pushing items to the side. `auto-fit` collapses the empty columns or rows while stretching the items to fit the size of the container.

Here's a note to remember from fCC:

> If your container can't fit all your items on one row,it will move them down to a new one.

From today's challenge, you'll see how this code styles to layout:

```
grid-template-columns: repeat(auto-fit, minmax(60px, 1fr));
```

---

### Overall thoughts:

🥳  Pending [out of town: Pflugerville, Texas]

![GIF of Ron Swanson squeeling with glee](https://media1.tenor.com/images/3781fb49f9f50c4b7d5c9590dcf9e710/tenor.gif?itemid=14647008)