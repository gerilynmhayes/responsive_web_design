# 100 Days of Projects

## Day 20 – Responsive Web Design | Introduction to the Responsive Web Design Challenges

YES! The coursework I've been waiting for. Looking forward to diving into media queries, responsive design, and so much more. Even after months of digging into responsive with Skillcrush, I feel like this refresher is really supplemental to my ongoing learning.

Here's to another day of coding!

## Keepin' it TIGHT Tuesday   🤓

![GIF image of Cookie Monster from Sesame Street dancing very enthusiastically because it is Tuesday](https://media1.tenor.com/images/a00d80b2d22a529a40674679df3bc966/tenor.gif?itemid=11719686)

---

## NOTES

## Introduction to the Responsive Web Design Challenges, 4 lessons to complete

### [Introduction to the Responsive Web Design Challenges](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-principles)

*These are general notes that can be used by anyone.*

---

## Responsive Web Design Principles: Create a Media Query

Media queries change the presentation of content on our various devices' viewport sizes.

*What's "viewport"?*

Viewport is "user's visible area of a web page; [it] varies with the device, and will be smaller on a mobile phone than on a computer screen." -w3school.com, learn more [here](https://www.w3schools.com/css/css_rwd_viewport.asp)

Although you can set the viewport in your `<meta>` tag, we're going to use media queries–a relatively new CSS standard that devs are using across the web.

In the fCC example, the tutorial tells us to add a media query to the existing code so that its `p` tag changes from 20px to 10px when our device height is less than or equal to 800px.

Here's what I came up with:

```
@media (max-height: 800px) {
    p {
        font-size: 10px;
    }
}
```

At first, I forgot to next the `p` tag, but once I remembered to do that, the challenge was met! Try it yourself now    👍🏾

## Make an Image Responsive

This is going to be a common factor in your web design code, even when you're using web builders. I've run into several issues where I've had to make images responsive using custom CSS because the builder would not apply its own default programming.

Here's an example from the fCC tutorial:

```
img {
    max-width: 100%;
    height: auto;
}
```
This code says that the image will never be wider than the container it is in (`max-width: 100%`), and it will keep its original aspect ratio (`height: auto;`).

Let's give it a shot with our own image, shall we?

<style>
.responsive-img {
    max-width: 100%;
    height: auto;
}
</style>

<html>
<body>
    <img class="responsive-img" src="https://scontent.faus1-1.fna.fbcdn.net/v/t1.0-0/s600x600/120039815_10218346609396058_1856031383829895473_o.jpg?_nc_cat=1&_nc_sid=825194&_nc_ohc=EcJ5R4isP2kAX-lCj6w&_nc_ht=scontent.faus1-1.fna&tp=7&oh=9e43508db2132d30296c015cdfbc3723&oe=5F912FE9" alt="a very dark meme">
</body>
</html>

## Use a Retina Image for Higher Resolution Displays

This is a great standard to adhere to when making images responsive, especially since pixelation is a common concern.

Take a look at what freeCodeCamp has to say:

> "Pixel density is an aspect that could be different on one device from others and this density is known as Pixel Per Inch(PPI) or Dots Per Inch(DPI). The most famous such display is the one known as a "Retina Display" on the latest Apple MacBook Pro notebooks, and recently iMac computers. Due to the difference in pixel density between a "Retina" and "Non-Retina" displays, some images that have not been made with a High-Resolution Display in mind could look "pixelated" when rendered on a High-Resolution display."

> The simplest way to make your images properly appear on High-Resolution Displays, such as the MacBook Pros "retina display" is to define their width and height values as only half of what the original file is.

<style>
  img { height: 50%; width: 50%; }
</style>
<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.M7KQsALZgHaSC6-mVedGOwHaEE%26pid%3DApi&f=1" alt="A most excellent picture">

Original dimension of the Bill and Ted image are 1092 x 601.

## Make Typography Responsive

This is pretty cool, too! Check out what fCC has to say:

> Instead of using em or px to size text, you can use viewport units for responsive typography. Viewport units, like percentages, are relative units, but they are based off different items. Viewport units are relative to the viewport dimensions (width or height) of a device, and percentages are relative to the size of the parent container element.

They have also provided students with this:

> The four different viewport units are:
>
> - `vw` (viewport width): `10vw` would be 10% of the viewport's width.
> - `vh` (viewport height): `3vh` would be 3% of the viewport's height.
> - `vmin` (viewport minimum): `70vmin` would be 70% of the viewport's smaller dimension (height or width).
> - `vmax` (viewport maximum): `100vmax` would be 100% of the viewport's bigger dimension (height or width).

In the tutorial challenge, we're asked to update the existing code. We need to set the `h2` width to 80% of the viewport's width and the `p` width to 75% of the viewport's smaller dimension.

To do this, both `vw` and `vmin` are going to be used. Here's the code I tested:

```
<style>
    h2 {
        width: 80vw;
    }
    p {
        width: 75vmin;
    }
</style>
```

My changes were reflected in the challenge window!

---

## Overall thoughts:

This short lesson was easy to understand and made me remember why I love to code. The digital manipulations we code into browsers, screen readers, and varied applications are akin to magic, a kind of binary alchemy that becomes more powerful with each design and programming decision we make. I love it!

Tomorrow, I will continue moving forward with the Responsive Web Design course curriculum and enter into the **"Introduction to the CSS Flexbox Challenges"**. I'm particularly enthused about this challenge thanks to my deep dive into it via egghead.io's Learner Advocacy program where I learned how to take deep, thoughtful notes to help me become a better, more conscientious developer.

👋🏾  Until tomorrow, keep on codin'!