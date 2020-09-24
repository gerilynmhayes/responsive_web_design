# 100 Days of Projects

## Day 4 – Responsive Web Design | Responsive Web Design | More CSS! Back to CatPhotoApp

Although I was feeling anxious about yesterday's lesson, I am feeling more confident about what the fCC coursework will deliver.

I'm eager to see how much progress I can make with this coursework.

## Diving Right In!

![man jumping off cliff and into ocean](https://media1.tenor.com/images/f2980040c539cc75b70abf785e376010/tenor.gif?itemid=14793998)

---

## NOTES

## Basic CSS, 44 lessons to complete

*These are general notes that can be used by anyone.*

### [Introduction to Basic CSS](https://www.freecodecamp.org/learn/responsive-web-design/basic-css)

---

## CSS Selectors

The attribute selector matches and styles elements with a specific attribute value.

Example given by fCC show us that the code changes the margins of all elements with the attribute `type` and a corresponding value of `radio`:

```
[type='radio'] {
  margin: 20px 0px 20px 0px;
}
```

Visit my [CodePen](https://codepen.io/gerilynmhayes/pen/mdPMpGO) to see the CatPhotoApp's progress.

---

## Units of Measure

fCC tells us that, "The two main types of length units are absolute and relative. Absolute units tie to physical units of length. For example, `in` and `mm` refer to inches and millimeters, respectively. Absolute length units approximate the actual measurement on a screen, but there are some differences depending on a screen's resolution."

fCC also tells us about `em` or `rem`: "Relative units, such as `em` or `rem`, are relative to another length value. For example, `em` is based on the size of an element's font. If you use it to set the `font-size` property itself, it's relative to the parent's `font-size`."

Visit the [CodePen](https://codepen.io/gerilynmhayes/pen/BaKwJPp) for the "Nightmare Trifecta" to see how these units of measure work.

---

## 🙀 Styling the HTML Body Element

Use CSS to style the body element (so that we can see it!!).

Code example:

```
body {
  background-color: black;
}
```
---

## Inheriting Styles from the HTML Body Element

*Did you know that the `body` element can be styled?* Well, it can be. All you have to do is treat it like any other HTML element.

When you do so, fCC says, "all your other elements will inherit your body element's styles."

Pretty neat, huh?

Here's my example which you can put into your own codepen and test:

```
body {
    background: brown;
    color: yellow;
    font-family: monospace;
}

<h1>What's up, Doc?</h1>
```

---

## Overriding Styles

The lessons in this tutorial are worthwhile, and should be practiced to understand heirarchy. For my purposes, I'm going to leave this web standard here as a reminder:

"Browsers read CSS from top to bottom in order of their declaration. That means that, in the event of a conflict, the browser will use whichever CSS declaration came last." -fCC

It's also worth mentioning that inline styles will override all CSS declarations, but the most *powerful* overriding call is `!important`. I try to use it sparingly, but sometimes it is necessary to declare when you need your element styled in a very specific way.

Here's an example. Notice that your CSS class `pink-text` has the keyword `!important` in it, making the color pink the overriding priority in the style:

```
<style>
  body {
    background-color: black;
    font-family: monospace;
    color: green;
  }
  #orange-text {
    color: orange;
  }
  .pink-text {
    color: pink !important;
  }
  .blue-text {
    color: blue;
  }
</style>
<h1 id="orange-text" class="pink-text !important blue-text" style="color: white">Hello World!</h1>

```
---

## Colors 🎨

This section is very fun and a lot of it is self-explanatory. I recommend playing with this portion of the tutorial in CodePen.

You can also find super cool colors using my favorite palette selector: [Coolors](https://coolors.co/881775)!

---

## Overall thoughts:

This portion of the tutorial was super fun! I especially enjoyed learning how the selectors are used to grab specific properties to style elements. I think they're going to come in handy for my upcoming web page projects.

For now, I'm stopping here so that I can spend tomorrow's session studying CSS Variables. The upcoming lesson, which features a CSS illustration, will be a fun one to work on!

*Following alongside my notes? Got questions? Suggestions?* Tweet me [@gerilynhayes](https://twitter.com/gerilynmhayes) and [@100ProjectDays](https://twitter.com/100ProjectDays) using hashtags #100DaysOfProjects and #LearningInPublic, and I'll answer your questions.

🤓 Keep on codin'!