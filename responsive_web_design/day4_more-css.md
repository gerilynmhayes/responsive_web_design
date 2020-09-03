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

Visit my [CodePen](https://codepen.io/gerilynmhayes/pen/mdPMpGO) to see the CatPhotoApp's progress. Or review the code below:

#### My HTML
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

#### My CSS
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

  [type='checkbox'] {
  margin: 10px 0px 15px 0px;
} 
```

---



---


## Overall thoughts:

Well, that's a wrap for day 3. This morning's experience with the Nightmare Trifecta wasn't as bad as I thought it was going to be. While I still need to build layouts using `padding` and `margin` to develop a deeper understanding (which I will get to during this 100-day challenge), I think that this is a great way to dive a bit deeper into the fCC curriculum.

The code featured in these notes, as a supplement to the freeCodeCamp tutorial, are in this [CodePen](https://codepen.io/gerilynmhayes/pen/BaKwJPp).

It looks like tomorrow I will expanding my knowledge, starting with the **"Basic CSS: Use Attribute Selectors to Style Elements"** portion of the tutorial.

🤓Until then, keep on codin'!

P.S. – If you'd like to code alongside me let's do it! Tweet your progress [@gerilynhayes](https://twitter.com/gerilynmhayes) and [@100ProjectDays](https://twitter.com/100ProjectDays) using hashtags #100DaysOfProjects and #LearningInPublic.