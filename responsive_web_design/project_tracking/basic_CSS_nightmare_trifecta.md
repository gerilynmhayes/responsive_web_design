# 100 Days of Projects

## Day 3 – Responsive Web Design | The Nightmare Trifecta (CSS)

It's a new day which means it's time to get my code on!

That said, I'm feeling a bit trepidatious about today's lesson in padding, margins, and borders.

So, instead of further rumination....

## Let's Get It!

![GIF image of Ozzy Osbourne walking away from a golf cart, yelling at camera](https://media1.tenor.com/images/a66ca3463edde822f857278b74fa38d4/tenor.gif?itemid=10143792)

---

## NOTES

## Basic CSS, 44 lessons to complete

*These are general notes that can be used by anyone.*

### [Introduction to Basic CSS](https://www.freecodecamp.org/learn/responsive-web-design/basic-css)

*"Three important properties control the space that surrounds each HTML element: `padding`, `margin`, and `border`."* – freeCodeCamp

While I know this to be true, I want to start off by creating a series of HTML coded boxes to test my skills. In the tutorial, the HTML is drafted for students, which is totally fine, but having taken this course before I think it would be worthwhile to try to create this one with the knowledge I've developed over the past year or so.

Visit my [CodePen](https://codepen.io/gerilynmhayes/pen/BaKwJPp) to see what I've come up with. Or review the code below:

#### My HTML
```
<p class="green-box">This is a box.</p>

<p class="gold-box">This too is a box.</p>

<p class="black-box">Here's another box.</p>
```

#### My CSS
```
.green-box {
	color: white;
	background: green;
}

.gold-box {
	color: black;
	background: gold;
}

.black-box {
	color: white;
	background: black;
}
```

---

## Padding

Now that I have the code in place for my boxes, I want to gain a deeper understanding of `padding`.

freeCodeCamp tells me that `padding` "controls the amount of space between the element's content and its `border`". It also tells me "when you increase the box's padding, it will increase the distance (`padding`) between **the text** and **the border** around it.

I think this makes sense 🤔 ...., but I'll test it, just to make sure I'm understanding the concept.

Take a look at my code (you can run a test of it on CodePen). *What do you think? Did I nail it?*

```
.green-box {
	color: white;
	background: green;
	padding: 10px;
}

.gold-box {
	color: black;
	background: gold;
	padding: 10px;
}

.black-box {
	color: white;
	background: black;
	padding: 10px;
}
```
fCC says, "CSS allows you to control the `padding` of all four individual sides of an element with the `padding-top`, `padding-right`, `padding-bottom`, and `padding-left` properties." The same can be said for `margin` so that's cool!

What's even cooler is that I don't have to write out each of these properties and their respective values. I can tell the browser how to render my element's paddings and margins using a **clockwise notation**.

Example 1:

```
padding: top right bottom left;

padding: 10px 20px 10px 20px;
```

Example 2:

```
margin: top right bottom left;

margin: 10px 20px 10px 20px;
```

Now, I'm going to get my boxes a bit 'o' character!

```
.green-box {
	color: white;
	background: green;
	padding: 50px 10px 50px 25px;
	margin: 25px 50px 10px 50px;
}

.gold-box {
	color: black;
	background: gold;
	padding: 50px 10px 50px 25px;
	margin: 5px 75px 25px 75px;
}

.black-box {
	color: white;
	background: black;
	padding: 50px 10px 50px 25px;
	margin: -15px 50px 10px 50px;
}
```

---

## Margin

I'm feeling pretty confident about my understanding of `padding`. Now, I'm moving on to `margin`.

freeCodeCamp tells me that "An element's margin controls the amount of space between an element's border and surrounding elements."

All right... I'll admit it: *I have NO IDEA what this means.*

Let's see if I can get a better understanding from YouTuber Ferdy (click the CSS Box Model image to see the video explanation):

[![The CSS Box Model](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Boxmodell-detail.png/300px-Boxmodell-detail.png)](https://youtu.be/WQ4piPjD0ZA "Padding and Margin Explained")

According to our pal Ferdy, `margin` impacts the area outside of the element; another way of saying what fCC described... okay. He also mentioned that you can't actually see an element's border! That's key info I need.

So, let me see what happens when I add margins to each of my boxes, understanding that the size of my element will not change; only the area outside of/surrounding my element will either increase or decrease depending on the values I give it.

```
.green-box {
	color: white;
	background: green;
	padding: 10px;
	margin: 10px 30px;
}

.gold-box {
	color: black;
	background: gold;
	padding: 10px;
	margin: 10px 20px;
}

.black-box {
	color: white;
	background: black;
	padding: 10px;
	margin: 10px 10px;
}
```

I feel good about this code. All of my boxes have margins that are 10 pixels from their top borders, with varying pixel sizes on their left and right sides. It looks like a staircase to me which is oddly comforting.

Conceptually, I understand `margin` at this point. Now, it's time to move on to `border` (*should I have started there first?*).

---


## Overall thoughts:

Well, that's a wrap for day 3. This morning's experience with the Nightmare Trifecta wasn't as bad as I thought it was going to be. While I still need to build layouts using `padding` and `margin` to develop a deeper understanding (which I will get to during this 100-day challenge), I think that this is a great way to dive a bit deeper into the fCC curriculum.

The code featured in these notes, as a supplement to the freeCodeCamp tutorial, are in this [CodePen](https://codepen.io/gerilynmhayes/pen/BaKwJPp).

It looks like tomorrow I will expanding my knowledge, starting with the **"Basic CSS: Use Attribute Selectors to Style Elements"** portion of the tutorial.

🤓Until then, keep on codin'!

P.S. – If you'd like to code alongside me let's do it! Tweet your progress [@gerilynhayes](https://twitter.com/gerilynmhayes) and [@100ProjectDays](https://twitter.com/100ProjectDays) using hashtags #100DaysOfProjects and #LearningInPublic.