# 100DaysOfCode Challenge - 3rd Round log

This is the first round I'll try and keep a daily log here on Github, as well as tweeting my progress on my [twitter page](https://twitter.com/ValeriaRagonese).

## Start date: 30th May 2019
------

### 1) May, 30 2019
**Project: Pomodoro Clock in React**


Started the FreeCodeCamp project on building a Pomodoro Clock. I have created the frontend and I wanted to experiment with CSS, so it won't be mobile-friendly. I started working on the timer but got stuck. The timer has always been my problem. I need to find a library that will help me implementing this.

------


### 2) May, 31 2019
**Project: Timer for Pomodoro Clock**

I haven't found a working solution for the timer. I have tried different codes found online, but some run too fast or it was getting too complicated to stop once the stop button has being pressed.
I will probably take a break tomorrow and working on something else.

------

### 3) June, 1 2019
**Project: Memory Card Game in Javascript | [Github](https://github.com/morwen80/bttf-memory-card)**

I've been curious about this project since forever. I follow a tutorial online by FreeCodeCamp but I don't want to just copy and paste. I have completed the project but I've been playing with it and tried to add new functionalities so I can fully understand the process.

**THINGS I'VE LEARNED TODAY:**
- The CSS properties "perspective: 1000px" and "transform-style: preserve-3d". I've used them to create the 3d flipping effect on the cards. Perspective creates the illusion of depth and preserve-3d makes it look like it's, well, in 3D. 
- I've found out that every CSS element has a backface-visibility property which can be used to show its mirrored image. During the creation of the game, since every card has its front and back, I set the property to hidden.

**IMPLEMENTATIONS**
I've added a Play Again button which, in the JS code, shuffle the cards and set them all back to the original state (aka you can only see the back) by removing the class "flip" that makes them visible.

I would also love to add a modal which will appear once the game is completed.
Also, a dropdown menu where you can select the difficulty level. Every level would have a higher number of cards to match.

------

### 4) June, 2 2019
**Project: Memory Card Game in Javascript**
I managed to implement a Modal with a message and as I'm writing I'm still working on a timer.
I create a button for the user to start the counter but then I thought that it should start automatically once the first card is clicked...easier said than done. I should probably go back to the original idea.
But I'm happy since I managed to create a couple of functions all by myself and I'm happy of what I've been learning.

**THINGS I'VE LEARNED TODAY:**
Inside a Javascript file, instead of adding or removing a class to activate some CSS style, I can simply add xxx.style.visibility = "visible" if, like in this case, there's an element with a property of visibility: hidden
That was really helpful!

---

### 5) May, 31 2019
**Project: Memory Card in Javascript **


## IMPLEMENTATIONS:
**TIMER:** I've been stuck working on a timer function. I have set a button PlayAgain, that would stop the timer, reset it to 0, but it doesn't work.
The timer works fine when the page first loads, but after the modal is closed or/and when the playAgain button is clicked (they both trigger the same function), the timer doesn't start.

**LEVELS:** I would love to create differet levels a user can select. I've added a dropdown menu with "easy", "medium" and "hard", and I've made some cards hidden as a test. Those will be visible when level "medium" will be selected.

I couldn't focus too much since I had the final review for my Flatiron project. I finally graduated and I couldn't be happier!!

------


### 6) June, 1 2019
**Project: Memory Card in Javascript **

## IMPLEMENTATIONS:
**TIMER:** I've been trying different solutions but I still have the same problem as yesterday. For the moment I will make the page reloads when clicking the button playAgain. This works fine since resets the whole page to the default state, but if I should decide to make the design a little bit more complicated I will be forced to find another solution.


------
