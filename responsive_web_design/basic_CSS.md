# 100 Days of Projects

## Day 2 – Responsive Web Design | Basic CSS

Today I'm starting the freeCodeCamp's [Introduction to Basic CSS](https://www.freecodecamp.org/learn/) portion of the Responsive Web Design course. I'm excited to revisit the basics of CSS in this lesson. I've always enjoyed styling sites so I'm looking forward to updating the code for the [CatPhotoApp](https://codepen.io/gerilynmhayes/pen/mdPMpGO) project.

Remember: If you'd like to code alongside me let's do it! Tweet your progress [@gerilynhayes](https://twitter.com/gerilynmhayes) and [@100ProjectDays](https://twitter.com/100ProjectDays) using hashtags #100DaysOfProjects and #LearningInPublic.

## IT'S TIME TO ROCK 'N' ROLL!

![GIF image of Ozzy Osbourne walking away from a golf cart, yelling at camera](https://media1.tenor.com/images/b16697c465677eed697ac0f2e72d116f/tenor.gif?itemid=14318263)

---

## NOTES

## Basic CSS, 44 lessons to complete

*These are general notes that can be used by anyone.* 

### [Introduction to Basic CSS](https://www.freecodecamp.org/learn/responsive-web-design/basic-css)

CSS stands for Cascading Style Sheets. Just like our good ol' friends HTML and HTML5, CSS tells our browsers "how to display the text and other content that you write in HTML." It's pretty dang cool!

Why? 

Well, because you can use CSS to style your HTML elements' colors, fonts, sizes, spacing, and so much more.

Although I prefer to style my HTML using a stylesheet document, I'm going to follow the inline stying method used by this freeCodeCamp tutorial.

---

### CSS Selectors

You'll use CSS Selectors to style HTML elements. Once you get the hang of it, you'll want to use it all the time to make your HTML look super nifty.

In order to style plain HTML, you'll want to add CSS to your code.

Start by coding in a `style` block at the top of your code; it's where you're going to write all of your CSS. It's going to look like this:

```
<style>
    </style>
```
Now, add in the HTML element you want styled. Let's style a heading.

```
<style>
    h1 {
        color: red;
    }
</style>

```
For CSS to work, you must give your selected element a style rule. In this case you are giving Heading 1 a red color style rule. For the browser to execute this, put your style rule in curly braces. And most importantly, type a semicolon at the end of your style rule; otherwise, the code will not render the style rule.

If you're following along and using CodePen, you'll see that you can use their CSS editor. That's what I'm doing alongside the tutorial.

---

### CSS Classes

"Classes are reusable styles that can be added to HTML elements."

```
  .purple-text {
    color: purple;
  }

```
In the above example, `purple-text` is a class. Depending on which HTML element you want to style, this class will impact its color. Remember that all CSS classes are called, or start, with a period.

Let's style Heading 2. In the example below, you'll see that the HTML element is given a class attribute with a value of `purple-text`.

```
<style>
    .purple-text {
        color: purple;
    }
</style>

<h2 class="purple-text">I am purple.</h2>
```

What's really great about CSS Classes is that you can use them to style as many HTML elements as you'd like.

For more information about the CSS Class Selector, please visit [w3schools.com](https://www.w3schools.com/cssref/sel_class.asp).

---

### Importing Google Fonts

This one is super fun! When you visit Google Fonts, you can choose some uniquely design fonts by talented artists. To immport Google Font to your code, visit [Google Fonts](https://fonts.google.com/) and select the font you like best. Copy the code snippet; it might look like this:

```
<link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@300&display=swap" rel="stylesheet">
```

Paste the code snippet at the top of your code (before your open `style` element). Then, update your CSS Selector to style the font in your document. Here's an example of what the CSS code will look like:

```
p {
    font-size: 20px;
    font-family: 'Fira Code', monospace;
}
```

CSS Classes are super cool because you can style images, paragraph blocks, menus and so much more! Check out my [CodePen](https://codepen.io/gerilynmhayes/pen/mdPMpGO) to review the code I used to spruce up the border surrounding the image of that ridiculously cute kitten. Be sure to see which classes I used and where they're placed in the code.

---

### Element id

The `id` can only be used once to style a single element so make sure that your id is unique the specific element you want to style.

```
<h2 id="cat-photo-app">

<form id="cat-photo-form">
```
---

To conclude this section of the Basic CSS curriculum, review the code below and see how it compares to your own:

## HTML for CatPhotoApp

```
<!DOCTYPE html>
<html>
  <head>
    <!-- metadata elements -->
  </head>
	
	<link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@300&display=swap" rel="stylesheet">
	
<body>
	
	<h2 class="purple-text">CatPhotoApp</h2>
<main>
    <p >Click here to view more
        <a href="#" target="_blank">cat photos</a>
    </p>
  
    <a href="#footer">Jump to Bottom</a><br/>

    <a href="#"><img class="smaller-image thick-gold-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

    <div class="silver-background">
    <p class="purple-text">Things cats loves:</p>
    <ul>
        <li>chin scritches</li>
        <li>stinky wet food</li>
        <li>scratching posts</li>
    </ul>

    <p class="purple-text">Things cats hate:</p>
    <ol>
        <li>loud noises</li>
        <li>healthy food</li>
        <li>mean doggies</li>
    </ol>
    </div>

    <form id="cat-photo-form" action="https://freecatphotoapp.com/submit-cat-photo">

        <label for="indoor">
            <input id="indoor" value="indoor" type="radio" name="indoor-outdoor" checked>Indoor
        </label>
        <label for="outdoor">
            <input id="outdoor" value="outdoor" type="radio" name="indoor-outdoor">Outdoor
        </label>
        <label for="loving">
        <input id="loving" value="loving" type="checkbox" name="personality" checked>Loving
        </label>
       <label for="grumpy">
        <input id="grumpy" value="grumpy" type="checkbox" name="personality">Grumpy
        </label>
        <label for="Lazy">
        <input id="lazy" value="lazy" type="checkbox" name="personality">Lazy
        </label><br/>
        <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
    </form>
</main>
<footer id="footer">Copyright Cat Photo App</footer>
	</body>
</html>
```

## CSS for CatPhotoApp

```
	.purple-text {
    color: purple;
  }

h2 {
	font-family: 'Fira Code';
}

  p {
    font-size: 20px;
		font-family: monospace;
  }

.smaller-image {
	width: 100px;
}

    .thick-gold-border {
    border-color: gold;
    border-width: 10px;
    border-style: ridge;
		border-radius: 25%;
  }

.silver-background {
	background: silver;
}

  #cat-photo-form {
  background-color: green;
}

```
## Overall thoughts:

I can say with 100% confidence that I'm a HUGE CSS FAN.

What I love most about CSS is its ability to take my HTML code and stylize it. The possibilities with this are limitless, in my opinion. I think it's the gateway for some web designers, and is going to help me further understand how items in WordPress and other content management platforms help devs quickly build websites.

My results from this freeCodeCamp tutorial are on [CodePen](https://codepen.io/gerilynmhayes/full/mdPMpGO).

I'm looking forward to starting the layout portion of the CSS curriculum which will highlight my archnemises: **`padding`, `margin`, and `border`**.

🤓Until then, keep on codin'!