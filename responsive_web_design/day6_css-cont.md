# 100 Days of Projects

## Day 6 – Responsive Web Design | CSS, Media Queries 

Yo yo yo! It's Sunday and I'm ready to knock the remaining three lessons in this portion of the fCC course.

## Here we GOOOO!

![GIF image of Brad Pitt dancing enthusiastically, a clip from the excellent film Burn Before Reading which you should watch when you're not coding or programming](https://media1.tenor.com/images/30fad02b061a48c5c7fb432870c9b512/tenor.gif?itemid=13794894)

---

## NOTES

## Basic CSS, 44 lessons to complete

*These are general notes that can be used by anyone.*

### [Introduction to Basic CSS](https://www.freecodecamp.org/learn/responsive-web-design/basic-css)

---

## Inherit CSS Variables

The fCC example highlights a variable called `:root` which is a *psuedo-class* selector that tells the browser which variables you want it to render from the document and into the front-end.

fCC gives us a great example of what this looks like. I've provided their example below:

```
:root {
    --penguin-belly: pink;
}

body {
    background: var(--penguin-belly, #c6faf1);
}
```

In this example, we're being shown that our body element will inherit the global style that's described in the `:root`. In this case, our website body will be pink. If you update the `:root` variable to --penguin-belly: blue; *guess what color it will turn*?

So, in a nutshell:

> When you create variables in `:root` they will set the value of that variable for the entire page. You can then over-write these variables by setting them again within a specific element. - freeCodeCamp

This means that you can override your global styles (you know, ones that are in your `:root`) by placing a specific variable within an element.

---

## Use a media query to change a variable

> CSS Variables can simply the way you use media queries. -freeCodeCamp

This is handy for responsive websites that need to fit on a variety of screens, no matter their shape or size.

---


## Overall thoughts:

This was a great opening HTML and CSS tutorial. Now that I've completed the first portion of the curriculum, I'll begin the section on Applied Visual Design. I want to pay close attention to the following topics as I move through the tutorial:

- Accessibility
- Color Theory
- Page Layout

I'm looking forward to it! 

For now, I need to put today's lesson on pause because **it's dinnertime!**

Although I normally share my CodePen here, I'd like to play with more of the code and understand the animation setting provided by fCC before uploading it here.

But make sure you let me know how you're doing! Tweet your progress [@gerilynhayes](https://twitter.com/gerilynmhayes) and [@100ProjectDays](https://twitter.com/100ProjectDays) using hashtags #100DaysOfProjects and #LearningInPublic.

🤓Until then, keep on codin'!