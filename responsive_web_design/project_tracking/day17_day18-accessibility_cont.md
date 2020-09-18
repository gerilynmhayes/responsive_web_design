# 100 Days of Projects

## Day 17 (nixed), Day 18 – Responsive Web Design | Applied Accessibility

Yesterday/last night, my brain reached its capacity for taking in new information because I was literally exhausted.

After a good night's sleep and a hearty protein-rich breakfast, I happy to get back into accessibility with a clear mind.

## TGIFYAY!

![GIF image of the incomparable Nic Cage stepping off a prison plane and basking in the sweet glow of semi-freedom in Con Air; text reads Feel that? That's Friday.](https://media1.tenor.com/images/7762a258133f334cbca1beaf5697701f/tenor.gif?itemid=12235300)

---

## NOTES

## Applied Accessibility, 22 lessons to complete

### [Introduction to  the Applied Accessibility Challenges](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/)

*These are general notes that can be used by anyone.*

---

## Jump Straight to the Content Using the main Element

This is a common navigation code operation that you should get familiar with. [Take the challenge](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/jump-straight-to-the-content-using-the-main-element) now to see how these accessibility features are programmed for use in assistive technology.

## Wrap Content in the `article` Element

fCC states:

> `article` is a sectioning element, and is used to wrap independent, self-contained content. The tag works well with blog entries, forum posts, or news articles.

Because people who use assistive technology need to engage with web content, you must ensure that your markup has semantic meaning. This is a very important lesson as there are multiple distinctions between elements `article`, `main`, and `section`. Here's what fCC has to say about the aforementioned distinctions:

> The `section` element [...] has a slightly different semantic meaning than article. An `article` is for **standalone content**, and a `section` is for grouping thematically related content. They can be used within each other, as needed. For example, if a book is the `article`, then each chapter is a `section`. *When there's no relationship between groups of content, then use a* `div`.

```
<div> – groups content
<section> – groups related content together
<article> – groups independent, self-contained content

```
^^ from freeCodeCamp    🤓 Test your understanding of this concept [here](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/wrap-content-in-the-article-element).

## Make Screen Reader Navigation Easier with the `header` Landmark

The `header` tag wraps around introductory information or nav links for its parent tag. If you've got content that repeats at the top of several pages on your website, you're going to want to use this tag. Test the concept [here](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/make-screen-reader-navigation-easier-with-the-header-landmark).

## Make Screen Reader Navigation Easier with the `nav` Landmark

The `nav` tag is used to wrap around the main nav links on your pages. So, just like the previously mentioned tags, you don't want to use a `<div>`; you want to ***replace the `<div>`*** with your landmark tag.

NOTE:

> If there are repeated site links at the bottom of the page, it isn't necessary to markup those with a `nav` tag as well. Using a `footer` is sufficient.

## Make Screen Reader Navigation Easier with the `footer` Landmark

fCC states:

> Similar to `header` and `nav`, the `footer` element has a built-in landmark feature that allows assistive devices to quickly navigate to it. It's primarily used to contain copyright information or links to related documents that usually sit at the bottom of a page.

## Improve Accessibility of Audio Content with the audio Element

Did you know that you can give semantic meaning to sound and audio streaming content? When you use the `audio` element, it makes it easy for assistive technologies to tell your site visitors what the content type is. Keep in mind that your `audio` tag will also need "a text alternative to be accessible to people who are deaf or hard of hearing."

fCC states:

> The `audio` tag supports the `controls` attribute. This shows the browser default play, pause, and other controls, and supports keyboard functionality. This is a **boolean attribute**, meaning *it doesn't need a value*, its presence on the tag turns the setting on.

and provides the following example:

```
<audio id="meowClip" controls>
  <source src="audio/meow.mp3" type="audio/mpeg" />
  <source src="audio/meow.ogg" type="audio/ogg" />
</audio>
```

Another solid rule of thumb provided by fCC:

> **Note**: Multimedia content usually has both visual and auditory components. It needs synchronized captions and a transcript so users with visual and/or auditory impairments can access it. Generally, a web developer is not responsible for creating the captions or transcript, but needs to know to include them.

See how easy it is to incorporate this tag when you take the challenge [here](https://www.freecodecamp.org/learn/responsive-web-design/applied-accessibility/improve-accessibility-of-audio-content-with-the-audio-element).

---

## Overall thoughts:

Well that was a worthwhile tutorial for the morning/early afternoon. I'm going to make my stopping point here and come back next week to study "Improve Chart Accessibility with the figure Element" and more accessibility lessons from freeCodeCamp.

I hope you have wonderful weekend and get plenty of rest aka *it's okay to take a code break    😉
👋🏾  Until next week, keep on codin'!