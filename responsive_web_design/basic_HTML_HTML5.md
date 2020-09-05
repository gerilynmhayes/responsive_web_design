# 100 Days of Projects

## #100DaysOfProjects: Day 1 – Responsive Web Design Project Initiative

Although I've been coding for years, I need to build up my projects portfolio and give myself a refresher on basic coding. The best way for me to put my skills to practice is by committing to the #100DaysOfProjects challenge, created by [Ceora](https://twitter.com/ceeoreo_)! She's an Instructor and Learner Advocate at egghead.io and you should follow her on Twitter to get loads of meme inspiration and more.

Today's notes will feature what I'm learning via freeCodeCamp's [Responsive Web Design Certification track](https://www.freecodecamp.org/learn/) course. With 300 hours of curriculum to cover, I wanted to document my journey in public so that other devs, code newbies and prospective project collaborators can see what Learning in Public is all about!

I'm looking forward to sharing my learnings and project progress with you, and if you'd like to code alongside me let's do it! Tweet your progress [@gerilynhayes](https://twitter.com/gerilynmhayes) and [@100ProjectDays](https://twitter.com/100ProjectDays) using hashtags #100DaysOfProjects and #LearningInPublic.

## LET'S GO!

![GIF image of little girl in hot rod car, throwing up the horns](https://media1.tenor.com/images/c4bb79c6bc4bfb26c9bcbee106275881/tenor.gif?itemid=13336149)

---

## NOTES

## Basic HTML and HTML5 curriculum, 28 lessons to complete

*These are general notes that can be used by anyone.*

### [Introduction to Basic HTML and HTML5](https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/)

To become a web savvy coder, you'll need to know HTML.

HTML stands for HyperText Markup Language. *What does that mean?*

**HyperText Markup Language** is really neat! Think of it as a computing language that tells your web browser how webpages are structured and describes all the cool information on these webpages–because that's exactly what it does! You're literally talking directly to your computer and telling it how you'd like for it to render in the form of a digital medium. *Pretty far out, right?*

That's why understanding this language, and how your computer interprets what you're telling it to do, will be the foundation of your coding and programming experience.

#### Building a simple web page using HTML

The documented code (below) is the result of today's curriculum. To build these items yourself, please visit [freeCodeCamp](https://www.freecodecamp.org/) and begin the [Responsive Web Design Certification track](https://www.freecodecamp.org/learn/) today!

If you have questions about the resulting code or the process, please tweet me [@gerilynhayes](https://twitter.com/gerilynmhayes) – thanks! 

```
<h1>Hello World</h1>

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```
---

We're about to get more descriptive with the HTML tags, starting with `<main>`.

**NOTE**: "HTML5 introduces more descriptive HTML tags. These include main, header, footer, nav, video, article, section and others.

These tags give a descriptive structure to your HTML, make your HTML easier to read, and help with Search Engine Optimization (SEO) and accessibility. The main HTML5 tag helps search engines and other developers find the main content of your page." - freeCodeCamp

You'll see below which information is considered "main" or most important.

You'll also want to take note of to the most common element used in HTML: `<div>` or the division element.

```

<h2>CatPhotoApp</h2>
<main>
    <p>Click here to view more
        <a href="#" target="_blank">cat photos</a>
    </p>
  
    <a href="#footer">Jump to Bottom</a>

    <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

    <div>
    <p>Things cats loves:</p>
    <ul>
        <li>chin scritches</li>
        <li>stinky wet food</li>
        <li>scratching posts</li>
    </ul>

    <p>Things cats hate:</p>
    <ol>
        <li>loud noises</li>
        <li>healthy food</li>
        <li>mean doggies</li>
    </ol>
    </div>

    <form action="https://freecatphotoapp.com/submit-cat-photo">
        <input type="text" required placeholder="cat photo URL">
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

```

---

## Doctype

What's interesting about this tutorial is that it introduces the Doctype declaration later on in the tutorial. Typically, you'd see this in the beginning of tutorials, but probably not in this instance since we're using an online code editor/simulation versus creating an HTML document on our local drive.

Essentially, the Doctype is used to tell your browser just what in the world the document you're telling it to render is. *Is it an HTML doc? Is it a CSS doc? Is it a dinosaur?* Whatever it is, you've got to specifiy it to the browser so that it understands the page's structure.

Take a look at the structure of an HTML page:

```
<!DOCTYPE html>
<html>
    <!-- Your nifty HTML code will be typed here. -->
</html>

```

---

## Head and Body

Other key elements to page structure are the head and body. The head stores all the important information about your website. Info like `link`, `meta`, `title`, and `style` go in this brain-level portion of your code. The body stores the contents of your page the super cool characteristcs of your web page(s).

```

<!DOCTYPE html>
<html>
  <head>
    <!-- metadata elements -->
  </head>
  <body>
    <!-- page contents -->
  </body>
</html>

```

---

### Checklist from responsive_web_design.md

- Declare #100DaysOfProjects participation [here](https://twitter.com/gerilynmhayes/status/1300536475650584583) using #100DaysOfProjects and #LearningInPublic
- Begin refresher of HTML and CSS via freeCodeCamp via the [Responsive Web Design Certification track (300 Hours)](https://www.freecodecamp.org/learn/)
- Create repo (local)
- Create README.txt
- Upload your notes to [GitHub](https://github.com/gerilynmhayes) so fellow devs can follow along and review your progress
- Update your progress on [Twitter](https://twitter.com/gerilynmhayes/) and [Facebook](https://www.facebook.com/thecodingcopywriter)

### Soundtrack

[Best of Nostal Synthwave Mix](https://youtu.be/5E4uPA2wwjY)

[Arcis – Speed Boat Theme](https://youtu.be/G8PVTiknvs4)

['Back To The 80's' | Marvel83' Edition | Best of Synthwave And Retro Electro Music Mix](https://youtu.be/0QKQlf8r7ls)

---

## Overall thoughts:

I've taken this tutorial before so it was nice to take it again as a refresher. My results from this freeCodeCamp tutorial are on [CodePen](https://codepen.io/gerilynmhayes/full/mdPMpGO).

What I liked most is that I got to work with HTML exclusively. Overall, it's a language that everyone needs to learn and understand – aka it's not just for the development and programming community.

I also like that the tutorial offers students a step-by-step coding experience that's not atypical of 'from-scratch' development. I'm looking forward to taking notes on the CSS portion that's to come in Day 2 of the #100DaysOfProjects challenge!

🤓Until then, keep on codin'! 