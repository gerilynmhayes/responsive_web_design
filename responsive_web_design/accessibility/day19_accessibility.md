# 100 Days of Projects

## Day 19 – Responsive Web Design | Applied Accessibility

Accessibility! What a great way to start of the work week!

## Monday Vibes   🤓

![GIF image of wording that says Motivation Monday](https://media1.tenor.com/images/c6885d268b2ab24552232e41ff0dd91d/tenor.gif?itemid=13264227)

---

## NOTES

## Applied Accessibility, 22 lessons to complete

### [Introduction to  the Applied Accessibility Challenges](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/)

*These are general notes that can be used by anyone.*

---

## Improve Chart Accessibility with the `figure` Element

The `figure` element and `figcaption` add semantic value to items that contain an image, chart or diagram. The `figcaption` is where you will describe the `figure` which will tell the screen reader what is on the screen.

fCC has an excellent example:

```
<figure>
    <img src="roundhouseDestruction.jpeg" alt="Photo of Camper Cat executing a roundhouse kick">
  <br>
  <figcaption>
    Master Camper Cat demonstrates proper form of a roundhouse kick.
  </figcaption>
</figure>
```

^^ This code turns into the figure set below:

<figure>
    <img src="https://media1.tenor.com/images/8bbd27043d45e73a67acb9a58943684e/tenor.gif?itemid=14172645" alt="Photo of a ninja racoon executing a strike move">
  <br>
  <figcaption>
    Master Racoon demonstrates proper form of a strike move.
  </figcaption>
</figure>


## Improve Form Field Accessibility with the `label` Element

You'll also want to give form fields semantic meaning by describing what each field is meant to do. You'll use the `label` tag for this. Here's another great example from fCC:

```
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
</form>
```

^^ This code turns into this super simple form for the screen reader to describe to the individual using it:

<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
</form>

*Remember this note from freeCodeCamp*:

> The `for` attribute on a `label` tag explicitly associates that `label` with the form control and is used by screen readers.

The same semantic goals need to apply to the various `fieldset` elements like radio button.

## Wrap Radio Buttons in a fieldset Element for Better Accessibility

You'll want to tell your screen reader what each of the buttons on your form mean by applying `fieldset`. `fieldset` typically wraps around all your radio button options so that you can give each one a proper label within the grouping. Review the following code example:

```
<form>
  <fieldset>
    <legend>Choose one of these three items:</legend>
    <input id="one" type="radio" name="items" value="one">
    <label for="one">Choice One</label><br>
    <input id="two" type="radio" name="items" value="two">
    <label for="two">Choice Two</label><br>
    <input id="three" type="radio" name="items" value="three">
    <label for="three">Choice Three</label>
  </fieldset>
</form>
```

^^ This semantic code will turn into this nicely designed form (below). Screen readers will be able to tell those with visual impairments which radio button is which, making it easier for those persons to make their selections with confidence.

<form>
  <fieldset>
    <legend>Choose one of these three items:</legend>
    <input id="one" type="radio" name="items" value="one">
    <label for="one">Choice One</label><br>
    <input id="two" type="radio" name="items" value="two">
    <label for="two">Choice Two</label><br>
    <input id="three" type="radio" name="items" value="three">
    <label for="three">Choice Three</label>
  </fieldset>
</form>

In the code above, you'll see the `fieldset` wrapper and the `legend` tag. fCC states that these aren't necessary when the choices are self-explanatory, like a gender selection (*although I'm thinking that might change due to more representation on the gender scale*). "Using a `label` with the `for` attribute for each radio button is sufficient."

Another good resource for this type of build is W3. Here's how they define `legend`:

> The `<legend>` tag defines a caption for the `<fieldset>` element.

Learn more from W3 [here](https://www.w3schools.com/TAGS/tag_legend.asp).

**Keep in mind that this particular build will come in handy for your website build at the end of the entire Responsive Web Design course!!**

## Add an Accessible Date Picker

There are many different types of form controls. You can discover them all via W3Schools [here](https://www.w3schools.com/html/html_form_input_types.asp).

The code used to show an accessible date picker is semantic! You're going to continue following the trend and tell the screen reader what your inputs mean. 

Read the following code to understand more about this:

```
<label for="input1">Enter a date:</label>
<input type="date" id="input1" name="input1">
```

For the screen reader, the lines of code (above) are structured perfectly because the values given are semantic. In the example below, those who are sighted do not see the semantics but are sharing in the same experience as someone who is not sighted.

<label for="input1">Enter a date:</label>
<input type="date" id="input1" name="input1">

## Standardize Times with the HTML5 datetime Attribute

Now we're moving into the `time` element–an inline element used to wrap around a date or time on a webpage. You're going to need to use the `datetime` attribute to make the times *standardized*.

Take a look at this example:

> <p>The sweltering Texas heat was borne of the hot and fiery summer season of 2011 which heavily impacted Bastrop County. On <time datetime="2011-09-04">September 4, 2011</time> the fires began to rage throughout the county.</p>

If you're sighted, like me, then you're not going to be able to see the semantic value, but the screen reader will and that's what we want!

---

## Make Elements Only Visible to a Screen Reader by Using Custom CSS

I love what fCC has to say about CSS in this context. Read more:

> CSS's magic can also improve accessibility on your page when you want to visually hide content meant only for screen readers. This happens when information is in a visual format (like a chart), but screen reader users need an alternative presentation (like a table) to access the data. CSS is used to position the screen reader-only elements off the visual area of the browser window.

This means that in CSS we're going to want to use out `.sr-only` to style items specifically for the screen reader!

Take a look at the challenge they've given us [here](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/make-elements-only-visible-to-a-screen-reader-by-using-custom-css).

## Improve Readability with High Contrast Text, Avoid Colorblindness Issues by Using Sufficient Contrast

This is what fCC and The Web Content Accessibility Guidelines (WCAG) recommends:

> The Web Content Accessibility Guidelines (WCAG) recommend at least a 4.5 to 1 contrast ratio for normal text. The ratio is calculated by comparing the relative luminance values of two colors. This ranges from 1:1 for the same color, or no contrast, to 21:1 for white against black, the strongest contrast. There are many contrast checking tools available online that calculate this ratio for you.

This is best explained within the challenge so please review [here](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/improve-readability-with-high-contrast-text).

You will also want to review guidelines for avoiding colorblindnesses issues [here](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/avoid-colorblindness-issues-by-using-sufficient-contrast).

I think that the two most important items to remember from the colorblindness challenge are:

>First, color alone should not be used as the only way to convey important information because screen reader users won't see it.

>Second, foreground and background colors need sufficient contrast so colorblind users can distinguish them.

## Avoid Colorblindness Issues by Carefully Choosing Colors that Convey Information

Since we want to ensure that all users can have a good web experience and access the information they need, it's imperative that the information is displayed using colors all people can see and process.

Please review the information in this challenge [here](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/avoid-colorblindness-issues-by-carefully-choosing-colors-that-convey-information) to understand why a brightly colored font against a brightly colored background would not be accessible for your site visitors.

So instead of having your `a` tag wrapped around a call-to-action prompt like "Click Here", you can wrap the tag around something more descriptive like "information about home security alarms" or "information about coding for accessibility". See the example code provided by fCC in their challenge to learn more.

---

## Give Links Meaning by Using Descriptive Link Text

By making your links readable to screen readers, you're adding in an extra layer of accessibility for your site visitors. I love that screen readers have this capability.

To make this work, you'll need to code in "brief but descriptive text within the `a` tags to provide meaning" for the screen reader users.

## Make Links Navigable with HTML Access Keys

Use the `accesskey` attribute to "specify a shortcut key to activate or bring focus to an element." This will make navigating the site more efficient for individuals that exclusively use their keyboards for navigation.

Here's an example provided by fCC:

<button accesskey="b">Important Button</button>

You can also add the `accesskey` to links like this:

```
    <h2><a id="first" href="#" accesskey="g">The Garfield Files: Lasagna as Training Fuel?</a></h2>
```

---

## Use `tabindex` to Add Keyboard Focus to an Element

This is very cool when considering navigation for users, especially since the `input` fields (for forms) always get keyboard focus–you'll be able to control this~

Learn more and experiment with the code in the challenge [here](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/use-tabindex-to-add-keyboard-focus-to-an-element).

## Use tabindex to Specify the Order of Keyboard Focus for Several Elements

This is similar to what we just learned, but focuses on how this code will override the default browser settings of tab navigation. Learn more in the challenge [here](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/use-tabindex-to-specify-the-order-of-keyboard-focus-for-several-elements).

---

## Overall thoughts:

Well, that was a very nice introduction to accessibility. There's much more to accessibility than is covered here, but I think that this is a great starting point for those of us interested in making semantic coding a web standard.

To get focused on accessibility and understand what it means for engineers, I recommend watching this helpful YouTube video from **SFHTML5**. Click the image to check it out!

[![img video about accessibility](https://www.outsystems.com/blog/-/media/images/blog/posts/building-web-accessibility-barriers-guidelines-standards/building-web-accessibility-barriers-guidelines-standards_01.jpg?la=en)](https://youtu.be/z8xUCzToff8)

Tomorrow, I'll start a new portion of the curriculum: *Introduction to the Responsive Web Design Challenges* where I'll learn how to create media queries, makes images and typography responsive, and so much more. Even though I know how to do these things already, it doesn't hurt to continue refreshing the old memory and sharpening those skills!

👋🏾  Until tomorrow, keep on codin'!