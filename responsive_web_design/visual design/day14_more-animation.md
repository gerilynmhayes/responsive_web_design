# 100 Days of Projects

## Day 14 – Responsive Web Design | Applied Visual Design, continued

So, I've decided to take my weekends off from coding. Not because I don't want to code, but because I just need to keep the computer off sometimes! Fortunately, the massive headache I had on Saturday subsidded, but on Sunday I had way too many things to do and couldn't squeeze an ounce of brain power out for coding. That made me realize that it's more important to come back to coding with a fresh pair of eyes and a clear mind on the weekedays than forcing myself to learn something new or even refresh and refine what I already know.

That said, it's a NEW day and I'm ready to jump right back into responsive design. Are you?

## Let's do it!

![GIF illustration of a white dog with text that says It's a new day and A new beginning](https://media1.tenor.com/images/a547005f4d3b38bcfca309873db05461/tenor.gif?itemid=12542285)

---

## NOTES

## Applied Visual Design, 52 lessons to complete

*These are general notes that can be used by anyone.*

### [Introduction to  the Applied Visual Design Challenges](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/)

---

## Use CSS Animation to Change the Hover State of a Button

@keyframes can change the color of a button in its hover state! In the fCC example, we're changing the `background-color` of a button element when a site visitor hovers over it. Here's the resulting code:

```
<style>
  button {
    border-radius: 5px;
    color: white;
    background-color: #0F5897;
    padding: 5px 10px 8px 10px;
  }

  button:hover {
    animation-name: background-color;
    animation-duration: 500ms;
  }

  @keyframes background-color {
    100% {
      background-color: #4791d0;
    }
  }

</style>
<button>Register</button>

```

I think it's important to note that our `@keyframes` only targets the background-color and the instructions for the browser to follow are nested inside the call. I don't know why, but I really like that; seems clean and logical to me. Okay, enough gushing about CSS magic  🧙🏾‍♀️✨

Also note that this code is **incomplete**. Move to the next fCC module to learn more.

---

## Modify Fill Mode of an Animation

Although the code is correct, the timing is not. That's because we're missing the `animation-fill-mode` property. This property "specifices the style applied to an element when the animation has finished." The `forwards` value will make it so that when we hover over our button, the element will stay highlighted. Follow the fCC lesson to see how to make it happen.

---

## Create Movement Using CSS Animation

fCC states:

> When elements have a specified position, such as fixed or relative, the CSS offset properties right, left, top, and bottom can be used in animation rules to create movement.

Refer to this specific lesson [(here)](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/create-movement-using-css-animation) to understand how to add animation to the keyframes so that the element moves about in any direction you set for the browser to render.

---

## Create Visual Direction by Fading an Element from Left to Right

So that an element has the appearance of movement, we're going to add `opacity`. The gradient effect is going to work beautifully for this purpose, as you'll see in the lesson [(here)](https://www.freecodecamp.org/learn/responsive-web-design/applied-visual-design/create-visual-direction-by-fading-an-element-from-left-to-right).

Keep in mind that in order for the animation to fade, you'll want to update the `@keyframes` code because it is specifying to the browser that the element with the `ball` id has an `animation-name` that needs to be updated with an `opacity` property and value.

---

## Animate Elements Continually Using an Infinite Animation Count

fCC states:

> Another animation property is the animation-iteration-count, which allows you to control how many times you would like to loop through the animation.

To do this, give your `animation-iteration-count` property an `infinite` value.

---

## Make a CSS Heartbeat using an Infinite Animation Count

I wanted to save this example for future study. The code is [here](https://codepen.io/gerilynmhayes/pen/YzqvNYz). I like the fCC walks us through the animated portions of the code. See what they have to say below:

> ...the `animation-iteration-count` property that uses the heart you designed in a previous challenge.

> The one-second long heartbeat animation consists of two animated pieces. The `heart` elements (including the `:before` and `:after` pieces) are animated to change size using the `transform` property, and the background `div` is animated to change its color using the `background` property.

---

## Overall thoughts:

Tomorrow we're going to go over the animation of elements at variable rates. I like the upcoming lesson because we get to make a fun nightsky scenario from HTML and CSS. Very cool stuff!

Now that today's lesson is wrapped, I will be moving on to a couple of clients that involve copywriting for a new business and conducting a WordPress site audit. It's going to be busy, but FUN.

Hope you have a great day today, fellow coder!

![GIF of baby Yoda waving](https://media1.tenor.com/images/e9509ddcab0a9121660fa748b98b50e5/tenor.gif?itemid=15921838)

Get the next set of notes via my GitHub repo [here](https://github.com/gerilynmhayes/responsive_web_design/tree/master/responsive_web_design).

👉🏾  Keep on codin'!