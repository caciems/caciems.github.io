---
layout: essay
type: essay
title: The Godforsaken Green Checkmark
# All dates must be YYYY-MM-DD format!
date: 2022-02-10
labels:
  - Software Engineering
  - Learning
  - JavaScript
  - IntelliJ IDE
---

## Comfort, but at what cost?

<div class="ui small rounded images">
  <img class="ui image" src="../images/eslintcheckmark.png">
</div>

If you’re a computer science major, you are required to take ICS 111 and ICS 211. These two classes are an introductory class to programming where students are to learn the basic blocks of coding using the Java language in the Eclipse IDE (although I wish we could just do block coding like in elementary school). Looking back on it, I think a combination of being thrown into a new environment and learning foreign topics traumatized me into thinking Eclipse is evil. And going through two semesters of pain and suffering only added more salt to the wound. Although we have been using ESLint for a week, I actually spent most of that week using ESLint incorrectly. I recently found out that ESLint wasn’t working in the way it was supposed to for this class. While working on the practice WODs we were assigned, ESLint kept telling me that using Underscore functions wasn’t correct, and would throw errors in the IntelliJ console when I ran my code. This confused me because I would run the same code in Google Chrome, and it would work perfectly fine. In my mind, I was thinking why is this ESLint thing being so nitpicky on Underscore, it’s so useful. It turned out that I had most of the options enabled in the JavaScript Inspection tab which was causing ESLint to have a tantrum whenever I used Underscore functions in the practice WODs. I ended up having Professor Moore guiding me through how to make ESLint be more lenient on using Underscore functions during the WOD today (2/10). On an off topic note, I find it interesting how ESLint will also check for misspelled words. In the WOD, we were asked to create functions based off of cities on Oahu, and one of those cities ended up being Waipahu. When I copy pasted the cities const into IntelliJ, I was being warned that Waipahu was misspelled, even though I was correct. In this context, it was kind of annoying dealing with a warning error for something I couldn’t do anything about. Although I do find that feature useful in the future if I were to spell a variable name wrong, ESLint can help me prevent a Syntax error and avoid pulling something similar to “I was missing a semicolon, and that caused my code to break”. 

## Saving my Sanity (?)

<div class="ui small rounded images">
  <img class="ui image" src="../images/squinting.jpg">
</div>

I do believe that coding standards can help someone learn a language. At first, I was going to disagree by saying that coding standards can’t help you learn any logic. I thought about it for a little bit, then I came to the conclusion that you are learning a language, and not learning the logic behind the code. We learn logic in the first few weeks of programming, then we move on to applying the logic into our assignments. I also forgot to consider that the logic behind the code stays the same no matter what language you use (although it’s annoying trying to remember what kind of functions you can use for what languages. I often find myself typing console.log() when programming for my ICS 212 class). For example, this semester I’m learning two languages on top of Java; C and JavaScript. These two languages are vastly different from each other function wise, but the logic all stays the same. An if statement in C will work the same way as an if statement in JavaScript. Getting back on topic, I do agree that coding standards can also help us learn a language. Sometimes, the format for languages can be so weird and foreign that our instincts from coding in other languages can cause us confusion. In addition, I do believe that coding standards enforced in our classes can help the quality of our code and improve our sanity while coding. When I was taking ICS 111, I managed to catch a glimpse of a classmate’s script of code. No shade to them because it was the first couple weeks of the  intro to programming class, but I couldn’t read anything in that file. Every line was on the left side of the screen and none of the lines were tabbed, and I couldn’t figure out what was inside of the main method or if the lines were inside an if statement. Seeing something like this would make me die on the inside. In one way, I’m glad that coding standards and class formats are enforced on us. It was kind of like a pushing force to keep my code organized not only for myself to look at later, but for the poor TA’s that have to look at my code.

