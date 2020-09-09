# 100 Days of Projects

## ## Day 7 and 8 – Responsive Web Design | Applied Visual Design

Sooooo.... I kinda skipped ahead and took several steps to get to where I am now in the freeCodeCamp tutorial: **Relative Position**.

I wanted to take a few notes on this subject since it comes up all the time in my WordPress code.

HTML elements are considered to have their own box, block, or container. No matter what you call it, CSS see it as a box to be styled. This is can the **CSS Box Model**, and it's kinda intimidating. At least to me it is, but *there's no better way to get over a hurdle than to consider what it's made of*. So, let's learn about it, shall we?

## Read and learn!

![GIF image of a baby reading a book in a rather hurried fashion](https://media1.tenor.com/images/80556186b94ecaff7a570a9c8148fb00/tenor.gif?itemid=4535602)

---

## NOTES

## Applied Visual Design, 52 lessons to complete

*These are general notes that can be used by anyone.*

### [Introduction to  the Applied Visual Design Challenges](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/)

---

## Change an Element's Relative Position

fCC states:

> CSS treats each HTML element as its own box, which is usually referred to as the CSS Box Model. Block-level items automatically start on a new line (think headings, paragraphs, and divs) while inline items sit within surrounding content (like images or spans). The default layout of elements in this way is called the normal flow of a document, but CSS offers the position property to override it.

This is the key right here: *When the position of an element is set to relative, it allows you to specify how CSS should move it relative to its current position in the normal flow of the page. Changing an element's position to relative does not remove it from the normal flow - other elements around it still behave as if that item were in its default position.*

fCC provides us with the following example:

```
p {
  position: relative;
  bottom: 10px;
}
```

Another incredibly important factor to remember when coding and programing is to make sure the HTML markup is consistent and organized for accessibility purposes.

---

### Move a Relatively Positioned Element with CSS Offsets

fCC states:

> The CSS offsets of top or bottom, and left or right tell the browser how far to offset an item relative to where it would sit in the normal flow of the document. You're offsetting an element away from a given spot, which moves the element away from the referenced side (effectively, the opposite direction). 

In the example, I want to move my heading to the right by 15px and up by 10px. To do this, I'd write the following code:

```
h2 {
    position: relative;
    left: 15px;
    bottom: 10px;
}
```

Although this seems counterintuitive, you have to remember that we're moving the box *from* a certain point. So the code above is telling the browser, "Hey there, buddy! I would like for you to position the H2 element **relative** to where it would normally render in our HTML code. Then, if you could pretty please position the element 15 pixels from the left-side of the container and 10 pixels from the bottom of the container, that'd be faaaaantastic. Thanks!"

I practiced coding offsets in my name-card project. It's pretty cool! I feel confident that with upcoming website building projects I'll be able to make sense of positioning all my elements to create accessible, inituitive layouts.

---

## Overall thoughts:

Taking time to fully digest each portion of this tutorial, while building out a project alongside it, is helping me to deepen my understanding of how HTML and CSS work together. It's making it easier for me to form layout ideas for the upcoming project I'd like to build.

In a nutshell, this is so much fun! I'm excited to jump back into the tutorial to see what else there is to learn and refresh myself on.

👋🏾  I'll see you tomorrow, friend. And keep on codin'!